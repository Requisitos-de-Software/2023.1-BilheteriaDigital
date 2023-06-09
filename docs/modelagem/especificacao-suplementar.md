# Especificação Suplementar

## Introdução

Especificação Suplementar pode ser definida como um documento em linguagem natural no qual são descritos os requisitos num sistema.<a id="anchor_1" href="#REF1">^1^</a> Ela é complementar aos [casos de uso](../modelagem/useCase.md), pois ela captura os requisitos do sistema que não foram elicitados no método anterior. Entre os requisitos capturados estão incluídos: Requisitos legais e de regulamentação, padrões de aplicativos, atributos de qualidade, requisitos de utilidade, confiabilidade, desempenho, suportabilidade e outros requisitos como sistemas e ambientes operacionais, requisitos de compatibilidade e restrições de design. A metodologia mais utilizada para a produção de uma especificação suplementar é a FURPS+.

## Finalidade

A finalidade deste artefato é definir os requisitos do sistema da Bilheteria Digital.

## Escopo

O objetivo da BILHETERIA DIGITAL PROMOCAO E ENTRETENIMENTO LTDA é facilitar o mercado nacional de venda de ingressos, sistemas de acompanhamento de vendas e controle de acesso.

## Metodologia

Para a produção desse artefato será utilizado uma versão modificada do FURPS+, que é uma metodologia na qual os requisitos são dividido nas seguintes categorias: F de Functionality (Funcionalidade), U de Usability (Usabilidade), R de Reliability (Confiabilidade), P de Performance (Desempenho), S de Supportability (Suportabilidade) e + que engloba outros requisitos não-funcionais (Requisitos de design, Requisitos de implementação, Requisitos de interface e Requisitos físicos). Nessa versão os requisitos de interface, além da seção de componentes adquiridos serão omitidos, dado que são atributos já especificados em outros artefatos, como os requisitos não-funcionais elicitados pelas técnicas de [Observação](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/observacao/), de [Introspecção](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/introspeccao/), de [Questionário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/questionario/) e de [Brainstorming](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/elicitacao/tecnicas/brainstorming/).

## Funcionalidade

Os requisitos funcionais foram elicitados na seção de elicitação e a [tabela 1](../../elicitacao/requisitos_elicitados/#tab_1) da página de [requisitos elicitados](../../elicitacao/requisitos_elicitados/) demonstra todos os requisitos priorizados.

## Usabilidade

Diz respeito ao quão fácil é para o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) realizar uma tarefa com a aplicação.

Para essa categoria os requisitos identificados estão representados na tabela 1 a seguir.

<font><p style="text-align: center">**Tabela 1** - Requisitos de Usabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                                |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| USA01 | O sistema deve apresentar cores compatíveis com a opção de alto contraste, e os botões das ações principais ou críticas devem ser de cor vermelha.                          |
| USA02 | O sistema deve possuir recursos de acessibilidade como teclado virtual, [mudar idioma](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l06-mudar-idioma), opção de alto contraste, aumento de fonte e audiodescrição.      |
| USA03 | O sistema deve dar feedback ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario), com pop ups e mensagens, por exemplo, ao [notificar eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l04-notificar-eventos) e ao [sugerir eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l02-sugestoes-de-eventos).                                                                         |
| USA04 | O sistema deve possuir caminhos curtos, com tarefas complexas sendo finalizadas em no máximo 7 cliques.                                   |
| USA05 | O sistema deve fornecer no mínimo as quatro principais formas de pagamentos: Boleto Bancário, Pix, Cartão de crédito e Cartão de débito. |
| USA06 | O sistema deve evitar que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) realize passos repetitivos.                                                                          |

</center>

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Confiabilidade

Diz respeito ao quão confiável é o sistema, ou seja, qual é a frequência de falhas, possibilidade de recuperação e prevenção e tempo entre as falhas.

Para essa categoria os requisitos identificados estão representados na tabela 2 a seguir.

<font><p style="text-align: center">**Tabela 2** - Requisitos de Confiabilidade.</p></font>

<center>

