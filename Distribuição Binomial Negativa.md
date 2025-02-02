#distribuição #probabilidade #discreta

[[Distribuições de Probabilidade]]


**1. Definição**

Modela a probabilidade de um certo número de tentativas ocorrerem antes de um número fixo de sucessos.

**2. Função Densidade de Probabilidade**

### $$\displaystyle P(X=k) = \binom{k+r-1}{r-1} p^r (1-p)^k$$ 

#binomial

**3. Parâmetros**

$k$ - número de ensaios
$r$ - número de sucessos desejados
$p$ - probabilidade de sucesso dos ensaios

**4. Propriedades**

$E[X] = \frac{r(1-p)}{p}$

$Var(X) = \frac{r(1-p)}{p^2}$

**5. Aplicações com Software**

#### **Excel**

|**Função**|**Comando**|
|---|---|
|**Densidade**|`=NEGBINOM.DIST(k-r, k, p, FALSE)`|
|**Acumulada**|`=NEGBINOM.DIST(k-r, k, p, TRUE)`|


#### **Python (scipy.stats)**

|**Função**|**Comando**|
|---|---|
|**Densidade**|`nbinom.pmf(k - r, k, p)`|
|**Acumulada**|`nbinom.cdf(k - r, k, p)`|
