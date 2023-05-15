# Casos de Uso

## Introdução

Um caso de uso se refere a uma descrição detalhada de como o sistema será utilizado em uma determinada situação ou contexto. Ele descreve as interações entre os usuários e o sistema, apresentando os passos necessários para alcançar um objetivo específico.
O objetivo dos casos de uso é auxiliar no processo de desenvolvimento de um sistema, fornecendo uma visão clara dos requisitos funcionais do sistema, descrevendo as ações que os usuários podem realizar e as respostas do sistema a ações.



## Metodologia
O diagrama de caso de uso é uma representação visual que resume as interações entre os usuários e um sistema, destacando suas funcionalidades e comportamentos. Ele é composto por atores, que representam os usuários, e casos de uso, que descrevem as ações realizadas pelos usuários e as respostas do sistema. Para a realização do caso de uso utilizamos da persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) para entender melhor as necessidades e desejos dos usuários finais do sistema. Usando a persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) em um diagrama de caso de uso, é possível modelar cenários realistas de uso do sistema que consideram as diferentes necessidades e objetivos do tipo de usuário que ela é. Agora voltando ao assnto sobre os diagramas de caso de uso, pode-se ver na Tabela 1 oa elemtnos do diagrama:

<font size="3"><p style="text-align: center"><b>Tabela 1</b>: Elementos do diagrama de casos de uso</p></font>

| Nome | Função | Elemento
|------|------|:-------:
| Ator | Representam os diferentes tipos de usuários externos que interagem com o sistema | <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](../assets/usecase/actor.png)</figure>
| Elipse (Caso de Uso) | É usada para representar os casos de uso no diagrama. Um caso de uso descreve uma funcionalidade ou uma ação específica que o sistema pode realizar em resposta às interações dos atores. A elipse contém o nome do caso de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](../assets/usecase/elipse.png)</figure>
| Retângulo (Sistema) | Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados | <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](../assets/usecase/retangulo.png)</figure>
| Flecha (Relações) | As flechas são usadas para representar as relações ou interações entre atores e casos de uso | <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](../assets/usecase/flecha.png)</figure>

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/nando3d3">Sidney Fernando</a></b></p></font>

Além disso, no diagrama de casos de uso é possível especificar:

- Os requisitos externos de um sistema, ou seja, as funcionalidades necessárias que o sistema deve oferecer para atender às necessidades dos usuários.
- As funcionalidades disponíveis no sistema, ou seja, o que o sistema é capaz de fazer para satisfazer as necessidades dos usuários.
- Os requisitos impostos pelo sistema ao ambiente em que está inserido, definindo como o sistema interage com o ambiente para realizar suas funções.

## Diagrama de Casos de Uso

<font size="3"><p style="text-align: center">Figura 1: Casos de uso do app BilheteriaDigital</p></font>

<img src="../../assets/usecase/diagramaCasoUso.png" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/nando3d3">Sidney Fernando</a> e <a href="https://github.com/manuziny">Geovanna Maciel</a></b></p></font>

## Especialização dos casos de uso

<font size="3"><p style="text-align: center">Tabela x: </p></font>

| UC0x | Informações |
| ----- | ---------- |
| Descrição | a |
| Ator | a |
| Pré-condições | a |
| Ação | a |
| Fluxo principal | a |
| Fluxo alternativo | a |
| Fluxo de exceção | a |
| Pós-condições | a |
| Data de Criação | a |
| Rastreabilidade | a |

<font size="3"><p style="text-align: center">Tabela 2: Ativar notificações sobre eventos </p></font>

