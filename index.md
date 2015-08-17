---
title       : GENMANIM - Exerc. 3
subtitle    : Quiz Interativo
author      : Atilio S. Calefi
job         : Colaboradora Profa. Karen B Muller
framework   : io2012     
highlighter : prettify.js  
hitheme     : solarized_light 
widgets     : [bootstrap, quiz, mathjax]
mode        : selfcontained
---

## Probabilidade de Eventos Aleat�rios

- Evento � um subconjunto de um espa�o amostral.
- Evento aleat�rio � a ocorrencia de um determinado evento ao acaso dentro das possibilidades.

Ex: Um dado possui 6 lados. Se jogarmos o dado obteremos um evento (n�mero) aleat�rio (1,2,3,4,5 ou 6).

--- &radio

- A segrega��o dos cromossomos para a forma��o dos gametas � gerada de forma aleat�ria. Sendo assim, considerando um animal heterozigoto para os genes *Aa*, qual a probabilidade de formar um gameta com o alelo *A*?

1. 0
2. _1/2_
3. 1/4
4. 1/6

*** .hint
Os gametas somente ser�o hapl�ides.

*** .explanation

A segrega��o cromossomica far� com que os gametas ou carreiem *A* ou *a*. Ou seja, a probalilidade de ter um gameta possuindo qualquer um dos alelos ? de $1/2$ ou de 50%.

--- &radio

- A segrega��o dos cromossomos para a forma��o dos gametas � gerada de forma aleat�ria. Sendo assim, considerando um animal heterozigoto para os genes *Aa*, qual a probabilidade de formar um gameta com o alelo *a*?

1. 0
2. _1/2_
3. 1/4
4. 1/6

*** .hint
Os gametas somente ser�o hapl�ides.

*** .explanation

A segrega��o cromossomica far� com que os gametas ou carreiem *A* ou *a*. Ou seja, a probalilidade de ter um gameta possuindo qualquer um dos alelos é de $1/2$ ou de 50%.

--- &radio

- Qual � a probabilidade de dois primos em primeiro grau, cujas m�es s�o g�meas monozig�ticas, serem heterozigotos para um gene autoss�mico oriundo de um acestral comum?

1. 0
2. 1/2
3. _1/4_
4. 1/6

*Borges-Os�rio M.R.; Robinson W.M. Gen�tica Humana. 2ed. Editora Artmed.

*** .explanation
Considerando-se que as m�es, g�meas monozig�ticas, s�o geralmente id�nticas, o valor **r** �, neste caso, igual a: $(1/2)^3 + (1/2)^3 = 1/4$

--- &radio

- Para a heran�a ligada ao X, em cruzamentos ao acaso, a frequ�ncia de uma caracteristica recessiva � sempre menor nas mulheres do que nos homens, acontecendo o contr�rio quando a caracter�stica for dominante. 

- Conidere que a frequ�ncia de um gene recessivo qualquer ligado ao X seja de 0.2 (q = 0.2), seu alelo dominante ter� frequ�ncia de p = 0.8.

- Qual a frequ�ncia da caracter�stica recessiva nas mulheres e homens ?

1. 5% nas mulheres e 6% nos homens
2. 2% nas mulheres e 15% nos homens
3. 25% nas mulheres e 5% nos homens
4. _4% nas mulheres e 20% nos homens_

*** .explanation
Para as mulheres $q^2 = (0.2)^2 = 0.004 ou 4%$
Para os homens $q = 0.2 ou 20%$

--- &radio

- Para a heran�a ligada ao X, em cruzamentos ao acaso, a frequ�ncia de uma caracteristica recessiva � sempre menor nas mulheres do que nos homens, acontecendo o contr�rio quando a caracteristica for dominante. 

- Conidere que a frequ�ncia de um gene recessivo qualquer ligado ao X seja de 0.2 (q = 0.2), seu alelo dominante ter� frequ�ncia p = 0.8.

- Qual a frequ�ncia da caracter�stica dominante nas mulheres e homens ?

1. 56% nas mulheres e 75% nos homens
2. 18% nas mulheres e 14% nos homens
3. _96% nas mulheres e 80% nos homens_
4. 32% nas mulheres e 1% nos homens

