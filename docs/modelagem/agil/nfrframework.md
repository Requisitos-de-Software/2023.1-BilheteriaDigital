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
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>



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
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>



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

## Metodologia

Os frameworks foram separados por temas. A plataforma utilizada para a elaboração foi o Draw.io.

## NFR 00 - Geral

A Figura 3 a seguir demonstra o Softgoal Interdependency Graph para se ter uma visão geral.


<font size="3"><p style="text-align: center"><b>Figura 3</b> - SIG Geral</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralL.png)

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Gabriel Campello](https://github.com/G16C)</p></font>

No entanto, dada a limitação do grupo de trabalhar apenas com Requisitos Não-Funcionais ainda não implementados pelo site, adaptou-se o SIG acima para a utilização dos tópicos necessários, presentes na Figura 4.

<font size="3"><p style="text-align: center"><b>Figura 4</b> - SIG Geral Adaptado</p></font>
<figure markdown class="usecaseElement">

![SIG GERAL](../../assets/nfr-framework/geralattD.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Gabriel Campello](https://github.com/G16C)</p></font>


## NFR 01 - Usabilidade

Os Requisitos utilizados para a confecção da Figura 5 estão presentes na Tabela 1:

- <a id="anchor_NF01" href="#NF01">RNF01</a>: indica que o usuário deve receber eventos sugeridos de acordo com sua atividade no site.
- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF05" href="#NF05">RNF05</a>: refere-se à necessidade da filtragem sob diversas óticas dentro da busca no site.

<figure markdown>

<font size="3"><p style="text-align: center"><b>Figura 5</b> - SIG Usabilidade</p></font>

![Diagrama do Modelo de Ciclo de Vida de Mayhew](../../assets/nfr-framework/usabilidade.png#only-light){width: 300}
![Diagrama do Modelo de Ciclo de Vida de Mayhew](../../assets/nfr-framework/usabilidadeD.png#only-dark){width: 300}

<font size="3"><p style="text-align: center"> Fonte: Autores</p></font>

</figure>

### Propagação dos Impactos


## NFR 02 - Eficiência

Os Requisitos utilizados para a confecção da Figura 6 estão presentes na Tabela 1:

- <a id="anchor_NF02" href="#NF02">RNF02</a>: infere que todas as informações de um evento devem estar contidas em uma única página, sem páginas adicionais ou pop-ups.
- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta em 200ms.


<font size="3"><p style="text-align: center"><b>Figura 6</b> - SIG Eficiência</p></font>
<figure markdown class="usecaseElement">

![SIG Eficiência](../../assets/nfr-framework/eficiencia.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>

### Propagação dos Impactos

## NFR 03 - Desempenho

Os Requisitos utilizados para a confecção da Figura 7 estão presentes na Tabela 1:

- <a id="anchor_NF03" href="#NF03">RNF03</a>: limita em até 5 a quantidade de páginas para realizar a compra.
- <a id="anchor_NF04" href="#NF04">RNF04</a>: limita o tempo de resposta em 200ms.

<font size="3"><p style="text-align: center"><b>Figura 7</b> - SIG Desempenho</p></font>
<figure markdown class="usecaseElement">

![SIG Desempenho](../../assets/nfr-framework/desempenhoL.png){width: 300}

</figure>
<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Sidney Fernando](https://github.com/nando3d3)</p></font>

### Propagação dos Impactos

## Requisitos Não-Funcionais

<p style="text-align: center"><b>Tabela 1</b> - Requisitos Não-Funcionais</p>

| ID    | Descrição                                                                     | Rastreabilidade                                                                                                                                                                                                                                                                                                                                                                                                                               | Implementação |
| ----- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| <a id="NF01" href="#anchor_NF01">RNF01</a> | O app deve fornecer eventos direcionados.                                     | [IS10](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q11](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [BS35](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS36](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS22](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                       | Não           |
| <a id="NF02" href="#anchor_NF02">RNF02</a> | O app deve disponibilizar todas as informações do evento em uma página.       | [IS11](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [BS25](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS26](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS27](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS28](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS29](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS30](../../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS15](<(../../../elicitacao/tecnicas/observacao/#anchor_OBSNF)>), [OBS16](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF) | Não           |
| <a id="NF03" href="#anchor_NF03">RNF03</a> | A compra deve ser feita em no máximo 5 páginas.                               | [IS13](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [IS16](../../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q14](../../../elicitacao/tecnicas/questionario/#anchor_QNF), [OBS17](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [OBS18](../../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [IS14](../../../elicitacao/tecnicas/introspeccao/#anchor_IS)                                                                                                                                                              | Não           |
| <a id="NF04" href="#anchor_NF04">RNF04</a> | O app não deve ter tempo de resposta superior a 200 ms.                       | [Q12](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |
| <a id="NF05" href="#anchor_NF05">RNF05</a> | O app deve permitir a filtragem dos eventos cadastrados no banco de dados.    | [Q13](../../../elicitacao/tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |

<font size="3"><p style="text-align: center"><b>Fonte: <a href="https://github.com/mathonaut">Matheus Henrique</a></p></font>


## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2023.

> <a id="REF2" href="#anchor_2">2.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.


## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 22/05/2023 | Introdução, SIG, Tipos de Softgoal e Interdependências.| [Arthur de Melo](https://github.com/arthurmlv)   | [Sidney Fernando](https://github.com/nando3d3)   |
| `1.1`  | 22/05/2023 | SIG Usabilidade e Desempenho | [Arthur de Melo](https://github.com/arthurmlv), [Gabriel Campello](https://github.com/G16C) e [Sidney Fernando](https://github.com/nando3d3)   | [Geovanna Maciel](https://github.com/manuziny) |
| `1.1`  | 22/05/2023 | SIG Eficiência | [Arthur de Melo](https://github.com/arthurmlv), [Gabriel Campello](https://github.com/G16C) e [Sidney Fernando](https://github.com/nando3d3)   | [Geovanna Maciel](https://github.com/manuziny) |