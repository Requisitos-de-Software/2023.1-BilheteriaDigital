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

## Histórias de Usuário

As tabelas de 3 a 35 descrevem as histórias de usuário elicitadas (Representadas pelo ID USX, onde X é o número da história).

### US01

</center>
<font size="3"><p style="text-align: center">Tabela 3 - História de Usuário Classificar eventos por local.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US01                   | Classificar eventos por local                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo classifique os eventos por local _para_ facilitar a busca por eventos em uma determinada região. |
| Critérios de Aceitação | - Na página principal do aplicativo, deve haver uma seção ou um filtro claramente visível para selecionar o local dos eventos. <br> - Ao selecionar um local, a lista de eventos exibidos deve ser atualizada para mostrar apenas eventos nessa localidade. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

</center>
<font size="3"><p style="text-align: center">Tabela 4 - História de Usuário Classificar eventos por modalidade.</p></font>

### US02

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US02                   | Classificar eventos por modalidade                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo classifique os eventos por modalidade _para_ que eu possa encontrar eventos específicos, como espetáculos teatrais, shows de música ou palestras. |
| Critérios de Aceitação | -Na página principal do aplicativo, deve haver uma seção ou um menu claramente visível para selecionar a modalidade dos eventos. <br> -Ao selecionar uma modalidade, a lista de eventos exibidos deve ser atualizada para mostrar apenas eventos dessa modalidade. <br>                     |
| Prioridade | Alta                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US03

</center>
<font size="3"><p style="text-align: center">Tabela 5 - História de Usuário Apresentar valor total dos ingressos selecionados.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US03                   | Apresentar valor total dos ingressos selecionados                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo apresente o valor total dos ingressos selecionados antes de confirmar a compra _para_ que eu possa revisar o custo total antes de prosseguir. |
| Critérios de Aceitação | -Na página de seleção de ingressos, deve haver um campo ou uma seção claramente visível que exiba o valor total acumulado dos ingressos selecionados. <br> -O valor total deve ser atualizado em tempo real à medida que o usuário adiciona ou remove ingressos do carrinho. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US04

</center>
<font size="3"><p style="text-align: center">Tabela 6 - História de Usuário Classificar eventos por data.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US04                   | Classificar eventos por data                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo classifique os eventos por data _para_  que eu possa encontrar eventos que ocorrerão em datas específicas. |
| Critérios de Aceitação | -Na página principal do aplicativo, deve haver uma seção ou um filtro claramente visível para selecionar a data dos eventos. <br> -Ao selecionar uma data, a lista de eventos exibidos deve ser atualizada para mostrar apenas eventos nessa data. <br>                     |
| Prioridade | Média                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US05

</center>
<font size="3"><p style="text-align: center">Tabela 7 - História de Usuário Histórico de visualização de eventos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US05                   | Histórico de visualização de eventos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo tenha um histórico de visualização de eventos _para_ que eu possa revisitar eventos que me interessei anteriormente |
| Critérios de Aceitação | -O aplicativo deve registrar e armazenar os eventos que o usuário visualizou. <br> -Deve haver uma seção ou uma página claramente visível onde o usuário possa acessar seu histórico de visualização de eventos. <br>                     |
| Prioridade | Baixa                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US06

</center>
<font size="3"><p style="text-align: center">Tabela 8 - História de Usuário Contagem regressiva para realização de eventos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US06                   | Contagem regressiva para realização de eventos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo exiba uma contagem regressiva para a realização de eventos _para_ que eu possa acompanhar quanto tempo falta para um evento específico |
| Critérios de Aceitação | -Na página de descrição de um evento, deve haver uma seção claramente visível que apresente a contagem regressiva para a realização desse evento. <br> -A contagem regressiva deve ser atualizada em tempo real e exibir os dias, horas, minutos e segundos restantes até o evento. <br>                     |
| Prioridade | Média                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US07

</center>
<font size="3"><p style="text-align: center">Tabela 9 - História de Usuário Venda de ingressos de diferentes categorias.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US07                   | Venda de ingressos de diferentes categorias                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo venda ingressos de diferentes categorias _para_ que eu possa escolher entre diferentes tipos de eventos. |
| Critérios de Aceitação | -Os eventos devem ser categorizados em diferentes categorias, como esportes, música, teatro, entre outros. <br> -O usuário deve poder selecionar uma categoria específica para visualizar os eventos relacionados a ela. <br>                     |
| Prioridade | Alta                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US08

