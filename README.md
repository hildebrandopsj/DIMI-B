# DIMI-B (DIMensIonamento de Blocos sobre estacas)
Programa para dimensIonamento de blocos sobre estacas

Protótipo de aplicação desenvolvido no software Smath Studio, posteriormente será portado para a linguagem Pascal. Portanto, trata-se de um simples MVP (Minimum Viable Product)

## Capabilidades:
- Inclusão de qualquer número de estacas
- Permite a inserção de estaqueamentos assimétricos
- Permite a inclusão do pilar excentrico ao baricentro do estaqueamento
- Cálculo automático das reações
- Divisão do pilar em áreas definidas arbitráriamente pelo usuário (Para cálculo do comprimento de projeção das bielas)
- Verificação das bielas pelo método do Ibracon e de Blévot
- Cálculo das armaduras

## Como usar a entrada gráfica?
- Defina as dimensões do pilar
- Defina as dimensões da estaca
- Defina as dimensões das divisões do pilar
- Delete o exemplo existente (Basta clicar sobre o elemento e pressionar DEL)
- Insira o pilar clicando sobre o primeiro ícone à direita e arrastando o elemento para a área gráfica
- Para definir a posição exata, clique duas vezes sobre o elemento
- Insira as estacas (Basta clicar sobre a estaca e arrastar para a área gráfica)
- Insira as áreas de divisão do pilar (Basta clicar sobre a estaca e arrastar para a área gráfica)
- **Obs.**: As áreas de divisão do pilar devem ser colocadas na mesma ordem em que as estacas foram inseridas

É **imprescindível** que as estacas e as áreas sejam inseridas na mesma sequência, ou o comprimento de projeção será calculado de forma errônea.

## Atenção!
- As armaduras são decompostas em x e y apenas
- Apesar de ser possível inserir mais de um pilar, o programa está preparado para suportar apenas um.

O ícone utilizado nesta aplicação foi obtido no site: https://icons8.com.br
