## Introdução

O Léxico é uma notação que, por meio da descrição de termos, tem como objetivo descrever os símbolos de uma linguagem. No entanto, seu principal objetivo na Engenharia de Requisitos é o reconhecimento de palavras ou frases peculiares ao contexto social aplicado no estudo. Cada símbolo possui sua noção e seu impacto. Noção é o que tal símbolos denota, já impacto é a conotação de um símbolos, ou seja, o efeito real que ele causa quando executado.

## Metodologia

Para a confeccção dos léxicos, utilizamos a notação do Léxico Ampliado da Linguagem (LAL)<a id="anchor_1" href="#REF1">^1^</a>, com os conceitos explicitados na Tabela 1, já o template utilizado está presente na Tabela 2:
<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 1</b> - Léxicos do tipo LAL</p></font>

| Tipo do símbolo | Noção | Impacto |
|-----------------|-------|-------|
| Sujeito | Quem é o sujeito | Ações que executa |
| Verbo | Quem realiza, quando acontece e quais os procedimentos | Quais os reflexos das ações no ambiente e novos estados decorrentes |
| Objeto | Definir o objeto e identificar outros objetos com os quais ele se relaciona | Ações que podem ser aplicadas ao objeto  |
| Estado | O que indica e ações que levaram a esse estado | Identificar outros estados que podem ocorrer a partir do estado que se descreve  |

<font size="3"><p style="text-align: center">Fonte: SAYÃO e CARVALHO<a id="anchor_1" href="#REF1">^1^</a>.</p></font>

</figure>


<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 2</b> - Template Léxicos</p></font>

| ID | Descrição |
|-----------------|-------|
| Classificação | Estado/Objeto/Verbo |
| Impacto | Descrição de ações e de seus efeitos | 
| Noção | Símbolo |
| Dicionário | Sinônimos |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

## Léxicos

### L01: Filtrar Eventos

O primeiro Léxico, presente na Tabela 3, faz o uso dos seguintes requisitos não implementados: filtrar por Estado e por Município (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>), filtrar por data e por horário (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a>), filtrar por idade mínima de entrada (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a>) e filtrar por categorias (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 3</b> - Léxico 01: Filtrar Eventos (L01)</p></font>

| L01 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | Os eventos são listados de acordo com o filtro requisitado | 
| Noção | Pessoa interessada em visualizar ou comprar algum ingresso |
| Dicionário | Aprimorar busca, Restringir busca e Limitar resultados |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### L02: Sugestões de Eventos

O segundo Léxico, presente na Tabela 4, faz o uso do seguinte requisito não implementado: o aplicativo da sugestões de eventos com base no histórico de buscas do usuário (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 4</b> - Léxico 02: Sugestões de Eventos (L02)</p></font>

| L02 | Descrição |
|-----------------|-------|
| Classificação | Estado |
| Impacto | A aba de sugestões se adapta ao que o usuário vê ou consome no site | 
| Noção | A aba de sugestões mostra os eventos sugeridos àquele usuário |
| Dicionário | Eventos Sugeridos, Palpites e Recomendações |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### L03: Evento com Tags

O terceiro Léxico, presente na Tabela 5, faz o uso do seguinte requisito não implementado: o aplicativo tem palavras-chave ou tags associadas aos eventos para facilitar a busca (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 5</b> - Léxico 03: Evento com Tags (L03)</p></font>


| L03 | Descrição |
|-----------------|-------|
| Classificação | Estado |
| Impacto | Eventos vinculados às tags | 
| Noção | Na busca, serão listados todos os eventos vinculados àquela determinada palavra-chave |
| Dicionário | Eventos com Palavras-chave e Eventos com Rótulo |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### L04: Notificar Eventos

O quarto Léxico, presente na Tabela 6, faz o uso do seguinte requisito não implementado: o aplicativo notifica usuário sobre eventos, quando permitido (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a>), o aplicativo tem palavras-chave ou tags associadas aos eventos para facilitar a busca (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a>), o aplicativo da sugestões de eventos com base no histórico de buscas do usuário (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a>), .

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 04: Notificar Eventos (L04)</p></font>


| L04 | Descrição |
|-----------------|-------|
| Classificação | Verbo |
| Impacto | Os eventos são notificados aos usuários que permitiram | 
| Noção | O usuário permitiu e, portanto, deseja receber notificações de determinados eventos |
| Dicionário | Aviso de eventos, Comunicar eventos e Informar eventos |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

### L05: Comprador

O quinto Léxico, presente na Tabela 7, faz o uso do seguinte requisito não implementado: o aplicativo notifica usuário sobre eventos, quando permitido (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a>), filtrar por Estado e por Município (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a>), filtrar por data e por horário (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a>), filtrar por idade mínima de entrada (<a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a>), filtrar por categorias (<a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a>), o usuário deve ser capaz de conectar uma carteira digital (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS18</a>), o usuário deve ser capaz de mudar o idioma do app (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a>) e o usuário deve ser capaz de acessar à assistente virtual (<a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS22</a>).

<figure markdown>
<font size="3"><p style="text-align: center"><b>Tabela 6</b> - Léxico 05: Comprador (L05)</p></font>


| L05 | Descrição |
|-----------------|-------|
| Classificação | Objeto |
| Impacto | O comprador pode escolher se quer ou não receber notificações ([L04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos)) </br> O comprador pode filtrar a busca por idade, Estado, Município, data, horário e categoria ([L01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos)) </br> O comprador é capaz de conectar uma carteira digital </br> O comprador pode acessar à assistente virtual </br> O comprador pode mudar o idioma do app </br> O comprador recebe sugestões de eventos de acordo com a sua atividade ([L02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos)) </br> | 
| Noção | Pessoa interessada em participar de algum evento ou procurar por eventos |
| Dicionário | Cliente, Usuário, Consumidor e Freguês |

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>
</figure>

## Bibliografia

>SERRANO, Milene. Requisitos – Aula 10. 2017. Apresentação de slides. Disponível em: [https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf](https://aprender3.unb.br/pluginfile.php/2523091/mod_resource/content/1/Aula%2010.pdf). Acesso em: 14/05/2023.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SAYÃO, Miriam, CARVALHO, Gustavo. Construção do léxico de aplicações. Information and Human Language Technology, 4th Workshop, Ribeirão Preto, 2006. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf/>. Acesso em: 14/05/2023.

## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 14/05/2023 | Criação dos léxicos.                           | [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Douglas Alves](https://github.com/dougalvs) e [Gabriel Campello](https://github.com/G16C) |