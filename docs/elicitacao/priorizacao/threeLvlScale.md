# Three Level Scale

## Introdução

A técnica de priorização _Three Level Scale_<a id="FTF1" href="#FTF1Ref">^1^</a> envolve a categorização dos requisitos em três categorias de acordo com sua prioridade relativa: alta, média e baixa prioridade. Nesse projeto, essa técnica foi utilizada por um desenvolvedor e um usuário, com o primeiro servindo de mediador e guiando o segundo durante o processo.

## Metodologia

A utilidade do método depende de que as partes interessadas concordem sobre o que cada nível de prioridade da escala signifique, sendo asssim, levamos em conta a urgência e importância de cada requisito para formar sua prioridade. Logo, as três categorias ficaram da seguinte forma:

* Alta prioridade: requisitos importantes e urgentes, devem estar implementados na release mais próxima.
* Média prioridade: requisitos importantes, mas não urgentes, logo podem esperar uma release mais distante.
* Baixa prioridade: requisitos nem importantes, nem urgentes, sua implementação pode demorar muito tempo.

## Participantes

A usuária da Bilheteria Digital Ana Luiza foi convidada para participar do presente método de priorização, informada dos fins de pesquisa deste e concordou com o uso das informações no projeto. Na data de 30/04/2023, das 9h às 9:30, foi realizada uma [reunião online](https://youtu.be/ZxptAgfMf6c) entre a usuária e o desenvolvedor [Douglas Alves](https://github.com/dougAlvs), na qual toda a dinâmica do Three Level Scale foi explicada e a usuária categorizou os requisitos de acordo com sua visão. As tabelas 1 e 2 apresentam os resultados dessa priorização.

## Requisitos priorizados

Legenda das tabelas: 

* RFx: Requisito Funcional nºx
* RNFx: Requisito Não-Funcional nºx
* OBSx: Requisito nºx elicitado pela observação.
* ISx: Requisito nºx elicitado pela introspecção.
* BSx: Requisito nºx elicitado pelo brainstorm.

### Funcionais

<font size="3"><p style="text-align: center">Tabela 1: Requisitos Funcionais.</p></font>

<center>


| Tipo |             Descrição            |   ID   | Prioridade |
|------|----------------------------------|--------|-------|
| RF01 	| O usuário deve poder realizar cadastro 	| BS01/IS05	| Alta  |
| RF02	| O usuário deve poder realizar login 	| BS02/IS05 	| Alta  |
| RF03	| O usuário deve poder comprar ingressos dentro do app 	|  BS03/IS04/OBS10	|  Alta |
| RF04	| O usuário deve poder buscar eventos 	| BS04/IS09/OBS02/Q01	|  Alta |
| RF05	| O usuário deve ser capaz de filtrar eventos 	|  BS05	| Alta  |
| RF06	| O usuário deve acessar as notificações sobre os eventos 	| BS06 	| Alta  |
| RF07	| O usuário deve salvar os dados do cartão no app 	| BS07 	| Media  |
| RF08	| O usuário deve poder filtrar as cidades que desejar 	| BS08/IS01/OBS01	|  Alta |
| RF09	| O usuário deve fornecer sua localização	| BS09 	| Alta  |
| RF10	|  O usuário deve poder acessar o calendário de eventos	| BS10	| Alta  |
| RF11	| O usuário deve poder acessar os eventos a gostos de acordo com o perfil do usuário 	|  BS11	| Alta  |
| RF12	| O usuário deve poder responder a pesquisa de perfil sobre seus gostos	|  BS12	| Media  |
| RF13	| O usuário deve ser capaz de acessar as informações do evento	|  BS13	| Alta  |
| RF14	| O usuário deve ser capaz de acessar as atrações do evento 	| BS14 	| Alta  |
| RF15	| O usuário deve poder realizar pagamento com de várias formas 	| BS15/IS07/Q08 	| Alta  |
| RF16	| O usuário deve ter acesso a pré-venda 	| BS16 	| Alta  |
| RF17	| O usuário deve receber a cópia do ingresso por e-mail 	| BS17 	| Alta  |
| RF18	| O usuário deve ser capaz de conectar uma carteira digital 	| BS18	| Media  |
| RF19	| O usuário deve ser capaz de mudar o idioma do app 	|  BS19	| Alta  |
| RF20	| O usuário deve ser capaz de aumentar a fonte 	| BS21 	| Baixa  |
| RF21	| O usuário deve ser capaz de dar zoom 	| BS22 	| Alta  |
| RF22	| O usuário deve ser capaz de acessar a assistente virtual 	| BS23 	| Media  |
| RF23	| O usuário deve ser capaz de compartilhar o evento 	| BS24/OBS03 	| Baixa  |
| RF24 | O aplicativo filtra os eventos por data e por horário.  | IS02/Q03 | Media |
| RF25 | O aplicativo filtra os eventos por idade mínima de entrada.  | IS03/Q02 | Media |
| RF26 | O aplicativo permite excluir cadastro.  | IS06 | Media |
| RF27 | O aplicativo permite cancelar compras.  | IS08/OBS12/Q09 | Alta |
| RF28 | O aplicativo permite escolher a quantidade de ingressos que o usuário deseja comprar. | OBS04 | Alta |
| RF29 | O aplicativo permite selecionar as poltronas para pessoas idosas, crianças, obesas ou com deficiência, caso as tenha. | OBS05 |  Alta  |
| RF30 | O aplicativo permite selecionar as poltronas especiais. | OBS06 | Alta |
| RF31 | Na seleção de ingresso, o aplicativo permite adicionar um cupom de desconto. | OBS07 |Alta |
| RF32 | Caso o local disponibilize, o aplicativo disponibiliza uma visão prévia da poltrona. | OBS08 | Alta |
| RF33 | O aplicativo permite a doação por parte do usuário para fundações. | OBS09 | Media  |
| RF34 | O aplicativo possui uma função para entrar em contato com o suporte. | OBS11 | Alta |
| RF35 | O aplicativo permite ao usuário alterar seus dados. | OBS13 |Alta |
| RF36 | O aplicativo possui uma função que auxilia na recuperação da conta do usuário. | OBS14 |  Alta  |
| RF37 | O aplicativo filtra eventos por categorias.  |Q04 | Alta  |
| RF38 | O aplicativo da sugestões de eventos com base no histórico de buscas do usuário.  |Q05 | Media  |
| RF39 | O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.  |Q06 | Alta  |
| RF40 | O aplicativo notifica usuário sobre eventos, quando permitido | Q07 | Media|   

</center>


<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>


### Não Funcionais

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Não Funcionais.</p></font>

<center>

| Tipo |             Descrição            |   ID   | Prioridade |
|------|----------------------------------|--------|-------|
| RNF01 	| O app deve exibir a duração do evento ao lado da informação do local. 	| BS25	| Alta|
| RNF02 	| O app deve atualizar a quantidade de assentos disponíveis em tempo real. 	| BS26 	| Alta
| RNF03 	| O app deve exibir a capacidade restante do evento atualizada em tempo real. 	|  BS27	| Alta
| RNF04 	| O deve exibir a faixa etária do evento de forma destacada.	| BS28	| Alta
| RNF05 	| O app exibir a data do evento destacada próxima ao nome do evento. 	|  BS29	| Alta
| RNF06 	| O app deve exibir a porcentagem de ingressos comprados atualizada em tempo real. 	| BS30 	| Baixa
| RNF07 	| O app deve fornecer segurança na compra do usuário. 	| BS31 	| Alta
| RNF08 	| O usuário deve ser capaz de visualizar seus ingressos com apenas 2 cliques.  	| BS32 	| Alta
| RNF09 	| O usuário deve ser capaz de acessar um tópico de ajuda com ao menos 3 cliques. 	| BS33/IS12/OBS19/Q15 	| Media
| RNF10 	|  O app deve exibir um e-mail para contato no footer.	| BS34	| Alta
| RNF11 	| O aplicativo deve disponibilizar em sua interface eventos de acordo com as preferências do usuário. 	|  BS35/Q11	| Media
| RNF12	| O app deve armazenar a localização do usuário e se adaptar de acordo com tal. 	|  BS36	| Media
| RNF13 |  O sistema deve alocar os eventos de acordo com a região selecionada a fim de facilitar a busca e a filtragem.  | IS10/OBS15 | Alta |
| RNF14 |  Deve possuir, na página do evento, uma descrição sobre o local, a qual possui data, horário, valor e informações sobre o evento que pode ser acessada em, no máximo, 3 cliques.   | IS11/OBS16 | Alta |
| RNF15 |  Deve dar um feedback sobre o início/fim de venda de ingressos para um dado evento em forma notificação, sendo essa acessível com 1 clique.  | IS13 | Alta |
| RNF16 |  Deve oferecer atendimento especial para idosos/deficientes durante o processo de compra de ingressos.  | IS14 | Alta |
| RNF17 |  Deve possuir uma tela para cadastro e login.  | IS15 | Alta|
| RNF18 |  Deve possuir uma área para os usuários reportarem erros de funcionamento do aplicativo.  | IS16 | Alta |
| RNF19 |  Deve adaptar a tela de seleção de poltronas de acordo com as poltronas já escolhidas. | OBS17 | Alta  |
| RNF20 |  Deve apresentar ao usuário o feedback da confirmação de suas ações. | OBS18 |  Alta |
| RNF21 |  Deve apresentar uma tela com os dados da conta com ao menos uma etapa de segurança.  | OBS20 | Media  |
| RNF22 |  Deve apresentar uma página com o histórico de pedidos do usuário em dois cliques. | OBS21 | Alta |
| RNF23 |  Deve apresentar uma tela com as regiões para filtrar os eventos. |OBS22| Alta  | 
| RNF24 | O aplicativo deve proteger os dados de cadastro e compra dos usuários.  | Q10 | Alta  |
| RNF25 | As notificações do aplicativo devem ser fornecidas em tempo hábil.  |Q12 | Alta  |
| RNF26 | O sistema deve ser capaz de indexar e pesquisar palavras-chave ou tags de eventos a fim de oferecer uma resposta rápida aos usuários durante a busca.  |Q13 | Alta  |
| RNF27 | O aplicativo deverá permitir a compra de ingressos de maneira simples (em menos de três telas) | Q14 |  Alta |
| RNF28 | O sistema deve alertar imediatamente ao usuário problemas ou erros relacionados a compra de ingressos. | Q15 | Alta  |

</center>

<font size="3"><p style="text-align: center">Fonte: [Douglas Alves](https://github.com/dougAlvs).</p></font>




## Referências Bibliográficas

> <a id="FTF1Ref" href="#FTF1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.


## Histórico de Versões

| Versão  | Data | Descrição | Autor(es) | Revisor(es) |
| ---------- | -----  | ------ | ---------- | ---------- |
| `1.0` | 30/04/2023 | Criação da página | [Douglas Alves](https://github.com/dougAlvs) | [Geovanna Maciel](https://github.com/manuziny) |
| `1.1`  | 01/07/2023 | Ajustes dos não-funcionais. | [Arthur de Melo](https://github.com/arthurmlv) | [Douglas Alves](https://github.com/dougAlvs) |
 