# Requisitos elicitados

## Introdução

Essa página reune todos os requisitos funcionais e não funcionais elicitados usando as técnicas de [introspecção](tecnicas/introspeccao.md), [questionário](tecnicas/questionario.md), [brainstorming](tecnicas/brainstorming.md) e [observação](tecnicas/observacao.md).

## Metodologia

As tabelas 1 e 2 apresentadas são dos requisitos funcionais e não funcionais, sendo que cada linha contém um ID, sua respectiva descrição, um hyperlink de rastreabilidade que direciona à página da(s) técnica(s) que elicitou o requisitão em questão e se ele foi implementado ou não.

A legenda para cada sigla é a seguinte:

* RFx: Requisito Funcional nºx
* RNFx: Requisito Não-Funcional nºx
* ISx: Requisito nºx elicitado pela Introspecção
* Qx: Requisito nºx elicitado pelo Questionário
* BSx: Requisito nºx elicitado pelo Brainstorming
* OBSx: Requisito nºx elicitado pela Observação

## Requisitos funcionais

<p style="text-align: center"><b>Tabela 1</b> - Requisitos funcionais</p>

| ID   | Descrição                                                                                                             | Rastreabilidade        | Implementação |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ---------------------- | ------------- |
| RF01 | O aplicativo filtra os eventos por Estado e por Município.                                                            | <a href="../tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS08</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS01</a>      | Não           |
| RF02 | O aplicativo filtra os eventos por data e por horário.                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS02</a>, <a href="../tecnicas/questionario/#anchor_Q">Q03</a>              | Não           |
| RF03 | O aplicativo filtra os eventos por idade mínima de entrada.                                                           | <a href="../tecnicas/introspeccao/#anchor_IS">IS03</a>, <a href="../tecnicas/questionario/#anchor_Q">Q02</a>              | Não           |
| RF04 | O aplicativo permite realizar a compra do ingresso.                                                                   | <a href="../tecnicas/introspeccao/#anchor_IS">IS04</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS03</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS10</a>      | Sim           |
| RF05 | O aplicativo permite o cadastro e o login do usuário.                                                                 | <a href="../tecnicas/introspeccao/#anchor_IS">IS05</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS01, <a href="../tecnicas/brainstorming/#anchor_BS">BS02       | Sim           |
| RF06 | O aplicativo permite excluir cadastro.                                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS06</a>                   | Sim           |
| RF07 | O aplicativo permite cadastrar métodos de pagamento.                                                                  | <a href="../tecnicas/introspeccao/#anchor_IS">IS07</a>, <a href="../tecnicas/questionario/#anchor_Q">Q08, <a href="../tecnicas/brainstorming/#anchor_BS">BS15</a>        | Sim           |
| RF08 | O aplicativo permite cancelar compras.                                                                                | <a href="../tecnicas/introspeccao/#anchor_IS">IS08</a>, <a href="../tecnicas/questionario/#anchor_Q">Q09</a>, <a href="../tecnicas/observacao/#anchor_IS">OBS12</a>      | Sim           |
| RF09 | O aplicativo possui um mecanismo de busca.                                                                            | <a href="../tecnicas/introspeccao/#anchor_IS">IS09</a>, <a href="../tecnicas/questionario/#anchor_Q">Q01</a>, <a href="../tecnicas/brainstorm/#anchor_BS">BS04</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS02</a> | Sim           |
| RF10 | O aplicativo filtra eventos por categorias.                                                                           | <a href="../tecnicas/questionario/#anchor_Q">Q04</a>                    | Não           |
| RF11 | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.                                      | <a href="../tecnicas/questionario/#anchor_Q">Q05</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS11</a>              | Não           |
| RF12 | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.                                  | <a href="../tecnicas/questionario/#anchor_Q">Q06</a>                    | Não           |
| RF13 | O aplicativo notifica usuário sobre eventos, quando permitido.                                                        | <a href="../tecnicas/questionario/#anchor_Q">Q07</a>, <a href="../tecnicas/brainstorming/#anchor_BS">BS06</a>              | Não           |
| RF14 | O usuário deve ser capaz de filtrar eventos                                                                           | <a href="../tecnicas/brainstorming/#anchor_BS">BS05</a>                   | Sim           |
| RF15 | O usuário deve salvar os dados do cartão no app                                                                       | <a href="../tecnicas/brainstorming/#anchor_BS">BS07</a>                  | Sim           |
| RF16 | O usuário deve fornecer sua localização                                                                               | <a href="../tecnicas/brainstorming/#anchor_BS">BS09</a>                   | Sim           |
| RF17 | O usuário deve poder acessar o calendário de eventos                                                                  | <a href="../tecnicas/brainstorming/#anchor_BS">BS10</a>                   | Sim           |
| RF18 | O usuário deve poder responder a pesquisa de perfil sobre seus gostos                                                 | <a href="../tecnicas/brainstorming/#anchor_BS">BS12</a>                   | Não           |
| RF19 | O usuário deve ser capaz de acessar as informações do evento                                                          | <a href="../tecnicas/brainstorming/#anchor_BS">BS13</a>                   | Sim           |
| RF20 | O usuário deve ser capaz de acessar as atrações do evento                                                             | <a href="../tecnicas/brainstorming/#anchor_BS">BS14</a>                   | Sim           |
| RF21 | O usuário deve ter acesso a pré-venda                                                                                 | <a href="../tecnicas/brainstorming/#anchor_BS">BS16</a>                   | Sim           |
| RF22 | O usuário deve receber a cópia do ingresso por e-mail                                                                 | <a href="../tecnicas/brainstorming/#anchor_BS">BS17</a>                   | Sim           |
| RF23 | O usuário deve ser capaz de conectar uma carteira digital                                                             | <a href="../tecnicas/brainstorming/#anchor_BS">BS18</a>                   | Não           |
| RF24 | O usuário deve ser capaz de mudar o idioma do app                                                                     | <a href="../tecnicas/brainstorming/#anchor_BS">BS19</a>                   | Não           |
| RF25 | O usuário deve ser capaz de aumentar a fonte                                                                          | <a href="../tecnicas/brainstorming/#anchor_BS">BS20</a>                   | Não           |
| RF26 | O usuário deve ser capaz de dar zoom                                                                                  | <a href="../tecnicas/brainstorming/#anchor_BS">BS21</a>                   | Não           |
| RF27 | O usuário deve ser capaz de acessar a assistente virtual                                                              | <a href="../tecnicas/brainstorming/#anchor_BS">BS22</a>                   | Não           |
| RF28 | O usuário deve ser capaz de compartilhar o evento                                                                     | <a href="../tecnicas/brainstorming/#anchor_BS">BS23</a>, <a href="../tecnicas/observacao/#anchor_OBS">OBS03</a>            | Sim           |
| RF29 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | <a href="../tecnicas/observacao/#anchor_OBS">OBS04</a>                  | Sim           |
| RF30 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | <a href="../tecnicas/observacao/#anchor_OBS">OBS05</a>                  | Sim           |
| RF31 | O aplicativo permite selecionar as poltronas especiais.                                                               | <a href="../tecnicas/observacao/#anchor_OBS">OBS06</a>                  | Sim           |
| RF32 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | <a href="../tecnicas/observacao/#anchor_OBS">OBS07</a>                  | Sim           |
| RF33 | Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                                  | <a href="../tecnicas/observacao/#anchor_OBS">OBS08</a>                  | Sim           |
| RF34 | O aplicativo permite a doação por parte do usuário para fundações                                                     | <a href="../tecnicas/observacao/#anchor_OBS">OBS09</a>                  | Sim           |
| RF35 | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | <a href="../tecnicas/observacao/#anchor_OBS">OBS11</a>                  | Sim           |
| RF36 | O aplicativo permite ao usuário alterar seus dados.                                                                   | <a href="../tecnicas/observacao/#anchor_OBS">OBS13</a>                  | Sim           |
| RF37 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | <a href="../tecnicas/observacao/#anchor_OBS">OBS14</a>                  | Sim           |