# Backlog

## Introdução

O Backlog do Produto é uma lista de todas as funcionalidades desejadas para um produto ordenado por prioridades O responsável por priorizar os itens é o Dono do Produto (_Product Owner_). Vale ressaltar que o Backlog do Produto é um artefato dinâmico, ou seja, ele cresce e muda à medida que os requisitos e a visão do produto são alterados.

## Metodologia

A definição do tema, épicos é realizada a partir dos [requisitos funcionais](../../../elicitacao/requisitos_elicitados/#requisitos-funcionais) apresentados na seção de [Requisitos Elicitados](../../../elicitacao/requisitos_elicitados). Em um primeiro momento os requisitos analisados foram os que ainda não tiveram a sua implementação, evitando assim engenharia reversa do produto. Os requisitos analisados foram estão sendo apresentados na tabela 1 a seguir.

<center>

**Tabela 1** - Requisitos Funcionais Elicitados não Implementados.

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
| RF25 | O usuário é capaz de aumentar a fonte                                                | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS20</a>                                                                                                                                                   | Não           |
| RF26 | O usuário é capaz de dar zoom                                                        | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS21</a>                                                                                                                                                   | Não           |
| RF27 | O usuário é capaz de acessar a assistente virtual                                    | <a href="../../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS22</a>                                                                                                                                                   | Não           |

Fonte: [Sidney Fernando](https://github.com/nando3d3).

</center>

## Temas

Analisando os requisitos da tabela, foi possível organizá-los em dois grandes temas.

- **Funcionalidades**: Agrupa funcionalidade que o sistema precisa oferecer para que o usuário consiga realizar com sucesso suas tarefas.
- **Perfil**: Agrupa requisitos relacionadas a como o usuário se apropria do sistema e o modifica de acordo com seus gostos e desejos.

## Épicos

Após a definição dos temas, são criadas épicos a fim de diminuir ainda mais a abstração das tarefas que deverão ser realizadas ao decorrer do projeto. Os épicos serão apresentados utilizando o padrão de escrita das histórias de usuário.

!!! Warning
    Rafael, tem que descrever melhor os épicos!!

### Épico 1 - Acessibilidade

Como usuário com necessidade especiais, eu desejo recursos que me permitam realizar tarefas no site.

### Épico 2 - Filtragem

Como usuário típico, eu desejo funcionalidades que me permitam filtrar eventos.

### Épicos 3 - Preferências

Como usuário típico, eu desejo modificar o site de acordo com as minhas preferências.

## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 22/05/2023 | Criação da página. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
