# Protótipo de Alta Fidelidade

## Introdução

A protipação envolve a criação de representações funcionais ou simulações de sistemas de interalção antes da implementação final. Como explica <a id="REF1" href="#anchor_1">1</a>, ao ter acesso às informações sobre práticas de trabalho e ideias para um sistema, é necessário experimentar essas ideias por meio da construção de protótipos e iterações contínuas. Quanto mais iterações forem realizadas, melhor será o resultado final do produto. A prototipação é essencial para realizar a validação do produto, pois permite testar ideias, funcionalidades e fluxos de interação com os usuários antes da implementação final. Com protótipos, é possível obter feedback, identificar problemas e realizar iterações para melhorar a usabilidade e garantir um produto final mais eficaz e satisfatório.

### Objetivos

O grupo desenvolveu um protótipo de alta fidelidade utilizando a ferramenta Figma para simular a tela do aplicativo Bilheteria Digital. O objetivo é implementar os <a href="../../elicitacao/requisitos_elicitados#tab_1">requisitos</a>:

* RF01 - O aplicativo filtra os eventos por Estado e por Município.
* RF02 - O aplicativo filtra os eventos por data e por horário.
* RF03 - O aplicativo filtra os eventos por idade mínima de entrada.
* RF10 - O aplicativo filtra eventos por categorias.

Após a criação do protótipo, foram realizadas três entrevistas com usuários reais. Essas entrevistas permitiram coletar feedback valioso sobre a usabilidade das novas funcionalidades implementadas, a compreensão das funcionalidades e a eficácia do design proposto, para assim poder validar esses requisitos.

### Método de avaliação

No início de todas as entrevistas foi apresentado o termo de consentimento para que o entrevistado dê sua resposta, sempre reforçando o fato de que está sendo gravado e de que a gravação será publicada. As entrevistas foram feitas pessoalmente na FGA, com o entrevistador mostrando e explicando as funcionalidades para o entrevistado, que expunha sua opinião a cerca da implementação e identificava pontos de melhoria. Enquanto isso, outro membro do grupo fazia anotações sobre os principais pontos observados. Portanto, fez-se a parte de preparação, e depois a coleta de dados. 
 

Caso queira conferir o protótipo, <a href="https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Prot%C3%B3tipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1&mode=design" target="blanket">clique aqui</a>.

<p style="text-align: center"><iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FCSsRpoXBR0BWWojN1ZrDn0%2FProt%25C3%25B3tipo-de-Alta-FIdelidade%3Fpage-id%3D0%253A1%26type%3Ddesign%26node-id%3D107-1118%26viewport%3D29390%252C34193%252C3.02%26scaling%3Dmin-zoom%26starting-point-node-id%3D107%253A1118%26show-proto-sidebar%3D1%26mode%3Ddesign" allowfullscreen></iframe></p>

O cronograma planejado para as entrevistas está presente na Tabela 1.

<center>

**Tabela 1** - Cronograma Planejado.

| Entrevistadores | Usuário | Data       | Início-Fim  | Local              |
| ------------- | ------- | ---------- | ----------- | ------------------ |
| [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3)  |<span style = "color: orange"> Eduardo Ferreira </span>| 21/06/2023 | 12:37-12:43 | FGA |
| [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3)  |<span style = "color: orange"> Arthur Grandão </span>| 21/06/2023 | 12:49-12:54 | FGA |
| [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3)  |<span style = "color: orange"> Bruno Martins </span>| 21/06/2023 | 13:00-13:07 | FGA |


Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).

</center>

### Seleção dos participantes 