| UC02 | Informações |
| ----- | ---------- |
| Descrição | O usuário é capaz de ativar as notificações sobre os eventos que deseja. |
| Ator | Usuário |
| Pré-condições | Acesso à internet, acesso ao app |
| Ação | O usuário ativa as notificações no aplicativo |
| Fluxo principal | <ul><li> O usuário acessa o aplicativo </br> <ul><li> O usuário acessa a aba de notificações em "Meu Painel" e acessa as configurações </br> <ul><li> O usuário ativa a opção de "Ativar notificações" dentro do app.
| Fluxo alternativo | <ul><li> O usuário abre o app em seu primeiro acesso </br> <ul><li> O app pergunta se o usuário deseja ativar as notificações </br> <ul><li>Usuário seleciona a opção "sim" e as notificações são ativadas |
| Fluxo de exceção | <ul><li>O usuário abre o app </br> <ul><li> O usuário vai nas configurações </br> <ul><li> O usuário ativa a opção de notificações por SMS </br> <ul><li> Usuário fornece número de telefone ao app |
| Pós-condições | O usuário agora está com as notificações ligadas e será notificado sobre novos eventos |
| Data de Criação | 15/05/2023 |
| Rastreabilidade | [RF13](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/) |

<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/manuziny">Geovanna Maciel</a></b></p></font>

<font size="3"><p style="text-align: center">Tabela 4: Responder pesquisa de perfil </p></font>

| UC04 | Informações |
| ----- | ---------- |
| Descrição | O usuário deve poder responder a uma pesquisa de perfil sobre seus gostos para eventos. |
| Ator | Usuário |
| Pré-condições | Possuir uma conta cadastrada e acesso à internet. |
| Ação | O usuário ira responder à pesquisa de perfil e gostos de acordo as opções de eventos ofertadas pelo app. |
| Fluxo principal | <ul><li>O usuário efetua cadastro no app<ul><li> Aparece uma mensagem sobre a pesquisa de perfil e se deseja responder <ul><li>Usuário seleciona a opção "sim" <ul><li> Usuário responde à pesquisa |
| Fluxo alternativo | <ul><li>O usuário efetua cadastro no app <ul><li>Aparece uma caixa de mensagem sobre a pesquisa de perfil <ul><li>Usuário sem querer pula a pesquisa de perfil selecionando a opção de "Responder mais tarde" <ul><li>O usuário abre o "Meu Painel" e responde a pesquisa que estará localizada ali. |
| Fluxo de exceção | <ul><li>O usuário efetua cadastro no app<ul><li> Aparece uma caixa de mensagem sobre a pesquisa de perfil e se deseja responder <ul><li>Usuário rejeita responder a pesquisa |
| Pós-condições | O usuário terá em sua tela principal somente eventos que sejam de seu interesse |
| Data de Criação | 15/05/2023 |
| Rastreabilidade | [RF18](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/) |



<font size="2"><p style="text-align: center"><b>Fonte: <a href="https://github.com/manuziny">Geovanna Maciel</a></b></p></font>

## Bibliografia

> Lucidchart. Diagrama de Caso de Uso UML. Disponível em: <<https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>>. Acesso em: 14 maio 2023.

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

> HENRIQUE, Paulo. Caso de Uso. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/](https://requisitos-de-software.github.io/2022.1-Youtube/modelagem/casouso/). Acesso em: 15 mai. 2023.

> MACEDO, Lucas. Caso de uso. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/casos_de_uso/). Acesso em: 15 mai. 2023.



## Histórico de Versões

| Versão | Data       | Descrição                                      | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ---------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| 1.0    | 13/05/2023 | Criação da página | [Sidney Fernando](https://github.com/nando3d3)   | [Geovanna Maciel](https://github.com/manuziny) |
| 1.1 | 15/05/2023 | Adição do Diagrama | [Geovanna Maciel](https://github.com/manuziny) e [Sidney Fernando](https://github.com/nando3d3) | [Douglas Alves](https://github.com/dougAlves)
| 1.2 | 15/05/2023 | Adição dos casos de ativar notificação e pesquisa de perfil | [Geovanna Maciel](https://github.com/manuziny) | [Sidney Fernando](https://github.com/nando3d3)