#distribuição #probabilidade #discreta

[[Distribuições de Probabilidade]]

**1. Definição**

Distribuição de probabilidade discreta. Descreve o número de ocorrências de um evento em um intervalo de tempo ou espaço específico.

**2. Distribuição de Probabilidade**

### $$\displaystyle P(X=k) = \frac{\lambda^k e^-\lambda}{k!}$$

$\displaystyle P(X <k) = \sum_{i=0}^{k} \frac{\lambda^i e^{-\lambda}}{i!}$ 

#e #fatorial 

**3. Parâmetros**

$\lambda$ - a taxa média de ocorrências
$k$ - número de ocorrências

**4. Propriedades** 

- $Var(X) = \lambda$
- Assimetria: Tende a ser assimétrica quando $\lambda$ é pequeno
- Independência: O número de ocorrências em intervalos diferentes é independente.


**5. Aplicações com Software**

##### **Excel**

|**Função**|**Comando**|
|---|---|
|**Densidade**|`=POISSON.DIST(k, λ, FALSE)`|
|**Acumulada**|`=POISSON.DIST(k, λ, TRUE)`|

---

##### **Python (scipy.stats)**

| **Função**    | **Comando**         |
| ------------- | ------------------- |
| **Densidade** | `poisson.pmf(k, λ)` |
| **Acumulada** | `poisson.cdf(k, λ)` |
