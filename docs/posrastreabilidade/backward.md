# Backward-From

## Introdução

Este artefato trata da pós-rastreabilidade Backward-From do projeto, uma técnica importante para gerenciar e monitorar os requisitos de um sistema durante a implementação. Ela cria vínculos entre os requisitos e os elementos do projeto, permitindo traçar o caminho inverso e identificar quais elementos do sistema estão relacionados a cada requisito específico.


A rastreabildiade de requisitos desempenha um papel fundamental no desenvolvimento de software, pois permite acompanhar a evolução dos requisitos ao longo de todo o ciclo de vida do projeto. A pós-rastreabilidade é responsável por designar as conexões entre os requisitos elicitados e as etapas subsequentes do projeto e implementação do sistema, ou seja, ela permite traçar a trajetório de cada requisito, desde a concepção inicial até a implementação. Esses elos de rastreabilidade são criados para rastrear e documentar as relações entre os diferentes artefatos e elementos do processo de desenvolvimento, garantindo a integridade e a rastreabilidade do sistema.

## Metodologia
Para o desenvolvimento do artefato backward-from, foi utilizada a tabela de [Requisitos Elicitados](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/), nela estão presentes os requisitos com sua rastreabilidade. Desta forma, foi utilizado o meta-modelo de Toranzo para classificar os níveis e os elos. Os níveis são:

* **Ambiental**: congrega informações oriundas do contexto ambiental onde a organização está inserida;
* **Organizacional**: informações relacionadas à organização e que podem impactar requisitos do sistema;
* **Gerencial**: informações que auxiliam a gerência do projeto;
* **Desenvolvimento**: informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento.

Após a classificação do nível, há a atribuição de um elo de rastreabilidade. Esses elos possuem tipos, que são:

* **Satisfação**: indica que a classe de origem tem dependência de satisfação com a classe de destino;
* **Recurso**: classe origem tem dependência de recurso com a classe destino;
* **Responsabilidade**: registra a participação, responsabilidade e ação de pessoas sobre artefatos;
* **Representação**: captura a representação ou modelagem dos requisitos em outras linguagens;
* **Alocado**: classe origem está relacionada à classe destino, que
representa um subsistema;
* **Agregação**: indica composição de elementos.

As categorias e os elos estarão em tabelas que seguem o modelo da tabela 1:

<center>

**Tabela 1** - Modelo de tabela.

| ID |  |
| --- | --- |
| Categoria |  |
| Elos |  |

Fonte: [Geovanna Maciel](https://github.com/manuziny)

</center>

## Requisitos Elicitados

As tabelas 2 e 3 fornecidas apresentam uma lista de requisitos funcionais e não funcionais. Cada linha dessas tabelas contém um ID único, uma descrição do requisito, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) utilizada(s) para elicitar o requisito e uma indicação se o requisito foi implementado ou não no sistema.

A legenda para cada sigla é a seguinte:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela Introspecção
- Qx: Requisito nºx elicitado pelo Questionário
- BSx: Requisito nºx elicitado pelo Brainstorming
- OBSx: Requisito nºx elicitado pela Observação

<p style="text-align: center"><b><a id="tab_1" style="visibility: hidden;"></a>Tabela 2</b> - Requisitos funcionais</p>

