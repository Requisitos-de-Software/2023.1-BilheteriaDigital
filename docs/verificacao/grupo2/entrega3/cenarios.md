# Verificação dos Cenários do Grupo 2

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas acerca do artefato [Cenários](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/cenarios/) da Etapa 3 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das [checklists](./planejamento-verificacao-e3-grupo2.md#checklists) elaboradas na página de planejamento. Para responder às perguntas apresentadas nas checklists o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital) [Douglas Alves](https://github.com/dougAlvs), que será responsável por realizar a avaliação e [Gabriel Campello](https://github.com/G16C), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](./planejamento-verificacao-e3-grupo2.md#cronograma). 

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist para a Verificação dos Cenários.

| ID  | Descrição                                                                                              | Avaliação | Observações |
| --- | ------------------------------------------------------------------------------------------------------ | --------- | ----------- |
| 1   | O artefato possui introdução? |      Sim     |             |
| 2   | O artefato possui uma bibliografia/referência bibliográfica?   |     Sim      |             |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? |    Sim       |             |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? |     Sim      |      Fonte e legenda fora da norma da ABNT       |
| 5   | Todos os textos estão na norma padrão? |     sim      |             |
| 6   | O cenário possui: título, metas/objetivos, contexto, ator(es), recursos, exceções, restrições e episódios?<a id="anchor_1" href="#REF1">^1^</a>  |     Sim      |            |
| 7   | O título do cenário é autoexplicativo?<a id="anchor_2" href="#REF2">^2^</a>  |     Sim      |      Justificativa no texto       |
| 8   | O objetivo do cenário é condizente com seu título?<a id="anchor_2" href="#REF2">^2^</a> |     Incompleto      |      Justificativa no texto       |
| 9   | O contexto descreve de forma sucinta o estado inicial do cenário? Em função de local, tempo e pré-condições, por exemplo <a id="anchor_1" href="#REF1">^1^</a>       |     Não      |      Justificativa no texto       |
| 10   | O cenário descreve situações realistas e relevantes de interação do sistema?<a id="anchor_1" href="#REF1">^5^</a>      |     Sim      |             |
| 11   | Os atores são condizentes com o contexto do cenário? <a id="anchor_2" href="#REF2">^2^</a>|     Sim      |       Justificativa no texto       |
| 12   | Os episódios do cenário estão coerentes e seguem uma ordem lógica para atingir o objetivo? <a id="anchor_2" href="#REF2">^2^</a>|     Sim      |             |
| 13   | Existe uma ligação entre os cenários e os léxicos?<a id="anchor_2" href="#REF2">^2^</a> |     Não      |       Justificativa no texto      |

_Fonte: [Douglas Alves](https://github.com/dougAlvs), 2023._

</center>

## Lista de Problemas e Análise

Parabéns à equipe, de forma geral o artefato está muito bom e a maior parte dos problemas encontrados só aparece em alguns cenários isolados, com exceção da descrição do contexto.

### ID 7 - O título do cenário é autoexplicativo?

Praticamente todos os cenários apresentam títulos autoexplicativos. Contudo, o Cenário 06 não, o título "Configuração de Perfil" é muito amplo e pode envolver diversos cenários distintos em uma aplicação. Dito isso, o título poderia ser modificado para abranger um cenário mais específico, ou até mesmo ser subdividido em outros cenários que envolvam modificar/visualizar determinada informação do perfil.

### ID 8 - O objetivo do cenário é condizente com seu título?

Praticamente todos os cenários apresentam objetivos condizentes com seus títulos. Contudo, o Cenário 06 (Configuração de Perfil) não, enquanto seu título remete a algo amplo, seu objetivo "Modificar dados do perfil de usuário e adicionar cartão de crédito para configurar perfil para viagens" envolve uma coisa mais específica (adicionar cartão de crédito). Dessa maneira, seu título poderia ser modificado para especificar melhor o objetivo de adicionar o cartão de crédito

### ID 9 - O contexto descreve de forma sucinta o estado inicial do cenário? Em função de local, tempo e pré-condições, por exemplo.

O contexto de um cenário é de suma importância, pois não somente descreve seu local de ocorrência, mas também o seu estado inicial e muitas vezes as motivações para sua ocorrência.<a id="anchor_2" href="#REF2">^2^</a>. Sendo assim, pegando como exemplo o contexto do Cenário 07 (Deletar Conta):

* Local: Casa
* Tempo: Ensolarado
* Pré-condições: Possuir conta no booking.com e internet.

Pode-se observar que o contexto em questão acaba sendo um pouco pobre em informações e vago, principalmente no que diz respeito ao estado inicial e motivações. Portanto, seria interessante modificar o contexto dos cenários de maneira que eles tragam mais informações sobre o estado inicial específico da aplicação.

### ID 11 - Os atores são condizentes com o contexto do cenário?

Os atores descritos nos cenários estão sim condizentes com o contexto, contudo poderia haver uma padronização entre eles, visto que em alguns momentos é utilizado o termo "Viajante" enquanto em outros é utilizado "Usuário do Aplicativo".

### ID 13 - Existe uma ligação entre os cenários e os léxicos?

No contexto da Engenharia de Requisitos, cenários são naturalmente ligados ao Léxico Ampliado da Linguagem. Isso pois os primeiros são,em suma, uma descrição evolutiva de situações em um domínio em específico<a id="anchor_2" href="#REF2">^2^</a>, enquanto o segundo é um metamodelo projetado justamente para ajudar a entender a linguagem de um determinado domínio. <a id="anchor_1" href="#REF1">^1^</a>. Dito isso, fazer a ponte entre os termos usados nos cenários e seus respectivos léxicos enriqueceria bastante o artefato e facilitaria o seu entendimento por outras pessoas.

## Sugestões de Correções

Tendo em vista os problemas abordados anteriormente, fica como sugestão a realização das seguintes correções:

* Normalizar as fontes e legendas de acordo com a norma da ABNT;
* Subdividir o Cenário 06 em outros mais ou modificar seu nome para deixá-lo mais específico;
* Reescrever os contextos dos cenários de forma que eles agreguem mais conteúdo ao artefato, sobretudo em relação à motivações e ao estado inicial.
* Normalizar o termo usado para descrever o ator "padrão" dos cenários (ou "Viajante" ou "Usuário do aplicativo").
* Estabelecer uma ligação entre os termos usados nos cenários e os léxicos correspondentes.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a>BERGMANN, Ulf. Evolução de Cenários Através de um Mecanismo de Rastreamento Baseado em Transformações. 2003. Tese de Doutorado (Departamento de Informática) - Pontifícia Universidade Católica do Rio de Janeiro, [S. l.], 2003. p. 47-50.

> <a id="REF2" href="#anchor_2">2.</a>Leite, J.C.S.d.P., Rossi, G., Balaguer, F. et al. Enhancing a requirements baseline with scenarios. Requirements Eng 2, 44–53 (1997).

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 08/06/2023 | Criação da página. | [Douglas Alves](https://github.com/dougAlvs) | [Gabriel Campello](https://github.com/G16C) |
| `1.1`  | 09/06/2023 | Att justificativa id 9. | [Douglas Alves](https://github.com/dougAlvs) | [Gabriel Campello](https://github.com/G16C) |