# Backlog

## Introdução

O Backlog do Produto é um artefato da metodologia ágil que toma a forma de uma lista de todas as tarefas pendentes a serem feitas em um projetos. O responsável por priorizar os itens é o Dono do Produto (_Product Owner_). Vale ressaltar que o Backlog do Produto é um artefato dinâmico, ou seja, ele cresce e muda à medida que os requisitos e a visão do produto são alterados. Para a produção do artefato haverá  a participação da persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) que será o Product Owner do projeto, para tal foi utilizado o método da encenação, melhor representado na tabela 1. A reunião foi realizada via Teams às 17h do dia 23 de maio de 2023.

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>
<center>

| **Participante** | **Função** |
|:-------|:---------|
| [Matheus Henrique](https://github.com/mathonaut) | Desenvolvedor |
| [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) ([Rafael Ferreira](https://github.com/RafaelCLG0)) | Product Owner |

</center>
<font size="3"><p style="text-align: center">[Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>


## Metodologia

Para o desenvolvimento deste artefato, foi definido um tema e um épico a serem realizados a partir dos requisitos funcionais apresentados na seção de Requisitos Elicitados. Em um primeiro momento os requisitos analisados foram os que ainda não tiveram a sua implementação, evitando assim engenharia reversa do produto. Os requisitos analisados estão sendo apresentados na Tabela 2.

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

Analisando os requisitos da tabela, foi possível organizá-los em dois grandes temas.

- **Funcionalidades**: Agrupa funcionalidade que o sistema precisa oferecer para que o usuário consiga realizar com sucesso suas tarefas.
- **Perfil**: Agrupa requisitos relacionadas a como o usuário se apropria do sistema e o modifica de acordo com seus gostos e desejos.

## Épicos

Após a definição dos temas, são criadas épicos de modo a diminuir ainda mais a abstração das tarefas que deverão ser realizadas ao decorrer do projeto. Após a definição de um épico, são geradas as Features que o compõe para serem trabalhadas em um curto período de tempo acompanhada de uma descrição às histórias de usuário. Os épicos serão descritos utilizando o padrão de escrita das histórias de usuário e seguindo o template apresentado na Tabela 3 com suas descrições.

<center>

**Tabela 3** - Template das Features e Histórias de Usuário.

| Feature | ID da História | História de usuário |
|----------|----|----------------------|
| Funcionalidade relacionada ao épico| Identificação da História de Usuário | Visão do usuário sobre um determinada funcionalidade|

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 1 - Filtragem
A história de usuário a seguir resume as caracteristicas desse épico e a Tabela 4 apresenta as features e histórias de usuário relacionada a esse épico.

Como usuário típico, eu desejo funcionalidades que me permitam filtrar eventos.

<center>

**Tabela 4** - Features e Histórias de Usuário.

| Feature | ID da História | História de usuário |
|----------|:----:|:----------------------|
| Feature 1 - Local e Data | US01<br>US02 | Filtro por estado e município<br>Filtro por data e por horário |
| Feature 2 - Categorias | US03<br>US04<br>US05 | Filtro por idade mínima de entrada<br>Filtro por categorias<br>Tags associadas a eventos |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 2 - Preferências
A história de usuário a seguir resume as caracteristicas desse épico e a Tabela 5 apresenta as features e histórias de usuário relacionada a esse épico.

Como usuário típico, eu desejo modificar o site de acordo com as minhas preferências.

<center>

**Tabela 5** - Features e Histórias de Usuário.

| Feature | ID da História | História de usuário |
|----------|:----:|:----------------------|
| Feature 3 - Avisos | US06 | Sugestão de busca |
| Feature 4 - Configurações | US07<br>US08 | Notificação de evento<br>Responder pesquisa de perfil |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### Épico 3 - Acessibilidade
A história de usuário a seguir resume as caracteristicas desse épico e a Tabela 6 apresenta as features e histórias de usuário relacionada a esse épico.

Como usuário com necessidade especiais, eu desejo recursos que me permitam realizar tarefas no site.

<center>

**Tabela 6** - Features e Histórias de Usuário.

| Feature | ID da História | História de usuário |
|----------|:----:|:----------------------|
| Feature 5 - Atalhos | US09 | Conectar carteira digital |
| Feature 6 - Central de Ajuda | US10 | Acessar à assistente virtual |
| Feature 7 - Ferramentas de Acessibilidade | US11<br>US12 | Mudar idioma do aplicativo<br>Dar zoom |

Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 22/05/2023 | Criação da página. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.1`  | 23/05/2023 | Adição das Features | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Arthur de Melo](https://github.com/arthurmlv) |
| `1.1.1`  | 23/05/2023 | Atualização metodologia | [Douglas Alves dos Santos](https://github.com/dougAlvs) | [Arthur de Melo](https://github.com/arthurmlv) |