| ID   | Descrição                                                                                                             | Rastreabilidade                                                                                                                                                                                                            | Implementação |
| ---- | --------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF01 | O aplicativo filtra os eventos por Estado e por Município.                                                            | <a href="../tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS08</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS01</a>                                                    | Não           |
| RF02 | O aplicativo filtra os eventos por data e por horário.                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS02</a>, <a href="../tecnicas/questionario/#anchor_Q">Q03</a>                                                                                                               | Não           |
| RF03 | O aplicativo filtra os eventos por idade mínima de entrada.                                                           | <a href="../tecnicas/introspeccao/#anchor_IS">IS03</a>, <a href="../tecnicas/questionario/#anchor_Q">Q02</a>                                                                                                               | Não           |
| RF04 | O aplicativo permite realizar a compra do ingresso.                                                                   | <a href="../tecnicas/introspeccao/#anchor_IS">IS04</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS03</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS10</a>                                                    | Sim           |
| RF05 | O aplicativo permite o cadastro e o login do usuário.                                                                 | <a href="../tecnicas/introspeccao/#anchor_IS">IS05</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS01, <a href="../tecnicas/brainstorming/#anchor_BS">BS02                                                           | Sim           |
| RF06 | O aplicativo permite excluir cadastro.                                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS06</a>                                                                                                                                                                     | Sim           |
| RF07 | O aplicativo permite cadastrar métodos de pagamento.                                                                  | <a href="../tecnicas/introspeccao/#anchor_IS">IS07</a>, <a href="../tecnicas/questionario/#anchor_Q">Q08, <a href="../tecnicas/brainstorming/#anchor_BS">BS15</a>                                                          | Sim           |
| RF08 | O aplicativo permite cancelar compras.                                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS08</a>, <a href="../tecnicas/questionario/#anchor_Q">Q09</a>, <a href="../tecnicas/observacao/#anchor_IS">OBS12</a>                                                        | Sim           |
| RF09 | O aplicativo possui um mecanismo de busca.                                                                            | <a href="../tecnicas/introspeccao/#anchor_IS">IS09</a>, <a href="../tecnicas/questionario/#anchor_Q">Q01</a>, <a href="../tecnicas/brainstorm/#anchor_BS">BS04</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS02</a> | Sim           |
| RF10 | O aplicativo filtra eventos por categorias.                                                                           | <a href="../tecnicas/questionario/#anchor_Q">Q04</a>                                                                                                                                                                       | Não           |
| RF11 | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.                                      | <a href="../tecnicas/questionario/#anchor_Q">Q05</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS11</a>                                                                                                              | Não           |
| RF12 | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.                                  | <a href="../tecnicas/questionario/#anchor_Q">Q06</a>                                                                                                                                                                       | Não           |
| RF13 | O aplicativo notifica usuário sobre eventos, quando permitido.                                                        | <a href="../tecnicas/questionario/#anchor_Q">Q07</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS06</a>                                                                                                              | Não           |
| RF14 | O usuário é capaz de filtrar eventos                                                                                  | <a href="../tecnicas/brainstorming/#anchor_BS">BS05</a>                                                                                                                                                                    | Sim           |
| RF15 | O usuário pode salvar os dados do cartão no app                                                                       | <a href="../tecnicas/brainstorming/#anchor_BS">BS07</a>                                                                                                                                                                    | Sim           |
| RF16 | O usuário pode fornecer sua localização                                                                               | <a href="../tecnicas/brainstorming/#anchor_BS">BS09</a>                                                                                                                                                                    | Sim           |
| RF17 | O usuário pode acessar o calendário de eventos                                                                        | <a href="../tecnicas/brainstorming/#anchor_BS">BS10</a>                                                                                                                                                                    | Sim           |
| RF18 | O usuário pode responder a pesquisa de perfil sobre seus gostos                                                       | <a href="../tecnicas/brainstorming/#anchor_BS">BS12</a>                                                                                                                                                                    | Não           |
| RF19 | O usuário consegue acessar as informações do evento                                                                   | <a href="../tecnicas/brainstorming/#anchor_BS">BS13</a>                                                                                                                                                                    | Sim           |
| RF20 | O usuário é capaz de acessar as atrações do evento                                                                    | <a href="../tecnicas/brainstorming/#anchor_BS">BS14</a>                                                                                                                                                                    | Sim           |
| RF21 | O usuário possui acesso a pré-venda                                                                                   | <a href="../tecnicas/brainstorming/#anchor_BS">BS16</a>                                                                                                                                                                    | Sim           |
| RF22 | O usuário recebe a cópia do ingresso por e-mail                                                                       | <a href="../tecnicas/brainstorming/#anchor_BS">BS17</a>                                                                                                                                                                    | Sim           |
| RF23 | O usuário é capaz de conectar uma carteira digital                                                                    | <a href="../tecnicas/brainstorming/#anchor_BS">BS18</a>                                                                                                                                                                    | Não           |
| RF24 | O usuário é capaz de mudar o idioma do app                                                                            | <a href="../tecnicas/brainstorming/#anchor_BS">BS19</a>                                                                                                                                                                    | Não           |
| RF25 | O usuário é capaz de aumentar a fonte                                                                                 | <a href="../tecnicas/brainstorming/#anchor_BS">BS20</a>                                                                                                                                                                    | Não           |
| RF26 | O usuário é capaz de dar zoom                                                                                         | <a href="../tecnicas/brainstorming/#anchor_BS">BS21</a>                                                                                                                                                                    | Não           |
| RF27 | O usuário é capaz de acessar a assistente virtual                                                                     | <a href="../tecnicas/brainstorming/#anchor_BS">BS22</a>                                                                                                                                                                    | Não           |
| RF28 | O usuário é capaz de compartilhar o evento                                                                            | <a href="../tecnicas/brainstorming/#anchor_BS">BS23</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS03</a>                                                                                                            | Sim           |
| RF29 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | <a href="../tecnicas/observacao/#anchor_OBS">OBS04</a>                                                                                                                                                                     | Sim           |
| RF30 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | <a href="../tecnicas/observacao/#anchor_OBS">OBS05</a>                                                                                                                                                                     | Sim           |
| RF31 | O aplicativo permite selecionar as poltronas especiais.                                                               | <a href="../tecnicas/observacao/#anchor_OBS">OBS06</a>                                                                                                                                                                     | Sim           |
| RF32 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | <a href="../tecnicas/observacao/#anchor_OBS">OBS07</a>                                                                                                                                                                     | Sim           |
| RF33 | Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                                  | <a href="../tecnicas/observacao/#anchor_OBS">OBS08</a>                                                                                                                                                                     | Sim           |
| RF34 | O aplicativo permite a doação por parte do usuário para fundações                                                     | <a href="../tecnicas/observacao/#anchor_OBS">OBS09</a>                                                                                                                                                                     | Sim           |
| RF35 | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | <a href="../tecnicas/observacao/#anchor_OBS">OBS11</a>                                                                                                                                                                     | Sim           |
| RF36 | O aplicativo permite ao usuário alterar seus dados.                                                                   | <a href="../tecnicas/observacao/#anchor_OBS">OBS13</a>                                                                                                                                                                     | Sim           |
| RF37 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | <a href="../tecnicas/observacao/#anchor_OBS">OBS14</a>                                                                                                                                                                     | Sim           |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/nando3d3">Sidney Fernando</a></p></font>


