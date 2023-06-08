# Three Level Scale

## Introdução

Este documento é de verificação do artefato [Three Level Scale](https://requisitos-de-software.github.io/2023.1-Booking/elicitacao/threeLevelScale/) produzido pelo [Grupo 2](https://requisitos-de-software.github.io/2023.1-Booking/) que tem como foco do projeto o aplicativo Booking. A partir da literatura _Software Requirements (Developer Best Practices), 3rd Edition, Microsoft Press, 2013._ <a id="FTF1" href="#FTF1Ref">^1^</a>, o documento de Personas será verificado.

## Metodologia

Para a verificação do artefato, a metodologia escolhida será baseada no método de inspeção de Fagan. Conforme proposto por ele, essa técnica consiste em uma revisão formal dos artefatos produzidos a fim de se encontrar defeitos. Essa revisão é realizada através de uma checklist onde se tem uma lista com os defeitos mais comuns que deverão ser identificados, analisados e classificados. A checklist, baseada nas literarturas especificada acima, será composta por 5 perguntas que serão o padrão exigido para a documentação e em seguida perguntas envolvendo o conteúdo do artefato Three Level Scale. Na Tabela 1 estão expostos todas as perguntas abordadas para verficação do artefato e suas respectivas avaliações, a versão utilizada para a verificação será a 1.1, feita no dia 24 de Abril de 2023, como proposto pelo [Planejamento da Verificação da Etapa 2](adicionar_link_da_pagina_aqui).

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
| 5   | Todos os textos estão na norma padrão?                                                                |    Sim       | 
| 6   |   A priorização usando Three Level Scale levou em consideração as duas dimensões '_Importância_' e '_Urgência_'? (_Importância e Urgência: Na técnica de priorização Three Level Scale usamos as duas classificações para dividir requisitos em grupos a serem priorizados._<a id="FTF3" href="#FTF3Ref">^3^</a>)   |     Sim      |
| 7   |     Os níveis de priorização foram divididos em 3? ('Alta', 'Média' e 'Baixa')                |    Sim       |
| 8   |  Foi utilizado um modelo de quadrante para enquadrar os requistitos entre prioridade 'Alta' (primeiro quadrante), 'Média' (segundo quadrante), 'Baixa (terceiro quadrante)' e requistos propostos com nenhum valor para o projeto (quarto quadrante)? (_Requisitos do quarto quadrante: São requisitos sem valor ao projeto, se não forem importantes devem ser movidos para o terceiro quadrante ou excluidos por completo._<a id="FTF1" href="#FTF1Ref">^1^</a>)               |    Sim       |
| 9   |   A prioridade estabelecida foi incluida como um atributo para cada requisito no documento de requisitos de usuário ou em alguma base de dados de requisitos? (_Prioridade de requistos como atributo: Isso deve ser feito visto que, estabelecer uma convenção para o atributo de priorização auxilia o leitor a ter maior compreensão lógica da priorização realizada._<a id="FTF1" href="#FTF1Ref">^1^</a>)                   |   Incompleto       | Será justificado no texto.|
| 10  |   As dependências de requisitos foram levadas em consideração no processo de ranqueamento?                   |    Não       | Será justificado no texto.|
| 11  | Foi determinado um cronograma para a realização dessa priorização? | Não  | Será justificado no texto.|
| 12  | Há no documento a expecificação dos participantes e seus respectivos papéis?  | Sim  |
| 13  | Foram apresentados no documento os resultados da priorização e a gravação da reunião?  |  Sim | 

_Fonte: [Gabriel Campello](https://github.com/g16c)._

</center>

Com base na tabela preenchida, serão feitas considerações acerca de alguns itens da tabela.

#### ID 9 - A prioridade estabelecida foi incluida como um atributo para cada requisito no documento de requisitos de usuário ou em alguma base de dados de requisitos? 

Não, apesar de estar descrito nas tabelas. É importante que essa carcterítica esteja especificada como um atributo para aquele requisito, tendo em vista que serão utilizados diversas vezes no decorrer do projeto. O ideal seria adicionar o nível de prioridade já na descrição do ID ou incluir essa distribuição ao gerar um link para o requisito específico.

Essas práticas tem como objetivo facilitar a visualização do leitor, é portanto, fundamental estabelecer uma convenção para o atributo de priorização<a id="FTF1" href="#FTF1Ref">^1^</a>.

#### ID 10 - As dependências de requisitos foram levadas em consideração no processo de ranqueamento? 

Não está especificado no texto, se foi utilizado deveria estar registrado.

#### ID 11 - Foi determinado um cronograma para a realização dessa priorização? 

Apesar de terem sido definidos os papéis dos participantes, e o documento ter a gravação da reunião disponível, não há nenhuma especificação quanto o cronograma de realização dessa atividade.

## Sugestões de Melhoria

O documento no geral está muito bem redigido, [a inclusão da gravação e dos resultados da priorização utilizando os quadrantes](https://requisitos-de-software.github.io/2023.1-Booking/elicitacao/threeLevelScale/#entrevista-com-o-usuario) são diferenciais que complementam bem o artefato. No entanto há alguns pontos que requerem atenção:

- Colocar as tabelas na forma da ABNT;

- Especificar melhor o nível de prioridade de cada requisito, seja no ID seja por definição de um atributo extra em sua definição;

- Apresentar no texto se as dependÇencias foram levadas em considerção no processo de ranqueamento, visto que a ausência desse critério pode causar problemas de implementação mais adiante no trabalho.

## Referências Bibliográficas

> <a id="FTF1Ref" href="#FTF1">1.</a> Wiegers, Karl; Beatty, Joy.Software Requirements (Developer Best Practices), 3rd Edition, Microsoft Press, 2013.

## Histórico de Versões

Versão  | Data | Descrição | Autor(es) | Revisor(es)
-------- | ------ | ------ | ---------- | ----------
`1.0` | 08/06/2023 | Criação do Documento | [Gabriel Campello](https://github.com/g16c) | [Sidney Fernando](https://github.com/nando3d3)