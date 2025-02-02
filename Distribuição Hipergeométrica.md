#distribuição #probabilidade #discreta

[[Distribuições de Probabilidade]]

**1. Definição**

Descreve a probabilidade de um número de sucessos em um evento sem reposição (dependente) de uma população finita.

**2. Função Densidade de Probabilidade**

$\displaystyle P(X=k) = \frac{\binom Kk \binom {N-K}{n-k}}{\binom Nn}$
#binomial

**3. Parâmetros**

$N$ - tamanho da população
$K$ - total de sucessos na população
$n$ - tamanho da amostra

**4. Propriedades**

$\displaystyle E[X]=n \frac{K}{N}$ 

$\displaystyle Var(X)=\frac{nK(N−K)(N−n)}{N^2(N-1)}$​

**5. Aplicações com Software**

#### **Excel**

|**Função**|**Comando**|
|---|---|
|**Densidade**|`=HYPGEOM.DIST(k, n, M, N, FALSE)`|
|**Acumulada**|`=HYPGEOM.DIST(k, n, M, N, TRUE)`|

---

#### **Python (scipy.stats)**

|**Função**|**Comando**|
|---|---|
|**Densidade**|`hypergeom.pmf(k, N, M, n)`|
|**Acumulada**|`hypergeom.cdf(k, N, M, n)`|