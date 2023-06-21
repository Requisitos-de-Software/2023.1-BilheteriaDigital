# Planejamento da Verificação da Etapa 3

## Introdução

A verificação é uma das etapas mais importantes do desenvolvimento de um projeto. Nela, os artefatos produzidos são analisados garantindo que os mesmos cumpram com os seus requisitos especificados. Sendo assim, este documento apresenta o planejamento da verificação dos artefatos de [Cenários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/), [Caso de Uso](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/) e [Especificação Suplementar](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/) produzido pelo [nosso próprio grupo (Grupo 1)](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/) na Etapa 3.

## Objetivos

O objetivo deste documento é verificar se os artefatos produzidos na Etapa 3 pela [nossa equipe](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/) possuem os itens e o padrão exigidos para tais.

## Metodologia

A metodologia escolhida para esta verificação é uma adptação da inspeção. Desenvolvida originalmente para códigos de software por Fagan na IBM em 1976, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos, a figura 1 exemplifica as etapas que Fagan propôs para esse processo.

Salienta-se que a inspeção aqui planejada será realizada somente até a etapa de "Reunião de Inspeção", que nessa adaptacação será a inspeção propriamente dita, realizada de maneira individual. Essa revisão será realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados, tudo isso com base na bibliografia especificada pelo autor da checklist.

<center>

**Figura 1** - Etapas da Inspeção de acordo com Fagan.

<figure markdown class="usecaseElement">

![inspecao-fagan](../../../assets/verificacao/inspecao-fagan.png)

</figure>

_Fonte: SOMMERVILLE (2007)._<a id="anchor_4" href="#REF4">^5^</a>

</center>

### Participantes

