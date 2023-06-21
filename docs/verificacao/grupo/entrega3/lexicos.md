# Verificação dos Léxicos do Grupo

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas em cima do artefato dos [Léxicos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/) da Etapa 3 do [nosso grupo (Grupo 1)](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e3-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários. A checklist foi feita com base em uma publicação de Julio Cesar Sampaio do Prado Leite<a id="anchor_1" href="#REF1">^1^</a>.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e3-grupo).

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist de Verificação.

|  ID | Descrição                                                                                              | Avaliação     | Observações                                     |
| --- | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1  | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2  | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           |                                                 |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Sim           |                                                 |
|  5  | Todos os textos estão na norma padrão?                                                                 | Sim           |            |
| 6   | Cada símbolo possui classificação, sinônimo, noção e impacto?                                          | Sim           |             |
| 7   | Cada símbolo apresenta sua noção de forma breve e compreensível?                                       | Sim           |             |
| 8   | Cada símbolo apresenta seu impacto de forma breve e compreensível?                                     | Sim          |             |
| 9   | Caso seja do tipo Estado, as definições de noção e de impacto se encaixam com o que é descrito?           | Incompleto          | [Léxico 03 - Evento com tags](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags)            | 
| 10  | Caso seja do tipo Verbo, as definições de noção e de impacto se encaixam com o que é descrito?            | Incompleto          | [Léxico 01 - Filtrar Eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos)            |
| 11  | Caso seja do tipo Objeto, as definições de noção e de impacto se encaixam com o que é descrito?           | Incompleto          | [Léxico 05 - Usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)            |
| 12  | O princípio circular foi devidamente propagado?                                                        | Sim          |             |
| 13  | A descrição dos léxicos é coerente e esclarecedora?                                                    | Sim          |             |
| 14  | O vocabulário mínimo foi apropriadamente adotado nas descrições?                                       | Sim          |             |
| 15  | Quanto à organização dos léxicos, eles respeitam sua ordem numérica?                                   | Sim          |             |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Lista de Problemas e Análise

### ID 9 - Caso seja do tipo Estado, as definições de noção e de impacto se encaixam com o que é descrito?

Por exemplo, na descrição do [Léxico 03 - Evento com tags](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags), a noção do léxico é descrita como: "Eventos vinculados às tags especificadas para aquele evento". O que significa é explicado, no entanto, não explica o que levou a esse estado. No caso, o símbolo é um Estado, logo o esperado na descrição de tal é: "o que significa e quais ações levaram a esse estado". Em alguns casos, as noções podem ser divididas em duas ou mais para simplificar algo que seria muito difícil de se explicar em uma só noção<a id="anchor_1" href="#REF1">^1^</a>. No caso, recomenda-se adicionar uma nova noção com o que levou a esse estado.

### 10 - Caso seja do tipo Verbo, as definições de noção e de impacto se encaixam com o que é descrito?

Por exemplo, na descrição do [Léxico 01 - Filtrar Eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos), a noção do léxico é descrita como: "O usuário interessado em visualizar ou comprar algum ingresso filtra os eventos na busca". No entanto, essa não se caracteriza como noção de um léxico do tipo Verbo, que deve se encaixar na seguinte definição: "quem realiza, quando acontece e quais os procedimentos envolvidos"<a id="anchor_1" href="#REF1">^1^</a>. Nesse caso, também pode se dividir as noções em duas ou mais para melhor compreensão, primeiro quem realiza e quando acontece e na outra os procedimentos.

### ID 11 - Caso seja do tipo Objeto, as definições de noção e de impacto se encaixam com o que é descrito?

No caso da noção, é representada parcialmente a definição real no caso do tipo Objeto. Por exemplo, no [Léxico 05 - Usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario), não se define o objeto em si, somente se explica quais ações afetam o objeto. Portanto, vale a seguinte definição para a noção do Objeto: "definir o objeto e identificar outros objetos com os quais se relaciona"<a id="anchor_1" href="#REF1">^1^</a>. Sendo assim, pode-se adicionar mais uma noção para explicar o objeto.


## Sugestões de Correções

- Revisar as definições de Noção e de Impacto para cada classificação de símbolo.
- Dividir as noções e os impactos em duas ou mais para simplificar.
- Adicionar as novas noções e impactos necessários.

## Acompanhamento

A figura 1 é possível análisar um gráfico com o percentual de erros e acertos de acordo com checklist dos resultados obtidos acima.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Gráfico com resultado da Checklist.</p></font>
<iframe style="border:3px solid red" width="648" height="401" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQeztVMQxGP3CuVAc6b_mQkdArz7op2O0cpvjrgQR0Tj4NUqwVxnIikBQyvyYcYsd0PeK5j7ldondnP/pubchart?oid=1638958261&amp;format=interactive"></iframe><figcaption><font size="3">Fonte: [Arthur de Melo](https://github.com/arthurmlv)</font></figcaption>
</figure>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> LEITE, Julio Cesar. Léxico Ampliado da Linguagem, 2012. Disponível em: <<https://www-di.inf.puc-rio.br/~julio/lal.pdf>>. Acesso em: 10/06/2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv)  | [Rafael Ferreira](https://github.com/RafaelCLG0) |