O número de participantes foi de cinco pessoas, sendo dois entrevistadores e três usuários. Por mais que essa validação não seja exatamente um teste de usabilidade, a escolha desse número foi baseada na recomendação de Krug (2010, p. 157)<a id="REF2" href="#anchor_2">2</a> para testes de usabilidade. A escolha dos participantes levou em conta o [perfil de usuário](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/perfil-usuario/#conclusao), tendo estes entre 20 e 35 anos e também são, de certa forma, tecnófilos.

### Entrevistas

No geral, todos os entrevistados aprovaram o protótipo, apenas pontuando alguns tópicos em específico nas interfaces, assim como poderá ser observado melhor no detalhamento de cada entrevista. Os vídeos 1, 2 e 3 trazem a gravação das respectivas entrevistas de validação.

#### Entrevista 1

<p style="text-align: center"><a href="https://www.youtube.com/embed/0PDnUfiT_7Q" target="blanket">Vídeo 1 - Entrevista Eduardo</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/0PDnUfiT_7Q"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>

O Eduardo gostou do protótipo de maneira geral, porém na página de filtrar as cidades ele citou que elas estarem em ordem alfabética facilitaria a busca. Além disso, ele comentou que o filtro por idade ficaria interessante se fosse implementado como um menu dropdown e que os filtros de categoria talvez ficariam melhor como uma lista ao invés de um carrosel, pois assim o usuário não precisaria percorrer muitas categorias no carrosel para encontrar a que ele deseja.

#### Entrevista 2

<p style="text-align: center"><a href="https://www.youtube.com/embed/T8Sp5q1kpMo" target="blanket">Vídeo 2 - Entrevista Arthur</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/T8Sp5q1kpMo"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>

O Arthur elogiou as implementações das funcionalidades no protótipo e comentou que acredita que elas fazem sentido com o contexto da aplicação.

#### Entrevista 3

<p style="text-align: center"><a href="https://www.youtube.com/embed/39FuMw23N9w" target="blanket">Vídeo 3 - Entrevista Bruno</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/39FuMw23N9w"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>

O Bruno elogiou o protótipo, contudo pontuou alguns fatos em específico. Assim como o Eduardo ele também acredita que o filtro de idade ficaria bem implementado como um menu dropdown, além disso, ele sugeriu que as páginas de filtragem por estado e cidade apresentasse uma caixa de busca. Por último, ele também citou que seria interessante que as telas dos filtros tivessem botões para confirmar a aplicação dos filtros ou cancelá-la de forma mais clara

### Sumário dos principais resultados

Isso posto, propõe-se as seguintes sugestões de correção:

- Transformar o filtro de idade em um menu dropdown.
- Adicionar uma opção de busca nas telas de estados e cidades.
- Definir mais claramente os botões de confirmar e voltar nas telas dos filtros.
- Diminuir a quantidade de categorias no carrosel e adicionar uma opção de "Ver mais..." nele, pois assim o usuário não precisaria percorrer muitas categorias no carrosel para encontrar a que ele deseja, e poderia ser redirecionado para uma tela que apresentasse uma lista de categorias.

### Planejamento de Reprojeto

As mudanças sugeridas e os outras vicissitudes encontradas ao se fazer a análise do artefato especificado devem ser consideradas para a realização de um reprojeto. No entanto, tal reprojeto deve manter a base do projeto original e realizar somente as alterações necessárias de fato. Logo, a Tabela 2 explicita um possível cronograma de reprojeto para realizar as mudanças sugeridas e analisadas.

<center>
**Tabela 2** - Cronograma de Reprojeto.

| Executores do Reprojeto  | Horário de Início | Horário de Fim |    Data    |
| :----------------:  | :---------------: | :------------: | :--------: |
| [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3)  | 19:00 | 20:00 | 24/06/2023 |

**Fonte** - [Douglas Alves](https://github.com/dougalvs).
</center>

## Referências Bibliográficas

> <a id="anchor_1" href="#REF1">1.</a> Design, Prototipação e Construção. In: ROGERS, Yvonne. Design de Interação: Além da Interação Humano-Computador. 3. ed. [S. l.]: Bookman, 2013. cap. 8, p. 259-297.cle

> <a id="anchor_2" href="#REF2">2.</a> GUILHERME SANTA ROSA, José. Avaliação E Projeto No Design De Interfaces. [S. l.: s. n.], 2010.


## Histórico de Versão

Versão  | Data | Descrição | Autor(es) | Revisor(es)
-------- | ------ | ------ | ---------- | ----------
`1.0` | 21/06/2023 | Criação do artefato  | [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3) | [Gabriel Campello](https://github.com/g16c)
