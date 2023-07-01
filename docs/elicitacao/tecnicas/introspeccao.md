# Introspecção

## Introdução

A introspecção é uma técnica de elicitação de requisitos que consiste em, por meio de uma análise pessoal e profunda, levantar o que é indispensável para software de tal natureza. Sendo assim, o responsável por realizar essa estratégia deve devanear uma situação hipotética na qual se realizaria uma determinada tarefa. Isso posto, os requisitos elicitados estão demonstrados na Tabela 1 e na Tabela 2.

## Metodologia

O processo de introspecção foi realizado individualmente pelos alunos [Arthur de Melo](https://github.com/arthurmlv) e [Gabriel Campello](https://github.com/G16C). Após esse desenvolvimento individual, os requisitos elicitados foram integrados em duas tabelas, Tabela 1 para Requisitos Funcionais e Tabela 2 para Requisitos Não-Funcionais. No fim desse processo revisitamos o aplicativo escolhido pelo grupo e avaliamos se os requisitos elicitados estavam ou não presentes. A seguir são apresentados os participantes e o cronograma de aplicação da técnica.

### Cronograma

<font size="3"><p style="text-align: center">Tabela 1: Participantes.</p></font>

<center>

| Nome                                             | Data                   |  Hora |
| ------------------------------------------------ | ------------------------ | -------------- |
| [Arthur de Melo](https://github.com/arthurmlv)   |  26/04/2023|  18:30 |
| [Gabriel Campello](https://github.com/G16C) |  26/04/2023|   21:00 |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

### [Arthur de Melo](https://github.com/arthurmlv)

Para a execução desse método, imaginei-me em uma situação na qual eu desejasse participar de um evento na minha cidade. Portanto, eu, enquanto usuário e sem visualizar o aplicativo, imaginei as funções que seriam necessárias para a realização dessa tarefa. Também mantive em mente as possíveis dificuldades enfrentadas e o que o aplicativo deveria ofertar para a solução dessas.

### [Gabriel Campello](https://github.com/G16C)

O processo de introspecção para elicitação de requisitos consiste em imaginar-se na posição de usuário de certo produto sem vizualizá-lo. Quando o processo de elicitação é iniciado precisamos ter em mente quais requisitos (funcionais e não funcionais) o produto em questão deve apresentar. Tendo em vista que o produto escolhido para a disciplina trata-se de um aplicativo para compra de ingressos, imaginei-me como usuário, e tendo a noção prévia de aplicativos concorrentes,
iniciei o exercício.

## Requisitos elicitados

### Funcionais

Legenda das Tabelas 2 e 3:

- RFx: Requisito Funcional nºx
- RNFx: Requisito Não-Funcional nºx
- ISx: Requisito nºx elicitado pela introspecção.

<font size="3"><p style="text-align: center">Tabela 2: Requisitos Funcionais.</p></font>

<center>

| Tipo | Descrição                                                   | <a id="anchor_IS" style="visibility: hidden;"></a> ID | Implementado |
| ---- | ----------------------------------------------------------- | ----------------------------------------------------- | ------------ |
| RF01 | O aplicativo filtra os eventos por Estado e por Município.  | IS01                                                  | Não          |
| RF02 | O aplicativo filtra os eventos por data e por horário.      | IS02                                                  | Não          |
| RF03 | O aplicativo filtra os eventos por idade mínima de entrada. | IS03                                                  | Não          |
| RF04 | O aplicativo permite realizar a compra do ingresso.         | IS04                                                  | Sim          |
| RF05 | O aplicativo permite o cadastro e o login do usuário.       | IS05                                                  | Sim          |
| RF06 | O aplicativo permite excluir cadastro.                      | IS06                                                  | Sim          |
| RF07 | O aplicativo permite cadastrar métodos de pagamento.        | IS07                                                  | Não          |
| RF08 | O aplicativo permite cancelar compras.                      | IS08                                                  | Sim          |
| RF09 | O aplicativo possui um mecanismo de busca.                  | IS09                                                  | Sim          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Gabriel Campello](https://github.com/G16C).</p></font>

Vale ressaltar que os requisitos RF01 e RF02, presentes na Tabela 2, estão parcialmente implementados pelo aplicativo, dado que o aplicativo filtra somente por estado e por data. O que não inclui a filtragem por Município e por horário.

### Não funcionais

<font size="3"><p style="text-align: center">Tabela 3: Requisitos Não-Funcionais.</p></font>

<center>

| Tipo  | Descrição                                                                                                                         | <a id="anchor_ISNF" style="visibility: hidden;"></a>ID | Implementado |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------ | ------------ |
| RNF01 | Deve possuir uma página que explicita os eventos da região selecionada.                                                           | IS10                                                   | Sim          |
| RNF02 | Todo evento disponibilizado na tela de busca deve aparecer a data, o local e o preço do ingresso.                                 | IS11                                                   | Não          |
| RNF03 | Deve possuir uma tela de dúvidas frequentes e uma central de ajuda.                                                               | IS12                                                   | Sim          |
| RNF04 | Deve possuir uma tela de aviso sobre o início/fim de venda de ingressos para um dado evento.                                      | IS13                                                   | Não          |
| RNF05 | Deve possuir espaço para a solicitação de atendimento especial para idosos/deficientes durante o processo de compra de ingressos. | IS14                                                   | Não          |
| RNF06 | Deve possuir uma tela para cadastro e login.                                                                                      | IS15                                                   | Sim          |
| RNF07 | Deve possuir uma área para os usuários reportarem erros de funcionamento do aplicativo.                                           | IS16                                                   | Não          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Arthur de Melo](https://github.com/arthurmlv) e [Gabriel Campello](https://github.com/G16C).</p></font>

Na Tabela 3, o requisito RNF02 é marcado como não implementado, no entanto, esse requisito foi apenas parcialmente implementado pelo aplicativo, que disponibiliza somente a data e o local na página de busca.

!!! info
    Os requisitos elicitados por essa técnica podem divergir dos demais, tendo em vista que é uma técnica aplicada por participantes do projeto por sua definição.

## Bibliografia

> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. **UnB Gama**, Brasília, 2023. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2580553/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf>>. Acesso em: 26/04/2023.

## Histórico de Versões

| Versão | Data       | Descrição                                     | Autor(es)                                      | Revisor(es)                                      |
| ------ | ---------- | --------------------------------------------- | ---------------------------------------------- | ------------------------------------------------ |
| 1.0    | 26/04/2023 | Introdução e requisitos iniciais              | [Arthur de Melo](https://github.com/arthurmlv) | [Gabriel Campello](https://github.com/G16C)      |
| 1.1    | 26/04/2023 | Requisitos atualizados                        | [Gabriel Campello](https://github.com/G16C)    | [Arthur de Melo](https://github.com/arthurmlv)   |
| 1.2    | 27/04/2023 | Metodologia usada e verificação de requisitos | [Gabriel Campello](https://github.com/G16C)    | [Arthur de Melo](https://github.com/arthurmlv)   |
| 1.3    | 27/04/2023 | Notas sobre alguns requisitos específicos     | [Arthur de Melo](https://github.com/arthurmlv) | [Matheus Henrique](https://github.com/mathonaut) |
| 1.4    | 29/04/2023 | Adição das legendas                           | [Arthur de Melo](https://github.com/arthurmlv) | [Sidney Fernando](https://github.com/nando3d3)   |
| 1.5    | 01/07/2023 | Retrabalho                           | [Arthur de Melo](https://github.com/arthurmlv) | [Sidney Fernando](https://github.com/nando3d3)   |
