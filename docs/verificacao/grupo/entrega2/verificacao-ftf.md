# Verificação do First Things First

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados da verificação realizada acerca do artefato [First Things First ](../../../../elicitacao/priorizacao/firstThingsfirst) da etapa 2 do [grupo](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e2-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes são os integrantes do grupo [Matheus Henrique](https://github.com/mathonaut), que será responsável por realizar a verificação e a correção dos problemas encontrados. Além disso, o integrante do grupo [Geovanna Maciel](https://github.com/manuziny) realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e2-grupo). A tabela 1 apresenta os participantes.

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
| [Matheus Henrique](https://github.com/mathonaut) | Avaliador |
|  [Geovanna Maciel](https://github.com/manuziny)  | Revisora  |

_Fonte: Elaborada por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

### Sumários dos Dados Encontrados

A tabela 2 a seguir apresenta a checklist com os dados obtidos a partir da verificação. As fontes de cada pergunta foram apresentadas na página de [planejamento](../planejamento-verificacao-e2-grupo/#first-things-first).

<center>

**Tabela 2** - Checklist de Verificação.

|           ID           | Descrição                                                                                                                   | Avaliação  | Observações |
| :--------------------: | --------------------------------------------------------------------------------------------------------------------------- | :--------: | :---------: |
|    **Padronização**    |                                                                                                                             |
|           1            | O artefato possui introdução?                                                                                               |    Sim     |      -      |
|           2            | O artefato possui uma bibliografia/referência bibliográfica?                                                                |    Sim     |      -      |
|           3            | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores?                      |    Sim     |      -      |
|           4            | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                                                | Incompleto |      -      |
|           5            | Todos os textos estão na norma padrão?                                                                                      |    Não     |      -      |
| **First Things First** |                                                                                                                             |            |             |
|           6            | Foram listados todos os requisitos a serem priorizados?                                                                     |    Sim     |      -      |
|          6.1           | Foram retirados os requisitos logicamente ligados, deixando apenas os não dependentes?                                      |    Sim     |      -      |
|           7            | Os benefícios relativos de cada recursos ao cliente/negócio é estimado em uma escala de 1 a 9?                              |    Sim     |      -      |
|          7.1           | O peso relativo desses itens são apresentados?                                                                              |    Sim     |      -      |
|          7.2           | Quem realizou essas estimativas foram representantes dos clientes?                                                          |    Sim     |      -      |
|           8            | As penalidades relativas que o negócio sofreria se o recursos não forem implementadas são estimados em uma escala de 1 a 9? |    Sim     |      -      |
|          8.1           | O peso relativo desses itens são apresentados?                                                                              |    Sim     |      -      |
|          8.2           | Quem realizou essas estimativas foram representantes dos clientes?                                                          |    Sim     |      -      |
|           9            | O valor total é calculado?                                                                                                  |    Sim     |      -      |
|          9.1           | A fórmula utilizada é (Benefício Relativo × Peso Relativo) + (Penalidade Relativa × Peso Relativo)?                         |    Sim     |      -      |
|           10           | Os custos relativos de implementação foram estimados em uma escala de 1 a 9?                                                |    Sim     |      -      |
|          10.1          | O peso relativo desses itens são apresentados?                                                                              |    Sim     |      -      |
|          10.2          | Quem realizou essas estimativas foi a equipe de desenvolvimento?                                                            |    Sim     |      -      |
|           11           | Os graus relativos de riscos foram estimados em uma escala de 1 a 9?                                                        |    Sim     |      -      |
|          11.1          | O peso relativo desses itens são apresentados?                                                                              |    Sim     |      -      |
|          11.2          | Quem realizou essas estimativas foi a equipe de desenvolvimento?                                                            |    Sim     |      -      |
|           12           | É calculado a prioridade para cada requisito?                                                                               |    Sim     |      -      |
|          12.1          | A fórmula utilizada é (Valor%)/[(Custo%)x(Peso Custo) + (Risco%)x(Peso Risco)]?                                             |    Sim     |      -      |
|           13           | A lista de requisitos foi ordenada decrescentemente em relação a prioridade?                                                |    Sim     |      -      |
|           14           | Os resultados da priorização são apresentados?                                                                              |    Sim     |      -      |
|          14.1          | Os valores totais são apresentados?                                                                                         |    Sim     |      -      |
|          14.2          | As porcentagens dos valores dos requisitos em relação ao valor total é apresentado?                                         |    Sim     |      -      |
|          14.3          | Os custos dos requisitos em relação ao custo relativo total são apresentados?                                               |    Sim     |      -      |
|          14.4          | Os riscos dos requisitos em relação ao risco relativo total são apresentados?                                               |    Sim     |      -      |
|           15           | Os participantes e suas funções são apresentados?                                                                           |    Sim     |      -      |
|          15.1          | Algum participante tem a função de gerente/mediador?                                                                        |    Sim     |      -      |
|          15.2          | Algum participante tem a função de representante dos clientes?                                                              |    Sim     |      -      |
|          15.3          | Algum participante tem a função de representante dos desenvolvedores?                                                       |    Sim     |      -      |
|           16           | Foi documentada a reunião com os participantes?                                                                             |    Sim     |      -      |
|          16.1          | Existe uma gravação?                                                                                                        |    Sim     |      -      |

_Fonte: Elaborada por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Problemas Encontrados e Análise dos Dados

### ID4 - Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?

Há uma duplicação do uso da tabela 1.

### ID5 - Todos os textos estão na norma padrão?

- Na lista de reuniões a um erro na ortografia da palavra vídeo;
- No tópico "Resultado de Priorização" a palavra ordenados não está em concordância.

## Sugestões de Correção

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Reordenar as tabelas;
- Corrigir os erros ortográficos.

A correção dos erros será realizada após uma discussão e validação dos problemas encontrados com o grupo e apresentação dos resultados para o professor da disciplina.

## Acompanhamento

A figura 1 apresenta um gráfico com o percentual de respostas sim, não, incompleto ou não se aplica, obtidas através da checklist de verificação.

<center>

**Figura 1** - Gráfico do resultado da verificação.

<iframe style="border-radius: 5px; border:3px solid red" width="600" height="371" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vS2PuVRCN2V5vlnGDomZb-FqFss_39CS89v4Zl3Ptf35OCryvrwYG2rNYSzunjnDYbYpU6gYU3CbC2z/pubchart?oid=2119230642&amp;format=interactive"></iframe>

_Fonte: Elaborado por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Retrabalho

Como proposto por Fagan, para o retrabalho os autores do artefato verificado serão responsáveis em um primeiro momento por corrigir os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente, porém há a possibilidade de outros integrantes do grupo realizarem as correções propostas. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição                       |                 Responsável(eis)                 |                   Revisor(es)                    |      Status      |
| ---------------- | :------------------------------ | :----------------------------------------------: | :----------------------------------------------: | :--------------: |
| 21/26/2023       | Reordenar as tabelas.           | [Rafael Ferreira](https://github.com/RafaelCLG0) | [Matheus Henrique](https://github.com/mathonaut) | :material-check: |
| 21/06/2023       | Corrigir os erros ortográficos. | [Rafael Ferreira](https://github.com/RafaelCLG0) | [Matheus Henrique](https://github.com/mathonaut) | :material-check: |

_Fonte: Elaborado por [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

!!! info

    O cronograma apresentado na tabela 3 pode ser alterado.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SIMÕES, Guilherme S.; VASQUEZ Carlos E. **Engenharia de Requisitos: Software Orientado ao Negócio.** Rio de Janeiro: Brasport, 2016.

## Histórico de Versões

| Versão | Data       | Descrição                                | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ---------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página.                       | [Matheus Henrique](https://github.com/mathonaut) | [Geovanna Maciel](https://github.com/manuziny)   |
| `1.1`  | 21/06/2023 | Atualização do cronograma de retrabalho. | [Rafael Ferreira](https://github.com/RafaelCLG0) | [Matheus Henrique](https://github.com/mathonaut) |
