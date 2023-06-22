# Verificação da Especificação Suplementar do Grupo

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [Especificação Suplementar](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/) da Etapa 3 do [nosso grupo (Grupo 1)](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e3-grupo). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e3-grupo). A tabela 1 apresenta os participantes dessa verificação.

<center>

**Tabela 1** - Participantes da Verificação.

|                   Participante                   |   Papel   |
| :----------------------------------------------: | :-------: |
| [Arthur de Melo](https://github.com/arthurmlv) | Avaliador |
|   [Rafael Ferreira](https://github.com/RafaelCLG0)   | Revisor  |

_Fonte: Elaborada por [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Sumário Dos Dados

A Tabela 2 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 2** - Checklist de Verificação.

|  ID  | Descrição                                                                                              | Avaliação     | Observações                                     |
| :--: | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1   | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2   | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           |                                                 |
|  4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Sim           |                                                 |
|  5   | Todos os textos estão na norma padrão?                                                                 | Sim           |                                                 |
|  6   | O documento segue o modelo FURPS+?                                                                     | Sim           |                                                 |
|  7   | O documento possui um tópico de Funcionalidade?                                                        | Sim           |                                                 |
| 7.1  | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
|  8   | O documento possui um tópico de Usabilidade?                                                           | Sim           |                                                 |
| 8.1  | Os requisitos apresentados são testáveis?                                                              | Incompleto    | Requisito USA01 de [Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade)                                                 |
| 8.2  | Os requisitos apresentados facilitam as tarefas realizadas pelos usuários?                             | Sim           |                                                 |
|  9   | O documento possui um tópico de Confiabilidade?                                                        | Sim           |                                                 |
| 9.1  | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
| 9.2  | Os requisitos apresentados aumentam a confiabilidade do sistema?                                       | Sim           |                                                 |
| 9.3  | Os requisitos relacionados à segurança são apresentados?                                               | Sim           |                                                 |
|  10  | O documento possui um tópico de Desempenho?                                                            | Sim           |                                                 |
| 10.1 | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
| 10.2 | Os requisitos sobre os tempos de respostas são apresentados?                                           | Sim           |                                                 |
| 10.3 | Os requisitos sobre a disponibilidade são apresentados?                                                | Sim           |                                                 |
|  11  | O documento possui um tópico de Suportabilidade?                                                       | Sim           |                                                 |
| 11.1 | Os requisitos apresentados são testáveis?                                                              | Incompleto    | Requisito SUP01 e SUP04 de [Suportabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade)                                                |
| 11.2 | É apresentado os sistemas operacionais que o sistema funcionará?                                       | Sim           |                                                 |
|  12  | O documento possui um tópico de Restrições de Design?                                                  | Sim           |                                                 |
| 12.1 | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
| 12.2 | Os requisitos apresentados especificam ou restringem o design do sistema?                                | Sim           |                                                 |
|  13  | O documento possui um tópico de Requisitos de Implementação?                                           | Sim           |                                                 |
| 13.1 | Os requisitos apresentados são testáveis?                                                              | Sim    |                                                 |
|  14  | O documento possui um tópico de Requisitos de Interface?                                               | Não           |                                                 |
| 14.1 | Os requisitos apresentados são testáveis?                                                              | Não se aplica           |                                                 |
|  15  | O documento possui um tópico de Requisitos Físicos?                                                    | Sim      |                                                 |
| 15.1 | Os requisitos apresentados são testáveis?                                                              | Sim           |                                                 |
| 15.2 | As características físicas de onde o sistema funcionará são apresentadas?                              | Sim           |                                                 |
|  16  | Os léxicos relacionados são citados no artefato?                                                       | Não           |                                                 |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Matheus Henrique](https://github.com/mathonaut), 2023._

</center>

## Lista de Problemas e Análise

### ID 8.1 - Os requisitos apresentados são testáveis? (Usabilidade)

Todos os outros requisitos deste tópico são testáveis, no entanto, o Requisito USA01 de [Usabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#usabilidade) é descrito como "o sistema deve ter um design minimalista, com ícones e cores que facilitem a compreensão do que está ocorrendo". No entanto, o conceito de minimalista é muito subjetivo e não específico, as cores e os ícones que facilitariam a compreensão, na verdade são tópicos também subjetivos e que não são testáveis.

### ID 11.1 - Os requisitos apresentados são testáveis? (Suportabilidade)

Os demais requisitos elicitados são testáveis. Entretanto, o Requisito SUP01 de [Suportabilidade](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/especificacao-suplementar/#suportabilidade) é descrito como: "O sistema deve possuir uma documentação clara e abrangente para facilitar a manutenção e o suporte". Sendo assim, as definições de "clara e abrangente" não são específicas. Dado que o intuito do requisito é que o sistema ofereça uma documentação para facilitar a manutenção e o suporte, seria interessante dizer que a referida documentação deve ser separada em tópicos e possuir os detalhes necessários para a compreensão daquele determinado tópico. Por fim, esses tópicos devem abranger pelo menos 30 entraves comuns, sendo 30 um número ilustrativo.

Além disso, o SUP04 também não especifica como seriam os "processos eficientes" citados, ou seja, o quão eficiente devem ser, o tempo de resposta ou como eles tratam as informações. Também não são descritas as interrupções significativas, outro que se enquadraria como algo subjetivo e, portanto, não testável.


### ID 14 - O documento possui um tópico de Requisitos de Interface?

Na metodologia, faz-se um breve aviso acerca da ausência dos Requisitos de Interface. Contudo, a ausência de tal não é explicada.

### ID 16 - Os léxicos relacionados são citados no artefato?

Em diversos momentos, o [Léxico 05](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario), que representa o usuário pode ser referenciado no artefato.

## Sugestões de Correções

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

- Corrigir o requisito USA01 de Usabilidade.
- Corrigir os requisitos SUP01 e SUP04 de Suportabilidade.
- Justificar a ausência dos Requisitos de Interface.
- Relacionar os léxicos, quando possível.

## Acompanhamento

A figura 1 é possível análisar um gráfico com o percentual de erros e acertos de acordo com checklist dos resultados obtidos acima.

<figure markdown>
<font size="3"><p style="text-align: center"><b>Figura 1</b> - Gráfico com resultado da Checklist.</p></font>
<iframe style="border:3px solid red" width="648" height="401" seamless frameborder="0" scrolling="no" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR_sgrch-9T5GOxMavolCxlDvDZvvc4d0Yf6BKOG0upNI2Z207kzZe92Rkoun9PTZrISi6glsf361uX/pubchart?oid=96662104&amp;format=interactive"></iframe><figcaption><font size="3">Fonte: [Arthur de Melo](https://github.com/arthurmlv)</font></figcaption>
</figure>

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> ALBUQUERQUE, Daniela. Desempenho e Performance. Como analisar? **Templum Consultoria**, 2012. Disponível em: <<https://certificacaoiso.com.br/desempenho-performance-como-analisar/>>. Acesso em: 05, junho e 2023.

> <a id="REF2" href="#anchor_1">2.</a> Artefato: Especificações Suplementares. **Centro de Informática - UFPE**. Disponível em: <<https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>>. Acesso em: 04 de junho de 2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 21/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv)  | [Rafael Ferreira](https://github.com/RafaelCLG0) |
