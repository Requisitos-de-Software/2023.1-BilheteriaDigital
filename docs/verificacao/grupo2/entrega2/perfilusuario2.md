# Perfil de Usuário

## Introdução

Este documento é de verificação do artefato [Perfil de Usuário](https://requisitos-de-software.github.io/2023.1-Booking/elicitacao/perfilDeUsuario/) produzido pelo [Grupo 2](https://requisitos-de-software.github.io/2023.1-Booking/) que tem como foco do projeto o aplicativo Booking. A partir da literatura _About Face: The Essentials of Interaction Design_ <a id="FTF1" href="#FTF1Ref">^1^</a> e _Interação Humano-Computador_ <a id="FTF2" href="#FTF2Ref">^2^</a>, o documento de Perfil de Usuário será verificado.

## Metodologia

Para a verificação do artefato, a metodologia escolhida será baseada no método de inspeção de Fagan. Conforme proposto por ele, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos. Essa revisão é realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados. A checklist, baseada nas literarturas especificada acima, será composta por 5 perguntas que serão o padrão exigido para a documentação e em seguida perguntas envolvendo o conteúdo do artefato Perfil de Usuário. Na Tabela 1 estão expostos todas as perguntas abordadas para verficação do artefato e suas respectivas avaliações, a versão utilizada para a verificação será a 1.1, feita no dia 10 de Maio de 2023, como proposto pelo [Planejamento da Verificação da Etapa 2](adicionar_link_da_pagina_aqui).

## Desenvolvimento

Na tabela 1, os campos de "Avaliação" e "Observações" representam respectivamente os resultados, sendo possível identificar os tópicos faltantes e/ou concluídos, e a indicação de haverá uma discussão posterior a respeito do item. Para tal será utilizado o ID da pergunta.

<center>

**Tabela 1** - Checklist preenchido.

| ID  | Descrição                                                                                              | Avaliação | Observação |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | --------- |
| 1   | O artefato possui Introdução?                                                                          |    Sim       |     |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?                                           |    Sim       |   |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |     Sim      |  |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           |     Sim      | Estão distribuídas fora da norma ANBT. |
| 5   | Todos os textos estão na norma padrão?                                                                 |    Não       | Será justificado no texto. |
| 6  |         O perfil de usuário identifica características de interesse como cargo, função, experiência, nível de instrução, atividades principais, faixa etária, relação com tecnologia, conhecimento do domínio do produto, principais tarefas realizadas, entre outras?                                                                  |    Incompleto       | Será justificado no texto. |
| 7   | Os dados para o perfil de usuário foram coletados por meio de algum estudo, como entrevistas ou questionários?  |     Sim      |
| 8   |   Os perfis de usuário são agrupados por faixa etária, experiência com o produto, atitude perante tecnologia e tarefas primárias no sistema?        |     Sim      |
| 9   |   As porcentagens de usuários em cada faixa de características foram determinadas?                                                              |     Sim      | Foram determinadas, no entanto há uma discrepância nos dados obtidos nas figuras e o que foi apresentado na conclusão. |

_Fonte: [Gabriel Campello](https://github.com/g16c)._

</center>

Com base na tabela preenchida, serão feitas considerações acerca de alguns itens da tabela.

#### ID 5 - Todos os textos estão na norma padrão?

Não, há alguns erros gramaticais. Como por exemplo, no techo: 

' Quanto tempo antes da viagem você costuma fazer sua reserva pelo Booking.com?, é possivel notar que os dados são mais distribuidos, porém existem mais pessoas que fazem sua reserva entre 1 e 4 semanas de antecedência. ' 

Essa vírgula não deveria estar após a interrogação.

#### ID 6 - O perfil de usuário identifica características de interesse como cargo, função, experiência, nível de instrução, atividades principais, faixa etária, relação com tecnologia, conhecimento do domínio do produto, principais tarefas realizadas, entre outras?

Faltou especificar no questionário utilizado alguns item listados na questão. Apesar de especificar a frequência em que os usuários usam o aplicativo, não foi registardo a relação destes com a tecnologia, nem as principais tarefas que o usuário realiza no app. O usuário por muitas vezes pode acessar o app somente para consultar preços.


## Sugestões de Melhoria

Apesar da grande quantidade de informações, o artefato esté bem bacana e as pesquisas utilizadas são um diferencial e dão uma profundidade muito interessante ao documento. De sugestões de melhorias ficam:

- Colocar as figuras na norma ABNT;

- Corrigir erros gramaticais;

- Revisar os dados das figuras, a fim de traçar um perfil de usuário mais bem definido. Da forma como está na conclusão ficou muito generalizado, o que dificultaria o processo de elicitação e priorização de requisitos, além de induzir a criação de personas muito elásticas. (_Elasticidade: é quando uma persona acaba por ter características muito generalizadas. Assim, uma persona elática pode induzir a equipe de desenvolvimento de projeto a seguir cainhos incorretos ou menos produtivos para a concepção do produto._<a id="FTF1" href="#FTF1Ref">^1^</a>  )

## Referências Bibliográficas 

> <a id="FTF1Ref" href="#FTF1">1.</a> COOPER, Alan; REIMANN, Robert; CRONIN, Dave. About Face: The Essentials of Interaction Design.

> <a id="FTF2Ref" href="#FTF2">2.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

Versão  | Data | Descrição | Autor(es) | Revisor(es)
-------- | ------ | ------ | ---------- | ----------
`1.0` | 07/06/2023 | Criação do Documento | [Gabriel Campello](https://github.com/g16c) | [Sidney Fernando](https://github.com/nando3d3)