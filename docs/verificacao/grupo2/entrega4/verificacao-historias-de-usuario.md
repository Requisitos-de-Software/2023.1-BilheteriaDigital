# Verificação das Histórias de Usuário do Grupo 2

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [Histórias de Usuário](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/historiasDeUsuario/) da Etapa 3 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das [checklists](./planejamento-verificacao-e4-grupo2.md#checklists) elaboradas na página de planejamento. Para responder às perguntas apresentadas nas checklists o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

O participante sera os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) [Douglas Alves](https://github.com/dougAlvs), que será responsável por realizar a avaliação e [Geovanna Maciel](https://github.com/manuziny), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](./planejamento-verificacao-e4-grupo2.md#cronograma). 

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist para a Verificação das Histórias de Usuários.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 1   | O artefato possui introdução?  |    Sim      |             |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?|  Sim  |             |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |    Sim      |             |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? |    Sim       |      Fonte e legenda fora da norma da ABNT e duas tabelas distintas estão numeradas como Tabela 1       |
| 5   | Todos os textos estão na norma padrão?  |     Sim      |             |
| 6  | As histórias de usuários estão escritas de forma clara e concisa, com descrição do "quem", "o que" e "por que"?<a id="anchor_1" href="#REF1">^1^</a>  |   Sim     | Somente atualizar o modelo de estrutura das Histórias de Usuário com adição da linha de rastreabilidade
| 7  | Cada história de usuário possui um título auto-explicativo, isto é, que resuma o objetivo principal da história?<a id="anchor_1" href="#REF1">^1^</a>   |   Sim    |
| 8  | As histórias de usuários foram provenientes do cliente?<a id="anchor_2" href="#REF2">^2^</a>    |    Não    | Justificativa no texto
| 9  | As histórias de usuário incluem critérios de aceitação que definam o que é necessário para que a história seja considerada concluída? <a id="anchor_1" href="#REF1">^1^</a>   |   Sim    |
| 10 | As histórias de usuário são testáveis, possibilitando a verificação e validação do sistema com base nos critérios de aceitação definidos?<a id="anchor_2" href="#REF2">^2^</a>  |  Incompleto     | Justificativa no texto

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

## Lista de Problemas e Análise

Parabéns à equipe, de maneira geral o artefato está muito bom. O único problema grande é o fato de que, de acordo com o que está documentado, as histórias de usuário não tiveram nenhuma participação do cliente em sua elaboração. Além disso, os critérios de aceitação de algumas histórias estão um pouco vagos e difíceis de serem verificados, mas em contrapartida uma boa parte das histórias apresentam critérios de aceitação muito bons e testáveis.

### ID 8 - As histórias de usuários foram provenientes do cliente??

Mas metodologias ágeis, a interação entre o cliente e a equipe de desenvolvimento é um ponto chave. Dito isso, as histórias de usuário surgem como uma maneira informal de elicitar requisitos, com o cliente no centro do processo.<a id="anchor_2" href="#REF2">^2^</a> Então esse foi um ponto importante que se mostrou ausente no artefato.

### ID 10 -As histórias de usuário são testáveis, possibilitando a verificação e validação do sistema com base nos critérios de aceitação definidos??

Os critérios de aceitação devem ser escritos pelo cliente para que se possa determinar se os objetivos de uma história de usuário foram satisfeitos.<a id="anchor_1" href="#REF1">^1^</a>. Partindo desse ponto, é importante que esses critérios sejam claros e verificáveis, para que seja possível, por meio de sua definição, atestar se uma história de usuário foi "completada" ou não.

Portanto, algumas histórias do artefato ficaram com critérios de aceitação muito bem definidos, como por exemplo a US 20 (Como usuário do aplicativo, quero poder acessar uma central de ajuda para obter informações e suporte sobre o uso do aplicativo.):

* O aplicativo deve ter uma central de ajuda acessível a partir do menu do aplicativo.
* A central de ajuda deve conter informações úteis e instruções sobre o uso do aplicativo.
* O usuário deve ser capaz de pesquisar por tópicos específicos na central de ajuda.
* A central de ajuda deve fornecer opções de contato para suporte adicional, se necessário.

Contudo, outras apresentam critérios de aceitação que atuam mais como restrições para a funcionalidade relacionada, ao invés de seguir seu objetivo inicial, como a US 36 (Eu, como usuário desejo realizar um aluguel de carro com opção de devolver o carro ao mesmo local, o local da retirada do carro, da inicio e fim do aluguel e idade do condutor): 

* A idade do condutor deve ter no mínimo 20 anos
* O período de aluguel deve ter limite máximo de  11 meses
* O usuário deve selecionar somente aereportos

Eu verifiquei essa inconsistência nos critérios das US de id: 24, 26, 27, 29, 32, 33, 34, 35, 36 e 37. Dessa forma, meu conselho é que seja feita uma refatoração delasas se baseando nos critérios das outras US, que estão muito bons, por sinal.

## Sugestões de Correções

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

* Normalizar as fontes e legendas de acordo com a norma da ABNT;
* Como as histórias de usuário e o backlog já estão prontos, talvez não seja viável refaze-los do zero com a presença de um cliente. Contudo, recomendo que pelo menos seja realizada (e documentada) uma validação desses artefatos por um cliente.
* Reescrever os critérios de aceitação das histórias de usuário indicadas no ID 10 se baseando nas outras que estão melhor escritas.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.

> <a id="REF2" href="#anchor_2">2.</a>Presman, Roger S; Maxim, Bruce R. Engenharia de software. 8. ed. Bookman, 2016 p. 87-92. 

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 09/06/2023 | Criação da página. | [Douglas Alves](https://github.com/dougAlvs) | [Gabriel Campello](https://github.com/G16C) |