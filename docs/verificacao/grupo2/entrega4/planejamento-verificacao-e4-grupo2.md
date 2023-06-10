# Planejamento da Verificação da Etapa 4 do Grupo 2

## Introdução

A verificação é uma das etapas mais importantes do desenvolvimento de um projeto. Nela os artefatos produzidos são analisados garantindo que os mesmos cumpram com os seus requisitos especificados. Sendo assim, este documento apresenta o planejamento da verificação dos artefatos de [NFR Framework](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/nfrFramework/), [Product Backlog](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/backlog/) e [Histórias de Usuário](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/historiasDeUsuario/) produzido pelo [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking) na Etapa 4.

## Objetivos

O objetivo deste documento é verificar se os artefatos produzidos na Etapa 4 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking) possuem os itens e o padrão exigidos para tais. É importante citar que essa verificação em momento nenhum busca diminuir os membros do Grupo 2 ou seu trabalho, apenas aplicar os conceitos de verificação nos artefatos.

## Metodologia

A metodologia escolhida para esta verificação é uma adptação da inspeção. Desenvolvida originalmente para códigos de software por Fagan na IBM em 1976, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos, a figura 1 exemplifica as etapas que Fagan propôs para esse processo. 

Salienta-se que a inspeção aqui planejada será realizada somente até a etapa de "Reunião de Inspeção", que nessa adaptacação será a inspeção propriamente dita, realizada de maneira individual. Essa revisão será realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados, tudo isso com base na bibliografia especificada pelo autor da checklist.
<center>

**Figura 1** - Etapas da Inspeção de acordo com Fagan.

