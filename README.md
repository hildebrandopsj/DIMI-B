# DIMI-B
Programa para DIMensIonamento de Blocos sobre estacas

Protótipo de aplicação desenvolvido no software Smath Studio, posteriormente será portado para a linguagem Pascal.

## Capabilidades:
- Inclusão de qualquer número de estacas
- Permite a inserção de estaqueamentos assimétricos
- Permite a inclusão do pilar excentrico ao baricentro do estaqueamento
- Cálculo automático das reações
- Divisão do pilar em áreas definidas arbitráriamente pelo usuário (Para cálculo do comprimento de projeção das bielas)
- Verificação das bielas pelo método do Ibracon e de Blévot
- Cálculo das armaduras

## Como usar ?
O usuário deverá definir os carregamentos, as dimensões do pilar, das estacas e das áreas arbitrárias para cada biela.
Após feita esta definição, o usuário poderá apagar o exemplo clicando sobre os elementos e pressionando a tecla DEL
A inserção é simples, basta escolher o pilar e puxar para dentro da área gráfica, o mesmo para as estacas e para as áreas.

É **imprescindível** que as estacas e as áreas sejam inseridas na mesma sequência.

## Atenção!
- As armaduras são decompostas em x e y
- Apesar de ser possível inserir mais de um pilar, o programa está preparado para suportar apenas um.