</center>
<font size="3"><p style="text-align: center">Tabela 10 - História de Usuário Classificação dos tipos de assentos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US08                   | Classificação dos tipos de assentos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo classifique os diferentes tipos de assentos e forneça explicações sobre eles _para_ que eu possa escolher um assento adequado às minhas preferências |
| Critérios de Aceitação | -Na página de seleção de ingressos, deve haver informações claras e descritivas sobre os diferentes tipos de assentos disponíveis. <br> -Deve ser fornecida uma explicação sobre as características e benefícios de cada tipo de assento. <br>                     |
| Prioridade | Baixa                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US09

</center>
<font size="3"><p style="text-align: center">Tabela 11 - História de Usuário Exigência de dados necessários para cadastro e pagamento.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US09                   | Exigência de dados necessários para cadastro e pagamento                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo solicite apenas os dados necessários para meu cadastro e pagamento _para_ garantir uma experiência ágil e segura. |
| Critérios de Aceitação | -Durante o processo de cadastro, o aplicativo deve solicitar apenas as informações essenciais, como nome, e-mail, senha e informações de pagamento. <br> -O aplicativo não deve exigir informações desnecessárias ou excessivas dos usuários. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US10

</center>
<font size="3"><p style="text-align: center">Tabela 12 - História de Usuário Opção de salvar dados de pagamento.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US10                   | Opção de salvar dados de pagamento                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter a opção de salvar meus dados de pagamento no aplicativo, _para_ facilitar futuras compras |
| Critérios de Aceitação | -Durante o processo de pagamento, o aplicativo deve fornecer uma opção para o usuário salvar seus dados de pagamento. <br> -O usuário deve poder optar por salvar ou não seus dados de pagamento, garantindo sua privacidade e segurança. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US11

</center>
<font size="3"><p style="text-align: center">Tabela 13 - História de Usuário Privacidade dos dados de pagamento.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US11                   | Privacidade dos dados de pagamento                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo garanta a privacidade dos meus dados de pagamento _para_ proteger minhas informações confidenciais. |
| Critérios de Aceitação | -O aplicativo deve implementar medidas de segurança adequadas para proteger os dados de pagamento dos usuários. <br> -As informações de pagamento dos usuários devem ser armazenadas de forma segura e criptografada. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US12

</center>
<font size="3"><p style="text-align: center">Tabela 14 - História de Usuário Lista de eventos disponíveis.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US12                   | Lista de eventos disponíveis                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter uma tela com a lista de eventos disponíveis _para_ que eu possa explorar todas as opções. |
| Critérios de Aceitação | -O aplicativo deve ter uma página ou uma seção claramente visível que apresente a lista de eventos disponíveis. <br> -Os eventos devem ser exibidos de forma organizada e de fácil navegação. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US13

</center>
<font size="3"><p style="text-align: center">Tabela 15 - História de Usuário Página de descrição de eventos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US13                   |  Página de descrição de eventos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ desejo ter uma página de descrição de eventos, onde possa encontrar informações como data, local e valor _para_ que eu possa ver mais informações dos eventos que me interessam |
| Critérios de Aceitação | -Ao clicar em um evento na lista, o aplicativo deve redirecionar o usuário para uma página detalhada com a descrição do evento. <br> -A página de descrição deve conter informações importantes, como data, local, valor dos ingressos e detalhes adicionais sobre o evento. <br>                     |
| Prioridade | Alta                |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US14

</center>
<font size="3"><p style="text-align: center">Tabela 16 - História de Usuário Lista de confirmação de pagamento.</p></font>
 
<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US14                   | Lista de confirmação de pagamento                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter uma lista de confirmação de pagamento _para_ para revisar os detalhes da minha compra antes de finalizá-la. |
| Critérios de Aceitação | -Após a seleção dos ingressos e o processo de pagamento, o aplicativo deve exibir uma lista com os detalhes da compra. <br> -A lista de confirmação de pagamento deve incluir informações como eventos selecionados, quantidade de ingressos, valor total e opções de pagamento <br>                     |
| Prioridade | Alta                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US15

