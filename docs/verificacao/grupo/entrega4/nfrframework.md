# Verificação do NFR Framework do Grupo

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas em cima do artefato do [NFR Framework](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/) da Etapa 3 do [Grupo](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e4-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários. A checklist foi feita com base na dissertação de mestrado de Reinaldo Antônio da Silva<a id="anchor_1" href="#REF1">^1^</a>.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e4-grupo). A tabela 1 apresenta os participantes dessa verificação.

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

**Tabela 2** - Checklist de Verificação.

|  ID | Descrição                                                                                              | Avaliação     | Observações                                     |
| --- | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1  | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2  | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           | No entanto, os ID's do versionamento estão com números repetidos e errados.                                                |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Sim           |                                                 |
|  5  | Todos os textos estão na norma padrão?                                                                 | Sim           |                                                 |
| 6  | Os gráficos SIG foram validados por Fontes Externas?<a id="anchor_1" href="#REF1">^1^</a>                                                    | Incompleto           | SIG de [Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade)                                                |
| 7  | Cada SIG possui sua respectiva propagação de Impacto?<a id="anchor_1" href="#REF1">^1^</a>  | Sim | |
| 8  | Os softgoals se refinam até um nível de especificação bem definido?<a id="anchor_1" href="#REF1">^1^</a> | Incompleto | Os SIG's de [Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) e de [Desempenho](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-03-desempenho) |
| 9  | Os cartões de especificação representam requisitos não-funcionais verificáveis? | Sim | |
| 10 | Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História?<a id="anchor_1" href="#REF1">^1^</a> | Sim | |
| 11 | Os Softgoals NFR estão representados apropriadamente dada a sua definição?<a id="anchor_1" href="#REF1">^1^</a> | Sim | |
| 12 | Os Softgoals de Operacionalização estão representados apropriadamente dada a sua definição?<a id="anchor_1" href="#REF1">^1^</a> | Sim | |
| 13 | Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição?<a id="anchor_1" href="#REF1">^1^</a> | Incompleto | Nos SIG's de [Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) e de [Desempenho](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-03-desempenho)  |
| 14 | Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método? | Sim | |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Lista de Problemas e Análise

### ID 6 - Os gráficos SIG foram validados por Fontes Externas?

Sim, por três fontes. Contudo, o [SIG de Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) apresenta um elemento não validado pelas fontes externas utilizadas, que é o de "Disponibilidade", o qual pode ser trocado sem maiores entraves por "Acessibilidade". Essa alteração, inclusive, é validada pelas fontes já utilizadas e não altera o curso do SIG.

### ID 8 - Os softgoals se refinam até um nível de especificação bem definido?

Por exemplo, nos SIG's de [Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) e de [Desempenho](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-03-desempenho), os softgoals de claim não apresentam limitações específicas. Dentro do SIG referido, podemos citar um: "Processar rapidamente". Esse requisito não é verificável, dado que para um requisito ser verificável, vale da seguinte definição: "Um requisito é verificável se existir um processo finito, com custo compensador, que possa ser executado por uma pessoa ou máquina, e que mostre a conformidade do produto final com o requisito"<a id="anchor_2" href="#REF2">^2^</a>.


### ID 13 - Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição?

Os softgoals de afirmação são fatores delimitantes dentro de um domínio, ou seja, servem como um filtro para as características<a id="anchor_4" href="#REF4">^4^</a>. No entanto, nos dois SIG's citados acima, os softgoals de claim não apresentam soluções testáveis, somente são especificadas no cartão de especificação, mas já deveria ser identificável nos claims.

## Sugestões de Correções

- Especificar os softgoals de afirmação nos SIG's de Eficiência e de Desempenho.
- Alterar o tópico de "Disponibilidade" por "Acessibilidade" no SIG de Usabilidade.
- Arrumar o histórico de versão.

## Acompanhamento

A figura 1 apresenta um gráfico com o percentual de respostas sim, não ou incompleto, obtidas através da checklist de verificação.

<center>

**Figura 1** - Gráfico do resultado da verificação.

<iframe style="border-radius: 5px; border:3px solid red" width="600" height="400" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSRYc9oKu_U7bHT1tcuDD3XMhc7FBGYo9Fxb6KBE8kC27jvIw7nwtty6gdh-OUgJlHcGCGnW1XWBhLk/pubchart?oid=1023223695&amp;format=interactive"></iframe>

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Retrabalho

Como proposto por Fagan, para o retrabalho o autor do artefato [Arthur de Melo](https://github.com/arthurmlv) corrigiu os problemas apresentados seguindo a lista de sugestão de correção apresentada anteriormente. O responsável por essa verificação fará uma revisão das correções feitas, checando se as correções são suficientes e se foi introduzido novos erros ou não. A tabela 3 a seguir apresenta o cronograma de correções.

<center>

**Tabela 3** - Cronograma de Correções.

| Data de Correção | Descrição                                                                                                         |                 Responsável(eis)                 |                   Revisor(es)                    |      Status      |
| ---------------- | :---------------------------------------------------------------------------------------------------------------- | :----------------------------------------------: | :----------------------------------------------: | :--------------: |
| 01/07/2023       | Correção SIG usabilidade.                                                                       | [Arthur de Melo](https://github.com/arthurmlv) |  [Matheus Henrique](https://github.com/mathonaut)  | :material-check: |
| 01/07/2023       | Correção dos softgoals de claim e histórico de versão.                                                                                   | [Arthur de Melo](https://github.com/arthurmlv) |  [Matheus Henrique](https://github.com/mathonaut)  | :material-check: |


_Fonte: Elaborado por [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

!!! info
    O cronograma apresentado na tabela 3 pode ser alterado.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 10/06/2023.

> <a id="REF2" href="#anchor_2">2.</a> MESQUITA, Renato Cardoso. Engenharia dos requisitos de software. Departamento de Eng. Elétrica da UFMG, Belo Horizonte, 2019. Disponível em: <https://www.cin.ufpe.br/~joa/menu_options/school/cursos/engsoft/aulas/requisitos-conceitos.pdf>. Acesso em: 10/06/2023.

> <a id="REF3" href="#anchor_3">3.</a> MAIRIZA, D.; ZOWGHI, D.; NURMULIANI, N. An investigation into the notion of non-functional requirements. In: Proceedings of the 2010 ACM Symposium on Applied Computing. ACM: [s.n.], 2010. p. 311–317.

> <a id="REF4" href="#anchor_4">4.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv) | [Gabriel Campello](https://github.com/G16C) |
| `1.1`  | 01/07/2023 | Retrabalho. | [Arthur de Melo](https://github.com/arthurmlv)   | [Matheus Henrique](https://github.com/mathonaut)   |
