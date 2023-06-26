## Introdução

A matriz geral é um documento que permite uma apresentação dos requisitos presentes nos artefatos de Backward-From e Forward-From de forma mais clara.

## Objetivos

Esse artefato tem como objetivo agregar os resultados obtidos nos artefatos de Backward-From e Forward-From em uma única matriz de rastreabilidade.

## Metodologia

Os requisitos apresentados são os elicitados no artefato de [Requisitos Elicitados](../../elicitacao/requisitos_elicitados) que não tinham sua implementação completa no momento de análise.

A matriz é apresentada com 7 colunas sendo elas:

- ID: apresenta o identificador relacionado ao requisito;
- Descrição: apresenta a descrição do requisito;
- Origem: apresenta apartir de quais requisitos foi elaborado;
- Artefatos: apresenta os artefatos relacionados ao requisito;
- Implementação: indica como está a implementação do requisito após a realização do projeto (Sim, Não e Parcialmente).

## Matriz Geral

A tabela 1 a seguir mostra a maatriz geral.

<center>

**Tabela 1** - Matriz Geral.

| ID    | Descrição                                                                            | Origem                                                   | Artefatos                                                                                                           | Implementação |
| ----- | ------------------------------------------------------------------------------------ | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF01  | O aplicativo filtra os eventos por Estado e por Município.                           | IS01, BS08 e OBS01.                                      | Introspecção, Brainstorming, Observação, Casos de Uso, Cenários, Léxicos e Histórias de Usuário.                    | Sim           |
| RF02  | O aplicativo filtra os eventos por data e por horário.                               | IS02 e Q03.                                              | Introspecção, Questionário, Casos de Uso, Cenários, Léxicos e Histórias de Usuário.                                 | Sim           |
| RF03  | O aplicativo filtra os eventos por idade mínima de entrada.                          | IS03 e Q02.                                              | Introspecção, Questionário, Cenários, Léxicos e Histórias de Usuário.                                               | Sim           |
| RF10  | O aplicativo filtra eventos por categorias.                                          | Q04.                                                     | Questionário, Casos de Uso, Cenários, Léxicos e Histórias de Usuário.                                               | Sim           |
| RF11  | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.     | Q05 e BS11.                                              | Questionário, Brainstorming, Léxicos e Histórias de Usuário.                                                        | Não           |
| RF12  | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca. | Q06.                                                     | Questionário, Léxicos e Histórias de Usuário.                                                                       | Não           |
| RF13  | O aplicativo notifica usuário sobre eventos, quando permitido.                       | Q07 e BS06.                                              | Brainstorming, Questionário, Casos de Uso, Léxicos e Histórias de Usuário.                                          | Não           |
| RF18  | O usuário pode responder a pesquisa de perfil sobre seus gostos                      | BS12.                                                    | Brainstorming, Casos de Uso e Histórias de Usuário.                                                                 | Não           |
| RF23  | O usuário é capaz de conectar uma carteira digital                                   | BS18.                                                    | Brainstorming, Casos de Uso, Cenários e Histórias de Usuário.                                                       | Não           |
| RF24  | O usuário é capaz de mudar o idioma do app                                           | BS19.                                                    | Brainstorming e Léxicos.                                                                                            | Não           |
| RF25  | O usuário é capaz de aumentar a fonte                                                | BS20.                                                    | Brainstorming.                                                                                                      | Não           |
| RF26  | O usuário é capaz de dar zoom                                                        | BS21.                                                    | Brainstorming.                                                                                                      | Não           |
| RF27  | O usuário é capaz de acessar a assistente virtual                                    | BS22.                                                    | Brainstorming, Léxicos e Histórias de Usuário.                                                                      | Não           |
| RNF02 | O app deve fornecer eventos direcionados.                                            | IS10, Q11, BS35, BS36 e OBS22.                           | Introspecção, Brainstorming, Observação, Questionário, Casos de Uso, Léxicos, NFR Framework e Histórias de Usuário. | Não           |
| RNF03 | O app deve disponibilizar todas as informações do evento em uma página.              | IS11, BS25, BS26, BS27, BS28, BS29, BS30, OBS15 e OBS16. | Introspecção, Brainstorming, Especificação Suplementar e NFR Framework                                              | Não           |
| RNF04 | A compra deve ser feita em no máximo 5 páginas.                                      | IS13, IS16, Q14, OBS17, OBS18 e IS14.                    | Introspecção, Observação, Questionário e NFR Framework.                                                             | Não           |
| RNF07 | O app não deve ter tempo de resposta superior a 200 ms.                              | Q12.                                                     | Questionário, Especificação Suplementar e NFR Framework.                                                            | Não           |
| RNF08 | O app deve permitir a filtragem dos eventos cadastrados no banco de dados.           | Q13.                                                     | Questionário e NFR Framework.                                                                                       | Não           |

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023_

</center>

## Bibliografia

> MATIAS, Davi. Matriz de Rastreabilidade. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/posrastreabilidade/matriz/>>. Acesso em: 25 junho 2023.

> LUIZA, Ana. Matriz Geral. Repositório do Grupo MEI - Microempreendedor Individual da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Pos-Rastreabilidade/MatrizGeral/>>. Acesso em: 25 junho 2023.

> CASTRO, Samuel; HENRIQUE, Breno. Matriz Geral. Repositório do Grupo LinkedIn da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-LinkedIn/pos-rastreabilidade/matrizGeral/>>. Acesso em: 25 junho 2023.

## Histórico de Versões

| Versão | Data       | Descrição             | Autor(es)                                        | Revisor(es)                                    |
| ------ | ---------- | --------------------- | ------------------------------------------------ | ---------------------------------------------- |
| `1.0`  | 26/06/2023 | Criação do documento. | [Matheus Henrique](https://github.com/mathonaut) | [Arthur de Melo](https://github.com/arthurmlv) |
