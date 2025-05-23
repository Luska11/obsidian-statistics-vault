---
dg-publish: true
---

Para entender o critério da integral para a convergência de séries, é importante primeiro definir as condições e aplicar o método corretamente.

## Definição Do Critério da Integral

Considere uma função $f(x)$ contínua, não-negativa e decrescente para $x \geq 1$. A série $\sum_{n=1}^{\infty} f(n)$ converge se e somente se a integral $\int_{1}^{\infty} f(x) \, dx$ convergir.

## Exemplos

### Exemplo 1: Série de Potência

Considere a série geométrica generalizada $\sum_{n=1}^{\infty} \frac{1}{n^p}$, onde $p > 0$. Aqui, $f(x) = \frac{1}{x^p}$.

- **Integral**:
$$
  \int_{1}^{\infty} \frac{1}{x^p} \, dx
$$
- Para $p > 1$, a integral converge:
$$
  \int_{1}^{\infty} x^{-p} \, dx = \left[ -\frac{1}{(p-1)x^{p-1}} \right]_1^\infty = \frac{1}{p-1}
$$
- Para $p \leq 1$, a integral diverge.

### Exemplo 2: Série de Termos Positivos

Considere a série $\sum_{n=1}^{\infty} \frac{1}{\sqrt{n}}$.

- **Integral**:
$$
  \int_{1}^{\infty} \frac{1}{\sqrt{x}} \, dx = \left[ 2\sqrt{x} \right]_1^\infty
$$
- Esta integral diverge porque $\lim_{x \to \infty} 2\sqrt{x} = \infty$.

### Aplicações e Considerações

- **Limitação**: O critério da integral é mais útil para séries com termos que podem ser expressos como funções contínuas, não-negativas e decrescentes.
- **Comparação**: Pode ser usado em combinação com outros testes de convergência, como o teste comparativo ou o teste do limite.
