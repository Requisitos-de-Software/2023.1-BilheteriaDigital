# Verificação dos Léxicos do Grupo 2

## Introdução

Realizado o planejamento do que verificar, é o momento de realizar a inspeção em si. Esse documento apresenta os objetivos da verificação, a metodologia utilizada e os dados da verificação. Além disso, os principais problemas encontrados são sumarizados e analisados obtendo informações valiosas que serão utilizadas para sugerir ações corretivas para os mesmos.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas em cima do artefato dos [Léxicos](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/lexicos/) da Etapa 3 do [Grupo 2](https://github.com/Requisitos-de-Software/2023.1-Booking).

## Metodologia

Os resultados da verificação do artefato foram obtidos a partir das checklists elaboradas na página de [planejamento](../planejamento-verificacao-e3-grupo2). Para responder às perguntas apresentadas nas checklist o avaliador usará as opções **Sim**, **Não**, **Incompleto** ou **Não se aplica**. O avaliador poderá também escrever observações em cada pergunta detalhando pontos que achar necessários. A checklist foi feita com base em uma publicação de Julio Cesar Sampaio do Prado Leite<a id="anchor_1" href="#REF1">^1^</a>.

## Cronograma e Participantes

Os participantes serão os integrantes do [Grupo 1](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital): [Arthur de Melo](https://github.com/arthurmlv), que será responsável por realizar a avaliação e [Rafael Ferreira](https://github.com/RafaelCLG0), que realizará a revisão do artefato produzido pelo avaliador. Em relação ao cronograma seguido, ele já foi explicitado na página de [planejamento](../planejamento-verificacao-e3-grupo2).

## Sumário Dos Dados

A Tabela 1 apresenta a checklist com os dados obtidos a partir da verificação.

<center>

**Tabela 1** - Checklist de Verificação.

|  ID | Descrição                                                                                              | Avaliação     | Observações                                     |
| --- | ------------------------------------------------------------------------------------------------------ | ------------- | ----------------------------------------------- |
|  1  | O artefato possui introdução?                                                                          | Sim           |                                                 |
|  2  | O artefato possui uma bibliografia/referência bibliográfica?                                           | Sim           |                                                 |
|  3  | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores? | Sim           |                                                 |
|  4  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes?                           | Sim           | Estão fora de ordem.                                           |
|  5  | Todos os textos estão na norma padrão?                                                                 | Não           | [Clique aqui para ver como citar tabela nas normas ABNT](https://normas-abnt.espm.br/index.php?title=Tabelas)           |
| 6   | Cada símbolo possui classificação, sinônimo, noção e impacto?                                          | Sim           |             |
| 7   | Cada símbolo apresenta sua noção de forma breve e compreensível?                                       | Não           |             |
| 8   | Cada símbolo apresenta seu impacto de forma breve e compreensível?                                     | Não          |             |
| 9   | Caso seja do tipo Estado, as definições de noção e de impacto se encaixam com o que é descrito?           | Não          |             |
| 10  | Caso seja do tipo Verbo, as definições de noção e de impacto se encaixam com o que é descrito?            | Não          |             |
| 11  | Caso seja do tipo Objeto, as definições de noção e de impacto se encaixam com o que é descrito?           | Incompleto          |             |
| 12  | O princípio circular foi devidamente propagado?                                                        | Não          |             |
| 13  | A descrição dos léxicos é coerente e esclarecedora?                                                    | Incompleto          |             |
| 14  | O vocabulário mínimo foi apropriadamente adotado nas descrições?                                       | Sim          |             |
| 15  | Quanto à organização dos léxicos, eles respeitam sua ordem numérica?                                   | Não          | Arrumar o número das tabelas e dos léxicos.    |

_Fonte: [Arthur de Melo](https://github.com/arthurmlv), 2023._

</center>

## Lista de Problemas e Análise

Primeiramente, parabéns a equipe pela entrega do artefato, a maioria dos problemas estão relacionados a como os requisitos são especificados deixando em muitos casos eles ambíguos. Muitos dos léxicos estão até mesmo repetidos.

### ID 7 e 9 - Cada símbolo apresenta sua noção de forma breve e compreensível? Caso seja do tipo Estado, as definições de noção e de impacto se encaixam com o que é descrito?

Por exemplo, na descrição do [Léxico 07 - Premium](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/lexicos/#l07-premium), a noção do léxico é descrita como: "uma condição que o usuario pode comprar para ter acesso a funcionalidade exclusivas ou prioridade no aplicativo". A ausência de paralelismo sintético dificulta o entendimento do conceito e a noção ainda tenta explicar o impacto de forma desnecessária. A noção é a própria denotação do símbolo, ou seja, o que significa. No caso, o símbolo é um Estado, logo o esperado na descrição de tal é: "o que significa e quais ações levaram a esse estado". Em alguns casos, as noções podem ser divididas em duas ou mais para simplificar algo que seria muito difícil de se explicar em uma só noção<a id="anchor_1" href="#REF1">^1^</a>. 

### ID's 8 e 10 - Cada símbolo apresenta seu impacto de forma breve e compreensível? Caso seja do tipo Verbo, as definições de noção e de impacto se encaixam com o que é descrito?

Por exemplo, na descrição do [Léxico 11 - Busca](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/lexicos/#l11-busca), o impacto do léxico é descrito como: "A busca é a primeira etapa para que o usuário possa encontrar e reservar acomodações ou atividades de interesse, portanto, é fundamental para a usabilidade do aplicativo". No entanto, essa não se caracteriza como impacto de um léxico do tipo Verbo, que deve se encaixar na seguinte definição: "quais os reflexos da ação no ambiente e quais os novos estados decorrentes". Nesse caso, também pode se dividir os impactos em dois ou mais para melhor compreensão. Além disso, a vigente descrição do impacto não fornece nenhuma informação útil sobre o símbolo. Já a noção de tal também está errada, dado que, enquanto Verbo, a noção deve ser: "quem realiza, quando acontece e quais os procedimentos envolvidos"<a id="anchor_1" href="#REF1">^1^</a>.

### ID 10 - Caso seja do tipo Objeto, as definições de noção e de impacto se encaixam com o que é descrito?

No caso da noção, é representada parcialmente a definição real no caso do tipo Objeto. Por exemplo, no [Léxico 08 - Idioma](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/lexicos/#l08-idioma_), o objeto é definido, mas não se identifica com quais outros objetos o léxico se relaciona. Portanto, vale a seguinte definição para a noção do Objeto: "definir o objeto e identificar outros objetos com os quais se relaciona"<a id="anchor_1" href="#REF1">^1^</a>. 

### ID 11 - O princípio circular foi devidamente propagado?

Mesmo que este tenha sido citado na metodologia, nenhum dos léxicos comunica com os outros, sequer são referenciados.

### ID 13 - A descrição dos léxicos é coerente e esclarecedora?

Em alguns casos, o grupo conseguiu esclarecer de forma concisa. Entretanto, grande parte dos símbolos, principalmente na noção e no impacto, foi explicada de forma prolixa e sem informações úteis que se encaixam na definição.

## Sugestões de Correções

- Revisar as definições de Noção e de Impacto para cada classificação de símbolo.
- Dividir as noções e os impactos em duas ou mais para simplificar.
- Relacionar os léxicos já criado com os outros, por exemplo, o Usuário pode se encaixar em diversos deles. As ações realizadas pelo usuário foram simplificadas demais na apresentação de seu impacto e de sua noção, explicite as interações em diferentes impactos e noções.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> LEITE, Julio Cesar. Léxico Ampliado da Linguagem, 2012. Disponível em: <<https://www-di.inf.puc-rio.br/~julio/lal.pdf>>. Acesso em: 10/06/2023.

## Histórico de Versões

| Versão | Data       | Descrição          | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | ------------------ | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 10/06/2023 | Criação da página. | [Arthur de Melo](https://github.com/arthurmlv) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
