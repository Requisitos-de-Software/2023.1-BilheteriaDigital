# Observação

## Introdução

A técnica de observação de requisitos é uma abordagem importante para coletar informações sobre os requisitos de software. Essa técnica envolve observar usuários, processos e sistemas em ação, com o objetivo de entender as necessidades e desejos dos usuários finais, bem como as limitações e restrições do ambiente em que o aplicativo será utilizado. No entanto, essa técnica precisa de um usuário externo, o qual não foi possível encontrar. Dessa forma, o desenvolvedor [Rafael Ferreira](https://github.com/RafaelCLG0) interpretou o papel da persona [Pedro Matos](../personas.md).

## Participantes

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Função                   |
| ------------------------------------------------ | ------------------------ |
| [Arthur de Melo](https://github.com/arthurmlv)   | Observador               |
| [Rafael Ferreira](https://github.com/RafaelCLG0) | Representante da persona |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

## Metodologia

Os integrantes se reuniram no dia 29/04/2023 das 14:00 às 15:00, com os participantes explicitados na Tabela 1, no ambiente Microsoft Teams com o objetivo de realizar uma Observação Participativa, na qual cabe a interferência do Engenheiro de Software. Nessa, o [observador](https://github.com/arthurmlv) ficou responsável de instruir quais ações o usuário precisa realizar no aplicativo da Bilheteria Digital. Durante a análise, o usuário compartilhou a tela do celular e o observador foi ditando os caminhos que ele gostaria de analisar. Os requisitos levantados estão presentes nas Tabelas 2 e 3.

### [Link para a gravação da observação.](https://www.youtube.com/watch?v=lvlobqw0rx8)

## Requisitos elicitados

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- OBSx: Requisito nºx elicitado pela observação.

### Funcionais

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo | Descrição                                                                                                             | <a id="anchor_OBS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RF01 | O aplicativo filtra os eventos por Estado.                                                                            | OBS01                                                  | Sim          |
| RF02 | O aplicativo permite a busca por eventos.                                                                             | OBS02                                                  | Sim          |
| RF03 | O aplicativo permite compartilhar o evento por meio das redes sociais.                                                | OBS03                                                  | Sim          |
| RF04 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar.                                 | OBS04                                                  | Sim          |
| RF05 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05                                                  | Sim          |
| RF06 | O aplicativo permite selecionar as poltronas especiais.                                                               | OBS06                                                  | Sim          |
| RF07 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto.                                          | OBS07                                                  | Sim          |
| RF08 | Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona.                                  | OBS08                                                  | Sim          |
| RF09 | O aplicativo permite a doação por parte do usuário para fundações.                                                    | OBS09                                                  | Sim          |
| RF10 | O aplicativo permite a realização da compra dos ingressos.                                                            | OBS10                                                  | Sim          |
| RF11 | O aplicativo possui uma função para entrar em contato com o suporte.                                                  | OBS11                                                  | Sim          |
| RF12 | O aplicativo permite ao usuário cancelar o pedido.                                                                    | OBS12                                                  | Sim          |
| RF13 | O aplicativo permite ao usuário alterar seus dados.                                                                   | OBS13                                                  | Sim          |
| RF14 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário.                                        | OBS14                                                  | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                                                                                        | <a id="anchor_OBSNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | -------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- | ------------ |
| RNF01 | Deve possuir uma página que explicita os eventos da região selecionada.                                                          | OBS15                                                   | Sim          |
| RNF02 | Deve possuir, na página do evento, uma descrição sobre o local, a qual possui data, horário, valor e informações sobre o evento. | OBS16                                                   | Sim          |
| RNF03 | Deve apresentar uma tela de confirmação da poltrona selecionada.                                                                 | OBS17                                                   | Sim          |
| RNF04 | Deve apresentar uma página de confirmação das informações do pedido.                                                             | OBS18                                                   | Sim          |
| RNF05 | Deve apresentar uma página de suporte e de perguntas frequentes.                                                                 | OBS19                                                   | Sim          |
| RNF06 | Deve apresentar uma tela com os dados da conta.                                                                                  | OBS20                                                   | Sim          |
| RNF07 | Deve apresentar uma página com o histórico de pedidos do usuário.                                                                | OBS21                                                   | Sim          |
| RNF08 | Deve apresentar uma tela com as regiões para filtrar os eventos.                                                                 | OBS22                                                   | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 29/04/2023.

## Histórico de Versões

| Versão | Data       | Descrição                      | Autor(es)                                                                                         | Revisor(es)                                    |
| ------ | ---------- | ------------------------------ | ------------------------------------------------------------------------------------------------- | ---------------------------------------------- |
| 1.0    | 29/04/2023 | Documentação da observação     | [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Geovanna Maciel](https://github.com/manuziny) |
| 1.1    | 29/04/2023 | Adição da introdução           | [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Geovanna Maciel](https://github.com/manuziny) |
| 1.2    | 29/04/2023 | Adição das legendas            | [Arthur de Melo](https://github.com/arthurmlv)                                                    | [Sidney Fernando](https://github.com/nando3d3) |
| 1.3    | 29/04/2023 | Adição da aba de implementados | [Arthur de Melo](https://github.com/arthurmlv)                                                    | [Gabriel Campello](https://github.com/G16C)    |