Os responsáveis por essa verificação são os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) que são: [Arthur de Melo](https://github.com/arthurmlv) e [Matheus Henrique](https://github.com/mathonaut), que realizam tanto o planejamento quanto a inspeção e o relato de seus resultados. Em relação a revisão dos artefatos produzidos por essa verificação, fica a cargo do integrante do mesmo grupo [Rafael Ferreira](https://github.com/RafaelCLG0).

### Objetos de Verificação

Os artefatos alvo dessa verificação são:

- [Cenários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/), na versão 1.0 de data 13/05/2023 produzida por [Douglas Alves](https://github.com/dougAlvs) e [Gabriel Campello](https://github.com/G16C) com a revisão de [Sidney Fernando](https://github.com/nando3d3).

- [Léxico](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/), na versão 1.2 de data 18/05/2023 produzida por [Arthur de Melo](https://github.com/arthurmlv) com a revisão de [Sidney Fernando](https://github.com/nando3d3).

- [Caso de Uso](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/), na versão 1.3 de data 15/05/2023 produzida por [Sidney Fernando](https://github.com/nando3d3) com revisão de [Geovanna Maciel](https://github.com/manuziny).

- [Especificação Suplementar](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/) na versão 1.2 de data 16/05/2023 produzida por [Rafael Ferreira](https://github.com/RafaelCLG0) com revisão de [Matheus Henrique](https://github.com/mathonaut).

Os resultados da verificação em si serão apresentados em uma página separada e que podem ser acessados através dos seguinte link:

- [Resultados da Verificação dos Cenários](../).
- [Resultados da verificação do Caso de uso](../);
- [Resultados da Verificação da Especificação Suplementar](../).
- [Resultados da Verificação dos Léxicos](../).

### Cronograma

A verificação será realizada no período de 18 de junho de 2023 até dia 21 de junho de 2023, com os resultados sendo relatados através da página de documentação do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) no dia 21 de junho de 2023. A tabela 1 a seguir, apresenta o cronograma das atividades a serem realizadas.

<center>

**Tabela 1** - Cronograma das Atividades.

| Data       | Descrição                                  | Responsável                                      |
| ---------- | ------------------------------------------ | ------------------------------------------------ |
| 20/06/2023 | Verificação do Caso de Uso.                | [Matheus Henrique](https://github.com/mathonaut)   |
| 21/06/2023 | Verificação do Especificação Suplementar.  | [Arthur de Melo](https://github.com/arthurmlv) |
| 21/06/2023 | Verificação dos Cenários.                  | [Arthur de Melo](https://github.com/arthurmlv)     |
| 21/06/2023 | Verificação dos Léxicos.                   | [Arthur de Melo](https://github.com/arthurmlv)   |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Checklists

As checklists foram construídas levando em conta os padrões esperados para os artefatos que estão disponíveis nas referências bibliográficas. Além dos itens listados anteriormente, também foi analisado o relatório referente à entrega produzido pelo o monitor do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking), Gustavo Martins. Para os Cenários e os Léxicos, foram utilizadas publicações de Julio Cesar Sampaio do Prado Leite, sendo estas (LEITE e ROSSI, 1997)<a id="anchor_7" href="#REF7">^7^</a> e (LEITE, 2012)<a id="anchor_8" href="#REF8">^8^</a>. Já as outras checklists estão referenciadas de acordo com a fonte que originou a referida pergunta.

Com o intuito de melhor organizar a verificação, a checklist será dividida em 2 checklists sendo que uma deverá estar presente em todas as etapas de verificação, no caso a geral. As checklists são as seguintes: Geral, Verificação dos Cenários, Verificação dos Léxicos, Verificação do Caso de Uso e Verificação da Especificação Suplementar. As tabelas de 2 a 6 apresentam as checklists de verificação.

### Geral

A tabela 2 a seguir apresenta a checklist referente aos aspectos gerais que os artefatos devem seguir.

<center>

**Tabela 2** - Checklist para os Itens Gerais.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 1   | O artefato possui introdução?                                                                          |           |             |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?                                           |           |             |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |           |             |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |           |             |
| 5   | Todos os textos estão na norma padrão?                                                                 |           |             |

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

### Verificação dos Cenários

<center>

**Tabela 3** - Checklist para a Verificação dos Cenários.

| ID  | Descrição                                                                                                                           | Avaliação | Observações |
| --- | ----------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------- |
| 6   | O cenário possui: título, metas/objetivos, contexto, ator(es), recursos, exceções e episódios?<a id="anchor_5" href="#REF5">^6^</a> |           |             |
| 7   | O título do cenário é autoexplicativo?<a id="anchor_6" href="#REF6">^7^</a>                                                         |           |             |
| 8   | O objetivo do cenário é condizente com seu título?<a id="anchor_6" href="#REF6">^7^</a>                                             |           |             |
| 9   | O contexto é descrito em função de local, tempo e pré-condições?<a id="anchor_5" href="#REF5">^6^</a>                               |           |             |
| 10  | O cenário descreve situações realistas e relevantes de interação do sistema?<a id="anchor_5" href="#REF5">^6^</a>                   |           |             |
| 11  | Os atores são condizentes com o contexto do cenário? <a id="anchor_6" href="#REF6">^7^</a>                                          |           |             |
| 12  | Os episódios do cenário estão coerentes e seguem uma ordem lógica para atingir o objetivo? <a id="anchor_6" href="#REF6">^7^</a>    |           |             |
| 13  | Existe uma ligação entre os cenários e os léxicos?<a id="anchor_6" href="#REF6">^7^</a>                                             |           |             |

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

### Verificação dos Léxicos

<center>

**Tabela 4** - Checklist para os Léxicos.

| ID  | Descrição                                                                                                 | Avaliação | Observações |
| --- | --------------------------------------------------------------------------------------------------------- | --------- | ----------- |
| 6   | Cada símbolo possui classificação, sinônimo, noção e impacto?<a id="anchor_8" href="#REF8">^8^</a>                                             |           |             |
| 7   | Cada símbolo apresenta sua noção de forma breve e compreensível?<a id="anchor_8" href="#REF8">^8^</a>                                          |           |             |
| 8   | Cada símbolo apresenta seu impacto de forma breve e compreensível?<a id="anchor_8" href="#REF8">^8^</a>                                        |           |             |
| 9   | Caso seja do tipo Estado, as definições de noção e de impacto se encaixam com o que é descrito?<a id="anchor_8" href="#REF8">^8^</a>           |           |             |
| 10  | Caso seja do tipo Verbo, as definições de noção e de impacto se encaixam com o que é descrito?<a id="anchor_8" href="#REF8">^8^</a>            |           |             |
| 11  | Caso seja do tipo Objeto, as definições de noção e de impacto se encaixam com o que é descrito?<a id="anchor_8" href="#REF8">^8^</a>           |           |             |
| 12  | O princípio circular foi devidamente propagado, ou seja, os léxicos são referenciados e estão conectados?<a id="anchor_8" href="#REF8">^8^</a> |           |             |
| 13  | A descrição dos léxicos é coerente e esclarecedora?<a id="anchor_8" href="#REF8">^8^</a>                                                       |           |             |
| 14  | O vocabulário mínimo foi apropriadamente adotado nas descrições?<a id="anchor_8" href="#REF8">^8^</a>                                          |           |             |
| 15  | Quanto à organização dos léxicos, eles respeitam sua ordem numérica?<a id="anchor_8" href="#REF8">^8^</a>                                      |           |             |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

### Verificação do Caso de uso

<center>

**Tabela 5** - Checklist para a Verificação do Caso de Uso.

| ID  | Descrição                                                                                                                                   | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------- | ----------- |
| 6   | Cada caso provem um resultado observável e de valor para os atores ou outros interessados no sistema? <a id="anchor_4" href="#REF4">^4^</a> |           |             |
| 7   | As elipses representam as ações caso de uso? (constituem internamente fluxos/cenários)? <a id="anchor_3" href="#REF3">^3^</a>               |           |             |
| 8   | Há o uso de verbos no infinitivo e não substantivos? <a id="anchor_2" href="#REF2">^2^</a>                                                  |           |             |
| 9   | Há relacionamentos de extend, include e generalization? <a id="anchor_4" href="#REF4">^4^</a>                                               |           |             |
| 10  | O caso de uso representa o usuário e suas interações com o sistema? <a id="anchor_4" href="#REF4">^4^</a>                                   |           |             |
| 11  | O ator principal está posicionado ao lado esquerdo do sistema? <a id="anchor_4" href="#REF4">^4^</a>                                        |           |             |
| 12  | O usuário reside fora das fronteiras da aplicação? <a id="anchor_4" href="#REF4">^4^</a>                                                    |           |             |
| 13  | O usuário possui um nome associado a ele? Como: cliente, analista de RH, estudante, etc. <a id="anchor_4" href="#REF4">^4^</a>              |           |             |
| 14  | Quando o ator é um software ou um hardware, há a tag << system >>? <a id="anchor_4" href="#REF4">^4^</a>                                    |           |             |
| 15  | O caso de uso produzido é uma funcionalidade completa que entrega algum valor? <a id="anchor_4" href="#REF4">^4^</a>                        |           |             |
| 16  | Os casos de uso são de requisitos funcionais? <a id="anchor_4" href="#REF6">^4^</a>                                                         |           |             |
| 17  | Foi usada alguma técnica para a produção dos casos de uso? <a id="anchor_4" href="#REF4">^4^</a>                                            |           |             |
| 18  | Os elementos de atores, sistema e metas estão presentes no caso de uso? <a id="anchor_3" href="#REF3">^3^</a>                               |           |             |
| 19  | A especificação dos casos de uso consistem no detalhamento de execução dos casos de uso? <a id="anchor_2" href="#REF2">^2^</a>              |           |             |
| 20  | Existem fluxos como: principal, alternativo e de exceção? <a id="anchor_2" href="#REF2">^2^</a>                                             |           |             |
| 21  | Cada especificação de caso uso tem somente um fluxo principal? <a id="anchor_2" href="#REF2">^2^</a>                                        |           |             |
| 22  | Os fluxos principais representam como usuário usaria a funcionalidade de forma primária? <a id="anchor_2" href="#REF2">^2^</a>              |           |             |
| 23  | Os fluxos alternativos são possibilidades de cenários alternativos ao fluxo principal? <a id="anchor_4" href="#REF4">^4^</a>                |           |             |
| 24  | Os fluxos de exceção demonstram como o sistema reagirá na presença de situações inesperadas? <a id="anchor_4" href="#REF4">^4^</a>          |           |             |

_Fonte: [Geovanna Maciel](https://github.com/manuziny), 2023._

### Verificação da Especificação Suplementar

**Tabela 6** - Checklist para a Verificação da Especificação Suplementar

| ID   | Descrição                                                                                         | Avaliação | Observações |
| ---- | ------------------------------------------------------------------------------------------------- | --------- | ----------- |
| 6    | O documento segue o modelo FURPS+?<a id="anchor_1" href="#REF1">^1^</a>                           |           |             |
| 7    | O documento possui um tópico de Funcionalidade?<a id="anchor_1" href="#REF1">^1^</a>              |           |             |
| 7.1  | Os requisitos apresentados são testáveis?                                                         |           |             |
| 8    | O documento possui um tópico de Usabilidade?<a id="anchor_1" href="#REF1">^1^</a>                 |           |             |
| 8.1  | Os requisitos apresentados são testáveis?                                                         |           |             |
| 8.2  | Os requisitos apresentados facilitam as tarefas realizadas pelos usuários?                        |           |             |
| 9    | O documento possui um tópico de Confiabilidade?<a id="anchor_1" href="#REF1">^1^</a>              |           |             |
| 9.1  | Os requisitos apresentados são testáveis?                                                         |           |             |
| 9.2  | Os requisitos apresentados aumentam a confiabilidade do sistema?                                  |           |             |
| 9.3  | Os requisitos relacionados à segurança são apresentados?                                          |           |             |
| 10   | O documento possui um tópico de Desempenho?<a id="anchor_1" href="#REF1">^1^</a>                  |           |             |
| 10.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 10.2 | Os requisitos sobre os tempos de respostas são apresentados?                                      |           |             |
| 10.3 | Os requisitos sobre a disponibilidade são apresentados?                                           |           |             |
| 11   | O documento possui um tópico de Suportabilidade?<a id="anchor_1" href="#REF1">^1^</a>             |           |             |
| 11.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 11.2 | É apresentado os sistemas operacionais que o sistema funcionará?                                  |           |             |
| 12   | O documento possui um tópico de Restrições de Design?<a id="anchor_1" href="#REF1">^1^</a>        |           |             |
| 12.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 12.2 | Os requisitos apresentados específica ou restringe o design do sistema?                           |           |             |
| 13   | O documento possui um tópico de Requisitos de Implementação?<a id="anchor_1" href="#REF1">^1^</a> |           |             |
| 13.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 14   | O documento possui um tópico de Requisitos de Interface?<a id="anchor_1" href="#REF1">^1^</a>     |           |             |
| 14.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 15   | O documento possui um tópico de Requisitos Físicos?<a id="anchor_1" href="#REF1">^1^</a>          |           |             |
| 15.1 | Os requisitos apresentados são testáveis?                                                         |           |             |
| 15.2 | As características físicas de onde o sistema funcionará são apresentadas?                         |           |             |

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> Artefato: Especificações Suplementares. **Centro de Informática - UFPE**. Disponível em: <<https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>>. Acesso em: 04 de junho de 2023.

> <a id="REF2" href="#anchor_2">2.</a> Slides da aula “Requisitos – Aula 11” dos professores Milene Serrano e Maurício Serrano. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf) Acesso em: 05 de junho de 2023.

> <a id="REF3" href="#anchor_3">3.</a> Lucidchart - Diagrama de caso de uso UML. Disponível em: [https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml). Acesso em: 05 de junho de 2023.

> <a id="REF4" href="#anchor_4">4.</a> REINEHR, Sheila. Engenharia de requisitos. [Insert Publisher Location]: Grupo A, 2020. E-book. ISBN 9786556900674. Disponível em: [https://integrada.minhabiblioteca.com.br/#/books/9786556900674/](https://integrada.minhabiblioteca.com.br/#/books/9786556900674/). Acesso em: 07 junho 2023.

> <a id="REF5" href="#anchor_5">5.</a> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007

> <a id="REF6" href="#anchor_6">6.</a> BERGMANN, Ulf. Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações. 2003. Tese de Doutorado (Departamento de Informática) - Pontifícia Universidade Católica do Rio de Janeiro, [S. l.], 2003. p. 47-50.

> <a id="REF7" href="#anchor_7">7.</a> Leite, J.C.S.d.P., Rossi, G., Balaguer, F. et al. Enhancing a requirements baseline with scenarios. Requirements Eng 2, 44–53 (1997).

> <a id="REF8" href="#anchor_8">8.</a> LEITE, Julio Cesar. Léxico Ampliado da Linguagem, 2012. Disponível em: <<https://www-di.inf.puc-rio.br/~julio/lal.pdf>>. Acesso em: 21/06/2023.


## Histórico de Versões

| Versão | Data       | Descrição                                   | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página.                          | [Arthur de Melo](https://github.com/arthurmlv) | [Rafael Ferreira](https://github.com/RafaelCLG0) |

