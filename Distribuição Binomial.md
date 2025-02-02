

[[Distribuições de Probabilidade]]

### **1. Definição** 

Descreve a probabilidade de um número fixo de sucessos de uma sequência de experimentos binários independentes


### **2. Função Densidade**


## $$\displaystyle P(X=k) = \binom nk p^k(1-p)^{n-k}$$
### $$\displaystyle P(X<k) = \sum_{i=0}^{k} \binom ni p^i(1-p)^{n-i}$$


### **3. Parâmetros**

##### $n$ - número de ensaios
##### $k$ -número de sucessos
##### $p$ - probabilidade de sucesso


##### $\displaystyle \binom nk$ - coeficiente binomial, dado por $\displaystyle \dfrac{n!}{k!(n-k)!}$


### **4. Propriedades**

$E[X] = n \cdot p$

$Var(X) = n \cdot p \cdot (1-p)$

Assimetricidade

### **5. Aplicação em Software**

 ### **Excel**

| **Função** | **Comando**                  |
| ---------- | ---------------------------- |
| Densidade  | `=BINOMDIST(k, n, p, FALSE)` |
| Massa      | `=BINOMDIST(k, n, p, TRUE)`  |

 **Python (scipy.stats)**

| **Função** | **Comando**          |
| ---------- | -------------------- |
| Densidade  | `binom.pmf(k, n, p)` |
| Massa      | `binom.cdf(k, n, p)` |
