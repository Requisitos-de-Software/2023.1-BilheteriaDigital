# Verificação da Especificação Suplementar do Grupo 2

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [Especificação Suplementar](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/) da Etapa 3 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e3-grupo2). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) [Matheus Henrique](https://github.com/mathonaut), que será responsável por realizar a avaliação e o [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e3-grupo2).

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist de Verificação.

|  ID  | Descrição                                                                                              | Avaliação     | Observações                                     |
| :--: | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1   | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           |                                                 |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Não se aplica |                                                 |
|  5   | Todos os textos estão na norma padrão?                                                                 | Não           |                                                 |
|  6   | O documento segue o modelo FURPS+?                                                                     | Incompleto    |                                                 |
|  7   | O documento possui um tópico de Funcionalidade?                                                        | Sim           |                                                 |
| 7.1  | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
|  8   | O documento possui um tópico de Usabilidade?                                                           | Sim           |                                                 |
| 8.1  | Os requisitos apresentados são testáveis?                                                              | Incompleto    |                                                 |
| 8.2  | Os requisitos apresentados facilitam as tarefas realizadas pelos usuários?                             | Sim           |                                                 |
|  9   | O documento possui um tópico de Confiabilidade?                                                        | Sim           |                                                 |
| 9.1  | Os requisitos apresentados são testáveis?                                                              | Incompleto    |                                                 |
| 9.2  | Os requisitos apresentados aumentam a confiabilidade do sistema?                                       | Sim           |                                                 |
| 9.3  | Os requisitos relacionados à segurança são apresentados?                                               | Sim           |                                                 |
|  10  | O documento possui um tópico de Desempenho?                                                            | Não           | Performance não é a mesma coisa que Desempenho. |
| 10.1 | Os requisitos apresentados são testáveis?                                                              | Incompleto    |                                                 |
| 10.2 | Os requisitos sobre os tempos de respostas são apresentados?                                           | Sim           |                                                 |
| 10.3 | Os requisitos sobre a disponibilidade são apresentados?                                                | Incompleto    | É apresentado no tópico de Confiabilidade.      |
|  11  | O documento possui um tópico de Suportabilidade?                                                       | Sim           |                                                 |
| 11.1 | Os requisitos apresentados são testáveis?                                                              | Incompleto    |                                                 |
| 11.2 | É apresentado os sistemas operacionais que o sistema funcionará?                                       | Sim           |                                                 |
|  12  | O documento possui um tópico de Restrições de Design?                                                  | Sim           |                                                 |
| 12.1 | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
| 12.2 | Os requisitos apresentados específica ou restringe o design do sistema?                                | Sim           |                                                 |
|  13  | O documento possui um tópico de Requisitos de Implementação?                                           | Sim           |                                                 |
| 13.1 | Os requisitos apresentados são testáveis?                                                              | Incompleto    |                                                 |
|  14  | O documento possui um tópico de Requisitos de Interface?                                               | Sim           |                                                 |
| 14.1 | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
|  15  | O documento possui um tópico de Requisitos Físicos?                                                    | Incompleto    |                                                 |
| 15.1 | Os requisitos apresentados são testáveis?                                                              | Não           |                                                 |
| 15.2 | As características físicas de onde o sistema funcionará são apresentadas?                              | Não           |                                                 |

_Fonte: [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Lista de Problemas e Análise

Primeiramente, parabéns a equipe pela entrega do artefato, a maioria dos problemas estão relacionados a como os requisitos são especificados deixando em muitos casos eles ambíguos.

### ID 5 - Todos os textos estão na norma padrão?

- Em "Requisitos de implementação" no texto de [metodologia](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#metodologia) **_específica_** está escrita errada;
- Em "Requisitos de interface" no texto de [metodologia](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#metodologia) **_específica_** está escrita errada;
- Em [Visibilidade do status do sistema](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#22-visibilidade-do-status-do-sistema) tem uma repetição da palavra deve;
- Em [Segurança dos dados](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#31-seguranca-dos-dados) a frase _"...não permitir modificações não autorizadas."_ está escrita errada.
  "

### ID 6 - O documento segue o modelo FURPS+?

O documento apresenta o tópico de desempenho com o nome errado.

### ID 8.1 - Os requisitos apresentados são testáveis? (Usabilidade)

Falta especificar mais os requisitos. Por exemplo, em [Eficiência](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#23-eficiencia) é pedido que as tarefas sejam realizadas com poucos cliques, mas quantos cliques são poucos? Cinco, três etc.

Existe o mesmo problema em Facilidade de uso. A utilização de expressões como _"facilmente aprendido"_ e _"ser intuitivo"_ dificulta que esses requisitos sejam testáveis.

### ID 9.1 - Os requisitos apresentados são testáveis? (Confiabilidade)

Novamente falta especificação. Em [Segurança dos dados](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/especificacaoSuplementar/#31-seguranca-dos-dados), deve se demonstrar como os dados devem ser mantidos seguros, através de criptografia ou outro meio por exemplo.

### ID 10 - O documento possui um tópico de Desempenho?

Há uma confusão em relação ao nome, a palavra Desempenho não é o mesmo que Perfomance. Temos as seguintes definições, segundo o dicionário Aurélio<a id=anchor_1 href="#REF1"><sup>1</sup></a>:

> Desempenho: “Ato ou efeito de desempenhar; cumprimento, exercício, execução: desempenho de uma atividade remunerada”

> Performance: “Resultado obtido, em cada uma de suas exibições em público, por um cavalo de corrida, por um atleta etc. / Conjunto dos resultados obtidos em um teste. / Proeza esportiva”

### ID 10.1 - Os requisitos apresentados são testáveis? (Desempenho)

É preciso informar o quão baixo deve ser o consumo energético.

### ID 10.3 - Os requisitos sobre a disponibilidade são apresentados?

O requisito sobre a disponibilidade do sistema está no tópico de confiabilidade, porém ele deveria estar aqui de acordo com os padrões.<a id=anchor_2 href="#REF2"><sup>2</sup></a>

### ID 11.1 - Os requisitos apresentados são testáveis? (Suportabilidade)

Os dispositivos no qual o sistema deve ser compatível e possuir uma responsividade não são especificados. Além disso, as "principais plataformas mobile Android e iOS" não estão bem explícitas, está se referindo às versões desses O.S's ou aos dispositivos que os usam?

### ID 13.1 - Os requisitos apresentados são testáveis? (Requisitos de Implementação)

Em "O aplicativo deve ser construído seguindo o padrão proposto pela empresa que o desenvolve", quais são esses padrões? São de arquitetura, de desenvolvimento (ágeis ou não), de governança de dados etc.

### ID 15 - O documento possui um tópico de Requisitos Físicos?

Apesar do nome do tópico falar em requisitos físicos, os requisitos apresentados são de suportabilidade e não especificam quais são as características dos dispositivos físicos que o sistema funcionará. Será só dispositivos mobile ou ele funcionará em aplicação web também?

## Sugestões de Correções

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Corrigir os erros ortográficos;
- Corrigir o nome do tópico de desempenho;
- Reescrever os requisitos ambíguos para deixá-los mais específicos e torná-los testáveis.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> ALBUQUERQUE, Daniela. Desempenho e Performance. Como analisar? **Templum Consultoria**, 2012. Disponível em: <<https://certificacaoiso.com.br/desempenho-performance-como-analisar/>>. Acesso em: 05, junho e 2023.

> <a id="REF2" href="#anchor_1">2.</a> Artefato: Especificações Suplementares. **Centro de Informática - UFPE**. Disponível em: <<https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>>. Acesso em: 04 de junho de 2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 06/06/2023 | Criação da página. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