*** .explanation
Para as mulheres $p^2 + 2pq = (0.8)^2 + 2(0.8 * 0.2) = 0.96 ou 96%$
Para os homens $p = 0.8 ou 80%$

Esta afirmativa � mais evidene quanto menor for a frequ�ncia g�nica considerada.

--- &radio

- Se, em uma determinada popula��o em equilibrio, a frequ�ncia de individuos albinos for de 1/10000. Qual a frequ�ncia do gene para o albinismo?

1. _0.01_
2. 0.05
3. 0.06
4. 0.31

*** .explanation

- $sqrt(p)$ = 100
- 100 / 10000 = 0.01

--- &radio

- Se, em uma determinada popula��o em equilibrio, a frequ�ncia de individuos albinos for de 1/10000. Qual a probabilidade de um casal normal, n�o aparentado, vir a ter um filho albino, sabendo-se que o genitor da mulher � afetado?

1. aproximadamente 0.01
2. _aproximadamente 0.005_
3. aproximadamente 0.0006
4. aproximadamente 0.15

*** .explanation

- 2pq * 1 * 1/4 = 2 * 0.99 * 0.01 * 1 * 0.25 = 0.00495 ou aprox. 0.5%
- (probabilidade do c�njuge masculino ser heterozigoto) * (certeza de que a mulher tem o gene em quest�o) * (probabilidade de que nas�a prole afetada, de um casal heterozigoto)

--- &radio

- Em uma amostra de 1500 indiv�duos, foram encontrados tr�s afetados por uma doen�a autoss�mica recessiva. Qual a probabilidade de cruzamento entre dois individuos nesta popula��o?

1. aproximadamente 0.99%
2. aproximadamente 0.012%
3. _aproximadamente 0.7%_
4. aproximadamente 0.42%

*** .explanation
$2pq * 2pq = (2 * 0.955 * 0.045) * (2 * 0.955 * 0.045) = 0.0074 ou aprox. 0.7%

--- &radio

- Considere as seguintes situa��es que ocorrem em popula��es com rela��o a um par de alelos **A** e **a**.

$I$ - Os cruzamentos ao acaso n�o selecionam nenhum dos alelos.

$II$ - H� emigra��o de um grande n�mero de individuos **aa**.

$III$ - Os individuos **aa** s�o atacados por agente infeccioso que causa a sua morte.

Haver� o aumento da frequ�ncia do alelo **A**:

1. apenas na situa��o I.
2. apenas na situa��o I e II.
3. apenas nas situa��o I e III.
4. _apenas nas situa��o II e III._
5. nas situa��o I, II e III.

*Amabis & Martho. Biologia das popula��o 3, Gen�tica, Evolu��o e Ecologia. Editora Moderna. 

*** .explanation

--- &radio

- A condi��o correta para que o equil�brio de Hardy-Weinberg se verifique �:

1. A popula��o considerada deve ser bastante pequena
2. As migra��es devem estar ocorrendo na popula��o.
3. As muta��es devem estar ocorrendo na popula��o.
4. Os genes alelos devem estar sujeitos a sele��o natural.
5. _Os cruzamentos devem ocorrer de maneira casual._

*** .explanation

--- &radio

- A an�lise de um par de alelos autoss�micos (A e a) em cinco popula��es mosrou as frequ�ncias genot�picas apresentadas abaixo. Assinale a popula��o que est� em equil�brio gen�tico:

1. 1% AA, 98% Aa, 1% aa.
2. 1% AA, 81% Aa, 18% aa.
3. _4% AA, 32% Aa, 64% aa._
4. 33% AA, 34% Aa, 33% aa.
5. 50% AA, 50% Aa, 0% aa.

*** .explanation

--- &radio

- Uma popula��o que est� em equil�brio de Hardy-Weinberg � constituida por 2 mil individuos. Sabe-se que 320 deles t�m uma certa anomalia, determinada por um gene autoss�mico recessivo. Entre os individuos normais nesta popula��o, qual o n�mero esperado de portadores do alelo recessivo?

1. _960_
2. 480
3. 420
4. 320
5. 240

---

# FIM

## Sugest�es: prof.atilio.calefi@usjt.br

---



