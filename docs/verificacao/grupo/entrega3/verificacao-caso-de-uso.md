# Verificação do Caso de Uso

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados da verificação realizada acerca do artefato [Caso de Uso](../../../../modelagem/useCase/) da Etapa 3 do [grupo](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e3-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes são os integrantes do grupo [Matheus Henrique](https://github.com/mathonaut), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Douglas Alves](https://github.com/dougAlvs) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e2-grupo). A tabela 1 apresenta os participantes dessa verificação.

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
| [Matheus Henrique](https://github.com/mathonaut) | Avaliador |
|   [Douglas Alves](https://github.com/dougAlvs)   | Revisor  |

_Fonte: Elaborada por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

### Sumários dos Dados Encontrados

A tabela 2 a seguir apresenta a checklist com os dados obtidos a partir da verificação. As fontes de cada pergunta foram apresentadas na página de [planejamento](../planejamento-verificacao-e2-grupo/#first-things-first).

<center>

**Tabela 2** - Checklist de Verificação.

|  ID  | Descrição                                                                                              |   Avaliação   | Observações |
| :--: | ------------------------------------------------------------------------------------------------------ | :-----------: | :---------: |
|      | **Padronização**                                                                                       |
|  1   | O artefato possui introdução?                                                                          |      Sim      |      -      |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                           |      Sim      |      -      |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |      Sim      |      -      |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |      Sim      |      -      |
|  5   | Todos os textos estão na norma padrão?                                                                 |      Não      |      -      |
|      | **Caso de Uso**                                                                                        |               |             |
|  6   | Cada caso provem um resultado observável e de valor para os atores ou outros interessados no sistema?  |      Sim      |      -      |
|  7   | As elipses representam as ações caso de uso? (constituem internamente fluxos/cenários)?                |      Sim      |      -      |
|  8   | Há o uso de verbos no infinitivo e não substantivos?                                                   |      Sim      |      -      |
|  9   | Os relacionamentos de extend, include e generalization estão sendo usados corretamente?                |      Não      |      -      |
|  10  | O caso de uso representa o usuário e suas interações com o sistema?                                    |      Sim      |      -      |
|  11  | O ator principal está posicionado ao lado esquerdo do sistema?                                         |      Sim      |      -      |
| 11.1 | Ele possui um nome associado?                                                                          |      Não      |      -      |
|  12  | Quando o ator é um software ou um hardware, há a tag << system >>?                                     | Não se aplica |      -      |
|  13  | O usuário reside fora das fronteiras da aplicação?                                                     |      Sim      |      -      |
|  14  | O usuário possui um nome associado a ele? Como: cliente, analista de RH, estudante, etc.               | Não se aplica |      -      |
|  15  | O caso de uso produzido é uma funcionalidade completa que entrega algum valor?                         |      Sim      |      -      |
|  16  | Os casos de uso são de requisitos funcionais?                                                          |      Sim      |      -      |
|  17  | Foi usada alguma técnica para a produção dos casos de uso?                                             |      Sim      |      -      |
|  18  | A especificação dos casos de uso consistem no detalhamento de execução dos casos de uso?               |      Sim      |      -      |
| 18.1 | A especificação segue o modelo proposto por Pimentel (2007)? <a id="anchor_1" href="#REF1">^1^</a>     |      Sim      |      -      |
|  19  | Existem fluxos como: principal, alternativo e de exceção?                                              |      Sim      |      -      |
|  20  | Cada especificação de caso uso tem somente um fluxo principal?                                         |      Sim      |      -      |
|  21  | Os fluxos principais representam como usuário usaria a funcionalidade de forma primária?               |      Sim      |      -      |
|  22  | Os fluxos alternativos são possibilidades de cenários alternativos ao fluxo principal?                 |      Sim      |      -      |
|  23  | Os fluxos de exceção demonstram como o sistema reagirá na presença de situações inesperadas?           |      Não      |      -      |
|  24  | A fronteira do sistema é apresentada?                                                                  |      Sim      |      -      |

_Fonte: Elaborada por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Problemas Encontrados e Análise dos Dados

### ID5 - Todos os textos estão na norma padrão?

- No tópico "Metodologia" a palavra assunto está errada.

### ID9 - Os relacionamentos de extend, include e generalization estão sendo usados corretamente?

A relação entre os casos de uso Buscar evento e Filtrar por município está errada segundo Pimentel (2007, p. 19-20).

### ID11.1 - Ele possui um nome associado?

O nome associado é o nome generico **Autor**.

### ID23 - Os fluxos de exceção demonstram como o sistema reagirá na presença de situações inesperadas?

No caso _Buscar evento_, o fluxo apresentado é alternativo e não de exceção.

No caso _Ativar notificações sobre eventos_, o fluxo apresentado se parece mais com um alternativo do que com uma exceção. Um fluxo de exceção seria o fluxo tratar caso o usuário recusar o acesso a localização no primeiro acesso.

No caso _Responder pesquisa de perfil_, não especificado como e essa rejeição. Selecionar "Responder mais tarde" no fluxo alternativo também não seria uma rejeição?

## Sugestões de Correção

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Corrigir os erros ortográficos.
- Corrigir os relacionamentos;
- Adicionar nome ao Autor;
- Corrigir os fluxos de exceção.

A correção dos erros será realizada após uma discussão e validação dos problemas encontrados com o grupo e apresentação dos resultados para o professor da disciplina.

## Retrabalho

Como por Fagan, para o retrabalho os autores do artefato ([Geovanna Maciel](https://github.com/manuziny) e [Sidney Fernando](https://github.com/nando3d3)) corrigiram os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição                       |                Responsável(eis)                |                   Revisor(es)                    |      Status      |
| ---------------- | :------------------------------ | :--------------------------------------------: | :----------------------------------------------: | :--------------: |
| 24/06/2023       | Corrigir os erros ortográficos. | [Geovanna Maciel](https://github.com/manuziny) | [Matheus Henrique](https://github.com/mathonaut) | :material-close: |
| 24/06/2023       | Corrigir os relacionamentos.    | [Sidney Fernando](https://github.com/nando3d3) | [Matheus Henrique](https://github.com/mathonaut) | :material-close: |
| 24/06/2023       | Adicionar nome ao Autor.        | [Sidney Fernando](https://github.com/nando3d3) | [Matheus Henrique](https://github.com/mathonaut) | :material-close: |
| 24/06/2023       | Corrigir os fluxos de exceção.  | [Geovanna Maciel](https://github.com/manuziny) | [Matheus Henrique](https://github.com/mathonaut) | :material-close: |

_Fonte: Elaborado por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

!!! info
O cronograma apresentado na tabela 3 pode ser alterado.

## Acompanhamento

A figura 1 apresenta um gráfico com o percentual de respostas sim, não, incompleto ou não se aplica, obtidas através da checklist de verificação.

<center>

**Figura 1** - Gráfico do resultado da verificação.

<iframe style="border-radius: 5px; border:3px solid red" width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS2PuVRCN2V5vlnGDomZb-FqFss_39CS89v4Zl3Ptf35OCryvrwYG2rNYSzunjnDYbYpU6gYU3CbC2z/pubchart?oid=2083379196&amp;format=interactive"></iframe>

_Fonte: Elaborado por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> PIMENTEL, Andrey R. **Projeto de Software Usando a UML.** Paraná, 2007.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                  |
| ------ | ---------- | ------------------ | ------------------------------------------------ | -------------------------------------------- |
| `1.0`  | 21/06/2023 | Criação da página. | [Matheus Henrique](https://github.com/mathonaut) | [Douglas Alves](https://github.com/dougAlvs) |
