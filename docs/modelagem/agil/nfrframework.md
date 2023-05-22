## Introdução

Uma forma de representação e análise dos [Requisitos Não-Funcionais](../../../elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) é o NFR Framework, o qual visa à implementação de resoluções particulares. Sendo assim, para tal, considera-se as características gerais do sistema em questão e de seu domínio. No NFR Framework, faz-se o uso do modelo de Softgoal Interdependency Graph (SIG).

## Softgoal Interdependency Graph

O Softgoal Interdependency Graph (SIG) é uma forma de visualização do funcionamento do NFR Framework. Dessa forma, trata-se de um gráfico que registra os posicionamentos da equipe de desenvolvimento acerca dos softgoals e explicita suas interdependências de forma gráfica e concisa<a id="anchor_1" href="#REF1">^1^</a>.

### Tipos de Softgoal

Para a compreensão do SIG, é inexorável discernir a definição de NFR Softgoal: um objetivo que não é explicitamente definido e seus critérios de satisfação são imprecisos. Sendo assim, um softgoal é uma característica abstrata que está sujeita à vistoria, ou seja, postula-se posteriormente o destino de um determinado softgoal. Além disso, os softgoals podem ser operacionalizados, nesse caso, tomam uma forma concreta. Portanto, entende-se como funcionalidades. Por fim, há os softgoals de afirmação, os quais são escritos em linguagem natural e se tratam de registros adicionais e argumentativos, os quais podem ser incrementados ao modelo<a id="anchor_1" href="#REF1">^1^</a>. Os tipos de softgoal estão ilustrados na Figura 1.

<figure markdown>

<font size="3"><p style="text-align: center"><b>Figura 1</b> - Tipos de Softgoal</p></font>

![Diagrama do Modelo de Ciclo de Vida de Mayhew](../../assets/nfr-framework/tipos.png#only-light){width: 300}
![Diagrama do Modelo de Ciclo de Vida de Mayhew](../../assets/nfr-framework/tipos2.png#only-dark){width: 300}

<font size="3"><p style="text-align: center"> Fonte: [Arthur de Melo](https://github.com/arthurmlv)</p></font>

</figure>

### Interdependências

As interdependências são definições para as associações que ocorrem entre softgoals. Tais são divididas em decomposições e contribuições:

#### Decomposições

As decomposições podem ocorrer em todos os níveis de abstração: Softgoals de NFR, de Operacionalização e de Afirmação. Nas três primeiras decomposições, os softgoals são subdivididos em softgoals especificados (SILVA, 2019)<a id="anchor_1" href="#REF1">^1^</a>.

- Decomposição NFR: ajuda a dividir vicissitudes primordiais em partes menores, o que reduz as ambiguidades e facilita a priorização.
- Decomposição de Operacionalização: tem por finalidade refinar uma solução geral em soluções particulares.
- Decomposição de Afirmação: serve como afirmação ou negação de justificativas específicas do projeto.
- Decomposição de Priorização: trata-se de uma decomposição especial, na qual o softgoal é refinado em outro softgoal de mesmo tipo e tópico. No entanto, associa-se uma prioridade.

#### Contribuições

Num NFR Framework, os softgoals se especializam cada vez mais. Por conseguinte, o um softgoal derivado de outro pode contribuir de forma integral ou truncada, e também de forma positiva ou negativa, para o softgoal do qual ele derivou. Portanto, listar-se-á os tipos de contribuição<a id="anchor_2" href="#REF2">^2^</a>:

- AND: se os softgoals derivados forem satisfeitos, o softgoal primordial também será.
- OR: se algum dos softgoals derivados forem satisfeitos, o softgoal primordial também será.
- MAKE(++): um softgoal originado contribui de forma plenamente positiva, logo o softgoal original também será satisfeito.
- BREAK(--): um softgoal originado contribui de forma plenamente negativa, logo o softgoal original será negado.
- HELP(+): um softgoal originado realiza uma contribuição restritamente positiva, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- HURT(-): um softgoal originado realiza uma contribuição restritamente negativa, o que reflete da mesma forma e na mesma intensidade no softgoal primordial.
- UNKNOWN(?): contribuição incógnita.
- EQUALS: relação direta entre as satisfações do softgoal derivado e a do primordial.
- SOME: a forma de contribuição é conhecida, no entanto, a intensidade dessa contribuição é desconhecida.


## Referências Bibliográficas

> <a id="REF1" href="#anchor_1">1.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Centro de Informática UFPE, Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150>. Acesso em: 22/05/2023.

> <a id="REF2" href="#anchor_2">2.</a>CHUNG, L., NIXON, B. A., YU, E., MYLOPOULOS, J. Non-functional requirementsin software engineering. Springer Science & Business Media: [S.l.], 2000. v. 5.


## Histórico de Versões

| Versão | Data       | Descrição                                    | Autor(es)                                        | Revisor(es)                                      |
| ------ | ---------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------------------ |
| `1.0`  | 22/05/2023 | Introdução, SIG, Tipos de Softgoal e Interdependências.| [Arthur de Melo](https://github.com/arthurmlv)   | [Sidney Fernando](https://github.com/nando3d3)   |