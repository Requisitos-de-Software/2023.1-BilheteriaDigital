# Forward-from

## Introdução

Este artefato objetiva realizar a conexão entre requisitos, arquitetura e implementação. Portanto, explicitar-se-á a relação de dependência entre requisitos e seus artefatos relacionados: de requisitos, de arquitetura e de implementação. A rastreabilidade é composta por ligações ou elos dadas pela interrelação dos artefatos especificados<a id="REF1" href="#anchor_1">^1^</a>.

## Metodologia

O meta-modelo utilizado como base para a realização da rastreabilidade foi proposto por Toranzo. Nesse modelo, todas as informações rastreadas podem ser classificadas em quatro categorias<a id="REF2" href="#anchor_2">^2^</a>:

- Ambiental: lei, objetivos, estratégias e padrão.
- Organizacional: objetivos, regras e processo.
- Gerencial: objetivos, tarefas e restrições.
- Desenvolvimento: requisitos, diagramas e programa.

Além disso, fez-se uma adaptação do meta-modelo de Toranzo para a realização da rastreabilidade forward-from, a qual explicita a conexão entre artefatos de desenho e de implementação aos requisitos elicitados. Nesse modelo, os elos são definidos por: satisfação, recurso, responsabilidade, representação, alocado e agregação<a id="REF2" href="#anchor_2">^2^</a>. No entanto, o elo de resposabilidade não será abordado neste artefato, dado que as informações presentes nos artefatos impede a realização de tal rastreabilidade.

A rastreabilidade foi feita somente nos requisitos não implementados pela Bilheteria Digital, sendo alguns implementados no protótipo de alta fidelidade feito para a [Validação](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/validacao/prototipo/).

<center>

Tabela 1 - Template Forward-from

| <span style = "color: red">Artefato Analisado</span>     | Classificação do Artefato Analisado |
| :----------------------: | :--------------------: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | - |
| Recurso | - |
| Representação | - |
| Alocado | - |
| Agregação | - |

Fonte: Meta-modelo de Toranzo (TORANZO, 2002)<a id="REF2" href="#anchor_2">^2^</a>.

</center>

## Rastreabilidade

Neste tópico, serão apresentadas as tabelas referentes aos elos dos artefatos analisados, que se referem aos requisitos não implementados pela Bilheteria Digital.

### RF01

O aplicativo filtra os eventos por Estado e por Município.

<center>

Tabela 2 - RF01

