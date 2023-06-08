# Backlog

## Introdução

O Backlog do Produto é um artefato da metodologia ágil que toma a forma de uma lista de todas as tarefas pendentes a serem feitas em um projetos. O responsável por priorizar os itens é o Dono do Produto (_Product Owner_). Vale ressaltar que o Backlog do Produto é um artefato dinâmico, ou seja, ele cresce e muda à medida que os requisitos e a visão do produto são alterados.

Para a produção do artefato teve a participação do PO do projeto, para tal foi utilizado o método da entrevista, que foi realizada via Discord às 20:45 do dia 31 de maio de 2023.Os participantes são apresentados na tabela 1 e gravação da entrevista é apresentado no vídeo 1.

<center>

**Tabela 1** - Participantes da entrevista.

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Ana</span>               | Product Owner  |
| [Douglas Alves dos Santos](https://github.com/dougAlvs) | Desenvolvedor  |
| [Geovanna Maciel](https://github.com/manuziny)          | Entrevistadora |
| [Matheus Henrique](https://github.com/mathonaut)        | Desenvolvedor  |
| [Rafael Ferreira](https://github.com/RafaelCLG0)        | Desenvolvedor  |


Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

<center>

**Vídeo 1** - Entrevista com o PO.

<iframe width="560" height="315" src="https://www.youtube.com/embed/2o3diusGVC8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<a href="https://www.youtube.com/embed/2o3diusGVC8" target="blanket">Clique aqui</a>

Fonte: [Geovanna Maciel](https://github.com/manuziny).

</center>

## Metodologia

Para o desenvolvimento deste artefato, foi criado em conjunto com as [Histórias de Usuário](../historia-de-usuario) e foram definidos temas, épicos e features a serem realizados a partir dos requisitos funcionais apresentados na tabela 2.

<center>

*Tabela 2* - Requisitos Elicitados com o Product Owner.

| ID    | Descrição                                                                                                        | Rastreabilidade | Implementação |
| ----- | ---------------------------------------------------------------------------------------------------------------- | --------------- | ------------- |
| REQ01 | O aplicativo deve classificar eventos por local.                                                                 |                 |               |
| REQ02 | O aplicativo deve classificar eventos por modalidade.                                                            |                 |               |
| REQ03 | O aplicativo deve apresentar o valor total dos ingressos selecionados antes da confirmação.                      |                 |               |
| REQ04 | O aplicativo deve classificar eventos por data.                                                                  |                 |               |
| REQ05 | O aplicativo deve possuir um histórico de visualização de eventos.                                               |                 |               |
| REQ06 | O aplicativo deve possuir uma contagem regressiva para realização de eventos.                                    |                 |               |
| REQ07 | O aplicativo deve vender ingressos de eventos de diferentes categorias.                                          |                 |               |
| REQ08 | O aplicativo deve classificar os diferentes tipos de assentos e explicá-los.                                     |                 |               |
| REQ09 | O aplicativo deve exigir somente os dados necessários para cadastro e pagamento.                                 |                 |               |
| REQ10 | O aplicativo deve dar ao usuário a opção de salvar ou não seus dados de pagamento.                               |                 |               |
| REQ11 | O aplicativo deve garantir a privacidade dos dados de pagamento dos usuários.                                    |                 |               |
| REQ12 | O aplicativo deve ter uma tela com a lista de eventos disponíveis.                                               |                 |               |
| REQ13 | O aplicativo deve ter uma página de descrição de eventos com data, local e valor.                                |                 |               |
| REQ14 | O aplicativo deve ter uma lista de confirmação de pagamento.                                                     |                 |               |
| REQ15 | O aplicativo deve limitar a compra de ingressos de determinado usuário.                                          |                 |               |
| REQ16 | O aplicativo deve possuir opção de transferência de ingresso.                                                    |                 |               |
| REQ17 | O aplicativo deve possuir diferentes opções de pagamento como pix, crédito, débito, boleto e carteiras digitais. |                 |               |
| REQ18 | O aplicativo deve realizar envio dos ingressos comprados por email como confirmação.                             |                 |               |
| REQ19 | O aplicativo deve apresentar uma aba de visualização de ingressos.                                               |                 |               |
| REQ20 | O aplicativo deve possuir uma opção de cancelar uma compra.                                                      |                 |               |
| REQ21 | O aplicativo deve possuir recomendação de eventos com base no gosto do usuário, por meio de uma avaliação.       |                 |               |
| REQ22 | O usuário pode escolher receber notificações ou não do aplicativo.                                               |                 |               |
| REQ23 | O aplicativo deve exibir notificações por eventos próximos com base no gosto do usuário.                         |                 |               |
| REQ24 | O aplicativo deve ter termos de privacidade explícitos em relação aos dados inseridos.                           |                 |               |
| REQ25 | O usuário deve poder criar uma conta e fazer login com email.                                                    |                 |               |
| REQ26 | O aplicativo deve ter autenticação de dois fatores.                                                              |                 |               |
| REQ27 | O aplicativo deve permitir opções de cadastro por redes sociais validados por email.                             |                 |               |
| REQ28 | O aplicativo deve exigir uma senha segura durante um cadastro.                                                   |                 |               |
| REQ29 | O aplicativo deve possuir informações sobre inclusão na descrição dos eventos.                                   |                 |               |
| REQ30 | O aplicativo deve possuir audiodescrição.                                                                        |                 |               |
| REQ31 | O aplicativo deve possuir alto contraste.                                                                        |                 |               |
| REQ32 | O aplicativo deve possuir opções de cores para daltónicos.                                                       |                 |               |
| REQ33 | O aplicativo deve possuir um botão de troca de idioma próximo à conta.                                           |                 |               |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

## Temas

Analisando os requisitos da tabela, foi possível organizá-los inicialmente em dois grandes temas.

- **Funcionalidades**: Agrupa funcionalidades que o sistema precisa oferecer para que o usuário consiga realizar com sucesso suas tarefas.
- **Perfil**: Agrupa funcionalidades relacionadas a como o usuário se apropria do sistema e o modifica de acordo com seus gostos e desejos.

## Épicos

Após a definição dos temas, eles são "quebrados" em épicos de modo a diminuir ainda mais a abstração das atividades que deverão ser realizadas no projeto. Para esse projeto, os épicos foram descritos utilizando o padrão de escrita das histórias de usuário e possuem um nível de abstração a mais chamado de _Features_.

## Features

Definido um épico, são geradas _features_, que são descrições simplificadas do que o produto faz para atender os objetivos dos usuários.  Elas representam as funcionalidades em um nível de abstração maior que as histórias de usuário.

### Histórias de Usuário

Elas especificam ainda mais as _features_ e serão apresentadas na seção de [Histórias de Usuário](../historia-de-usuario). No contexto desse trabalho, as _features_ e as histórias de usuário seguiram o template apresentado na tabela 3.

<center>

**Tabela 3** - Template das Features e Histórias de Usuário.

| Feature                             | ID da História                       | História de usuário                                  |
| ----------------------------------- | ------------------------------------ | ---------------------------------------------------- |
| Funcionalidade relacionada ao épico | Identificação da História de Usuário | Visão do usuário sobre um determinada funcionalidade |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 1 - Categorizar

Esse épico apresenta as funcionalidades que permite aos usuários busque eventos em classes específicas, como por localidade, data, horário, classificação e categorias. A história de usuário a seguir o generaliza:

<center>
*"Como usuário típico, eu desejo funcionalidades que me permitam categorizar os eventos"*
</center>

A tabela 4 a seguir apresenta as features e histórias de usuário relacionadas a esse épico.

<center>

**Tabela 4** - Features e Histórias de Usuário.

| Feature                  | ID da História | História de usuário |
| ------------------------ | :------------: | :------------------ |
| Feature 1 - Local e Data |                |                     |
| Feature 2 - Modalidade   |                |                     |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 2 - Preferências

Esse épico apresenta as funcionalidades que permite aos usuários modificarem o sistema de acordo com os seus gostos, mas também funcionalidades que permitem que o sistema ofereça sugestões de eventos personalizadas para cada usuário. A história de usuário a seguir o generaliza:

<center>
*"Como usuário típico, eu desejo modificar o site de acordo com as minhas preferências"*
</center>

A tabela 5 apresenta as features e histórias de usuário relacionada a esse épico.

<center>

**Tabela 5** - Features e Histórias de Usuário.

| Feature                   | ID da História | História de usuário |
| ------------------------- | :------------: | :------------------ |
| Feature 3 - Notificações  |                |                     |
| Feature 4 - Configurações |                |                     |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 3 - Acessibilidade

Esse épico apresenta as funcionalidades que auxiliam os usuários a realizarem tarefas dentro do sistema, esse auxílio pode ser com atalhos que aceleram a conclusão de uma determinada tarefa como também através de ferramentas que permite que usuário com deficiência (PCD) consigam de fato utilizar o sistema. A história de usuário a seguir o generaliza:

<center>
*"Como usuário, eu desejo recursos que me permitam realizar com velocidade tarefas no site"*
</center>

A tabela 6 apresenta as features e histórias de usuário relacionada a esse épico.

<center>

**Tabela 6** - Features e Histórias de Usuário.

| Feature                                   | ID da História | História de usuário |
| ----------------------------------------- | :------------: | :------------------ |
| Feature 5 - Ferramentas de Acessibilidade |                |                     |
| Feature 6 - Atalhos                       |                |                     |
| Feature 7 - Ferramentas Complementares    |                |                     |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 4 - Segurança

Esse épico apresenta as funcionalidades que garantem aos usuário segurança contra condições desfavoráveis ou até mesmo perigosas. Evitando que o usuário cometa erros e realize atividades não desejáveis, como também oferecer maneiras de recuperação desses erros aos usuários.

<center>
*"Como usuário, eu desejo recursos de segurança"*
</center>

A tabela 7 apresenta as features e histórias de usuário relacionada a esse épico.

<center>

**Tabela 7** - Features e Histórias de Usuário.

| Feature                          | ID da História | História de usuário |
| -------------------------------- | :------------: | :------------------ |
| Feature 8 - Integridade de Dados |                |                     |
| Feature 9 - Prevenção de Erros   |                |                     |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 5 - Padronização

Este épico enfatiza as funcionalidades e atributos que contribuem para a eficiência e eficácia do sistema. Essas características garantem que o sistema seja capaz de executar suas tarefas de maneira rápida, precisa e com ótimos resultados. Além disso, o sistema é projetado de forma a ser facilmente memorizado pelos usuários, permitindo que eles se familiarizem rapidamente com suas funcionalidades e navegação.

<center>
*"Como usuário, eu desejo um sistema de fácil utilização"*
</center>

A tabela 8 apresenta as features e histórias de usuário relacionada a esse épico.

<center>

**Tabela 8** - Features e Histórias de Usuário.

| Feature                              | ID da História | História de usuário |
| ------------------------------------ | :------------: | :------------------ |
| Feature 10 - Interface               |                |                     |
| Feature 11 - Ferramentas Necessárias |                |                     |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

## Histórico de Versões

| Versão  | Data       | Descrição                             | Autor(es)                                                                                           | Revisor(es)                                                                                   |
| ------- | ---------- | ------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `1.0`   | 22/05/2023 | Criação da página.                    | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Rafael Ferreira](https://github.com/RafaelCLG0)                                              |
| `1.1`   | 23/05/2023 | Adição das Features.                  | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `1.1.1` | 23/05/2023 | Atualização metodologia.              | [Douglas Alves dos Santos](https://github.com/dougAlvs)                                             | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `1.2`   | 24/05/2023 | Ajustes nos textos e adição de links. | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `2.0`   | 08/06/2023 | Refatoração do Artefato               | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) |
