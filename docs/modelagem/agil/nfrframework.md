## Introdução

Uma forma de representação e análise dos [Requisitos Não-Funcionais](../../../elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) é o NFR Framework, o qual visa à implementação de resoluções particulares. Sendo assim, para tal, considera-se as características gerais do sistema em questão e de seu domínio. No NFR Framework, faz-se o uso do modelo de Softgoal Interdependency Graph (SIG).

## Softgoal Interdependency Graph

O Softgoal Interdependency Graph (SIG) é uma forma de visualização do funcionamento do NFR Framework. Dessa forma, trata-se de um gráfico que registra os posicionamentos da equipe de desenvolvimento acerca dos softgoals e explicita suas interdependências de forma gráfica e concisa<a id="anchor_1" href="#REF1">^1^</a>.

### Tipos de Softgoal

Para a compreensão do SIG, é inexorável discernir a definição de NFR Softgoal: um objetivo que não é explicitamente definido e seus critérios de satisfação são imprecisos. Sendo assim, um softgoal é uma característica abstrata que está sujeita à vistoria, ou seja, postula-se posteriormente o destino de um determinado softgoal. Além disso, os softgoals podem ser operacionalizados, nesse caso, tomam uma forma concreta. Portanto, entende-se como funcionalidades. Por fim, há os softgoals de afirmação, os quais são escritos em linguagem natural e se tratam de registros adicionais e argumentativos, os quais podem ser incrementados ao modelo<a id="anchor_1" href="#REF1">^1^</a>. Os tipos de softgoal estão ilustrados na Figura 1.



<font size="3"><p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal</p></font>
<figure markdown class="usecaseElement">