</center>
<font size="3"><p style="text-align: center">Tabela 17 - História de Usuário Sem limite de compra de ingresso.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US15                   | Sem limite de compra de ingresso                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ poder comprar a quantidade desejada de ingressos para um evento _para_ que eu possa levar quantas pessoas eu quiser junto comigo |
| Critérios de Aceitação | - O aplicativo deve permitir que o usuário selecione e adicione ao carrinho a quantidade desejada de ingressos para um evento. No entanto, o sistema deve aplicar o limite total de ingressos disponíveis para o evento.<br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US16

</center>
<font size="3"><p style="text-align: center">Tabela 18 - História de Usuário Opção de transferência de ingresso.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US16                   | Opção de transferência de ingresso                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter a opção de transferir um ingresso adquirido para outra pessoa _para_ o caso que eu não possa comparecer ao evento ou deseje levar acompanhantes |
| Critérios de Aceitação | -O aplicativo deve fornecer uma opção de transferência de ingresso, que permita ao usuário enviar o ingresso para outro destinatário na tela de compra de ingresso e na tela de ingressos já comprados. <br>                     |
| Prioridade | Média                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US17

</center>
<font size="3"><p style="text-align: center">Tabela 19 - História de Usuário Diferentes opções de pagamento.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US17                   | Diferentes opções de pagamento                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter diferentes opções de pagamento disponíveis, como pix, crédito, débito, boleto e carteiras digitais _para_ para escolher a forma de pagamento mais conveniente para mim |
| Critérios de Aceitação | -O aplicativo deve suportar várias opções de pagamento, como pix, cartões de crédito, cartões de débito, boleto bancário e carteiras digitais. <br> -Durante o processo de pagamento, o usuário deve poder selecionar a opção de pagamento desejada e inserir as informações necessárias. <br>                     |
| Prioridade | Alta                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US18

</center>
<font size="3"><p style="text-align: center">Tabela 20 - História de Usuário Envio de ingressos por e-mail.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US18                   | Envio de ingressos por e-mail                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo envie os ingressos comprados por email  _para_ que eu receba a confirmação da minha compra |
| Critérios de Aceitação | -Após a conclusão do processo de compra, o aplicativo deve enviar automaticamente os ingressos comprados para o endereço de email fornecido pelo usuário. <br> -O email de confirmação deve incluir os detalhes da compra, como nome do evento, data, local e informações do ingresso. <br>                     |
| Prioridade | Média                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US19

</center>
<font size="3"><p style="text-align: center">Tabela 21 - História de Usuário Aba de visualização de ingressos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US19                   | Aba de visualização de ingressos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter uma aba no aplicativo onde eu possa visualizar todos os ingressos que comprei _para_ verificar qualquer informação do ingresso que me interesse |
| Critérios de Aceitação | -O aplicativo deve ter uma seção ou uma aba claramente visível no seu perfil que exiba todos os ingressos adquiridos pelo usuário. <br> -O aplicativo deve permitir selecionar um ingresso da lista para ver suas informações. <br>                     |
| Prioridade | Alta                 |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US20

</center>
<font size="3"><p style="text-align: center">Tabela 22 - História de Usuário Opção de cancelamento de compra.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US20                   | Opção de cancelamento de compra                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter a opção de cancelar uma compra de ingresso _para_ caso mude de ideia ou não possa comparecer ao evento |
| Critérios de Aceitação | -O aplicativo deve fornecer uma opção de cancelamento de compra que permita ao usuário desistir da compra e receber um reembolso, se aplicável. <br> -O processo de cancelamento de compra deve ser claro e orientado ao usuário, com instruções sobre como proceder. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US21

</center>
<font size="3"><p style="text-align: center">Tabela 23 - História de Usuário Recomendação de eventos baseada no gosto do usuário.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US21                   | Recomendação de eventos baseada no gosto do usuário                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ desejo receber recomendações de eventos com base no meu gosto pessoal, por meio de uma avaliação ou histórico de preferências _para_ que eu encontre eventos que eu goste mais facilmente |
| Critérios de Aceitação | -O aplicativo deve implementar um algoritmo de recomendação que analise as preferências do usuário com base em avaliações anteriores, histórico de compras ou outras informações relevantes. E com base nessa análise, o aplicativo deve sugerir eventos similares ou de interesse para o usuário. <br> -O usuário deve permitir que seus dados sejam usados pelo algoritmo de recomendação. <br>                     |
| Prioridade | Média                 |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US22

