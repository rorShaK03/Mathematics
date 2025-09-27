# 1
$$
\left(
\begin{array}{cccc|c}
12 & 9 & 3 & 10 & 13 \\
4 & 3 & 1 & 2 & 3 \\
8 & 6 & 2 & 5 & 7
\end{array}
\right)
=
\left(
\begin{array}{cccc|c}
0 & 0 & 0 & 3 & 3 \\
4 & 3 & 1 & 2 & 3 \\
0 & 0 & 0 & 1 & 1
\end{array}
\right)
=
\left(
\begin{array}{cccc|c}
4 & 3 & 1 & 0 & 0 \\
0 & 0 & 0 & 1 & 1
\end{array}
\right)
$$
Ответ
$$
\begin{pmatrix}
x_{3} \\
x_{4}
\end{pmatrix}
=
\begin{pmatrix}
0 \\
1
\end{pmatrix}
-
x_{1}\begin{pmatrix}
4 \\
0
\end{pmatrix}
-
x_{2}
\begin{pmatrix}
3 \\
0
\end{pmatrix}
$$
## 2

Пусть $\lambda \ne 0$
$$
\begin{aligned}
\left(
\begin{array}{\mathbb{ccc|c}}
(1 + \lambda) & 1 & 1 & 1 \\
1 & (1 + \lambda) & 1 & \lambda \\
1 & 1 & (1 + \lambda) & \lambda^2
\end{array}
\right)
=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & -\lambda & -\lambda^2 - 2\lambda & 1 - \lambda^2(1 + \lambda) \\
0 & \lambda & -\lambda & -\lambda^2 + \lambda \\
1 & 1 & (1 + \lambda) & \lambda^2
\end{array}
\right)
\\\\=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & 0 & -\lambda^2 - 3\lambda & 1 - \lambda^2(1 + \lambda) - \lambda^2 + \lambda \\
0 & \lambda & -\lambda & -\lambda^2 + \lambda \\
1 & 1 & (1 + \lambda) & \lambda^2
\end{array}
\right)
=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & 0 & -\lambda^2 - 3\lambda & -\lambda^3 - 2\lambda^2 + \lambda + 1 \\
0 & 1 & -1 & -\lambda + 1 \\
1 & 1 & (1 + \lambda) & \lambda^2
\end{array}
\right)
\\ \\=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & 0 & 1 &  \lambda - 1 + \frac{2\lambda - 1}{\lambda^2 + 3\lambda}\\
0 & 1 & 0 & \frac{2\lambda - 1}{\lambda^2 + 3\lambda} \\
1 & 1 & (1 + \lambda) & \lambda^2
\end{array}
\right)
=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & 0 & 1 &  \lambda - 1 + \frac{2\lambda - 1}{\lambda^2 + 3\lambda}\\
0 & 1 & 0 & \frac{2\lambda - 1}{\lambda^2 + 3\lambda} \\
1 & 0 & 0 & \lambda^2 - \frac{2\lambda - 1}{\lambda^2 + 3\lambda} - (1 + \lambda)(\lambda - 1 + \frac{2\lambda - 1}{\lambda^2 + 3\lambda})
\end{array}
\right)
\\ \\=
\left(
\begin{array}{\mathbb{ccc|c}}
0 & 0 & 1 &  \lambda - 1 + \frac{2\lambda - 1}{\lambda^2 + 3\lambda}\\
0 & 1 & 0 & \frac{2\lambda - 1}{\lambda^2 + 3\lambda} \\
1 & 0 & 0 & \frac{3\lambda + 2}{\lambda + 3}
\end{array}
\right)
\end{aligned}
$$
Пусть $\lambda = 0$, тогда
$$
\begin{align}
\left(
\begin{array}{\mathbb{ccc|c}}
1 & 1 & 1 & 1 \\
1 & 1 & 1 & 0 \\
1 & 1 & 1 & 0
\end{array}
\right)
\end{align}
$$
очевидно эта СЛАУ решений не имеет.

