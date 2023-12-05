# Lab 8

```math
y = w * x
MSE(w) = SUM (x_i * w - y_i) ^ 2

MSE'(w) = SUM 2 * (x_i * 2 - y_i) * x_i

MSE'(w) = 0

2 * x^T * (x * w - y) = 0
x^T * x * w - x^T * y = 0
x^T * x * w = x^T * y

w = (x^T * x) ^ -1 * x^T * y
```

```math
M = (1 | 2)
    (0 |-1)

=> f(1) = 0
=> f(2) = -1

|  / <- (1, 1) (presupunem ca e la 45 grade)
| /
|/____

(1, 1) * M => (1, 2)

|  / <- (1, 2) (ar trebui sa fie aplecata spre stanga)
| /
|/____
```

```math
MSE(w) = SUM (x_i * w - y_i) ^ 2 + lambda * ||w|| ^ 2
(||W|| = W^T * W)
MSE'(w) = SUM 2 * (x_i * 2 - y_i) * x_i + 2 * lambda * w

MSE'(w) = 0

w = (x^T * x + lambda * I) ^ -1 * x^T * y


```

## Lab 7