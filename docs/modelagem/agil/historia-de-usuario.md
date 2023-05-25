## Introdução

A história de usuário é uma técnica amplamente utilizada na disciplina de requisitos de software para capturar e descrever as necessidades e expectativas dos usuários de um sistema. Trata-se de uma breve narrativa que descreve uma funcionalidade específica do software, do ponto de vista do usuário, com o objetivo de comunicar de forma clara e concisa o que o usuário deseja alcançar ao utilizar o sistema. Para a elaboração da história do usuário do projeto, foram usados os épicos produzidos no [backlog](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/), porque em termos mais simples, o [backlog](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/) serve como uma lista do que a aplicação deve seguir, portanto as histórias de usuário devem produzidas a partir dele.

## Metodologia

Para a produção do artefato haverá a participação da persona [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) que será o Product Owner do projeto, para tal foi utilizado o método da encenação, melhor representado na tabela 1. A reunião foi realizada via Teams às 18h do dia 23 de maio de 2023.

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| **Participante**                                                                                                                                     | **Função**    |
| :--------------------------------------------------------------------------------------------------------------------------------------------------- | :------------ |
| [Douglas Alves](https://github.com/dougAlvs)                                                                                                         | Desenvolvedor |
| [Lara Dias](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/personas/) ([Geovanna Maciel](https://github.com/manuziny)) | Product Owner |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

As histórias de usuário são provenientes do [backlog do produto](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/) e serão descritas em tabelas com base na tabela 2.

<font size="3"><p style="text-align: center">Tabela 2: Modelo de tabela para histórias de usuário.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| USXX                   | Titulo                                  |
| Descrição              | _Eu, como_ XXX, _desejo_ XXX _para_ XXX |
| Critérios de Aceitação | -XXX <br> -XXX <br>                     |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

## Épicos

Na tabela 3 são os épicos (Representadas pelo id EX) listados e suas respectivas features.

<font size="3"><p style="text-align: center">Tabela 3: Épicos.</p></font>

<center>

| Épico                |                           Descrição                           | Features                                                                       |
| :------------------- | :-----------------------------------------------------------: | :----------------------------------------------------------------------------- |
| E01 - Filtragem      |                 Engloba filtragem de eventos.                 | -> Local e data; </br> -> Categoria.                                           |
| E02 - Preferências   | Engloba a parte de configurações da aplicação e notificações. | -> Avisos; </br> -> Configurações.                                             |
| E03 - Acessibilidade |        Engloba a parte de acessibilidade da aplicação.        | -> Atalhos; </br> -> Central de ajuda; </br> -> Ferramentas de Acessibilidade. |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

## Features

As tabelas de 4 a 15 descrevem as histórias de usuário (Representadas pelo id USX) elicitadas em suas respectivas features.

### Feature 1 - Local e Data

<font size="3"><p style="text-align: center"><a id="US01" style="visibility: hidden;"></a>Tabela 4: US01 - Filtro por estado e município.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                              |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| US01                   | Filtro por estado e município                                                                                                                         |
| Descrição              | _Eu, como_ usuário, _desejo_ poder filtrar os eventos por estado e município _para_ visualizar apenas os eventos da minha cidade com mais facilidade. |
| Critérios de Aceitação | ->Lista de municípios com eventos de cada estado para o usuário escolher.                                                                             |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

<font size="3"><p style="text-align: center"><a id="US02" style="visibility: hidden;"></a>Tabela 5: US02 - Filtro por data e por horário.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                                                         |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US02                   | Filtro por data e por horário                                                                                                                                                    |
| Descrição              | _Eu, como_ usuário, _desejo_ poder filtrar os eventos por data e horário _para_ poder visualizar apenas os eventos que ocorram em datas e horários que eu tenha disponibilidade. |
| Critérios de Aceitação | ->Calendário para escolha de data. <br> ->Relógio para escolha de horário. <br>                                                                                                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 2 - Categoria

<font size="3"><p style="text-align: center"><a id="US03" style="visibility: hidden;"></a>Tabela 6: US03 - Filtro por idade mínima de entrada.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                                                    |
| :--------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US03                   | Filtro por idade mínima de entrada                                                                                                                                          |
| Descrição              | _Eu, como_ usuário, _desejo_ poder filtrar os eventos por idade mínima de entrada _para_ poder visualizar apenas os eventos condizentes com a faixa etária dos meus filhos. |
| Critérios de Aceitação | ->Lista de idade mínima de entrada para o usuário selecionar.                                                                                                               |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

<font size="3"><p style="text-align: center"><a id="US04" style="visibility: hidden;"></a>Tabela 7: US04 - Filtro por categorias.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                                                 |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US04                   | Filtro por categorias                                                                                                                                                    |
| Descrição              | _Eu, como_ usuário, _desejo_ poder filtrar os eventos por categorias (como tipo de evento ou gênero) _para_ poder visualizar apenas os eventos do tipo que me interesse. |
| Critérios de Aceitação | ->Lista de categorias de eventos para o usuário selecionar.                                                                                                              |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

<font size="3"><p style="text-align: center"><a id="US05" style="visibility: hidden;"></a>Tabela 8: US05 - Tags associadas a eventos.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                                   |
| :--------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US05                   | Tags associadas a eventos                                                                                                                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que os eventos tenham tags associadas (como gênero, artista, tipo de evento) _para_ facilitar a busca e filtro por categoria. |
| Critérios de Aceitação | ->Presença das tags na descrição do evento.<br> ->Uso das tags na busca e na categorização.                                                                |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 3 - Avisos

<font size="3"><p style="text-align: center"><a id="US06" style="visibility: hidden;"></a>Tabela 9: US06 - Sugestão de busca.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                   |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------------------- |
| US06                   | Sugestão de busca                                                                                                                          |
| Descrição              | _Eu, como_ usuário, _desejo_ receber sugestões de eventos durante minha busca _para_ que eu encontre os eventos que gosto mais facilmente. |
| Critérios de Aceitação | ->Dar sugestões de eventos com base no histórico de buscas do usuário e pesquisa de perfil.                                                |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

<font size="3"><p style="text-align: center"><a id="US07" style="visibility: hidden;"></a>Tabela 10: US07 - Notificação de evento.</p></font>

<center>

| **ID**                 | **Nome**                |                                                                                                                   |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------- |
| US07                   | Notificação de evento                                                                                                                       |
| Descrição              | _Eu, como_ usuário, _desejo_ receber notificações de eventos (quando permitido) _para_ que eu fique ciente de eventos de meu interesse      | ->Pedir permissão do usuário para enviar notificações.<br>->Enviar notificações de eventos que se encaixem nos gostos coletados do usuário. |
| Critérios de aceitação | ->Pedir permissão do usuário para enviar notificações.<br>->Enviar notificações de eventos que se encaixem nos gostos coletados do usuário. |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 4 - Configurações

<font size="3"><p style="text-align: center"><a id="US08" style="visibility: hidden;"></a>Tabela 11: US08 - Responder pesquisa de perfil</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                              |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| US08                   | Responder pesquisa de perfil                                                                                                                          |
| Descrição              | _Eu, como_ usuário, _desejo_ poder responder a pesquisa de usuário _para_ que o app possa mostrar os eventos de acordo com os meus gostos             |
| Critérios de Aceitação | - Exibir uma lista de eventos que possam ser do interesse do usuário<br> - Uma variedade de eventos, de forma que o usuário possa se identificar <br> |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 5 - Atalhos

<font size="3"><p style="text-align: center"><a id="US09" style="visibility: hidden;"></a>Tabela 12: US09 - Conectar carteira digital</p></font>

<center>

| **ID**                 | **Nome**                                                                                                           |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------- |
| US09                   | Conectar carteira digital                                                                                          |
| Descrição              | _Eu, como_ usuário, _desejo_ poder conectar minha carteira digital _para_ meu processo de compra seja mais prático |
| Critérios de Aceitação | - Possuir os idiomas mais falados do mundo <br>                                                                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 6 - Central de ajuda

<font size="3"><p style="text-align: center"><a id="US10" style="visibility: hidden;"></a>Tabela 13: US10 - Acessar à assistente virtual</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                                             |
| :--------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| US10                   | Acessar à assistente virtual                                                                                                                                         |
| Descrição              | _Eu, como_ usuário, _desejo_ poder acessar a assistente virtual _para_ que o acesso às informações sobre o aplicativo e possíveis dúvidas que possam surgir          |
| Critérios de Aceitação | - A assistnte estar presente em todas as abas que possam ter ações que necessitem de consulta <br> - Informações claras e suscintas sobre os assuntos abordados <br> |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

### Feature 7 - Ferramentas de Acessibilidade

<font size="3"><p style="text-align: center"><a id="US11" style="visibility: hidden;"></a>Tabela 14: US11 - Mudar idioma do aplicativo</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                       |
| :--------------------- | :----------------------------------------------------------------------------------------------------------------------------- |
| US11                   | Mudar idioma do aplicativo                                                                                                     |
| Descrição              | _Eu, como_ usuário, _desejo_ mudar o idioma do aplicativo _para_ que possa ser inclusivo para pessoas não falantes de portugês |
| Critérios de Aceitação | - Possuir as opções mais utilizadas de pagamento digital (Picpay, Paypal,Nubank, C6 Bank, etc )<br>                            |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

<font size="3"><p style="text-align: center"><a id="US12" style="visibility: hidden;"></a>Tabela 15: US12 - Dar zoom.</p></font>

<center>

| **ID**                 | **Nome**                                                                                                                                              |
| :--------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- |
| US12                   | Dar zoom                                                                                                                                              |
| Descrição              | _Eu, como_ usuário, _desejo_ poder dar zoom no aplicativo _para_ que eu possa ter melhor leitura e visualização das informações que desejo consultar. |
| Critérios de Aceitação | - Forcener um ícone de lupa <br> - O zoom ser de fácil acesso aos usuários <br>                                                                       |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny).</p></font>

## Bibliografia

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> SERRANO, Milene. Requisitos – Aula 15. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523115/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf](https://aprender3.unb.br/pluginfile.php/2523115/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 20/05/2023.

## Histórico de versões

| Versão | Data       | Descrição                  | Autor(es)                                                                                    | Revisor(es)                                  |
| ------ | ---------- | -------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------- |
| 1.0    | 20/05/2023 | Criação da página          | [Geovanna Maciel](https://github.com/manuziny)                                               | [Douglas Alves](https://github.com/dougAlvs) |
| 1.1    | 20/05/2023 | Adição metodologia         | [Douglas Alves](https://github.com/dougAlvs)                                                 | [Gabriel Campello](https://github.com/G16C)  |
| 1.2    | 23/05/2023 | Adição features 5, 6, 7    | [Geovanna Maciel](https://github.com/manuziny)                                               | [Gabriel Campello](https://github.com/G16C)  |
| 1.2    | 23/05/2023 | Adição features 1, 2, 3, 4 | [Douglas Alves](https://github.com/dougAlvs)                                                 | [Gabriel Campello](https://github.com/G16C)  |
| 1.3    | 23/05/2023 | Finalização do artefato    | [Douglas Alves](https://github.com/dougAlvs), [Geovanna Maciel](https://github.com/manuziny) | [Gabriel Campello](https://github.com/G16C)  |
