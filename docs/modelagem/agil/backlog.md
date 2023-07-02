# Backlog

## Introdução

O Backlog do Produto é um artefato da metodologia ágil que toma a forma de uma lista de todas as tarefas pendentes a serem feitas em um projeto. O responsável por sugerir e priorizar os itens é o Dono do Produto (_Product Owner_). Vale ressaltar que o Backlog do Produto é um artefato dinâmico, ou seja, ele cresce e muda à medida que os requisitos e a visão do produto são alterados.

Para a produção desse artefato , houve a participação de um usuário fazendo o papel de PO do projeto, que foi entrevistado via Discord às 20:45 do dia 31 de maio de 2023. Os participantes são apresentados na tabela 1 e gravação da entrevista é apresentada no vídeo 1.

<center>

**Tabela 1** - Participantes da entrevista.

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
| <span style = "color: orange"> Ana</span>               | Product Owner  |
| [Douglas Alves dos Santos](https://github.com/dougAlvs) | Desenvolvedor  |
| [Geovanna Maciel](https://github.com/manuziny)          | Entrevistadora |
| [Matheus Henrique](https://github.com/mathonaut)        | Desenvolvedor  |
| [Rafael Ferreira](https://github.com/RafaelCLG0)        | Desenvolvedor  |


Fonte: [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0).

</center>

<center>

**Vídeo 1** - Entrevista com o PO.

<iframe width="560" height="315" src="https://www.youtube.com/embed/2o3diusGVC8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<a href="https://www.youtube.com/embed/2o3diusGVC8" target="blanket">Clique aqui</a>

Fonte: [Geovanna Maciel](https://github.com/manuziny).

</center>

## Metodologia

Na entrevista realizada com o PO, enquanto ele comentava suas funcionalidades desejadas os desenvolvedores/entrevistadores anotavam e faziam questionamentos acerca de suas falas. Depois de elicitadas as histórias de usuário, os critérios de aceitação foram definidos e elas foram priorizadas pelo PO em: Alta, Média ou Baixa prioridade (Basicamente foi utilizado o método Three Level Scale de priorização de requisitos). Posteriormente, foram definidos temas, épicos e features de forma a categorizar as histórias de usuário. A tabela 2 exemplifica o product backlog, com o detalhamento de cada história de usuário estando presente no seu respectivo [artefato](../historia-de-usuario). Além disso, o resto dessa documento explica melhor como foi o processo de definição dos temas, épicos e features e o significado de cada termo.

<center>

*Tabela 2* - Product Backlog Elaborado com o Product Owner.
<table>
<thead>
  <tr>
    <th>Épico</th>
    <th>Feature</th>
    <th>História de usuário</th>
    <th>Priorização</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="4">Épico 1 - Categorizar</td>
    <td rowspan="2">Feature 1 - Local e Data</td>
    <td><a href="../historia-de-usuario#us01"> US01 </a> - Classificar eventos por local</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us04"> US04 </a> - Classificar eventos por data</td>
    <td>Média</td>
  </tr>
  <tr>
    <td rowspan="2">Feature 2 - Modalidade</td>
    <td><a href="../historia-de-usuario#us02"> US02 </a> - Classificar eventos por modalidade</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us07"> US07 </a> - Venda de ingressos de diferentes categorias</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td rowspan="4">Épico 2 - Preferências</td>
    <td rowspan="2">Feature 3 - Notificações</td>
    <td><a href="../historia-de-usuario#us22"> US22 </a> - Opção de receber notificações do aplicativo</td>
    <td>Baixa</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us23"> US23 </a> - Exibição de notificações de eventos próximos</td>
    <td>Baixa</td>
  </tr>
  <tr>
    <td rowspan="2">Feature 4 - Configurações</td>
    <td><a href="../historia-de-usuario#us10"> US10 </a> - Opção de salvar dados de pagamento</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us21"> US21 </a> - Recomendação de eventos baseada no gosto do usuário</td>
    <td>Média</td>
  </tr>
  <tr>
    <td rowspan="6">Épico 3 - Acessibilidade</td>
    <td rowspan="2">Feature 5 - Ferramentas de Acessibilidade</td>
    <td><a href="../historia-de-usuario#us32"> US32 </a> - Audiodescrição para eventos</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us30"> US30 </a> - Acessibilidade visual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td rowspan="3">Feature 6 - Atalhos</td>
    <td><a href="../historia-de-usuario#us31"> US31 </a> - Opção de troca de idioma</td>
    <td>Média</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us17"> US17 </a> - Diferentes opções de pagamento</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us27"> US27 </a> - Cadastro por redes sociais validado por email</td>
    <td>Média</td>
  </tr>
  <tr>
    <td>Feature 7 - Ferramentas Complementares</td>
    <td><a href="../historia-de-usuario#us16"> US16 </a> - Opção de transferência de ingresso</td>
    <td>Média</td>
  </tr>
  <tr>
    <td rowspan="10">Épico 4 - Segurança</td>
    <td rowspan="5">Feature 8 - Integridade de Dados</td>
    <td><a href="../historia-de-usuario#us11"> US11 </a> - Privacidade dos dados de pagamento</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us09"> US09 </a> - Exigência de dados necessários para cadastro e pagamento</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us26"> US26 </a> - Autenticação de dois fatores</td>
    <td>Média</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us28"> US28 </a> - Senha segura durante o cadastro</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us24"> US24 </a> - Termos de privacidade explícitos</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td rowspan="5">Feature 9 - Prevenção de Erros</td>
    <td><a href="../historia-de-usuario#us03"> US03 </a> - Apresentar valor total dos ingressos selecionados</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us08"> US08 </a> - Classificação dos tipos de assentos</td>
    <td>Baixa</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us14"> US14 </a> - Lista de confirmação de pagamento</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us18"> US18 </a> - Envio de ingressos por e-mail</td>
    <td>Média</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us15"> US15 </a> - Sem limite de compra de ingresso</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td rowspan="8">Épico 5 - Padronização</td>
    <td rowspan="6">Feature 10 - Interface</td>
    <td><a href="../historia-de-usuario#us05"> US05 </a> - Histórico de visualização de eventos</td>
    <td>Baixa</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us06"> US06 </a> - Contagem regressiva para realização de eventos</td>
    <td>Média</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us12"> US12 </a> - Lista de eventos disponíveis</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us13"> US13 </a> - Página de descrição de eventos</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us29"> US29 </a> - Informações sobre inclusão na descrição dos eventos</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us19"> US19 </a> - Aba de visualização de ingressos</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td rowspan="2">Feature 11 - Ferramentas Necessárias</td>
    <td><a href="../historia-de-usuario#us25"> US25 </a>- Criação de conta e login com e-mail</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td><a href="../historia-de-usuario#us20"> US20 </a> - Opção de cancelamento de compra</td>
    <td>Alta</td>
  </tr>
</tbody>
</table>

Fonte: [Matheus Henrique](https://github.com/mathonaut), [Rafael Ferreira](https://github.com/RafaelCLG0) e [Douglas Alves dos Santos](https://github.com/dougAlvs).

</center>

## Temas

Analisando as histórias de usuário, foi possível organizá-las inicialmente em dois grandes temas.

- **Funcionalidades**: Agrupa funcionalidades que o sistema precisa oferecer para que o usuário consiga realizar com sucesso suas tarefas.
- **Perfil**: Agrupa funcionalidades relacionadas a como o usuário se apropria do sistema e o modifica de acordo com seus gostos e desejos.

## Épicos

Após a definição dos temas, eles são "quebrados" em épicos de modo a diminuir ainda mais a abstração das atividades que deverão ser realizadas no projeto. Para esse projeto, os épicos foram descritos utilizando o padrão de escrita das histórias de usuário e possuem um nível de abstração a mais chamado de _Features_.

## Features

Definido um épico, são geradas _features_, que são descrições simplificadas do que o produto faz para atender os objetivos dos usuários.  Elas representam as funcionalidades em um nível de abstração maior que as histórias de usuário.

### Histórias de Usuário

Elas especificam ainda mais as _features_ e serão detalhadas melhor na seção de [Histórias de Usuário](../historia-de-usuario). Se apresentam como descrições concisas e de alto nível de uma funcionalidade desejada em termos do cliente. Usualmente seguem a forma "Eu, como \_\_\_, desejo \_\_\_ para ___."

### Épico 1 - Categorizar

Esse épico apresenta as funcionalidades que permite aos usuários busque eventos em classes específicas, como por localidade, data, horário, classificação e categorias. A história de usuário a seguir o generaliza:

<center>
*"Como usuário típico, eu desejo funcionalidades que me permitam categorizar os eventos"*
</center>

### Épico 2 - Preferências

Esse épico apresenta as funcionalidades que permite aos usuários modificarem o sistema de acordo com os seus gostos, mas também funcionalidades que permitem que o sistema ofereça sugestões de eventos personalizadas para cada usuário. A história de usuário a seguir o generaliza:

<center>
*"Como usuário típico, eu desejo modificar o site de acordo com as minhas preferências"*
</center>

### Épico 3 - Acessibilidade

Esse épico apresenta as funcionalidades que auxiliam os usuários a realizarem tarefas dentro do sistema, esse auxílio pode ser com atalhos que aceleram a conclusão de uma determinada tarefa como também através de ferramentas que permite que usuário com deficiência (PCD) consigam de fato utilizar o sistema. A história de usuário a seguir o generaliza:

<center>
*"Como usuário, eu desejo recursos que me permitam realizar com velocidade tarefas no site"*
</center>


### Épico 4 - Segurança

Esse épico apresenta as funcionalidades que garantem aos usuário segurança contra condições desfavoráveis ou até mesmo perigosas. Evitando que o usuário cometa erros e realize atividades não desejáveis, como também oferecer maneiras de recuperação desses erros aos usuários.

<center>
*"Como usuário, eu desejo recursos de segurança"*
</center>

### Épico 5 - Padronização

Este épico enfatiza as funcionalidades e atributos que contribuem para a eficiência e eficácia do sistema. Essas características garantem que o sistema seja capaz de executar suas tarefas de maneira rápida, precisa e com ótimos resultados. Além disso, o sistema é projetado de forma a ser facilmente memorizado pelos usuários, permitindo que eles se familiarizem rapidamente com suas funcionalidades e navegação.

<center>
*"Como usuário, eu desejo um sistema de fácil utilização"*
</center>


## Bibliografia

> SOUZA, Nicolas; MACEDO, Lucas. Backlog do Produto. Repositório do Grupo Lichess da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/>>. Acesso em: 18 maio 2023.

> POPOV, Arthur Taylor de Jesus; SANTOS, Eduardo Schuindt. Backlog do Produto. Repositório do Grupo MEI da disciplina de Requisitos de Software da Universidade de Brasília, 2022. Disponível em: <<https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/Agil/BacklogDoProduto/>>. Acesso em: 18 maio 2023.

> PRESSMAN, Roger S.; MAXIM, Bruce R.. Engenharia de software: uma abordagem profissional. 8 Porto Alegre: AMGH, 2016, 940 p.

> Bourque, P., Fairley, R. E. Guide to the Software Engineering Body of Knowledge, Version 3.0. SWEBOK. IEEE Computer Society, 2014. Disponível em: http://www.computer.org/web/swebok/v3. p. 38.

## Histórico de Versões

| Versão  | Data       | Descrição                             | Autor(es)                                                                                           | Revisor(es)                                                                                   |
| ------- | ---------- | ------------------------------------- | --------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| `1.0`   | 22/05/2023 | Criação da página.                    | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Rafael Ferreira](https://github.com/RafaelCLG0)                                              |
| `1.1`   | 23/05/2023 | Adição das Features.                  | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `1.1.1` | 23/05/2023 | Atualização metodologia.              | [Douglas Alves dos Santos](https://github.com/dougAlvs)                                             | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `1.2`   | 24/05/2023 | Ajustes nos textos e adição de links. | [Matheus Henrique](https://github.com/mathonaut)                                                    | [Arthur de Melo](https://github.com/arthurmlv)                                                |
| `2.0`   | 08/06/2023 | Refatoração do Artefato               | [Matheus Henrique](https://github.com/mathonaut) e [Rafael Ferreira](https://github.com/RafaelCLG0) | [Douglas Alves](https://github.com/dougAlvs) e [Geovanna Maciel](https://github.com/manuziny) |
| `2.1`   | 09/06/2023 | Adição das Histórias de Usuário e refatoração dos épicos em uma única tabela              | [Douglas Alves](https://github.com/dougAlvs) | [Matheus Henrique](https://github.com/mathonaut) |
| `2.2`   | 01/07/2023 | Retrabalho de acordo com a Verificação    | [Rafael Ferreira](https://github.com/RafaelCLG0) | [Matheus Henrique](https://github.com/mathonaut) |