![inspecao-fagan](../../../assets/verificacao/inspecao-fagan.png#only-light)
![inspecao-fagan](../../../assets/verificacao/inspecao-fagan-e.png#only-dark)

_Fonte: SOMMERVILLE (2007)._<a id="anchor_2" href="#REF2">^1^</a>
</center>

### Participantes

Os responsáveis por essa verificação são os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) que são: [Arthur de Melo](https://github.com/arthurmlv), [Douglas Alves](https://github.com/dougAlvs) e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizam tanto o planejamento quanto a inspeção e o relato de seus resultados. Em relação a revisão dos artefatos produzidos por essa verificação, fica a cargo dos integrantes do mesmo grupo [Matheus Henrique](https://github.com/mathonaut), [Gabriel Campello](https://github.com/G16C) e [Geovanna Maciel](https://github.com/manuziny).

### Objetos de Verificação

Os artefatos alvo dessa verificação são:  

- [NFR Framework](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/nfrFramework/), na versão 1.0 de data 23/05/2023 produzido por [Henrique Pucci](https://github.com/HenriPucci) e [Samuel Gomes](https://github.com/SamuelGSouza) com a revisão de [Chaydson Ferreira](https://github.com/chaydson).

- [Product Backlog](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/backlog/), na versão 1.0 de data 24/05/2023 produzido por [Lucas Frazão](https://github.com/LucasLopesFrazao) e [Chaydson Ferreira](https://github.com/chaydson) com a revisão de [Henrique Pucci](https://github.com/HenriPucci).

- [Histórias de Usuário](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/historiasDeUsuario/) na versão 1.0 de data 23/05/2023 produzido por [Pedro Henrique](https://github.com/PedroHenrique2077) e [Gabriel Silva](https://github.com/oo7gabriel) com revisão de [Samuel Gomes](https://github.com/SamuelGSouza).

Os resultados da verificação em si serão apresentados em uma página separada e que podem ser acessados através dos seguinte link:

- [Resultados da verificação do NFR Framework](./verificacao-nfr.md).
- [Resultados da Verificação do Product Backlog](./verificacao-backlog.md).
- [Resultados da Verificação das Histórias de Usuário](./verificacao-historias-de-usuario.md).

### Cronograma

A verificação será realizada no período de 04 de junho de 2023 até dia 13 de junho de 2023, com os resultados sendo relatados através da página de documentação do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) até no máximo no dia 13 de junho de 2023. A tabela 1 a seguir, apresenta o cronograma das atividades a serem realizadas.

<center>

**Tabela 1** - Cronograma das Atividades.

| Data       | Descrição                                  | Responsável                                      |
| ---------- | ------------------------------------------ | ------------------------------------------------ |
| 08/06/2023 | Verificação do backlog. |[Rafael Ferreira](https://github.com/rafaelCLG0) 
| 09/06/2023 | Verificação das histórias de usuário.  | [Douglas Alves](https://github.com/dougAlvs) |
| 09/06/2023 | Adição da documentação na página do grupo. | [Douglas Alves](https://github.com/dougAlvs) |

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

## Checklists

As checklists foram construídas levando em conta os padrões esperados para os artefatos que estão disponíveis nas referências bibliográficas.  Além dos itens listados anteriormente, também foi analisado o relatório referente à entrega produzido pelo o monitor do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking), Gustavo Martins.

Com o intuito de melhor organizar a verificação, a checklist de cada artefato será dividida em duas, sendo que uma deverá estar presente em todas as etapas de verificação, no caso a geral, representada na tabela 2. Dessa forma as checklists são as seguintes: Geral, Verificação dos Cenários, Verificação dos Léxicos, Verificação do Caso de Uso e Verificação da Especificação Suplementar. As tabelas de 3 a 6 apresentam as checklists de verificação de cada artefato.

### Geral

<center>

**Tabela 2** - Checklist para os Itens Gerais.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 1   | O artefato possui introdução?                                                                          |           |             |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?                                           |           |             |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |           |             |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |           |             |
| 5   | Todos os textos estão na norma padrão?                                                                 |           |             |

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

### Verificação do NFR Framework

<center>

**Tabela 3** - Checklist para a Verificação do NFR.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 6 | Os gráficos SIG foram validados por Fontes Externas? | | |
| 7 | Cada SIG possui sua respectiva propagação de Impacto?  | | |
| 8 | Os softgoals se refinam até um nível de especificação bem definido? | | |
| 9 | Os cartões de especificação representam requisitos não-funcionais verificáveis? | | |
| 10 | Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História? | | |
| 11 | Os Softgoals NFR estão representados apropriadamente dada a sua definição? | | |
| 12 | Os Softgoals de Operacionalização estão representados apropriadamente dada a sua definição? | | |
| 13 | Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição? | | |
| 14 | Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método? | | |


_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

### Verificação do Backlog

<center>

**Tabela 4** - Checklist para a Verificação do Backlog.

| ID  | Descrição                                                                                              | Avaliação |
| --- | ------------------------------------------------------------------------------------------------------ | --------- |
| 6  | A participação do cliente e/ou persona na elicitação de requisitos ?                                     |       |
| 7  | São apresentados os requisitos priorizados ?                                                             |       |
| 8  | Os requisitos listados estão vinculados a uma história de usuário ?                                      |       |
| 9  | Os requisitos listados apresentam uma história de usuário condizente ao épico definido e vice-versa?     |       |
| 10 | O backlog possui épicos e temas bem definidos e descritos ?                                              |       |
| 11 | O backlog possui validação de um PO ?                                                                    |       |
| 12 | O backlog possui ligação com o artefato História de Usuário ?                                            |       |

_Fonte: [Rafael Ferreira](https://github.com/rafaelCLG0), 2023._

</center>

### Verificação das Histórias de Usuário

<center>

**Tabela 5** - Checklist para a Verificação das Histórias de Usuário.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 6  | As histórias de usuários estão escritas de forma clara e concisa, com descrição do "quem", "o que" e "por que"??                                     |        |
| 7  | Cada história de usuário possui um título auto-explicativo, isto é, que resuma o objetivo principal da história?                                                             |       |
| 8  | As histórias de usuários foram provenientes do cliente?                                      |        |
| 9  | As histórias de usuário incluem critérios de aceitação que definam o que é necessário para que a história seja considerada concluída?     |       |
| 10 | As histórias de usuário são testáveis, possibilitando a verificação e validação do sistema com base nos critérios de aceitação definidos?                                              |        |


_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

## Bibliografia

> Gerência e Qualidade de Software - Aula 05 - Verificação e Validação, UNIVESP. Acesso em: 05 de junho de 2023.
> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 10/06/2023.

## Referências Bibliográficas

> <a id="REF2" href="#anchor_2">1.</a> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007



## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 09/06/2023 | Criação da página. | [Douglas Alves](https://github.com/dougAlvs) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.1`  | 10/06/2023 | Adição do NFR | [Arthur de Melo](https://github.com/arthurmlv) | [Gabriel Campello](https://github.com/G16C) |
