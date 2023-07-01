# First Things First

## Introdução

A técnica _First Things First_ <a id="FTF1" href="#FTF1Ref">^1^</a> (FTF) enfatiza a necessidade de avaliar cuidadosamente os custos e benefícios de cada requisito de um software, bem como as implicações que cada um terá na sua arquitetura. É importante também garantir que os requisitos estejam alinhados com as regras de negócios e que o risco técnico associado a cada requisito seja considerado. Em resumo, a técnica destaca a importância de priorizar os requisitos de forma criteriosa e estratégica, a fim de maximizar os benefícios e minimizar os riscos e custos envolvidos no desenvolvimento do software.

## Metodologia

As pessoas que participaram da elaboração dessa técnica estão descritas abaixo e listadas na tabela 1:

- **Mediador**: Responsável por apresentar os requisitos listados
- **Cliente**: Responsável por classificar benefícios e penalidades na implementação de cada requisito.
- **Desenvolvedor**: Responsável por identificar custos e riscos na implementação de cada requisito.

<center>

**Tabela 1** - Participantes.

| Nome                                              | Função        |
| ------------------------------------------------- | ------------- |
| [Rafael Ferreira](https://github.com/rafaelclg0)  | Mediador      |
| <span style = "color: orange">Felipe Costa</span> | Usuário       |
| [Matheus Henrique](https://github.com/mathonaut)  | Desenvolvedor |
| [Sidney Fernando](https://github.com/nando3d3)    | Mediador      |

_Fonte: Elaborada por [Sidney Fernando](https://github.com/nando3d3)._

</center>

Duas reuniões foram realizadas na plataforma Microsoft Teams:

- Entre o desenvolvedor e o mediador, na data de 29/04/2023 às 20h. [Vídeo da entrevista com o desenvolvedor](https://youtu.be/Nb_xTFSltQQ)
- Entre o cliente e o mediador, na data de 29/04/2023 às 20:30. [Vídeo da entrevista com o cliente](https://youtu.be/NTsldexRzLo)

A técnica foi elaborada da seguinte forma:

1. Listar todos os requisitos elicitados e retirar aqueles que são logicamente ligados (se X depende de Y, então apenas é X é listado).
2. Para cada requisito, o cliente deve estimar de 1 a 9 o benefício agregado, sendo que 1 indica pouco benefício e 9 é o maior benefício possível, e a penalidade da não implementação, sendo que 1 significa que não há penalidade e 9 indica uma penalidade muito séria. O **valor total** é calculado da seguinte forma: <br> <p align="center" style="font-size: 18px;">`valor total = (benefício * peso) + (penalidade * peso)`</p>
3. Para cada requisito, o desenvolvedor deve estimar de 1 a 9 o **custo** de implementação de cada requisito, sendo 1 o custo mais baixo e 9 é o mais alto, levando em consideração a complexidade, a interface necessária, a capacidade de reutilização do código e os testes.
4. Os desenvolvedores também estimam o grau relativo de **riscos** associados com o recurso em uma escala de 1 a 9, sendo que 1 significa grande facilidade na implementação e 9 indica preocupações sérias sobre viabilidade, disponibilidade de equipe ou mesmo falta de experiência com novas ferramentas ou tecnologias.
5. Então é feito o cálculo de **prioridade** para cada requisito da seguinte forma:<br> <p align="center" style="font-size: 18px;">`prioridade = valor(%)/(custo(%) * peso do custo + risco(%) * peso do risco)`</p>
6. A tabela deve ser ordenada de acordo com a ordem decrescente de prioridade, sendo os requisitos do topo da lista os mais equilibrados em termos de valor, custo e risco. Tendo isso em mente, tais requisitos devem ser priorizados.

## Resultado de Priorização

Na Tabela 2 é possível ver os resultados ordenada de acordo com a ordem decrescente de prioridade, sendo os requisitos do topo da lista os mais equilibrados em termos de valor, custo e risco.
Nas Tabelas 3 e 4 estão os ID's dos requisitos presentes na tabela de resultados e sua respectiva descrição.

**Peso relativo**:

- Benefício: 2
- Penalidade: 1
- Custo: 1
- Risco: 0,5

<center>

**Tabela 2** - Tabela de resultado da priorização de requisitos.

| Funcionalidade | Benefício<br>Relativo | Penalidade<br>Relativa | Valor<br>total | Valor<br>(%) | Custo<br>Relativo | Custo<br>% | Risco<br>Relativo | Risco<br>% | Prioridade |
| -------------- | --------------------- | ---------------------- | -------------- | ------------ | ----------------- | ---------- | ----------------- | ---------- | ---------- |
| BS24           | 9                     | 9                      | 27             | 4,53         | 1                 | 1,35       | 1                 | 1,16       | 2,344      |
| IS16           | 9                     | 9                      | 27             | 4,53         | 1                 | 1,35       | 1                 | 1,16       | 2,344      |
| IS11           | 8                     | 8                      | 24             | 4,03         | 1                 | 1,35       | 1                 | 1,16       | 2,083      |
| Q14            | 7                     | 7                      | 21             | 3,52         | 1                 | 1,35       | 1                 | 1,16       | 1,823      |
| BS13           | 9                     | 9                      | 27             | 4,53         | 1                 | 1,35       | 3                 | 3,49       | 1,463      |
| BS19           | 5                     | 5                      | 15             | 2,52         | 1                 | 1,35       | 1                 | 1,16       | 1,302      |
| IS08           | 9                     | 9                      | 27             | 4,53         | 2                 | 2,70       | 2                 | 2,33       | 1,172      |
| IS13           | 9                     | 9                      | 27             | 4,53         | 2                 | 2,70       | 2                 | 2,33       | 1,172      |
| IS15           | 9                     | 9                      | 27             | 4,53         | 2                 | 2,70       | 2                 | 2,33       | 1,172      |
| Q13            | 8                     | 8                      | 24             | 4,03         | 2                 | 2,70       | 2                 | 2,33       | 1,042      |
| IS06           | 9                     | 7                      | 25             | 4,19         | 2                 | 2,70       | 4                 | 4,65       | 0,834      |
| IS05           | 9                     | 9                      | 27             | 4,53         | 2                 | 2,70       | 6                 | 6,98       | 0,732      |
| Q15            | 8                     | 8                      | 24             | 4,03         | 3                 | 4,05       | 3                 | 3,49       | 0,694      |
| Q07            | 5                     | 5                      | 15             | 2,52         | 2                 | 2,70       | 2                 | 2,33       | 0,651      |
| Q11            | 7                     | 7                      | 21             | 3,52         | 3                 | 4,05       | 3                 | 3,49       | 0,608      |
| IS09           | 9                     | 9                      | 27             | 4,53         | 4                 | 5,41       | 4                 | 4,65       | 0,586      |
| IS10           | 9                     | 9                      | 27             | 4,53         | 4                 | 5,41       | 4                 | 4,65       | 0,586      |
| IS12           | 9                     | 9                      | 27             | 4,53         | 4                 | 5,41       | 4                 | 4,65       | 0,586      |
| BS05           | 6                     | 5                      | 17             | 2,85         | 3                 | 4,05       | 3                 | 3,49       | 0,492      |
| IS04           | 9                     | 9                      | 27             | 4,53         | 5                 | 6,76       | 5                 | 5,81       | 0,469      |
| Q12            | 9                     | 9                      | 27             | 4,53         | 5                 | 6,76       | 5                 | 5,81       | 0,469      |
| IS14           | 7                     | 8                      | 22             | 3,69         | 5                 | 6,76       | 6                 | 6,98       | 0,360      |
| Q05            | 7                     | 5                      | 19             | 3,19         | 5                 | 6,76       | 6                 | 6,98       | 0,311      |
| Q10            | 9                     | 9                      | 27             | 4,53         | 7                 | 9,46       | 9                 | 10,47      | 0,308      |
| BS23           | 6                     | 6                      | 18             | 3,02         | 6                 | 8,11       | 6                 | 6,98       | 0,260      |
| TOTAL          |                       |                        | 596            |              | 74                | 100        | 86                | 100        |

_Fonte - Autores._

</center>

### Descrição dos requisitos funcionais

<center>

**Tabela 3** - ID dos Requisitos funcionais e sua respectiva descrição.

| ID                                                         | Descrição                                                                        |
| ---------------------------------------------------------- | -------------------------------------------------------------------------------- |
| <a href="../../tecnicas/introspeccao/#anchor_IS">IS04</a>  | O aplicativo permite realizar a compra do ingresso.                              |
| <a href="../../tecnicas/introspeccao/#anchor_IS">IS05</a>  | O aplicativo permite o cadastro e o login do usuário.                            |
| <a href="../../tecnicas/introspeccao/#anchor_IS">IS06</a>  | O aplicativo permite excluir cadastro.                                           |
| <a href="../../tecnicas/introspeccao/#anchor_IS">IS08</a>  | O aplicativo permite cancelar compras.                                           |
| <a href="../../tecnicas/introspeccao/#anchor_IS">IS09</a>  | O aplicativo possui um mecanismo de busca.                                       |
| <a href="../../tecnicas/questionario/#anchor_Q">Q05</a>    | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário. |
| <a href="../../tecnicas/questionario/#anchor_Q">Q07</a>    | O aplicativo notifica usuário sobre eventos, quando permitido.                   |
| <a href="../../tecnicas/brainstorming/#anchor_BS">BS05</a> | O usuário é capaz de filtrar eventos                                      |
| <a href="../../tecnicas/brainstorming/#anchor_BS">BS13</a> | O usuário é capaz de acessar as informações do evento                     |
| <a href="../../tecnicas/brainstorming/#anchor_BS">BS19</a> | O usuário é capaz de mudar o idioma do app                                |
| <a href="../../tecnicas/brainstorming/#anchor_BS">BS23</a> | O usuário é capaz de acessar a assistente virtual                         |
| <a href="../../tecnicas/brainstorming/#anchor_BS">BS24</a> | O usuário é capaz de compartilhar o evento                                |

_Fonte: Autores._

</center>

### Descrição dos requisitos não funcionais

<center>

**Tabela 4** - ID dos Requisitos não-funcionais e sua respectiva descrição.

| ID                                                        | Descrição                                                                                                                         |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| [IS10](../../tecnicas/introspeccao/#anchor_ISNF)          | Deve possuir apresentar eventos de forma personalizada, de acordo com a atividade do usuário.                                                           |
| [IS11](../../tecnicas/introspeccao/#anchor_ISNF)          | O usuário deve ser capaz de acessar as seguintes informações do evento durante a busca em, no máximo, 2 cliques: a data, o local e o preço do ingresso.                                 |
| [IS12](../../tecnicas/introspeccao/#anchor_ISNF)          | O usuário deve ser capaz de acessar um tópico de ajuda com ao menos 3 cliques.                                                               |
| [IS13](../../tecnicas/introspeccao/#anchor_ISNF)          | Deve possuir uma tela de aviso sobre o início/fim de venda de ingressos para um dado evento em forma notificação, sendo essa acessível com 1 clique.                                      |
| [IS14](../../tecnicas/introspeccao/#anchor_ISNF)          | Deve oferecer atendimento especial para idosos/deficientes durante o processo de compra de ingressos. |
| [IS15](../../tecnicas/introspeccao/#anchor_ISNF)          | Deve oferecer um mecanismo de autenticação seguro que permita aos usuários realizar o login com suas credenciais.                                                                                      |
| [IS16](../../tecnicas/introspeccao/#anchor_ISNF)          | Deve possuir uma área para os usuários reportarem erros de funcionamento do aplicativo.                                           |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q10</a> | O aplicativo deve proteger os dados de cadastro e compra dos usuários.                                                            |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q11</a> | O aplicativo deve disponibilizar em sua interface eventos que são relevantes ao usuário.                                          |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q12</a> | As notificações do aplicativo devem ser fornecidas em tempo hábil.                                                                |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q13</a> | O sistema deve ser capaz de indexar e pesquisar palavras-chave ou tags de eventos a fim de oferecer uma resposta rápida aos usuários durante a busca.                                         |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q14</a> | O aplicativo deverá permitir a compra de ingressos de maneira simples (em menos de três telas).                                   |
| <a href="../../tecnicas/questionario/#anchor_QNF">Q15</a> | O sistema deve solucionar problemas relacionados a compra de ingressos.                                       |

_Fonte: Autores._

</center>

## Referências Bibliográficas

> <a id="FTF1Ref" href="#FTF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.

## Histórico de versões

| Versão | Data       | Descrição                                                                                           | Autor(es)                                                                                                                                          | Revisor(es)                                      |
| ------ | ---------- | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| `1.0`  | 29/04/2023 | Definição dos passos para realizar a ténica FTF                                                     | [Sidney Fernando](https://github.com/nando3d3)                                                                                                     | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.1`  | 29/04/2023 | Adição dos resultados e entrevista                                                                  | [Sidney Fernando](https://github.com/nando3d3), [Rafael Ferreira](https://github.com/RafaelCLG0), [Matheus Henrique](https://github.com/mathonaut) | [Douglas Alves](https://github.com/dougalvs)     |
| `1.2`  | 21/06/2023 | Corrigido os erros ID4 e ID5 da [verificação](../../../verificacao/grupo/entrega2/verificacao-ftf). | [Rafael Ferreira](https://github.com/RafaelCLG0)                                                                                                   | [Matheus Henrique](https://github.com/mathonaut) |
| `1.3`  | 01/07/2023 | Ajustes dos não-funcionais. | [Arthur de Melo](https://github.com/arthurmlv) | [Douglas Alves](https://github.com/dougAlvs) |
