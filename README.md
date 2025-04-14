# Teoria Moderna  de Portfolio







#  Problema de Negócio



O objetivo principal do projeto é construir uma carteira de investimentos composta por ações americanas (AAPL, NKE, GOOGL e AMZN), buscando maximizar o retorno esperado para um dado nível de risco, ou alternativamente, minimizar o risco para um determinado retorno esperado. Para isso, o projeto aplica a Teoria Moderna de Portfólio, desenvolvida por Harry Markowitz, e utiliza o Índice de Sharpe para avaliar o desempenho das carteiras eficientes.





## Entendimento do Negócio



📘 Conceitos: Markowitz e Índice de Sharpe


Markowitz (Teoria Moderna do Portfólio)


Harry Markowitz introduziu a ideia de que uma carteira de ativos deve ser construída considerando diversificação: o risco de um portfólio pode ser reduzido se os ativos não forem perfeitamente correlacionados. A ideia central é:

Cada ativo possui retorno esperado e risco (desvio padrão);

A combinação de ativos forma uma carteira com retorno e risco próprios;

Existe uma fronteira eficiente, que representa as carteiras com melhor retorno possível para cada nível de risco.

Índice de Sharpe
Criado por William Sharpe, o índice mede o retorno adicional por unidade de risco assumida. A fórmula é:

Sharpe
=
𝑅
𝑝
−
𝑅
𝑓
𝜎
𝑝
Sharpe= 
σ 
p
​
 
R 
p
​
 −R 
f
​
 
​
 
Onde:

𝑅
𝑝
R 
p
​
 : Retorno da carteira;

𝑅
𝑓
R 
f
​
 : Retorno livre de risco (geralmente é um título do governo);

𝜎
𝑝
σ 
p
​
 : Risco (desvio padrão da carteira).

Quanto maior o índice de Sharpe, melhor o desempenho ajustado ao risco da carteira.
