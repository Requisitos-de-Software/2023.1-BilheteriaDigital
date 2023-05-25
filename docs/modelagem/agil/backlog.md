# Backlog

## Introdução

O Backlog do Produto é um artefato da metodologia ágil que toma a forma de uma lista de todas as tarefas pendentes a serem feitas em um projetos. O responsável por priorizar os itens é o Dono do Produto (_Product Owner_). Vale ressaltar que o Backlog do Produto é um artefato dinâmico, ou seja, ele cresce e muda à medida que os requisitos e a visão do produto são alterados.

Para a produção do artefato haverá a participação da persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) que será o _Product Owner_ do projeto, para tal foi utilizado o método da encenação. A encenação foi realizada via Teams às 17h do dia 23 de maio de 2023 e os participantes são apresentados na tabela 1.

<center>

**Tabela 1** - Participantes da encenação.

| **Participante**                                                                                                                                       | **Função**    |
| :----------------------------------------------------------------------------------------------------------------------------------------------------- | :------------ |
| [Matheus Henrique](https://github.com/mathonaut)                                                                                                       | Desenvolvedor |
| [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) ([Rafael Ferreira](https://github.com/RafaelCLG0)) | Product Owner |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

## Metodologia

Para o desenvolvimento deste artefato, foi definido um tema e um épico a serem realizados a partir dos requisitos funcionais apresentados na seção de [Requisitos Elicitados](../../../elicitacao/requisitos_elicitados). Em um primeiro momento os requisitos analisados foram os que ainda não tiveram a sua implementação, evitando assim engenharia reversa do produto. Os requisitos analisados estão sendo apresentados na tabela 2.

<center>

**Tabela 2** - Requisitos Funcionais Elicitados não Implementados.

| ID   | Descrição                                                                            | Rastreabilidade                                                                                                                                                                                                            | Implementação |
| ---- | ------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------- |
| RF01 | O aplicativo filtra os eventos por Estado e por Município.                           | <a href="../../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a>, <a href="../../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a> | Não           |
| RF02 | O aplicativo filtra os eventos por data e por horário.                               | <a href="../../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a>, <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a>                                                                             | Não           |
| RF03 | O aplicativo filtra os eventos por idade mínima de entrada.                          | <a href="../../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a>, <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a>                                                                             | Não           |
| RF10 | O aplicativo filtra eventos por categorias.                                          | <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a>                                                                                                                                                      | Não           |
| RF11 | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.     | <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a>, <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a>                                                                            | Não           |
| RF12 | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca. | <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a>                                                                                                                                                      | Não           |
| RF13 | O aplicativo notifica usuário sobre eventos, quando permitido.                       | <a href="../../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a>, <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a>                                                                            | Não           |
| RF18 | O usuário pode responder a pesquisa de perfil sobre seus gostos                      | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS12</a>                                                                                                                                                   | Não           |
| RF23 | O usuário é capaz de conectar uma carteira digital                                   | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS18</a>                                                                                                                                                   | Não           |
| RF24 | O usuário é capaz de mudar o idioma do app                                           | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a>                                                                                                                                                   | Não           |
| RF26 | O usuário é capaz de dar zoom                                                        | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS21</a>                                                                                                                                                   | Não           |
| RF27 | O usuário é capaz de acessar a assistente virtual                                    | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS22</a>                                                                                                                                                   | Não           |

Fonte: [Sidney Fernando](https://github.com/nando3d3).

</center>

## Temas

Analisando os requisitos da tabela, foi possível organizá-los inicialmente em dois grandes temas.

- **Funcionalidades**: Agrupa funcionalidades que o sistema precisa oferecer para que o usuário consiga realizar com sucesso suas tarefas.
- **Perfil**: Agrupa funcionalidades relacionadas a como o usuário se apropria do sistema e o modifica de acordo com seus gostos e desejos.

## Épicos

Após a definição dos temas, eles são "quebrados" em épicos de modo a diminuir ainda mais a abstração das atividades que deverão ser realizadas no projeto. Para esse projeto, os épicos foram descritos utilizando o padrão de escrita das histórias de usuário e possuem um nível de abstração a mais chamado de _Features_.

Definido um épico, são geradas _features_, que representa as funcionalidades em um nível de abstração maior que as histórias de usuário, e as próprias histórias de usuário que especifica ainda mais as _features_. Em relação às histórias de usuário, elas serão especificadas na seção de [Histórias de Usuário](../historia-de-usuario). No contexto desse trabalho, as _features_ e as histórias de usuário serão apresentadas seguindo o template apresentado na tabela 3.

<center>

**Tabela 3** - Template das Features e Histórias de Usuário.

| Feature                             | ID da História                       | História de usuário                                  |
| ----------------------------------- | ------------------------------------ | ---------------------------------------------------- |
| Funcionalidade relacionada ao épico | Identificação da História de Usuário | Visão do usuário sobre um determinada funcionalidade |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 1 - Filtragem

Esse épico apresenta as funcionalidades que permite aos usuários filtrarem eventos em classes específicas, como por localidade, data, horário, idade e categorias. A história de usuário a seguir o generaliza:

<center>
*"Como usuário típico, eu desejo funcionalidades que me permitam filtrar os eventos"*
</center>

A tabela 4 a seguir apresenta as features e histórias de usuário relacionadas a esse épico.

<center>

**Tabela 4** - Features e Histórias de Usuário.

| Feature                  |                                                    ID da História                                                    | História de usuário                                                                         |
| ------------------------ | :------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------ |
| Feature 1 - Local e Data |                     [US01](../historia-de-usuario/#US01)<br>[US02](../historia-de-usuario/#US02)                     | Filtro por estado e município.<br>Filtro por data e por horário.                            |
| Feature 2 - Categorias   | [US03](../historia-de-usuario/#US03)<br>[US04](../historia-de-usuario/#US04)<br>[US05](../historia-de-usuario/#US05) | Filtro por idade mínima de entrada.<br>Filtro por categorias.<br>Tags associadas a eventos. |

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

| Feature                   |                                ID da História                                | História de usuário                          |
| ------------------------- | :--------------------------------------------------------------------------: | :------------------------------------------- |
| Feature 3 - Avisos        | [US06](../historia-de-usuario/#US06)<br>[US07](../historia-de-usuario/#US07) | Sugestão de busca.<br>Notificação de evento. |
| Feature 4 - Configurações |                     [US08](../historia-de-usuario/#US08)                     | Responder pesquisa de perfil.                |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 3 - Acessibilidade

Esse épico apresenta as funcionalidades que auxiliam os usuários a realizarem tarefas dentro do sistema, esse auxílio pode ser com atalhos que aceleram a conclusão de uma determinada tarefa como também através de ferramentas que permite que usuário com deficiência (PCD) consigam de fato utilizar o sistema. A história de usuário a seguir o generaliza:

<center>
*"Como usuário com necessidades especiais, eu desejo recursos que me permitam realizar com velocidade tarefas no site"*
</center>

A tabela 6 apresenta as features e histórias de usuário relacionada a esse épico.

<center>

**Tabela 6** - Features e Histórias de Usuário.

| Feature                                   |                                ID da História                                | História de usuário                      |
| ----------------------------------------- | :--------------------------------------------------------------------------: | :--------------------------------------- |
| Feature 5 - Atalhos                       |                     [US09](../historia-de-usuario/#US09)                     | Conectar carteira digital.               |
| Feature 6 - Central de Ajuda              |                     [US10](../historia-de-usuario/#US10)                     | Acessar à assistente virtual.            |
| Feature 7 - Ferramentas de Acessibilidade | [US11](../historia-de-usuario/#US11)<br>[US12](../historia-de-usuario/#US12) | Mudar idioma do aplicativo.<br>Dar zoom. |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

## Histórico de Versões

| Versão  | Data       | Descrição                             | Autor(es)                                                                                           | Revisor(es)                                      |
| ------- | ---------- | ------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| `1.0`   | 22/05/2023 | Criação da página.                    | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.1`   | 23/05/2023 | Adição das Features.                  | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Arthur de Melo](https://github.com/arthurmlv)   |
| `1.1.1` | 23/05/2023 | Atualização metodologia.              | [Douglas Alves dos Santos](https://github.com/dougAlvs)                                             | [Arthur de Melo](https://github.com/arthurmlv)   |
| `1.2`   | 24/05/2023 | Ajustes nos textos e adição de links. | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Arthur de Melo](https://github.com/arthurmlv)   |
