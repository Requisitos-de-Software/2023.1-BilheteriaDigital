# First Things First

## Introdução

A técnica _First Things First_ <a id="TEC1" href="#anchor_1">^1^</a> (FTF) enfatiza a necessidade de avaliar cuidadosamente os custos e benefícios de cada requisito de um software, bem como as implicações que cada um terá na sua arquitetura. É importante também garantir que os requisitos estejam alinhados com as regras de negócios e que o risco técnico associado a cada requisito seja considerado. Em resumo, a técnica destaca a importância de priorizar os requisitos de forma criteriosa e estratégica, a fim de maximizar os benefícios e minimizar os riscos e custos envolvidos no desenvolvimento do software.


## Metodologia
As pessoas que participaram da elaboração dessa técnica são

* **Mediador**: Responsável por apresentar os requisitos listados
* **Cliente**: Responsável por classificar benefícios e penalidades na implementação de cada requisito
* **Desenvolvedor**: Responsável por identificar custos e riscos na implementação de cada requisito

A ténica foi elaborada da seguinte forma:

1. Listar todos os requisitos elicitados e retirar aqueles que são logicamente ligados (se X depende de Y, então apenas é X é listado).
2. Para cada requisito, o cliente deve estimar de 1 a  9 o benefício agregado, sendo que 1 indica pouco benefício e 9 é o maior benefício possível, e a penalidade da não implementação, sendo que 1 significa que não há penalidade e 9 indica uma penalidade muito séria. O **valor total** é calculado da seguinte forma: <br> <p align="center" style="font-size: 18px;">`valor total = (benefício * peso) + (penalidade * peso)`</p>
3. Para cada requisito, o desenvolvedor deve estimar de 1 a  9 o **custo** de implementação de cada requisito, sendo 1 o custo mais baixo e 9 é o mais alto,  levando em consideração a complexidade, a interface necessária, a capacidade de reutilização do código e os testes.
4. Os desenvolvedores também estimam o grau relativo de **riscos** associados com o recurso em uma escala de 1 a 9, sendo que 1 significa grande facilidade na implementação e 9 indica preocupações sérias sobre viabilidade, disponibilidade de equipe ou mesmo falta de experiência com novas ferramentas ou tecnologias.
5. Então é feito o cálculo de **prioridade** para cada requisito da seguinte forma:<br> <p align="center" style="font-size: 18px;">`prioridade = valor(%)/(custo(%) * peso do custo + risco(%) * peso do risco)`</p>
6. A tabela deve ser ordenada de acordo com a ordem decrescente de prioridade, sendo os requisitos do topo da lista os mais equilibrados em termos de valor, custo e risco. Tendo isso em mente, tais requisitos devem ser priorizados.

## Referências

> <a id="FRM1" href="#anchor_1">1.</a> FIRST things first: Setting requirement priorities. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665.


## Histórico de versões

Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
1.0 | 29/04/2023 | Definição dos passos para realizar a ténica FTF | [Sidney Fernando](https://github.com/nando3d3) | [Rafael Ferreira](https://github.com/RafaelCLG0)