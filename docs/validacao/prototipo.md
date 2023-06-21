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
 

Caso queira conferir o protótipo, <a href="https://marvelapp.com/prototype/9i40deb" target="blanket">clique aqui</a>.

<p style="text-align: center"><iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Ffile%2FCSsRpoXBR0BWWojN1ZrDn0%2FProt%25C3%25B3tipo-de-Alta-FIdelidade%3Ftype%3Ddesign%26node-id%3D107%253A1118%26t%3D0G0oREDbF7bGYprn-1" allowfullscreen></iframe></p>

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

O número de participantes foi de cinco pessoas, sendo dois entrevistadores e três usuários. Por mais que essa validação não seja exatamente um teste de usabilidade, a escolha desse número foi baseada na recomendação de Krug (, p. 157)<a id="REF2" href="#anchor_2">2</a> para testes de usabilidade. A escolha dos participantes levou em conta o [perfil de usuário](https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/analise-de-requisitos/perfil-usuario/#conclusao), tendo estes entre 20 e 35 anos e também são, de certa forma, tecnófilos.

### Entrevistas

De maneira geral, todos os entrevistados aprovaram o protótipo, apenas pontuando alguns tópicos em específico nas interfaces, assim como poderá ser observado melhor no detalhamento de cada entrevista. Os vídeos 1, 2 e 3 trazem a gravação das respectivas entrevistas de validação.

#### Entrevista 1

<p style="text-align: center"><a href="https://www.youtube.com/embed/172V6xKaw0g" target="blanket">Vídeo 1 - Entrevista Eduardo</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/172V6xKaw0g"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>


#### Entrevista 2

<p style="text-align: center"><a href="https://www.youtube.com/embed/6zlfjwXuqHM" target="blanket">Vídeo 2 - Entrevista Arthur</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/6zlfjwXuqHM"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>

#### Entrevista 3

<p style="text-align: center"><a href="https://www.youtube.com/embed/oW9w-VyjHUc" target="blanket">Vídeo 3 - Entrevista Bruno</a></p>

<p style="text-align: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/oW9w-VyjHUc"></iframe></p>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3).</p></font>

### Sumário dos principais resultados

Isso posto, propõe-se as seguintes sugestões de correção:

- Transformar o filtro de idade em um menu dropdown.
- Adicionar uma opção de busca nas telas de estados e cidades.
- Definir mais claramente os botões de confirmar e voltar nas telas dos filtros.

### Planejamento de Reprojeto

As mudanças sugeridas e os outras vicissitudes encontradas ao se fazer a análise do artefato especificado devem ser consideradas para a realização de um reprojeto. No entanto, tal reprojeto deve manter a base do projeto original e realizar somente as alterações necessárias de fato. Logo, a Tabela 2 explicita um possível cronograma de reprojeto para realizar as mudanças sugeridas e analisadas.

<center>
**Tabela 2** - Cronograma de Reprojeto.

| Executores do Reprojeto  | Horário de Início | Horário de Fim |    Data    |
| :----------------:  | :---------------: | :------------: | :--------: |
| [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3)  | 19:00 | 19:30 | 24/06/2023 |

**Fonte** - [Douglas Alves](https://github.com/dougalvs).
</center>

## Referências Bibliográficas

> <a id="anchor_1" href="#REF1">1.</a> Design, Prototipação e Construção. In: ROGERS, Yvonne. Design de Interação: Além da Interação Humano-Computador. 3. ed. [S. l.]: Bookman, 2013. cap. 8, p. 259-297.
> <a id="anchor_2" href="#REF2">2.</a> GUILHERME SANTA ROSA, José. Avaliação E Projeto No Design De Interfaces. [S. l.: s. n.], 2010.


## Histórico de Versão

Versão  | Data | Descrição | Autor(es) | Revisor(es)
-------- | ------ | ------ | ---------- | ----------
`1.0` | 21/06/2023 | Criação do artefato  | [Douglas Alves](https://github.com/dougalvs) e [Sidney Fernando](https://github.com/nando3d3) | [Gabriel Campello](https://github.com/g16c)
