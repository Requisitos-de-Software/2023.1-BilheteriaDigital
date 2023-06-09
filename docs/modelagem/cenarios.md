# Cenários

## Introdução 

Os cenários se apresentam como descrições detalhadas, geralmente em linguagem natural, de situações ou eventos que envolvem determinados atores São úteis para entender como os ambientes, sistemas e atores interagem entre si, além de fornecer uma visão de como o sistema deve funcionar em diversas situações, seus comportamentos e fluxo. Os cenários produzidos estão listados nas tabelas de 1 a 5.

## Cenário 1

<center>

Tabela 1: Filtrar por categorias.

|**Cenário 1**|
|--------------|
|**Titulo**    |
|_[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por categoria._|
|**Objetivo**  |
|_Permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) encontre eventos disponíveis por categoria._|
|**Contexto**  |
|<p>Local: _Tela inicial do aplicativo._</p> <p>Tempo: _Aproximadamente 1 min._</p> <p>Pré-condição: _Existirem eventos cadastrados para a categoria selecionada_</p>|
|**Atores**    |
|_[Usuário da Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)._|
|**Recursos**  |
|<p>_Internet._</p><p>_Smartphone com a Bilheteria Digital instalada._ </p> |
|**Episódios** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de [filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) na tela inicial._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de filtrar eventos por categoria._</p> <p>_O aplicativo exibe uma lista das categorias de eventos dsponíveis._</p> <p>_O aplicativo filtra os eventos disponíveis de acordo a categoria selecionada e o tipo de evento correspondente._</p>|
|**Restrição** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) só pode filtrar os eventos por categorias em que há eventos cadastrados._</p> <p>_O aplicativo deve fornecer uma lista de categorias disponíveis para seleção._</p>|
|**Exceção**   |
|<p>_Erro de conexão à internet._</p> <p>_Se não houver eventos cadastrados para a categoria selecionada, o aplicativo deve apresentar uma mensagem indicando que não há eventos disponíveis para aquela categoria_</p>|

Fonte: [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs)

</center>

## Cenário 2

<center>

Tabela 2: Filtrar por data e hora.

|**Cenário 2**|
|--------------|
|**Titulo**    |
|_[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por data e hora de ocorrência._|
|**Objetivo**  |
|_Permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) encontre eventos que ocorram em um determinado intervalo de tempo._|
|**Contexto**  |
|<p>Local: _Tela inicial do aplicativo._</p> <p>Tempo: _Aproximadamente 1 min._</p> <p>Pré-condição: _Usuário estar logado, os eventos terem informações sobre data e hora de ocorrência._</p>|
|**Atores**    |
|_[Usuário da Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)._|
|**Recursos**  |
|<p>_Internet._</p><p>_Smartphone com a Bilheteria Digital instalada._ </p> |
|**Episódios** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de [filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) na tela inicial._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção "[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por data e hora de ocorrência"._</p> <p>_O aplicativo apresenta uma tela de seleção de data e hora._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a data e hora desejada para a ocorrência dos eventos._</p> <p>_O aplicativo filtra os eventos disponíveis de acordo com a data e hora de ocorrência selecionada e apresenta a lista de eventos correspondentes._</p>
|**Restrição** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) só pode filtrar os eventos por data e hora de ocorrência futura._</p>|
|**Exceção**   |
|<p>_Erro de conexão à internet._</p> <p>_Se não houver eventos cadastrados que ocorram na data e hora selecionada, o aplicativo deve apresentar uma mensagem indicando que não há eventos disponíveis naquela data e hora._</p>|

Fonte: [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs)

</center>


## Cenário 3

<center>

Tabela 3: Filtrar por idade mínima.

|**Cenário 3**|
|--------------|
|**Titulo**    |
|_[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por idade mínima de entrada._|
|**Objetivo**  |
|_Permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) encontre eventos que tenham uma idade mínima de entrada adequada._|
|**Contexto**  |
|<p>Local: _Tela inicial do aplicativo._</p> <p>Tempo: _Aproximadamente 1 min._</p> <p>Pré-condição: _[usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) estar logado, os eventos terem informações sobre faixa etária cadastradas_</p>|
|**Atores**    |
|_[Usuário da Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)._|
|**Recursos**  |
|<p>_Internet._</p><p>_Smartphone com a Bilheteria Digital instalada._ </p> |
|**Episódios** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de [filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) na tela inicial._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção "[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por idade mínima de entrada" ._</p> <p>_O aplicativo apresenta uma lista de faixas etárias para seleção._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a faixa etária adequada para a idade mínima de entrada desejada._</p> <p>_O aplicativo filtra os eventos disponíveis de acordo com a idade mínima de entrada selecionada e apresenta a lista de eventos correspondentes._</p>
|**Restrição** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) só pode filtrar os eventos por idade mínima de entrada adequada para sua faixa etária._</p>|
|**Exceção**   |
|<p>_Erro de conexão à internet._</p> <p>_Se não houver eventos cadastrados com a idade mínima de entrada adequada para a faixa etária selecionada, o aplicativo deve apresentar uma mensagem indicando que não há eventos disponíveis naquela faixa etária._</p>|
 
