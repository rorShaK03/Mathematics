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
A_{mn} = \begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n}  \\
a_{21} & a_{22} & \cdots & a_{2n}  \\
\vdots &        &.       & \vdots  \\
a_{m1} & a_{m2} & \cdots & a_{mn}  \\
\end{pmatrix}
$$

Для начала будем считать, что $m = n$
## 1. Получим диагональную матрицу
Рассмотрим $a_{11}$ и $a_{12}$. Проведем между ними алгоритм Евклида, при помощи элементарных операций над первыми двумя строками. Если после этого ненулевое число оказалось во второй строчке поменяем первые две строки местами
$$
\begin{pmatrix}
НОД(a_{11}, a_{12}) & a'_{12} & \cdots & a'_{1n}  \\
0 & a'_{22} & \cdots & a'_{2n}  \\
\vdots &        &.       & \vdots  \\
a_{n1} & a_{n2} & \cdots & a_{nn}  \\
\end{pmatrix}
$$
Штрихами покажем элементы, которые могли поменяться.

Теперь $a_{12} = 0$. Аналогично занулим все числа в первом столбце и потом в первой строке (при помощи элементарных преобразований столбцов). 
$$
\begin{pmatrix}
gcd_{11} & 0 & \cdots & 0  \\
0 & a''_{22} & \cdots & a''_{2n}  \\
\vdots &        &.       & \vdots  \\
0 & a''_{n2} & \cdots & a''_{nn}  \\
\end{pmatrix}
$$

Теперь проведем то же самое для минора без первой строки и первого столбца. И так далее для правых нижних миноров. Получим диагональную матрицу
$$
\begin{pmatrix}
gcd_{11} & 0 & \cdots & 0  \\
0 & gcd_{22} & \cdots & 0  \\
\vdots &        &.       & \vdots  \\
0 & 0 & \cdots & gcd_{nn}  \\
\end{pmatrix}
$$

## 2. Превратим диагональ в последовательность делителей

Прибавим к первому столбцу все остальные и опять занулим все элементы в нем кроме первого алгоритмом Евклида. При этом правые нижние миноры никак не поменяются так как в первой строке все элементы кроме первого нули. А еще в первом элементе окажется $НОД(gcd_{11}, gcd_{22}, ..., gcd_{nn})$.

Теперь прибавим ко второму столбцу все столбцы начиная с третьего и тоже проведем алгоритм Евклида. Это тоже не поменяет следующие миноры при этом в $gcd_{22}$ окажется $НОД(gcd_{22}, gcd_{33}, ..., gcd_{nn})$.

По свойствам НОД выполнится свойство что каждый предыдущий элемент в диагонали делит следующий чтд.


Пусть  $m < n$ тогда после тех же преобразований получим матрицу
$$
\begin{pmatrix}
gcd_{11} & 0 & \cdots & 0 & 0 & \cdots & 0  \\
0 & gcd_{22} & \cdots & 0 & 0 & \cdots & 0 \\
\vdots &        &.       & \vdots  \\
0 & 0 & \cdots & gcd_{nn} & 0 & \cdots & 0  \\
\end{pmatrix}
$$

или если $m > n$, то матрицу
$$
\begin{pmatrix}
gcd_{11} & 0 & \cdots & 0  \\
0 & gcd_{22} & \cdots & 0  \\
\vdots &        &.       & \vdots  \\
0 & 0 & \cdots & gcd_{nn}  \\
0 & 0 & \cdots & 0 \\
\vdots & & & \vdots \\
0 & 0 & \cdots & 0
\end{pmatrix}
$$
при этом для элементов на главной диагонали "подквадрата" будут выполняться те же свойства.

В общем виде матрица будет иметь вид, описанный в условии:
$$
\begin{pmatrix}
diag(d_1, ..., d_r) & 0 \\
0 & 0
\end{pmatrix}
$$
при этом $d_i | d_{i + 1}$

# 6

Рассмотрим матрицу $A$. Если система $Ax = 0$ имеет ровно одно решение, то это решение нулевое. А это значит, что после прохода алгоритма Гаусса матрица $A$ приводится к виду
$$
\begin{pmatrix}
1 & 0 & \cdots & 0 \\
0 & 1 & \cdots & 0 \\
\vdots & & & \vdots \\
0 & 0 & \cdots & 1
\end{pmatrix}
$$

А значит, что после прохода алгоритма Гаусса по СЛАУ $(A|B)x = b$ она будет иметь вид:
$$
\left(
	\begin{array}{cccccccc|c}
	1 & 0 & \cdots & 0 & B'_{11} & B'_{12} & \cdots & B'_{1n} & b'_1 \\
	0 & 1 & \cdots & 0 & B'_{21} & B'_{22} & \cdots & B'_{2n} & b'_2 \\
	\vdots & & & \vdots & \vdots & & & \vdots & \vdots \\
	0 & 0 & \cdots & 1 & B'_{m1} & B'_{m2} & \cdots & B'_{mn} & b'_m
	\end{array}
\right)
$$
В такой СЛАУ $n$ свободных переменных и существует решение
$$
\begin{pmatrix}
x_1 \\ x_2 \\ \vdots \\ x_n
\end{pmatrix}
=
\begin{pmatrix}
b'_1 \\ b'_2 \\ \vdots \\ b'_m
\end{pmatrix}
-
x_{m + 1}
\begin{pmatrix}
B'_{11} \\ B'_{21} \\ \vdots \\ B'_{m1}
\end{pmatrix}
-...-
x_{m + n}
\begin{pmatrix}
B'_{1n} \\ B'_{2n} \\ \vdots \\ B'_{mn}
\end{pmatrix}
$$
а значит решений бесконечно много.

# 7
Количество ступенек в ступенчатом виде = количеству главных переменных в СЛАУ. Когда мы меняем два столбца местами