| ID    | Descrição                                                                                                                         |
| ----- | --------------------------------------------------------------------------------------------------------------------------------- |
| CON01 | O sistema deve ser acessível 24 horas por dia, 7 dias por semana.                                                                 |
| CON02 | O sistema deve possuir as informações atualizadas e condizentes com a realidade.                                                  |
| CON03 | O sistema deve manter íntegra as informações sobre o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) e seus meios de pagamentos.                                          |
| CON04 | O sistema deve seguir a Lei Geral de Proteção de Dados (LGPD).                                                                    |
| CON05 | O sistema deve permitir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) se recupere de problemas e erros com no máximo 3 cliques.                                   |
| CON06 | O sistema deve deixar claro e de fácil acesso toda e qualquer informação sobre taxas aplicada aos [usuários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario).                       |
| CON07 | O sistema deve possuir backups dos dados dos [usuários](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) e eventos.                                                                  |
| CON08 | O sistema deve impedir que o [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) realize atividades que possa colocar a integridade do sistema e de outros usuários em risco. |
| CON09 | O sistema deve ser distribuído em diversos servidores.                                                                            |

</center>

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Desempenho

Diz respeito às condições que os requisitos devem operar. A velocidade, limites superiores e inferiores, tempo de resposta, restrições de interface e de funções, etc.

Para essa categoria os requisitos identificados estão representados na tabela 3 a seguir.

<font><p style="text-align: center">**Tabela 3** - Requisitos de Desempenho.</p></font>

| ID    | Descrição                                                                                          |
| ----- | -------------------------------------------------------------------------------------------------- |
| DES01 | O sistema deve, mostrar como padrão no máximo 20 eventos por página, por exemplo, ao fazer uma busca com [filtragem de eventos](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l01-filtrar-eventos).                               |
| DES02 | O sistema não deve ter um tempo de resposta superior a 200ms.                                      |
| DES03 | O sistema deve permitir mais de 1 milhão requisições por segundo.                                  |
| DES04 | O sistema deve possuir uma navegação fluida, sem engasgo e caminhos seguindo uma sequência lógica. |
| DES05 | O sistema deve possuir uma interface leve, com no máximo 30 elementos na tela de uma vez.          |

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Suportabilidade

Envolve os requisitos relacionados ao suporte e manutenção do sistema. Isso inclui requisitos relacionados à facilidade de manutenção, capacidade de ser modificado e atualizado, documentação adequada, facilidade de teste e diagnóstico de problemas.

Para essa categoria os requisitos identificados estão representados na tabela 4 a seguir.

<font><p style="text-align: center">**Tabela 4** - Requisitos de Suportabilidade.</p></font>

| ID    | Descrição                                                                                                                                                                                                                                                                  |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| SUP01 | O sistema deve possuir uma documentação separada em tópicos (ao menos 10 tópicos principais) e que apresente grande parte das dúvidas mais frequentes.                                                                                                                                                                        |
| SUP02 | O sistema deve possuir uma facilidade de manutenção através de uma estrutura modular e código bem organizado.                                                                                                                                                              |
| SUP03 | O sistema deve possuir uma capacidade de extensão para adicionar novas funcionalidades e acompanhar as mudanças.                                                                                                                                                           |
| SUP04 | O sistema deve possuir uma facilidade de atualização com processos eficientes (de até 200ms) e sem interrupções significativas, que ultrapassem o tempo limite de resposta.                                                                                                                                                           |
| SUP05 | O sistema deve possuir um suporte ao [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) com canais adequados de suporte e equipe disponível.                                                                                                                                                                          |
| SUP06 | O sistema deve possuir uma testabilidade, com facilidade de realização de testes durante o desenvolvimento e a manutenção.                                                                                                                                                 |
| SUP07 | O sistema deve possuir uma rastreabilidade com mecanismos para registrar e rastrear mudanças e correções ao longo do tempo, incluindo controle de versão e registros de alterações.                                                                                        |
| SUP08 | O sistema deve possuir uma tolerância a falhas para garantir que o sistema possa lidar com falhas adequadamente, por meio de mecanismos de recuperação, detecção de falhas, manutenção da integridade dos dados, backups regulares e restauração rápida em caso de falhas. |