<p style="text-align: center"><b>Tabela 3</b> - Requisitos Não Funcionais</p>

| ID    | Descrição                                                                     | Rastreabilidade                                                                                                                                                                                                                                                                                                                                                                                                                               | Implementação |
| ----- | ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RNF01 | O app deve encriptar as informações do usuário.                               | [Q10](../tecnicas/questionario/#anchor_QNF), [BS31](../tecnicas/brainstorming/#anchor_BSNF)                                                                                                                                                                                                                                                                                                                                                   | Sim           |
| RNF02 | O app deve fornecer eventos direcionados.                                     | [IS10](../tecnicas/introspeccao/#anchor_IS), [Q11](../tecnicas/questionario/#anchor_QNF), [BS35](../tecnicas/brainstorming/#anchor_BSNF), [BS36](../tecnicas/brainstorming/#anchor_BSNF), [OBS22](../tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                       | Não           |
| RNF03 | O app deve disponibilizar todas as informações do evento em uma página.       | [IS11](../tecnicas/introspeccao/#anchor_IS), [BS25](../tecnicas/brainstorming/#anchor_BSNF), [BS26](../tecnicas/brainstorming/#anchor_BSNF), [BS27](../tecnicas/brainstorming/#anchor_BSNF), [BS28](../tecnicas/brainstorming/#anchor_BSNF), [BS29](../tecnicas/brainstorming/#anchor_BSNF), [BS30](../tecnicas/brainstorming/#anchor_BSNF), [OBS15](<(../tecnicas/observacao/#anchor_OBSNF)>), [OBS16](../tecnicas/observacao/#anchor_OBSNF) | Não           |
| RNF04 | A compra deve ser feita em no máximo 5 páginas.                               | [IS13](../tecnicas/introspeccao/#anchor_IS), [IS16](../tecnicas/introspeccao/#anchor_IS), [Q14](../tecnicas/questionario/#anchor_QNF), [OBS17](../tecnicas/observacao/#anchor_OBSNF), [OBS18](../tecnicas/observacao/#anchor_OBSNF), [IS14](../tecnicas/introspeccao/#anchor_IS)                                                                                                                                                              | Não           |
| RNF05 | O app deve permitir a resolução de problemas sem uma interação com um humano. | [IS12](../tecnicas/introspeccao/#anchor_IS), [Q15](../tecnicas/questionario/#anchor_QNF), [Q16](../tecnicas/questionario/#anchor_QNF), [OBS19](../tecnicas/observacao/#anchor_OBSNF), [BS33](../tecnicas/brainstorming/#anchor_BSNF), [BS34](../tecnicas/brainstorming/#anchor_BSNF)                                                                                                                                                          |       Sim        |
| RNF06 | O app deve permitir o cadastro e login em uma tela separada.                  | [IS15](../tecnicas/introspeccao/#anchor_IS)                                                                                                                                                                                                                                                                                                                                                                                                   | Sim           |
| RNF07 | O app não deve ter tempo de resposta superior a 200 ms.                       | [Q12](../tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |
| RNF08 | O app deve permitir a filtragem dos eventos cadastrados no banco de dados.    | [Q13](../tecnicas/questionario/#anchor_QNF)                                                                                                                                                                                                                                                                                                                                                                                                   | Não           |
| RNF09 | O app deve mostrar as informações de compras do usuário em uma única tela.    | [BS32](../tecnicas/brainstorming/#anchor_BSNF), [OBS21](../tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                                                                                                                                                                 |   Sim             |
| RNF10 | O app deve permitir o acesso às informações do usuário em até 3 cliques.      | [OBS20](../tecnicas/observacao/#anchor_OBSNF)                                                                                                                                                                                                                                                                                                                                                                                                 | Sim           |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/mathonaut">Matheus Henrique</a></p></font>

## Elos

## Referências
> SAYÃO, LEITE, Miriam e Julio. Rastreabilidade de Requisitos. Departamento de informçatica. Disponível em: [file:///C:/Users/geooj/Downloads/Sayao%20e%20Leite%20-%20Rastreabilidade%20de%20Requisitos.pdf](file:///C:/Users/geooj/Downloads/Sayao%20e%20Leite%20-%20Rastreabilidade%20de%20Requisitos.pdf). Acesso em 24 de jun de 2023.

> SERRANO, Milene. Requisitos - Aula 26. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf](https://aprender3.unb.br/pluginfile.php/2523172/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf). Acesso em: 24 de jun de 2023.

## Histórico de Versão

Versão  | Data | Descrição | Autor(es) | Revisor(es)
-------- | ------ | ------ | ---------- | ----------
`1.0` | 24/06/2023 | Criação da página  | [Sidney Fernando](https://github.com/nando3d3) | [Geovanna Maciel](https://github.com/manuziny) |
`1.1` | 24/06/2023 | Adição da metodologia | [Geovanna Maciel](https://github.com/manuziny) | [Sidney Fernando](https://github.com/nando3d3)
`1.2` | 24/06/2023 | Adição dos requisitos | [Sidney Fernando](https://github.com/nando3d3) | [Geovanna Maciel](https://github.com/manuziny) |