# 3
$$
\begin{align}
f(x) = Ax^2 + Bx + C \\
f(1) = A + B + C = 8 \\
f(-1) = A - B + C = 2 \\
f(2) = 4A + 2B +C = 14
\end{align}
$$
В матричном виде
$$
\begin{align}
\left(
\begin{array}{\mathbb{ccc|c}}
1 & 1 & 1 & 8 \\
1 & -1 & 1 & 2 \\
4 & 2 & 1 & 14
\end{array}
\right)
=
\left(
\begin{array}{\mathbb{ccc|c}}
1 & 1 & 1 & 8 \\
0 & -2 & 0 & -6 \\
0 & -2 & -3 & -18
\end{array}
\right) = \\ \\
\left(
\begin{array}{\mathbb{ccc|c}}
1 & 1 & 1 & 8 \\
0 & -2 & 0 & -6 \\
0 & 0 & -3 & -12
\end{array}
\right) =
\left(
\begin{array}{\mathbb{ccc|c}}
1 & 0 & 0 & 1 \\
0 & 1 & 0 & 3 \\
0 & 0 & 1 & 4
\end{array}
\right)
\end{align}
$$
Ответ: $f(x) = x^2 + 3x + 4$

# 4
$$
\begin{pmatrix}
1 & x & 1 & 1 & x & 1 \\
x & 1 & x & x & 1 & x \\
x & 1 & 1 & 1 & 1 & x \\
1 & x & 1 & 1 & x & 1 \\
1 & 1 & x & x & 1 & 1
\end{pmatrix}
=
\begin{pmatrix}
1 & x & 1 & 1 & x & 1 \\
x & 1 & x & x & 1 & x \\
x & 1 & 1 & 1 & 1 & x \\
1 & 1 & x & x & 1 & 1
\end{pmatrix}
$$
По равенству столбцов
$$
\begin{align}
(1) = (6) \\
(2) = (5)  \\
(3) = (4)
\end{align}
$$
сделаем замену
$$
\begin{align}
y_{1} = x_{1} + x_{6} \\
y_{2} = x_{2} + x_{5} \\
y_{3} = x_{3} + x_{4}
\end{align}
$$
 Тогда матрица будет
$$
\begin{pmatrix}
1 & x & 1 \\
x & 1 & x \\
x & 1 & 1 \\
1 & 1 & x
\end{pmatrix}
=
\begin{pmatrix}
1 & x & 1 \\
x & 1 & x \\
0 & 0 & 1 - x \\
0 & 1 - x & x - 1
\end{pmatrix}
$$

### Пусть $x \ne 1$

Тогда $y_{3} = 0$, но тогда $y_{2} = 0$ и $y_{1} = 0$. Делая обратную замену, есть только 3 главных переменных.

### Пусть $x = 1$

Тогда матрица имеет вид
$$
\begin{pmatrix}
1 & 1 & 1 \\
\end{pmatrix}
$$
То есть $y_{1} = -y_{2} - y_{3}$. Делая обратную замену $x_{1} + x_{6} = -x_{2} - x_{5} - x_{3} - x_{4}$ или $x_{1} = -x_{2} - x_{3} - x_{4} - x_{5} - x_{6}$. То есть только одна главная переменная.


# 5

Пусть дана матрица
$$
A = \begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n}  \\
a_{21} & a_{22} & \cdots & a_{2n}  \\
\vdots &        &.       & \vdots  \\
a_{m1} & a_{m2} & \cdots & a_{mn}  \\
\end{pmatrix}
$$

### 1. Модифицированный прямой ход алгоритма Гаусса

Использую элементарные операции 1 типа с целыми параметрами и 3 типа с параметром $\pm 1$, мы можем привести $A$ к верхнетреугольному виду
$$
A = \begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n}  \\
0 & a_{22} & \cdots & a_{2n}  \\
\vdots &        &       & \vdots  \\
0 & 0 & \cdots & a_{mn}  \\
\end{pmatrix}
$$
#### Доказательство
Нам достаточно доказать, что если есть числа $a$ и $b$, мы можем несколькими операциями $a \pm \lambda b$ и $b \pm \lambda a$ c целым $\lambda$ сделать $b$ равным нулю или $a$ равным нулю (тогда просто потом поменяем строки местами).

Но мы здесь можем действовать точно как в алгоритме Евклида, а мы знаем что он рано или поздно сходится к нулю.

Пользуясь этим фактом как в прямом проходе алгоритма Гаусса добьемся того, что все числа в первом столбце кроме первого равны нулю, во втором столбце кроме первого и второго и так далее.

Заметим, что числа в матрице все еще остались целыми так как мы не используем деление.

## 2. Модифицированный обратный ход

Полностью аналогично зануляя элементы сверху сделаем матрицу диагональной. Сначала последней строкой зануляем последний столбец, потом предпоследней строкой предпоследний столбец и тд





