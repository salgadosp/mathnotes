#distribuição #probabilidade #discreta

[[Distribuições de Probabilidade]]

**1. Definição**

Generalização da binomial para mais de dois resultados possíveis. Em uma sequencia de n ensaios independentes, em que cada ensaio tem k resultados possíveis, a distribuição multinomial é utilizada para modelar a probabilidade de se observar uma combinação específica de frequência para cada um dos k resultados.

**2. Função Densidade de Probabilidade**

$\displaystyle P(X_1 = x_1, X_2 = x_2, ..., X_k = x_k) = \frac{n!}{x_1!x_2!...x_k!}p_1^{x_1}p_2^{x_2}...p_k^{x_k}$
#fatorial

**3. Parâmetros**

$n$ - número de ensaios
$p_i$ - probabilidade de $X_i$

**4. Propriedades**

$E[X_i] = np_i$

$Var(X_i) = np_i(1-p_i)$

 **5. Aplicações com Software**

#### **Excel**

| **Função**    | **Comando**                        |
| ------------- | ---------------------------------- |
| **Densidade** | `=MULTINOMIAL(k1, k2, ..., kn, n)` |

#### **Python (scipy.stats)**

| **Função**    | **Comando**                                                |
| ------------- | ---------------------------------------------------------- |
| **Densidade** | `multinomial.pmf([k1, k2, ..., kn], n, [p1, p2, ..., pn])` |