| [RF01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Cenário 04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4) <br> [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) |
| Alocado | [Léxico 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [Épico 1](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar) <br> [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Casos de Uso UC01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) |
| Agregação | [Cenário 04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-4) <br> [História de Usuário US01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us01) <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS01</a>, <a href="../../elicitacao/elicitacao/tecnicas/brainstorming/#anchor_BS">BS08</a> e <a href="../../elicitacao/tecnicas/observacao/#anchor_OBS">OBS01</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF02

O aplicativo filtra os eventos por data e por horário.

<center>

Tabela 3 - RF02

| [RF02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Cenário 02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-2) <br> [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br> [Casos de Uso](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#diagrama-de-casos-de-uso) |
| Alocado | [Léxico 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [Épico 1 - Feature 1](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar) <br> [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Casos de Uso UC01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) |
| Agregação | [História de Usuário US04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us04) <br> Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS02</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q03</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF03

O aplicativo filtra os eventos por idade mínima de entrada.

<center>

Tabela 4 - RF03

| [RF03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Cenário 03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-3) <br> [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br> [Casos de Uso](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#diagrama-de-casos-de-uso) |
| Alocado | [Léxico 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [Épico 1 - Feature 2](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar)  <br> [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Casos de Uso UC01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso)  |
| Agregação | Requisitos: <a href="../../elicitacao/tecnicas/introspeccao/#anchor_IS">IS03</a> e <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q02</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF10

O aplicativo filtra eventos por categorias.

<center>

Tabela 5 - RF10

| [RF10](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Cenário 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1) <br> [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br> [Casos de Uso](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#diagrama-de-casos-de-uso) <br> [História de Usuário US02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us02) |
| Alocado | [Léxico 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [Épico 1 - Feature 2](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar)  <br> [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Casos de Uso UC01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) |
| Agregação | Requisito: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q04</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF11

O aplicativo dá sugestões de eventos com base no histórico de buscas do usuário.

<center>

Tabela 6 - RF11

| [RF11](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Léxico 02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos)  |
| Alocado | [Léxico 01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) |
| Agregação | [Casos de Uso UC02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) <br> Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q05</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS11</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF12

O aplicativo tem palavras-chave ou tags associadas a eventos para facilitar a busca.

<center>

Tabela 7 - RF12

| [RF12](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar DES01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Léxico 03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l03-evento-com-tags) |
| Alocado | [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Casos de Uso UC02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) |
| Agregação | Requisito: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q06</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF13

O aplicativo notifica usuário sobre eventos, quando permitido.

<center>

Tabela 7 - RF13

| [RF13](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [Especificação Suplementar DES01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Casos de Uso UC02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) <br> [Requisitos NFR02 e NFR03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#requisitos-nao-funcionais) <br> [Especificação Suplementar CON01 e CON02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#confiabilidade) |
| Representação | [Léxico 04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos) <br> [Histórias de Usuário US22 e US23](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us22) |
| Alocado | [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Épico 2 - Feature 3](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-2-preferencias) |
| Agregação | [Léxico 02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos) <br> Requisitos: <a href="../../elicitacao/tecnicas/questionario/#anchor_Q">Q07</a> e <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS06</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF23

O usuário é capaz de conectar uma carteira digital.

<center>

Tabela 7 - RF23

| [RF23](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [Especificação Suplementar DES01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Casos de Uso UC03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) <br> [Cenário 05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5) |
| Representação | [Cenário 05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-5) |
| Alocado | [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Épico 2 - Feature 4](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-2-preferencias) |
| Agregação | Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS18</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RF24

O usuário é capaz de mudar o idioma do app.

<center>

Tabela 7 - RF24

| [RF24](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar USA06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) <br> [Especificação Suplementar DES01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) <br> [NFR Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) |
| Recurso | [Casos de Uso UC03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/#especializacao-dos-casos-de-uso) |
| Representação | [História de Usuário US31](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us31) <br> [Léxico 06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l06-mudar-idioma) |
| Alocado | [NFR Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade) <br> [Épico 3 - Feature 6](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-2-preferencias) |
| Agregação | Requisitos: <a href="../../elicitacao/tecnicas/brainstorming/#anchor_BS">BS19</a> |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

### RNF02




O app deve fornecer eventos direcionados.




<center>




Tabela 5 - RNF02




| [RF02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar - USA01, DES01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) |
| Recurso | - |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br> |
| Alocado | [Léxico 02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos) <br> [Épico 5 - Padronização - 10](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar) <br> [NFR - Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-01-usabilidade)|
| Agregação | [História de Usuário - US12](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12) <br> Requisitos: [IS10](../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q11](../../elicitacao/tecnicas/questionario/#anchor_QNF), [BS35](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS36](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF) e [OBS22](../../elicitacao/tecnicas/observacao/#anchor_OBSNF) |




Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).




</center>

### RNF03




O app deve disponibilizar todas as informações do evento em uma página.




<center>




Tabela 6 - RNF03




| [RNF03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar - USA01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) | 
| Recurso | - | 
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br>   |
| Alocado | [NFR - Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia)<br> [Épico 5 - Padronização - Feature 10](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar) <br> |
| Agregação | [História de Usuário - US13](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12) <br> Requisitos: [IS11](../../elicitacao/tecnicas/introspeccao/#anchor_IS), [BS25](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS26](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS27](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS28](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS29](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [BS30](../../elicitacao/tecnicas/brainstorming/#anchor_BSNF), [OBS15](<(../../elicitacao/tecnicas/observacao/#anchor_OBSNF)>) e [OBS16](../../elicitacao/tecnicas/observacao/#anchor_OBSNF) |




Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).




</center>

### RNF04




A compra deve ser feita em no máximo 5 páginas.




<center>




Tabela 7 - RNF04




| [RNF04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar - USA04, USA05 e USA06](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) |
| Recurso | - |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br>   |
| Alocado | [NFR - Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia)<br> |
| Agregação | Requisitos: [IS13](../../elicitacao/tecnicas/introspeccao/#anchor_IS), [IS16](../../elicitacao/tecnicas/introspeccao/#anchor_IS), [Q14](../../elicitacao/tecnicas/questionario/#anchor_QNF), [OBS17](../../elicitacao/tecnicas/observacao/#anchor_OBSNF), [OBS18](../../elicitacao/tecnicas/observacao/#anchor_OBSNF) e [IS14](../../elicitacao/tecnicas/introspeccao/#anchor_IS) |




Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).




</center>

### RNF07




O app não deve ter tempo de resposta superior a 200 ms.




<center>




Tabela 8 - RNF07




| [RNF07](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar - DES02](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) |
| Recurso | - |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br>   |
| Alocado | [NFR - Eficiência](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/nfrframework/#nfr-02-eficiencia) <br> |
| Agregação | Requisitos: [Q12](../../elicitacao/tecnicas/questionario/#anchor_QNF) |

Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).




</center>

### RNF08




O app deve permitir a filtragem dos eventos cadastrados no banco de dados.




<center>




Tabela 9 - RNF08




| [RNF08](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/requisitos_elicitados/#requisitos-funcionais)     | Desenvolvimento |
| :----------------------: | -------------------- |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | [Especificação Suplementar - USA01, DES01 e DES05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#desempenho) |
| Recurso | [Casos de Uso - UC01](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/) <br> [Cenário 01, 02, 03 e 04](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/cenarios/#cenario-1) |
| Representação | [Protótipo de Alta Fidelidade](https://www.figma.com/proto/CSsRpoXBR0BWWojN1ZrDn0/Protótipo-de-Alta-FIdelidade?page-id=0%3A1&type=design&node-id=107-1118&viewport=29390%2C34193%2C3.02&scaling=min-zoom&starting-point-node-id=107%3A1118&show-proto-sidebar=1) <br>   |
| Alocado | [Léxico 01 e 03](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos) <br> [Épico 1 e 5 - Categorizar e Padronização - Feature 1, 2 e 10](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/backlog/#epico-1-categorizar) <br> |
| Agregação | [História de Usuário - US01, US02, US04, US12, US13](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/#us12) <br> Requisitos:  [Q13](../../elicitacao/tecnicas/questionario/#anchor_QNF) |




Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).




</center>


## Referências Bibliográficas

> <a id="anchor_1" href="#REF1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 25 de jun de 2023.

> <a id="anchor_2" href="#REF2">2.</a> TORANZO, M.; CASTRO, J; MELLO, E. Uma proposta para melhorar o rastreamento de requisitos. PUC-Rio: Workshop em Engenharia de Requisitos, Rio de Janeiro, 2002. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/toranzo.pdf. Acesso em: 25 de jun de 2023.

## Histórico de Vesões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| --- | --- | --- | --- | --- |
| 1.0 | 25/06/2023 | Criação da documentação e Requisitos Funcionais. | [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Sidney Fernando](https://github.com/nando3d3) |
| 1.1 | 25/06/2023 | Requisitos Não-Funcionais | [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Sidney Fernando](https://github.com/nando3d3) |


