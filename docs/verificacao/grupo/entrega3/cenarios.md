# Verificação dos Cenários do Grupo

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [Cenários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/) da Etapa 3 do [nosso grupo (Grupo 1)](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das [checklists](./planejamento-verificacao-e3-grupo.md#checklists) elaboradas na página de planejamento. Para responder às perguntas apresentadas nas checklists o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](./planejamento-verificacao-e3-grupo.md#cronograma). A tabela 1 apresenta os participantes dessa verificação.

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
| [Arthur de Melo](https://github.com/arthurmlv) | Avaliador |
|   [Rafael Ferreira](https://github.com/RafaelCLG0)   | Revisor  |

_Fonte: Elaborada por [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center> 

## Sumário Dos Dados

A Tabela 2 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 2** - Checklist para a Verificação dos Cenários.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 1   | O artefato possui introdução? |      Sim     |             |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?   |     Sim      |             |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |    Sim       |             |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? |     Sim      |             |
| 5   | Todos os textos estão na norma padrão? |     Sim      |  Tabelas de 1 a 4 com título escrito errado.           |
| 6   | O cenário possui: título, metas/objetivos, contexto, ator(es), recursos, exceções, restrições e episódios?<a id="anchor_1" href="#REF1">^1^</a>  |     Sim      |            |
| 7   | O título do cenário é autoexplicativo?<a id="anchor_2" href="#REF2">^2^</a>  |     Sim      |   No entanto, seria interessante especificar o título de cada cenário no tópico do referido.          |
| 8   | O objetivo do cenário é condizente com seu título?<a id="anchor_2" href="#REF2">^2^</a> |     Incompleto      |  [Cenário 2](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-2)          |
| 9   | O contexto descreve de forma sucinta o estado inicial do cenário? Em função de local, tempo e pré-condições, por exemplo.<a id="anchor_1" href="#REF1">^1^</a>       |     Sim      |             |
| 10   | O cenário descreve situações realistas e relevantes de interação do sistema?<a id="anchor_1" href="#REF1">^5^</a>      |     Sim      |             |
| 11   | Os atores são condizentes com o contexto do cenário?<a id="anchor_2" href="#REF2">^2^</a>|     Sim      |              |
| 12   | Os episódios do cenário estão coerentes e seguem uma ordem lógica para atingir o objetivo?<a id="anchor_2" href="#REF2">^2^</a>|     Sim      |             |
| 13   | Existe uma ligação entre os cenários e os léxicos?<a id="anchor_2" href="#REF2">^2^</a> |     Não      |             |

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

## Lista de Problemas e Análise

### ID 8 - O objetivo do cenário é condizente com seu título?

Praticamente todos os cenários apresentam objetivos condizentes com seus títulos. Contudo, o Cenário 02 (Filtrar eventos por data e hora de ocorrência) não, enquanto seu título remete a algo amplo, que pode ser tanto um intervalo de tempo quanto um horário mais restrito num mesmo dia, seu objetivo apresenta somente "permitir que o usuário encontre eventos que ocorram em uma data e hora específica". Dessa maneira, o objetivo deveria apresentar esse caráter mais amplo da atividade.

### ID 13 - Existe uma ligação entre os cenários e os léxicos?

No contexto da Engenharia de Requisitos, cenários são naturalmente ligados ao Léxico Ampliado da Linguagem. Isso pois os primeiros são, em suma, uma descrição evolutiva de situações em um domínio em específico<a id="anchor_2" href="#REF2">^2^</a>, enquanto o segundo é um metamodelo projetado justamente para ajudar a entender a linguagem de um determinado domínio<a id="anchor_1" href="#REF1">^1^</a>. Portanto, para facilitar a compreensão de alguns artefatos, deve-se realizar a conexão entre esses e os léxicos relacionados. Por exemplo, o usuário pode ser explicado pelo [Léxico 05 - Usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario).

Além disso, como grande parte dos Cenários envolvem a filtragem de uma busca, o [Léxico 01 - Filtrar Eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) engloba esse aspecto e está diretamente relacionado a essa parcela, bem como lista os requisitos conectados.

## Sugestões de Correções

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

* Corrigir os erros nos títulos das tabelas.
* Reescrever o objetivo do Cenário 02 de forma apropriada;
* Estabelecer uma ligação entre os termos usados nos cenários e os léxicos correspondentes.

## Acompanhamento

A figura 1 é possível análisar um gráfico com o percentual de erros e acertos de acordo com checklist dos resultados obtidos acima.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Gráfico com resultado da Checklist.</p></font>
<iframe style="border:3px solid red" width="648" height="401" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRhhY2KSUnywMQLD7HQhpDvpx2kI7Z02TieYtu8wLwtz65WXYw4c9odBXZzAnSDtKEeB2TUjCNkZZU2/pubchart?oid=618472477&amp;format=interactive"></iframe><figcaption><font size="3">Fonte: [Arthur de Melo](https://github.com/arthurmlv)</font></figcaption>
</figure>


## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>BERGMANN, Ulf. Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações. 2003. Tese de Doutorado (Departamento de Informática) - Pontifícia Universidade Católica do Rio de Janeiro, [S. l.], 2003. p. 47-50.

> <a id="REF2" href="#anchor_2">2.</a>Leite, J.C.S.d.P., Rossi, G., Balaguer, F. et al. Enhancing a requirements baseline with scenarios. Requirements Eng 2, 44–53 (1997).

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv)  | [Rafael Ferreira](https://github.com/RafaelCLG0) |