<font size="3"><p style="text-align: center">Fonte: [Rafael Ferreira](https://github.com/RafaelCLG0).</p></font>

## Restrições de Design

O design do sistema deverá seguir os padrões de boas práticas utilizadas atualmente pela indústria, como os padrões de interface dos dispositivos mobile iOS e Android, arquitetura limpa, microserviços e componentização. Além disso, o design deve utilizar cores que permitam que pessoas com restrições como o daltonismo consiga distinguir elementos, mas sem que ocorra a perda da identidade visual da marca.

## Requisitos de Implementação

Eles específica ou restringe o código ou a construção de um sistema.<a id="anchor_2" href="#REF2">^2^</a>

O sistema deve ser construído em C++/C#, Python, Javascript (tipado com TypeScript), Kotlin e Swift.

O sistema deve ser implementado nos sistemas iOS 11.0 ou posterior e Android 5.0 ou superior.

Os recursos necessários para a aplicação são: mínimo de 50 mb de armazenamento e 1,5 GB de memória ram. Recursos adicionais devem ser consultados nos manuais dos mantenedores dos sistemas operacionais, para o [iOS](https://support.apple.com/en-us/HT209574) e para o [Android](https://source.android.com/compatibility/10/android-10-cdd.pdf).

## Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line

Para essa categoria os requisitos identificados estão representados na tabela 5 a seguir.

<font><p style="text-align: center">**Tabela 5** - Requisitos de Sistema de Ajuda e de Documentação de Usuário On-line.</p></font>

<center>

| ID    | Descrição                                                                                                                                            |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| RAU01 | O sistema deve disponibilizar uma seção com as perguntas e respostas mais frequentes.                                                                |
| RAU02 | O tempo de resposta para um pedido de ajuda do [usuário](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/lexicos/#l05-usuario) não pode ultrapassar 1 dia.                                                                   |
| RAU03 | O sistema não pode ter mais de 20 aberturas de chamados de problemas para cada 100 compras.                                                          |
| RAU04 | O sistema deve permitir a resolução dos problemas mais comuns na compra de ingresso, como reembolso e troca de dados sem a intervenção de um humano. |

</center>

<font size="3"><p style="text-align: center">Fonte: [Matheus Henrique](https://github.com/mathonaut).</p></font>

## Requisitos de Licenciamento

O sistema deve restringir o uso através de termos de uso.

## Observações Legais, de Copyright e Outras

O sistema está sujeito à lei dos direitos autorais, portanto, para a utilização de outras marcas será necessário uma autorização prévia dos envolvidos. Deve-se atentar também para a legislação de proteção de dados (a LGPD) e as de serviços financeiros.

## Padrões Aplicáveis

O sistema deve seguir os padrões definidos pelas normas: WCAG, ISO 9241-11, ISO/TC-211, ISO 9000, ISO 9001-3, ISO 12207, ISO 12202 e pelos guias de estilo dos sistemas Android e iOS.

## Requisitos Físicos

O sistema deve funcionar em computadores de mesa e laptops, além de tablets e smartphones com navegadores de internet compatíveis.

## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SERRANO, et al. Requisitos - Aula 13. Disponível em: <<https://aprender3.unb.br/course/view.php?id=18538&section=6>> Acesso em 11 maio 2023.

> <a id="REF2" href="#anchor_2">2.</a> Artefato: Especificações Suplementares. **Centro de Informática - UFPE**. Disponível em: <<https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>>. Acesso em: 12 de maio de 2023.

## Bibliografia

> MATIAS, Davi. Especificação Suplementar. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/especificacao_suplementar/>>. Acesso em: 09 maio 2023.

> CARNEIRO, Caio Vitor. Especificação Suplementar. Repositório do Grupo Grasshopper da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Grasshopper/modelagem/especificao-suplementar/>>. Acesso em: 09 maio 2023.

> SANTOS, Eduardo Schuindt; POPOV, Arthur Taylor de Jesus. Personas. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/EspecificacaoSuplementar/>>. Acesso em: 09 maio 2023.

## Histórico de Versões

| Versão | Data       | Descrição                                                                                                                                                                                                                   | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 12/05/2023 | Criação da página.                                                                                                                                                                                                          | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.1`  | 12/05/2023 | Adição dos tópicos: Requisitos de Funcionalidade, de Usabilidade, de Confiabilidade, de Desempenho, de Implementação, de Sistema de Ajuda, de Licenciamento, Restrições de Design, Observações Legais e Padrões Aplicáveis. | [Matheus Henrique](https://github.com/mathonaut) | [Rafael Ferreira](https://github.com/RafaelCLG0) |
| `1.2`  | 16/05/2023 | Adição dos tópicos: Requisitos de Suportabilidade.                                                                                                                                                                          | [Rafael Ferreira](https://github.com/RafaelCLG0) | [Matheus Henrique](https://github.com/mathonaut) |
| `1.3`  | 01/07/2023 | Retrabalho.| [Arthur de Melo](https://github.com/arthurmlv)   | [Matheus Henrique](https://github.com/mathonaut)   |
