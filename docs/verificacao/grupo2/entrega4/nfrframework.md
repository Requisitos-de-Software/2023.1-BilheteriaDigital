# Verificação do NFR Framework do Grupo 2

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas em cima do artefato dos [Léxicos](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/lexicos/) da Etapa 3 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e4-grupo2). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários. A checklist foi feita com base na dissertação de mestrado de Reinaldo Antônio da Silva<a id="anchor_1" href="#REF1">^1^</a>.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e4-grupo2).

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist de Verificação.

|  ID | Descrição                                                                                              | Avaliação     | Observações                                     |
| --- | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1  | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2  | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           |                                                 |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Sim           |                                                 |
|  5  | Todos os textos estão na norma padrão?                                                                 | Não           | [Clique aqui para ver como citar figuras nas normas ABNT](https://normas-abnt.espm.br/index.php?title=Figuras)           |
| 6  | Os gráficos SIG foram validados por Fontes Externas? | Sim | No entanto, somente uma |
| 7  | Cada SIG possui sua respectiva propagação de Impacto?  | Sim | |
| 8  | Os softgoals se refinam até um nível de especificação bem definido? | Não | |
| 9  | Os cartões de especificação representam requisitos não-funcionais verificáveis? | Não | |
| 10 | Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História? | Incompleto | |
| 11 | Os Softgoals NFR estão representados apropriadamente dada a sua definição? | Sim | |
| 12 | Os Softgoals de Operacionalização estão representados apropriadamente dada a sua definição? | Sim | |
| 13 | Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição? | Não estão presentes | |
| 14 | Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método? | Não | |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Lista de Problemas e Análise

Primeiramente, parabéns a equipe pela entrega do artefato, a maioria dos problemas estão relacionados a como os requisitos são especificados deixando em muitos casos eles ambíguos.

### ID's 8 e 9 - Os softgoals se refinam até um nível de especificação bem definido? Os cartões de especificação representam requisitos não-funcionais verificáveis?

Por exemplo, no [SIG Usabilidade](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/nfrFramework/#nfr03-usabilidade), todos os softgoals são extremamente gerais e não apresentam soluções específicas para se levantar bem um Requisito Não-Funcional verificável. Sendo assim, estes deveriam ser refinados ainda mais para cada SIG. Dentro do SIG referido, podemos citar um: "O sistema deve ser claro e de fácil uso". Esse requisito não é verificável, dado que para um requisito ser verificável, vale da seguinte definição: "Um requisito é verificável se existir um processo finito, com custo compensador, que possa ser executado por uma pessoa ou máquina, e que mostre a conformidade do produto final com o requisito"<a id="anchor_2" href="#REF2">^2^</a>.

### ID 10 - Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História?

Não apresenta as dependências, as histórias e os conflitos. A história é sua data de criação, as dependências são os requisitos relacionados e os conflitos são os requisitos que causam conflitos, sendo estes mais visíveis na propagação de impactos<a id="anchor_1" href="#REF1">^1^</a>. Além disso, a definição de alguns, por exemplo, o de Usabilidade, não está de acordo com a literatura utilizada para validar dentro do projeto. De acordo com a dissertação, Usabilidade é: "um requisito que especifica a interação do usuário final com o sistema e o esforço necessário para aprender, operar, preparar a entrada e interpretar a saída do sistema"<a id="anchor_3" href="#REF3">^3^</a>.

### ID 13 - Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição?

Um dos motivos da falta de refinamento dos softgoals é a ausência de Softgoals de Afirmação. Os softgoals de afirmação são fatores delimitantes dentro de um domínio, ou seja, servem como um filtro para as características<a id="anchor_4" href="#REF4">^4^</a>.


### ID 14 - Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método?

Provavelmente todos os requisitos presentes nos cartões possuem relações com requisitos já elicitados e priorizados pelo seu grupo anteriormente. Por exemplo, a relação entre Desempenho e o requisito NFST02 priorizado pelo [Three Level-Scale](https://requisitos-de-software.github.io/2023.1-Booking/elicitacao/threeLevelScale/), cuja descrição é: "o aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos".


## Sugestões de Correções

- Refinar os softgoals.
- Criar ao menos 5 cartões de especificação para requisitos não-funcionais mais específicos.
- Utilizar softgoals de afirmação para ajudar o processo de refinação.
- Tomar cuidado com a verificabilidade dos requisitos ao refiná-los, evite ambiguidades.
- Reaproveitar priorizações já feitas para priorizar os RNF dos cartões.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 10/06/2023.

> <a id="REF2" href="#anchor_2">2.</a> MESQUITA, Renato Cardoso. Engenharia dos requisitos de software. Departamento de Eng. Elétrica da UFMG, Belo Horizonte, 2019. Disponível em: <https://www.cin.ufpe.br/~joa/menu_options/school/cursos/engsoft/aulas/requisitos-conceitos.pdf>. Acesso em: 10/06/2023.

> <a id="REF3" href="#anchor_3">3.</a> MAIRIZA, D.; ZOWGHI, D.; NURMULIANI, N. An investigation into the notion of non-functional requirements. In: Proceedings of the 2010 ACM Symposium on Applied Computing. ACM: [s.n.], 2010. p. 311–317.

> <a id="REF4" href="#anchor_4">4.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 10/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv) | [Gabriel Campello](https://github.com/G16C) |
