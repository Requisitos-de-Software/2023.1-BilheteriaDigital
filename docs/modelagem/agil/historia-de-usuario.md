## Introdução

A história de usuário é uma técnica de elicitação de requisitos amplamente utilizada nas metodologias de desenvolvimento ágil e se refere a descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Além disso, as histórias de usuário devem possuir critérios de aceitação bem definidos para que seja possível verificar sua implementação.

## Objetivo

Esse documento propõe trazer uma descrição detalhada e critérios de aceitação das histórias de usuário presentes no [product backlog](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/).

## Metodologia

Para a produção desse artefato , houve a participação de um usuário fazendo o papel de PO do projeto, que foi entrevistado via Discord às 20:45 do dia 31 de maio de 2023. Enquanto o PO comentava suas funcionalidades desejadas os desenvolvedores/entrevistadores anotavam e faziam questionamentos acerca de suas falas. Depois de elicitadas as histórias de usuário, os critérios de aceitação foram definidos e elas foram priorizadas pelo PO em: Alta, Média ou Baixa prioridade (Basicamente foi utilizado o método Three Level Scale de priorização de requisitos). Os participantes são apresentados na tabela 1, a gravação da entrevista é apresentado no vídeo 1 e o modelo de card para as histórias de usuário é descrito na tabela 2.



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


<font size="3"><p style="text-align: center">Tabela 2: Modelo de tabela para histórias de usuário.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| USXX                   | Titulo                                  |
| Descrição              | _Eu, como_ XXX, _desejo_ XXX _para_ XXX |
| Critérios de Aceitação | -XXX <br> -XXX <br>                     |
| Prioridade | Alta, Média ou Baixa                    |

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



	