</center>
<font size="3"><p style="text-align: center">Tabela 24 - História de Usuário Opção de receber notificações do aplicativo.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US22                   | Opção de receber notificações do aplicativo                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter a opção de receber notificações do aplicativo _para_ para ficar atualizado sobre eventos próximos e novidades |
| Critérios de Aceitação | -O aplicativo deve fornecer uma opção de ativar ou desativar as notificações para o usuário. <br> -As notificações devem ser relevantes e informar sobre eventos próximos, promoções ou atualizações importantes. <br>                     |
| Prioridade | Baixa                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US23

</center>
<font size="3"><p style="text-align: center">Tabela 25 - História de Usuário Exibição de notificações de eventos próximos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US23                  | Exibição de notificações de eventos próximos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo exiba notificações de eventos próximos com base no meu gosto pessoal _para_ para que eu possa me planejar e participar de eventos de interesse |
| Critérios de Aceitação | -O aplicativo, caso permitido, deve analisar as preferências do usuário, como histórico de compras, avaliações ou seleções anteriores, para enviar notificações relevantes sobre eventos próximos. <br> -As notificações devem ser exibidas de forma clara e apropriada, destacando informações relevantes, como data, local e tipo de evento. <br>                     |
| Prioridade |  Baixa                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US24

</center>
<font size="3"><p style="text-align: center">Tabela 26 - História de Usuário Termos de privacidade explícitos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US24                   | Termos de privacidade explícitos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo forneça termos de privacidade explícitos em relação aos dados que inseri _para_ garantir que minha privacidade seja protegida. |
| Critérios de Aceitação | -O aplicativo deve fornecer uma seção clara e acessível que contenha os termos de privacidade. <br> -Os termos de privacidade devem explicar como os dados do usuário são coletados, armazenados, usados e protegidos. <br>                     |
| Prioridade | Alta                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US25

</center>
<font size="3"><p style="text-align: center">Tabela 27 - História de Usuário Criação de conta e login com e-mail.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US25                   | Criação de conta e login com e-mail                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ poder criar uma conta e fazer login no aplicativo usando meu email _para_ para ter acesso aos recursos do aplicativo. |
| Critérios de Aceitação | -O aplicativo deve fornecer uma opção de criação de conta que permita ao usuário registrar-se usando seu endereço de email. <br> -O usuário deve poder fazer login no aplicativo utilizando seu email e senha previamente cadastrados. <br>                     |
| Prioridade | Alta                 |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US26

</center>
<font size="3"><p style="text-align: center">Tabela 28 - História de Usuário Autenticação de dois fatores.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US26                   | Autenticação de dois fatores                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo ofereça autenticação de dois fatores _para_ aumentar a segurança da minha conta |
| Critérios de Aceitação | -O aplicativo deve fornecer a opção de ativar a autenticação de dois fatores para a conta do usuário. <br> -O processo de autenticação de dois fatores deve exigir uma combinação de senha e código único gerado no dispositivo do usuário. <br>                     |
| Prioridade | Média                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US27

</center>
<font size="3"><p style="text-align: center">Tabela 29 - História de Usuário Cadastro por redes sociais validado por email.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US27                   | Cadastro por redes sociais validado por e-mail                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter a opção de realizar o cadastro no aplicativo utilizando minhas redes sociais, com validação por email _para_ que seja mais simples de criar conta no aplicativo |
| Critérios de Aceitação | -O aplicativo deve permitir que o usuário se registre utilizando suas contas em redes sociais populares, como Facebook, Google ou Twitter. <br> -Após selecionar a opção de cadastro por rede social, o usuário deve fornecer um endereço de email válido para validação. <br>                     |
| Prioridade | Média                  |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US28

</center>
<font size="3"><p style="text-align: center">Tabela 30 - História de Usuário Senha segura durante o cadastro.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US28                   | Senha segura durante o cadastro                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo exija uma senha segura durante o processo de cadastro _para_ proteger minha conta contra acessos não autorizados. |
| Critérios de Aceitação | -Durante o processo de cadastro, o aplicativo deve exigir que o usuário crie uma senha que atenda a requisitos mínimos de segurança, como combinação de letras maiúsculas e minúsculas, números e caracteres especiais. <br> -O aplicativo deve fornecer orientações claras sobre os critérios de segurança da senha durante o processo de criação. <br>                     |
| Prioridade | Alta                    |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US29