Fonte: [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs)

 </center>


## Cenário 4

<center>

Tabela 4: Filtrar por municípios.

|**Cenário 4**|
|--------------|
|**Titulo**    |
|_[Filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por municípios._|
|**Objetivo**  |
|_Permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) encontre eventos disponíveis em um município específico._|
|**Contexto**  |
|<p>Local: _Tela inicial do aplicativo._</p> <p>Tempo: _Aproximadamente 1 min._</p> <p>Pré-condição: _[usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) estar logado, o município desejado estar cadastrado no aplicativo e existirem eventos cadastrados naquele município_</p>|
|**Atores**    |
|_[Usuário da Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)._|
|**Recursos**  |
|<p>_Internet._</p><p>_Smartphone com a Bilheteria Digital instalada._ </p> |
|**Episódios** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de [filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) na tela inicial._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção de [filtrar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) por localização._</p> <p>_O aplicativo exibe uma lista dos estados do país._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona o estado desejado_</p> <p>_O aplicativo exibe uma lista de municípios disponíveis_</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a cidade desejada._</p> <p>_O aplicativo filtra os eventos disponíveis de acordo com a cidade selecionada e apresenta a lista de eventos correspondentes._</p>|
|**Restrição** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) só pode filtrar os eventos por cidades em que há eventos cadastrados._</p> <p>_O aplicativo deve fornecer uma lista de cidades disponíveis para seleção._</p>|
|**Exceção**   |
|<p>_Erro de conexão à internet._</p> <p>_Se não houver eventos cadastrados para a cidade selecionada, o aplicativo deve apresentar uma mensagem indicando que não há eventos disponíveis naquela cidade_</p>|

Fonte: [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs)

</center>

## Cenário 5

<center>

Tabela 5: Conectar carteira digital.

|**Cenário 5**|
|--------------|
|**Titulo**    |
|_Conectar uma carteira digital._|
|**Objetivo**  |
|_Permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) do aplicativo conecte uma carteira digital compatível para fazer pagamentos._|
|**Contexto**  |
|<p>Local: _Aba "Minha conta"._</p> <p>Tempo: _Aproximadamente 5 min._</p> <p>Pré-condição: _[usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) estar logado e possui carteira digital compatível._</p>|
|**Atores**    |
|_[Usuário da Bilheteria Digital](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario)._|
|**Recursos**  |
|<p>_Internet._</p><p>_Smartphone com a Bilheteria Digital instalada._ </p><p>_Carteira digital compatível com o aplicativo._</p> |
|**Episódios** |
|<p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) acessa a seção "Minha conta"._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a opção "Conectar carteira digital"._</p> <p>_O aplicativo exibe uma lista de carteiras digitais compatíveis._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) seleciona a carteira digital desejada._</p> <p>_O aplicativo solicita ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) as informações necessárias para conectar a carteira digital, como o endereço da carteira ou informações de autenticação._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) fornece as informações solicitadas._</p> <p>_O aplicativo verifica se as informações estão corretas e se a carteira digital é compatível._</p> <p>_O aplicativo confirma que a carteira digital foi conectada com sucesso._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) pode agora usar a carteira digital para fazer pagamentos no aplicativo._</p>|
|**Restrição** |
|<p>_A carteira digital deve ser compatível com o aplicativo._</p> <p>_O [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) deve fornecer informações corretas para conectar a carteira digital._</p> <p>_O processo de conexão da carteira digital pode ser interrompido em caso de problemas de conectividade de internet ou de interrupção no serviço da carteira digital._</p>|
|**Exceção**   |
|<p>_Erro de conexão à internet._</p> <p>_Erro de conexão ao serviço de carteira digital_</p>|

Fonte: [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs)

</center>

## Bibliografia

>SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Último acesso em: 24 abr. 2023. 
>ANÁLISE de Requisitos de Software da Aplicação Duolingo, 2019. Disponível em: [https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/](https://requisitos-de-software.github.io/2019.2-Duolingo/modelagem/Cenarios/). Último acesso em: 24 abr. 2023.


## Histórico de Versões

| Versão | Data       | Descrição                                 | Autor(es)                                                                                           | Revisor(es)                                      |
| ------ | ---------- | ----------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------ |
| `1.0`  | 13/05/2023 | Criação dos cenários.                        | [Gabriel Campello](https://github.com/G16C) e [Douglas Alves](https://github.com/dougAlvs) | [Sidney Fernando](https://github.com/nando3d3)   |
| `1.1`  | 01/07/2023 | Retrabalho.| [Arthur de Melo](https://github.com/arthurmlv)   | [Matheus Henrique](https://github.com/mathonaut)   |