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
 и разделим на 2. Тогда матрица будет
$$
\begin{pmatrix}
1 & x & 1 \\
x & 1 & x \\
x & 1 & 1 \\
1 & 1 & x
\end{pmatrix}
$$



