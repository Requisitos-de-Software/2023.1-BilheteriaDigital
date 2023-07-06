# Verificação da Técnica de Elicitação - $100

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos. Como já citado no [planejamento](../planejamento-verificacao-e2-grupo) as questões aqui presentes nesse artefato foram retiradas dos livros _Understending your users: a pratical guide to user requirements, methods, tools, and techniques_<a id=anchor_1 href="#REF1"><sup>1</sup></a> e _User and task analysis for interface design_<a id=anchor_3 href="#REF3"><sup>3</sup></a>.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [$100](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/priorizacao/100/) da Etapa 2 do [grupo](https://github.com/Interacao-Humano-Computador/2023.1-BilheteriaDigital).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e2-grupo) Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

### Cronograma e Participantes

Os participantes são os integrantes do grupo [Gabriel Campello](https://github.com/G16C), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Matheus Henrique](https://github.com/mathonaut) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e2-grupo). A tabela 1 apresenta os participantes.

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
|    [Gabriel Campello](ttps://github.com/G16C)    | Avaliador |
| [Matheus Henrique](https://github.com/mathonaut) |  Revisor  |

_Fonte: [Gabriel Campello](https://github.com/G16C), 2023._

</center>

### Sumários dos Dados Encontrados

A tabela 2 a seguir apresenta a checklist com os dados obtidos a partir da verificação. As fontes de cada pergunta foram apresentadas na página de [planejamento](../planejamento-verificacao-e2-grupo).

<center>

**Tabela 2** - Checklist de Verificação.

|        ID        | Descrição                                                                                                                     | Avaliação  |     Observações     |
| :--------------: | ----------------------------------------------------------------------------------------------------------------------------- | :--------: | :-----------------: |
| **Padronização** |                                                                                                                               |            |                     |
|        1         | O artefato possui introdução?                                                                                                 |    Sim     |          -          |
|        2         | O artefato possui uma bibliografia/referência bibliográfica?                                                                  |    Sim     |          -          |
|        3         | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores?                        |    Sim     |          -          |
|        4         | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                                                  |    Sim     |          -          |
|        5         | Todos os textos estão na norma padrão?                                                                                        |    Sim     |          -          |
|     **$100**     |                                                                                                                               |            |                     |
|        6         | A prorização foi realizada em conjunto com um usuário real?                                                                   |    Sim     |          -          |
|       6.1        | O usuário que participou se enquadrava no perfil de usuário estabelecido?                                                     |    Sim     |          -          |
|        7         | Os requisitos priorizados aviam sido previamente eleicitados?                                                                 |    Sim     |          -          |
|       7.1        | Os requisitos prioizados passaram por algum processo de validação?                                                            | Incompleto | Falta detalhamento. |
|       7.2        | Os requisitos piorizados tinham ID identificando de qual técnica de elicitação eles eram o provenientes?                      |    Sim     |          -          |
|        8         | Utilizou-se $100 para serem distribuidos entre os requisitos a fim de prioriza-los?                                           |    Sim     |          -          |
|        9         | O processo de priorização levou em consideração a dependêcia entre requisitos?                                                |    Sim     |          -          |
|       9.1        | Os requisitos de maior prioridade são também os com mais dependências?                                                        |    Sim     |          -          |
|        10        | Para o uso posterior dessa artefato, fase de modelagem, os requisitos foram separados de forma clara quanto a sua prioridade? | Incompleto |          -          |
|       10.1       | Os requisitos foram, posteriormente, separados por nível de prioridade?                                                       |    Não     |          -          |

_Fonte: [Gabriel Campello](https://github.com/G16C) e [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Problemas Encontrados e Análise dos Dados

### ID 7.1

No artefato, está explícito que os requisitos nele utilizados foram obtidos através de técnicas de elicitação. No entanto não está aparente se os dados obtidos foram de alguma forma validados, ou seja, se houve a reunião como PO para definir se esses requisitos estavam condizentes com o intuito do projeto.

### ID 10

Segundo a literatura _Requirements (Developer Best Practices), 3rd Edition, Microsoft Press_<a id=anchor_2 href="#REF2"><sup>2</sup></a>, é importante que após a obtenção de dados vindos de alguma técnica de priorização, esses requisitos sejam separados de forma clara para que sejam reutilizados de forma eficiente em etapas posteriores do projeto.

### ID 10.1

Ainda segundo a literatura _Requirements (Developer Best Practices), 3rd Edition, Microsoft Press_<a id=anchor_2 href="#REF2"><sup>2</sup></a>, uma das formas de demarcar essas prioridades é criar um marcador (ID) que possa representar de forma clara se é um requisito de alta ou baixa prioridade.

## Sugestões de Correção

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Apresentar no artefato se essa priorização foi previamente validada;
- Separar por prioridade os requisitos após a execução da técnica.

A correção dos erros será realizada após uma discussão e validação dos problemas encontrados com o grupo e apresentação dos resultados para o professor da disciplina assim como ficou definido no [planejamento](../planejamento-verificacao-e2-grupo).

## Acompanhamento

A figura 1 apresenta um gráfico com o percentual de respostas sim, não, incompleto ou não se aplica, obtidas através da checklist de verificação.

A correção dos erros será realizada após uma discussão e validação dos problemas encontrados com o grupo e apresentação dos resultados para o professor da disciplina assim como ficou definido no [planejamento](../planejamento-verificacao-e2-grupo).

<center>

**Figura 1** - Gráfico do resultado da verificação.

<iframe style="border-radius: 5px; border:3px solid red" width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSvECp79FmirgoCcUbyhy5iAULdrv86zTI0-MOz8UbGjgT1Q9N7Ley6Y0PcGc7VxT6J-bI2KjXA4Wdw/pubchart?oid=739957801&amp;format=interactive"></iframe>

_Fonte: [Gabriel Campello](https://github.com/G16C), 2023._

</center>

## Retrabalho

Como proposto por Fagan, para o retrabalho os autores do artefato verificado serão responsáveis em um primeiro momento por corrigir os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente, porém há a possibilidade de outros integrantes do grupo realizarem as correções propostas. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição                                      |              Responsável(eis)               |                   Revisor(es)                    |      Status      |
| ---------------- | :--------------------------------------------- | :-----------------------------------------: | :----------------------------------------------: | :--------------: |
| 01/07/2023       | Apresentar a validação dos requisitos.         | [Gabriel Campello](https://github.com/G16C) | [Matheus Henrique](https://github.com/mathonaut) | :material-check: |
| 01/07/2023       | Separar por ordem de prioridade os requisitos. | [Gabriel Campello](https://github.com/G16C) | [Matheus Henrique](https://github.com/mathonaut) | :material-check: |

_Fonte: Elaborado por [Gabriel Campello](https://github.com/G16C), 2023._

</center>

As correções solicitadas acima foram realizadas.

!!! info

    O cronograma apresentado na tabela 3 pode ser alterado.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> COURAGE, C. & BAXTER,K. Understending your users: a pratical guide to user requirements, methods, tools, and techniques. San Francisco: Morgan Kaufman Publishers, 2005.

> <a id="REF2" href="#anchor_2">2.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best Practices), 3rd Edition, Microsoft Press, 2013..

> <a id="REF3" href="#anchor_3">3.</a> HACKOS, J.T. & REDISH, J.C. User and task analysis for interface design. New York: John Wiley & Sons, 1998.

## Bibliografia

> HENRIQUE, Matheus. **Verificação do Guia de Estilo.** Repositório do Grupo Bilheteria Digital da Disciplina de Interação Humano Computador da Universidade de Brasília, 2023. Disponível em: <<https://interacao-humano-computador.github.io/2023.1-BilheteriaDigital/verificacao/grupo/etapa3/guia-de-estilo/>>. Acesso em: 20 de junho de 2023

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                   | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------- | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página. | [Gabriel Campello](https://github.com/G16C) | [Matheus Henrique](https://github.com/mathonaut) |