![TIPOS](../../assets/nfr-framework/tipos.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>



### Interdependências

As interdependências são definições para as associações que ocorrem entre softgoals. Tais são divididas em decomposições e contribuições:

#### Decomposições

As decomposições podem ocorrer em todos os níveis de abstração: Softgoals de NFR, de Operacionalização e de Afirmação. Nas três primeiras decomposições, os softgoals são subdivididos em softgoals especificados (SILVA, 2019)<a id="anchor_1" href="#REF1">^1^</a>. Os quatro tipos estão explicitados na figura 2.

- Decomposição NFR: ajuda a dividir vicissitudes primordiais em partes menores, o que reduz as ambiguidades e facilita a priorização.
- Decomposição de Operacionalização: tem por finalidade refinar uma solução geral em soluções particulares.
- Decomposição de Afirmação: serve como afirmação ou negação de justificativas específicas do projeto.
- Decomposição de Priorização: trata-se de uma decomposição especial, na qual o softgoal é refinado em outro softgoal de mesmo tipo e tópico. No entanto, associa-se uma prioridade.



<font size="3"><p style="text-align: center"><b>Figura 2</b> - Tipos de Decomposição</p></font>

<figure markdown class="usecaseElement">

![DECOMPOSIÇÃO](../../assets/nfr-framework/decompL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>



#### Contribuições

Num NFR Framework, os softgoals se especializam cada vez mais. Por conseguinte, o um softgoal derivado de outro pode contribuir de forma integral ou truncada, e também de forma positiva ou negativa, para o softgoal do qual ele derivou. Portanto, listar-se-á os tipos de contribuição<a id="anchor_2" href="#REF2">^2^</a>:

- AND: se os softgoals derivados forem satisfeitos, o softgoal primordial também será.
- OR: se algum dos softgoals derivados forem satisfeitos, o softgoal primordial também será.
- MAKE(++): um softgoal originado contribui de forma plenamente positiva, logo o softgoal original também será satisfeito.
- BREAK(--): um softgoal originado contribui de forma plenamente negativa, logo o softgoal original será negado.
- HELP(+): um softgoal originado realiza uma contribuição restritamente positiva, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- HURT(-): um softgoal originado realiza uma contribuição restritamente negativa, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- UNKNOWN(?): contribuição incógnita.
- EQUALS: relação direta entre as satisfações do softgoal derivado e a do primordial.
- SOME: a forma de contribuição é conhecida, no entanto, a intensidade dessa contribuição é desconhecida.

#### Propagação de Impactos

A propagação de impactos no NFR Framework  envolve a identificação das relações de dependência entre os requisitos não funcionais, bem como a análise de como uma mudança em um requisito pode afetar outros requisitos relacionados. Isso requer uma compreensão clara das interações entre os requisitos, bem como a capacidade de avaliar as prioridades e trade-offs entre eles. Ao considerar a propagação de impactos, os engenheiros de requisitos podem tomar decisões informadas sobre mudanças e gerenciar os possíveis efeitos colaterais de forma eficaz. A seguir são apresentados os tipos de softgoals de impacto e suas respectivas notações<a id="anchor_2" href="#REF2">^2^</a>:

- ✓ (satisfeito): Indica que um requisito não funcional contribui positivamente para a satisfação de outro requisito.
- 𝒲+ (fracamente satisfeito): ndica uma relação de impacto positiva, mas menos forte do que a notação ✓.
- X (negado): Indica que um requisito não funcional afeta negativamente outro requisito, negando ou contradizendo sua realização. 
- 𝒲- (fracamente negado): Similar à notação X, mas com uma relação de negação mais fraca. 
- 🗲 (conflitante): Indica uma relação de conflito entre requisitos não funcionais. Isso significa que os requisitos possuem características positivas e negativas.
- u (indeterminado): Uma relação indeterminada ou desconhecida entre requisitos não funcionais. Isso ocorre quando não há informações suficientes para determinar o impacto de um requisito em outro.

## Metodologia

Os frameworks foram separados por temas, esses temas foram divididos em três para limitar o escopo aqui trabalhado. Após isso, fez-se uma introspecção para a construção do SIG a partir dos tópicos gerais definidos, a fim de fazer relações com os Requisitos Não-Funcionais da Tabela 12, após isso, fez-se o uma revisão na literatura e foi feita a validação do SIG confeccionado. A plataforma utilizada para a elaboração foi o Draw.io.

## Cartões de Especificação

Os cartões de especificação a seguir, Tabelas de 1 a 5, foram utilizados para definir os Requisitos Não-Funcionais a serem utilizados na confecção dos NFR Frameworks. Fontes de evidência na literarura: <a id="anchor_FE2" href="#FE2">FE2</a>. 

Obs: Os valores de prioridade foram baseados no modelo de priorização First Things First que pode ser encontado [aqui](../../../elicitacao/priorizacao/firstThingsfirst).

<center>

<b>Tabela 1</b> - Cartão de Especificação 1

| Nº Requisito: 1 (<a id="anchor_NF01" href="#NF01">RNF01</a>)| Classificação: Usabilidade |
|---------------| ------------|
| Descrição: O app deve fornecer eventos direcionados.
| Justificativa: O sistema deve ser capaz de direcionar eventos ao usuário a partir de suas preferências pessoais. Assim o usuário não irá perder tempo buscando por eventos que se adequem ao seu perfil .
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve ser capaz de recomendar ao usuário eventos condizentes com suas preferências. 
| Dependências: Atividade do Usuário
| Prioridade: 4,05
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 2</b> - Cartão de Especificação 2

| Nº Requisito: 2 (<a id="anchor_NF02" href="#NF02">RNF02</a>)| Classificação: Usabilidade/Eficiência |
|---------------| ------------|
| Descrição: O app deve disponibilizar todas as informações do evento em uma página.
| Justificativa: Contribui para uma melhor visualização das informações por parte do usuário, e por conseguinte melhora a eficiência do app.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve disponibilizar todas informações necessárias sobre o evento em uma única página.
| Dependências: Nenhuma
| Prioridade: 2,70
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 3</b> - Cartão de Especificação 3

| Nº Requisito: 3 (<a id="anchor_NF03" href="#NF03">RNF03</a>)| Classificação: Eficiência/Desempenho |
|---------------| ------------|
| Descrição: A compra de ingressos deve ser realizada em menos de 5 páginas (botões)
| Justificativa: Operações que podem ser efetuadas em menos de 5 cliques em geral são consideradas eficientes. No caso do processo de compra, quão mais rapidamente essa operação for efetuada, não só o tempo gasto pelo usuário, mas também o gasto de energia do aplicativo serão reduzidos.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: O sistema deve efetuar a operação de compra em menos de 5 cliques.
| Dependências: Informações Suficientes
| Prioridade: 1,35
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

<center>

<b>Tabela 4</b> - Cartão de Especificação 4

| Nº Requisito: 4 (<a id="anchor_NF04" href="#NF04">RNF04</a>)| Classificação: Eficiência |
|---------------| ------------|
| Descrição: As ações realizadas no app não devem demorar mais que 200 ms para responder ao usuário
| Justificativa: As ações rápidas no app garantem uma experiência fluida, mantendo o usuário engajado e evitando frustrações desnecessárias.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: As ações realizadas no app devem ser executadas e responder ao usuário em um tempo máximo de 250 ms para garantir uma experiência ágil e satisfatória.
| Dependências: Performance
| Prioridade: 0,469
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Sidney Fernando](https://github.com/nando3d3)

</center>


<center>

<b>Tabela 5</b> - Cartão de Especificação 5

| Nº Requisito: 5 (<a id="anchor_NF05" href="#NF05">RNF05</a>)| Classificação: Usabilidade |
|---------------| ------------|
| Descrição: O app deve permitir a filtragem dos eventos cadastrados no banco de dados.
| Justificativa: A filtragem de eventos no app proporciona aos usuários a capacidade de encontrar rapidamente informações relevantes, melhorando a usabilidade e a eficiência na busca de eventos específicos no banco de dados.
| Origem do Requisisto: Projetista de Software
| Critério de Aceitação: Filtragem flexível.
| Dependências: Atividade do Usuário
| Prioridade: 1,042
| Conflitos: Nenhum
| História: 23/05/2023

Fonte: [Sidney Fernando](https://github.com/nando3d3)

</center>

## NFR 00 - Geral

A Figura 3 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.


<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralL.png)

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>

No entanto, dada a limitação do grupo de trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo site, adaptou-se o SIG acima para a utilização dos tópicos necessários, presentes na Figura 4.

<font size="3"><p style="text-align: center"><b>Figura 4</b> - SIG Geral Adaptado</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralattD.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: (SILVA, 2019)</p></font>


## NFR 01 - Usabilidade

Os Requisitos utilizados para a confecção da Figura 5 estão presentes na Tabela 12:

- <a id="anchor_NF01" href="#NF01">RNF01</a>: indica que o usuário deve receber eventos sugeridos de acordo com sua atividade no site.
- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF05" href="#NF05">RNF05</a>: refere-se à necessidade da filtragem sob diversas óticas dentro da busca no site.


<font size="3"><p style="text-align: center"><b>Figura 5</b> - SIG Usabilidade</p></font>

<figure markdown markdown class="usecaseElement">

![SIG Usabilidade](../../assets/nfr-framework/usabilidade.png){width: 300}

</figure>

<font size="3"><p style="text-align: center"> Fonte: Autores</p></font>



Legenda:

- Sugestões: refere-se ao [L02 - Sugestões de Eventos](../../lexicos/#l02-sugestoes-de-eventos).
- Opções de filtro: refere-se ao [L01 - Filtrar Eventos](../../lexicos/#l01-filtrar-eventos).

### Requisitos Não-Funcionais - Usabilidade

Na Tabela 6, estão listados os RNF presentes no NFR Famework de Usabilidade :

<center>
<b>Tabela 6</b> - Requisitos Não-Funcionais 1

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Adaptação (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve ser adaptativo às atividades do usuário. | Usabilidade | Sugestões |
| Disponibilidade (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve disponibilizar as informações. | Usabilidade | Usabilidade |
| Exibir Inf. do Evento (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve exibir as informações do evento específico. | Usabilidade | Informações Relevantes |
| Sugestões Gerais (<a id="anchor_FE3" href="#FE3">FE3</a>) | O sistema deve exibir as sugestões padrões antes de se ter uma atividade do usuário no site, feitas com base no [Usuário](../../lexicos/#l05-usuario). | Usabilidade | Sugestões |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)
</center>

### Propagação dos Impactos - Usabilidade

A seguir, na Tabela 7, temos a avaliação da propagação dos impactos relativa à Figura 5.

<center>

<b>Tabela 7</b> - Impactos Usabilidade

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Usabilidade|  𝒲-| [Gabriel Campello](https://github.com/G16C)|
|Antecipação |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Sugestões| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Adaptação| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Sugestões Gerais| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Atividade do Usuário| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Disponibilidade| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Busca| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Filtro| 𝒲-|[Gabriel Campello](https://github.com/G16C)|
|Opções de Filtro| X|[Gabriel Campello](https://github.com/G16C)|
|Busca Multivalorada| X|[Gabriel Campello](https://github.com/G16C)|
|Informações Relevantes| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Exibir Inf. do Evento| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Página Única| X|[Gabriel Campello](https://github.com/G16C)|

Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 02 - Eficiência

Os Requisitos utilizados para a confecção da Figura 6 estão presentes na Tabela 12:

- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.


<font size="3"><p style="text-align: center"><b>Figura 6</b> - SIG Eficiência</p></font>
<figure markdown class="usecaseElement">

![SIG Eficiência](../../assets/nfr-framework/eficiencia.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>

Legenda:

- Processar Rapidamente: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.
- Informações Suficientes: informações suficientemente relevantes para a realização de um processo.

### Requisitos Não-Funcionais - Eficiência

Na Tabela 8, estão listados os RNF presentes no NFR Famework de Eficiência:

<center>

<b>Tabela 8</b> - Requisitos Não-Funcionais 2

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Eficiência | Limitações |
| Limite de Páginas (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma limitação do espaço ocupado. | Eficiência | Limitações |
| Apresentar Informações (<a id="anchor_FE1" href="#FE1">FE1</a>) | O sistema deve exibir as informações do evento específico. | Eficiência | Limite de Páginas |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

### Propagação dos Impactos - Eficiência

Na Tabela 9, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 9</b> - Impactos Eficiência

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Eficiência|  𝒲+| [Gabriel Campello](https://github.com/G16C)|
|Executar Apropriadamente |  𝒲+|  [Gabriel Campello](https://github.com/G16C)|
|Processar Requisitos| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Processar Corretamente| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Recuperar de Erros| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Prevenção de Erros|  𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Limitações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de Páginas| 𝒲+|[Gabriel Campello](https://github.com/G16C)|
|Apresentar Informações| ✓|[Gabriel Campello](https://github.com/G16C)|
|Informações Suficientes| ✓|[Gabriel Campello](https://github.com/G16C)|
|Limite de 5 Páginas| X|[Gabriel Campello](https://github.com/G16C)|
|Tempo de Resposta| ✓ |[Gabriel Campello](https://github.com/G16C)|
|Processar Rapidamente| ✓ |[Gabriel Campello](https://github.com/G16C)|


Fonte: [Gabriel Campello](https://github.com/G16C)

</center>

## NFR 03 - Desempenho

Os Requisitos utilizados para a confecção da Figura 7 estão presentes na Tabela 12:

- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta a 200ms.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho</p></font>
<figure markdown class="usecaseElement">

![SIG Desempenho](../../assets/nfr-framework/desempenhoL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Sidney Fernando](https://github.com/nando3d3)</p></font>

Legenda:

- Ordem Lógica: uma compra deve aplicar a ordem lógica observada na vida real.
- Limite de páginas: refere-se ao <a id="anchor_NF03" href="#NF03">RNF03</a>, o qual limita a quantidade de páginas em até 5 para a compra.
- Velocidade: refere-se ao <a id="anchor_NF04" href="#NF04">RNF04</a>, o qual limita o tempo de resposta a 200ms.

### Requisitos Não-Funcionais - Desempenho

Na Tabela 10, estão listados os RNF presentes no NFR Famework de Desempenho :

<center>

<b>Tabela 10</b> - Requisitos Não-Funcionais 3

| RNF (Fonte) | Descrição | Classificação | Origem |
|-------------|---------|-------|-------|
| Tempo de Resposta (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) |  O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. | Desempenho | Desempenho |
| Infraestrutura (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve possuir uma infraestrutura para processar e perdurar os dados. | Desempenho | Tempo de Resposta |
| Servidores (<a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve exibir possuir servidores para perdurar os dados. | Desempenho | Infraestrutura |
| Manutenção (<a id="anchor_FE1" href="#FE1">FE1</a> e <a id="anchor_FE2" href="#FE2">FE2</a>) | O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura. | Desempenho | Infraestrutura |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

### Propagação dos Impactos - Desempenho

Na Tabela 11, está presente a avaliação da propagação dos impactos referentes à Figura 6.

<center>

<b>Tabela 11</b> - Impactos Desempenho

| NFR | Impacto | Avaliador |
|-----|---------|-------|
|Desempenho |  🗲| [Arthur de Melo](https://github.com/arthurmlv)|
|Realizar Ações| 🗲|[Arthur de Melo](https://github.com/arthurmlv)|
|Compra| 🗲|[Arthur de Melo](https://github.com/arthurmlv)|
|Ordem Lógica| ✓|[Arthur de Melo](https://github.com/arthurmlv)|
|Ações Rápidas|  X|[Arthur de Melo](https://github.com/arthurmlv)|
|Limite de Páginas| 𝒲-|[Arthur de Melo](https://github.com/arthurmlv)|
|Velocidade| 𝒲-|[Arthur de Melo](https://github.com/arthurmlv)|
|Processar Corretamente| ✓|[Arthur de Melo](https://github.com/arthurmlv)|
|Tempo de Resposta| 𝒲+|[Arthur de Melo](https://github.com/arthurmlv)|
|Infraestrutura| 𝒲+|[Arthur de Melo](https://github.com/arthurmlv)|
|Servidores| 𝒲+ |[Arthur de Melo](https://github.com/arthurmlv)|
|Manutenção| ✓ |[Arthur de Melo](https://github.com/arthurmlv)|


Fonte: [Arthur de Melo](https://github.com/arthurmlv)

</center>

## Requisitos Não-Funcionais

A Tabela 12 a seguir lista os Requisitos Não-Funcionais utilizados para a criação do NFR Framework.

<p style="text-align: center"><b>Tabela 12</b> - Requisitos Não-Funcionais Não Implementados</p>

| ID    | Descrição                                                                     | Rastreabilidade                                                                                                                                                                                                                                                                                                                                                                                                                               | Implementação |
| ----- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| <a id="NF01" href="#anchor_NF01">RNF01</a> | O app deve fornecer eventos direcionados.                                     | [IS10](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q11](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [BS35](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS36](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS22](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                       | Não           |
| <a id="NF02" href="#anchor_NF02">RNF02</a> | O app deve disponibilizar todas as informações do evento em uma página.       | [IS11](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [BS25](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS26](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS27](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS28](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS29](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS30](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS15](<(../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)>), [OBS16](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF) | Não           |
| <a id="NF03" href="#anchor_NF03">RNF03</a> | A compra deve ser feita em no máximo 5 páginas.                               | [IS13](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [IS16](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q14](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [OBS17](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [OBS18](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [IS14](../../../elicitacao/tecnicas/introspeccao/#anchor_IS)                                                                                                                                                              | Não           |
| <a id="NF04" href="#anchor_NF04">RNF04</a> | O app não deve ter tempo de resposta superior a 200 ms.                       | [Q12](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |
| <a id="NF05" href="#anchor_NF05">RNF05</a> | O app deve permitir a filtragem dos eventos cadastrados no banco de dados.    | [Q13](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/mathonaut">Matheus Henrique</a> e <a href="https://github.com/arthurmlv">Arthur de Melo</a></p></font>

A Tabela 13 lista os Requisitos Não-Funcionais elicitados pelo NFR Framework.

<center>
<b>Tabela 13</b> - Requisitos Elicitados NFR

|  ID  | Descrição |
|------|---------|
|NFR01| O sistema deve possuir uma limitação superior do tempo de processamento de uma requisição. |
|NFR02| O sistema deve possuir uma infraestrutura para processar e perdurar os dados.|
|NFR03| O sistema deve exibir possuir servidores para perdurar os dados.|
|NFR04| O sistema deve ser capaz de realizar a manutenção dos servidores e de outros aspectos da infraestrutura.|
|NFR05| O sistema deve possuir uma limitação do espaço ocupado.|
|NFR06| O sistema deve exibir as informações do evento específico.|
|NFR07| O sistema deve disponibilizar as informações.|
|NFR08| O sistema deve ser adaptativo às atividades do usuário.|

Fonte: [Arthur de Melo](https://github.com/arthurmlv)
</center>

## Fontes Externas

Por fim, a Tabela 14 explicita as Fontes Externas como revisão na literatura.

<center>
<b>Tabela 14</b> - Fontes Externas

| ID  | Autores | Título |
|-----|---------|--------|
| <a id="FE1" href="#anchor_FE1">FE1</a> |  SILVA  | NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados |
| <a id="FE2" href="#anchor_FE2">FE2</a> |  PAIM, et al | Enhancing Data Warehouse Design with the NFR Framework |
| <a id="FE3" href="#anchor_FE3">FE3</a> |  CHUNG, et al | Non-functional requirementsin software engineering |

Fonte: [Arthur de Melo](https://github.com/arthurmlv)
</center>

## Bibliografia

> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: <http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf>. Acesso em: 22/05/2023

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2023.

> <a id="REF2" href="#anchor_2">2.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.


## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 22/05/2023 | Introdução, SIG, Tipos de Softgoal e Interdependências.| [Arthur de Melo](https://github.com/arthurmlv)   | [Geovanna Maciel](https://github.com/manuziny)   |
| `1.1`  | 22/05/2023 | SIG Usabilidade e Desempenho | [Arthur de Melo](https://github.com/arthurmlv), [Gabriel Campello](https://github.com/G16C) e [Sidney Fernando](https://github.com/nando3d3)   | [Geovanna Maciel](https://github.com/manuziny) |
| `1.1`  | 22/05/2023 | SIG Eficiência | [Arthur de Melo](https://github.com/arthurmlv), [Gabriel Campello](https://github.com/G16C) e [Sidney Fernando](https://github.com/nando3d3)   | [Geovanna Maciel](https://github.com/manuziny) |
| `1.4`  | 22/05/2023 | Adição Notações de Impacto e Avaliação Impactos Usabilidade  |  [Gabriel Campello](https://github.com/G16C)  | [Geovanna Maciel](https://github.com/manuziny) |
| `1.5`  | 22/05/2023 | Avaliação Impactos Eficiência  |  [Gabriel Campello](https://github.com/G16C)  | [Geovanna Maciel](https://github.com/manuziny) |
| `1.6`  | 23/05/2023 | Cartões de Especificação e Avaliação Impactos Desempenho.| [Arthur de Melo](https://github.com/arthurmlv)   | [Geovanna Maciel](https://github.com/manuziny)   |
| `1.7`  | 23/05/2023 | Requisitos Elicitados e hyperlinks.| [Arthur de Melo](https://github.com/arthurmlv)   | [Geovanna Maciel](https://github.com/manuziny)   |
| `1.8`  | 23/05/2023 | Adição dos Cartões 1 a 3 e refatoração de Tabelas  |  [Gabriel Campello](https://github.com/G16C)  | [Geovanna Maciel](https://github.com/manuziny) |
| `1.9`  | 23/05/2023 | Adição dos Cartões 4 e 5  |  [Sidney Fernando](https://github.com/nando3d3)  | [Geovanna Maciel](https://github.com/manuziny) |