</center>
<font size="3"><p style="text-align: center">Tabela 31 - História de Usuário Informações sobre inclusão na descrição dos eventos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US29                   | Informações sobre inclusão na descrição dos eventos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que a descrição dos eventos inclua informações sobre acessibilidade e inclusão _para_ tomar decisões informadas sobre minha participação nos eventos. |
| Critérios de Aceitação | -A descrição dos eventos deve fornecer informações claras sobre recursos de acessibilidade disponíveis, como audiodescrição, legendas, libras, entre outros. <br> -O aplicativo deve destacar de forma visível as informações sobre inclusão na descrição dos eventos. <br>                     |
| Prioridade | Alta                   |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>

### US30

</center>
<font size="3"><p style="text-align: center">Tabela 32 - História de Usuário Acessibilidade visual.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US30                   | Acessibilidade visual                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo seja acessível visualmente, com recursos como alto contraste e opções de cores para daltônicos _para_ que todas pessoas possam utilizar o aplicativo |
| Critérios de Aceitação | -O aplicativo deve fornecer opções de configuração de alto contraste para melhorar a legibilidade para usuários com deficiência visual. <br> -O aplicativo deve oferecer opções de cores adaptadas para usuários daltônicos, garantindo uma experiência visual acessível. <br>                     |
| Prioridade | Alta                 |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>


### US31

</center>
<font size="3"><p style="text-align: center">Tabela 33 - História de Usuário Opção de troca de idioma.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US31                   | Opção de troca de idioma                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ ter um botão ou região na interface do aplicativo onde eu possa trocar o idioma _para_ algum minha preferência. |
| Critérios de Aceitação | -O aplicativo deve fornecer uma opção clara e facilmente acessível para o usuário trocar o idioma da interface. <br> -O aplicativo deve oferecer suporte a múltiplos idiomas e aplicar a tradução correta em todas as seções do aplicativo. <br>                     |
| Prioridade | Média                |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>


### US32

</center>
<font size="3"><p style="text-align: center">Tabela 34 - História de Usuário Audiodescrição para eventos.</p></font>

<center>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US32                   |  Audiodescrição para eventos                                  |
| Descrição              | _Eu, como_ usuário, _desejo_ que o aplicativo forneça audiodescrição para os eventos _para_ que eu possa obter uma experiência inclusiva ao explorar as informações visuais do evento |
| Critérios de Aceitação | -O aplicativo deve oferecer a opção de ativar ou desativar a audiodescrição nas configurações. <br> -A audiodescrição deve fornecer informações visuais relevantes do evento de forma clara e concisa. <br>                     |
| Prioridade | Alta                 |

</center>
<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>




## Bibliografia

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> SERRANO, Milene. Requisitos – Aula 15. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523115/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf](https://aprender3.unb.br/pluginfile.php/2523115/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 20/05/2023.

> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 09 Julho 2023.

## Histórico de versões

| Versão | Data       | Descrição                  | Autor(es)                                                                                    | Revisor(es)                                  |
| ------ | ---------- | -------------------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------- |
| 1.0    | 20/05/2023 | Criação da página          | [Geovanna Maciel](https://github.com/manuziny)                                               | [Douglas Alves](https://github.com/dougAlvs) |
| 1.1    | 20/05/2023 | Adição metodologia         | [Douglas Alves](https://github.com/dougAlvs)                                                 | [Gabriel Campello](https://github.com/G16C)  |
| 1.2    | 23/05/2023 | Adição features 5, 6, 7    | [Geovanna Maciel](https://github.com/manuziny)                                               | [Gabriel Campello](https://github.com/G16C)  |
| 1.2    | 23/05/2023 | Adição features 1, 2, 3, 4 | [Douglas Alves](https://github.com/dougAlvs)                                                 | [Gabriel Campello](https://github.com/G16C)  |
| 1.3    | 23/05/2023 | Finalização do artefato    | [Douglas Alves](https://github.com/dougAlvs), [Geovanna Maciel](https://github.com/manuziny) | [Gabriel Campello](https://github.com/G16C)  |
| 1.4    | 09/06/2023 | Refatoração do artefato com histórias de usuário do PO   | [Douglas Alves](https://github.com/dougAlvs)                                                 | [Geovanna Maciel](https://github.com/manuziny) |




	