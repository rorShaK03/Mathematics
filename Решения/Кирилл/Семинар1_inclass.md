# 1
![[Снимок экрана 2025-09-27 в 20.20.14.png]]
Знак равенства здесь означает эквивалентность систем.
#### a)
$$
\begin{aligned}
\left(
	\begin{array}{cccc|c}
	3 & 3 & 2 & 2 & 1 \\
	2 & 2 & 1 & 1 & 0
	\end{array}
\right) 
= 
\left(
	\begin{array}{cccc|c}
	3 & 3 & 2 & 2 & 1 \\
	6 & 6 & 3 & 3 & 0
	\end{array}
\right) 
=
\left(
	\begin{array}{cccc|c}
	3 & 3 & 2 & 2 & 1 \\
	0 & 0 & -1 & -1 & -2
	\end{array}
\right)
=
\left(
	\begin{array}{cccc|c}
	3 & 3 & 0 & 0 & -3 \\
	0 & 0 & 1 & 1 & 2
	\end{array}
\right)
\\\\=
\left(
	\begin{array}{cccc|c}
	1 & 1 & 0 & 0 & -1 \\
	0 & 0 & 1 & 1 & 2
	\end{array}
\right)
\end{aligned}
$$
Ответ
$$
\begin{pmatrix}
x_1 \\x_3
\end{pmatrix}
=
\begin{pmatrix}
-1 \\ 2
\end{pmatrix}
-
\begin{pmatrix}
x_2 \\ x_4
\end{pmatrix}
$$
#### б)
$$
\left(
	\begin{array}{cc|c}
		9 & 7 & 5 \\
		5 & 3 & 1
	\end{array}
\right)
=
\left(
	\begin{array}{cc|c}
		9 & 7 & 5 \\
		45 & 27 & 9
	\end{array}
\right)
=
\left(
	\begin{array}{cc|c}
		9 & 7 & 5 \\
		0 & -8 & -16
	\end{array}
\right)
=
\left(
	\begin{array}{cc|c}
		9 & 0 & -9 \\
		0 & 1 & 2
	\end{array}
\right)
=
\left(
	\begin{array}{cc|c}
		1 & 0 & -1 \\
		0 & 1 & 2
	\end{array}
\right)
$$
Ответ
$$
\begin{pmatrix}
x_1 \\
x_2
\end{pmatrix}
=
\begin{pmatrix}
-1 \\
2
\end{pmatrix}
$$
#### в)
$$
\begin{aligned}
\left(
	\begin{array}{ccc|c}
	2 & 1 & 1 & 1 \\
	1 & 2 & 1 & 0 \\
	1 & 1 & 2 & 0
	\end{array}
\right)
=
\left(
	\begin{array}{ccc|c}
	1 & 2 & 1 & 0 \\
	1 & 1 & 2 & 0 \\
	2 & 1 & 1 & 1
	\end{array}
\right)
=
\left(
	\begin{array}{ccc|c}
	1 & 2 & 1 & 0 \\
	0 & -1 & 1 & 0 \\
	0 & -3 & -1 & 1
	\end{array}
\right)
\\\\=
\left(
	\begin{array}{ccc|c}
	1 & 2 & 1 & 0 \\
	0 & -1 & 1 & 0 \\
	0 & 0 & -4 & 1
	\end{array}
\right)
=
\left(
	\begin{array}{ccc|c}
	1 & 2 & 1 & 0 \\
	0 & -1 & 1 & 0 \\
	0 & 0 & 1 & -\frac{1}{4}
	\end{array}
\right)
=
\left(
	\begin{array}{ccc|c}
	1 & 2 & 1 & 0 \\
	0 & -1 & 0 & \frac{1}{4} \\
	0 & 0 & 1 & -\frac{1}{4}
	\end{array}
\right)
\\\\=
\left(
	\begin{array}{ccc|c}
	1 & 0 & 0 & \frac{3}{4} \\
	0 & -1 & 0 & \frac{1}{4} \\
	0 & 0 & 1 & -\frac{1}{4}
	\end{array}
\right)
=
\left(
	\begin{array}{ccc|c}
	1 & 0 & 0 & \frac{3}{4} \\
	0 & 1 & 0 & -\frac{1}{4} \\
	0 & 0 & 1 & -\frac{1}{4}
	\end{array}
\right)
\end{aligned}
$$
Ответ
$$
\begin{pmatrix}
x_1 \\ x_2 \\ x_3
\end{pmatrix}
=
\begin{pmatrix}
\frac{3}{4} \\ -\frac{1}{4} \\ -\frac{1}{4}
\end{pmatrix}
$$
# 2
![[Снимок экрана 2025-09-27 в 22.49.05.png]]
Поменяем местами 1 и 3 столбцы. При этом произойдет замена $x_1 = y_3, \, x_2 = y_2, \, x_3 = y_1$
$$
\left(
	\begin{array}{ccc|c}
		1 & 0 & 2 & 1 \\
		0 & 1 & 3 & 1
	\end{array}
\right)
$$
А значит
$$
\begin{pmatrix}
y_1 \\ y_2
\end{pmatrix}
=
\begin{pmatrix}
1 \\ 1
\end{pmatrix}
-
y_3
\begin{pmatrix}
2 \\ 3
\end{pmatrix}
$$
Ответ
$$
\begin{pmatrix}
x_3 \\ x_2
\end{pmatrix}
=
\begin{pmatrix}
1 \\ 1
\end{pmatrix}
-
x_1
\begin{pmatrix}
2 \\ 3
\end{pmatrix}
$$
# 3
![[Снимок экрана 2025-09-27 в 22.59.31.png]]
#### a) 

$$ A={\left(\begin{array}{l l l l}{x}&{1}&{\cdots}&{1}\\ {1}&{x}&{\cdots}&{1}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {1}&{1}&{\cdots}&{x}\end{array}\right)}$$
Пусть $x \ne 1$

Вычтем из всех строк $(n)$-ю. Получим
$$
{\left(\begin{array}{l l l l}{x - 1}&{0}&{\cdots}&{1- x}\\ {0}&{x - 1}&{\cdots}&{1 - x}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {1}&{1}&{\cdots}&{x}\end{array}\right)}
$$
А теперь вычтем из последней все строки деленные на $(x - 1)$
$$
{\left(\begin{array}{l l l l}{x - 1}&{0}&{\cdots}&{1- x}\\ {0}&{x - 1}&{\cdots}&{1 - x}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {0}&{0}&{\cdots}&{x - (-1)(n - 1)}\end{array}\right)}
=
{\left(\begin{array}{l l l l}{x - 1}&{0}&{\cdots}&{1- x}\\ {0}&{x - 1}&{\cdots}&{1 - x}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {0}&{0}&{\cdots}&{x + n - 1}\end{array}\right)}
$$

То есть все переменные - главные.

Пусть теперь $x = 1$, тогда матрица состоит полностью из единиц и ОСЛАУ имеет одну главную переменную.

#### б) Несколько замен переменных

Рассмотрим матрицу подсистемы состоящую из строк с $(3)$ по $(n - 2)$.
$$
\begin{pmatrix}
1&1&1&\cdots&1&x&1&1\\
1&1&1&\cdots&x&1&1&1\\
&&&\vdots\\
1&1&x&\cdots&1&1&1&1
\end{pmatrix}
$$
В ней вычтем из предыдущей строчки следующую и получим
$$
\begin{pmatrix}
0&0&0&\cdots&1-x&x-1&0&0\\
0&0&0&\cdots&x-1&0&0&0\\
&&&\vdots\\
1&1&x&\cdots&1&1&1&1
\end{pmatrix}
$$
Это значит в любом решении СЛАУ $x_4 = x_5 = x_6 = ... = x_{n - 2}$. Раз так, то можно сделать замену:
$$
\begin{aligned}
y_1 = x_1 \\
y_2 = x_2 \\
y_3 = x_3 \\
y_4 = x_4 \\
y_5 = x_{n - 1} \\
y_6 = x_n
\end{aligned}
$$
И матрица новой системы будет
$$
\begin{pmatrix}
x&x&1&(n - 4)&x&x\\
1&1&1&(n-5+x)&x&x\\
1&1&1&(n-5+x)&1&1\\
&&&\vdots\\
1&1&1&(n-5+x)&1&1\\
1&1&x&(n-4)&1&x\\
1&x&1&(n-4)&1&x
\end{pmatrix}
$$
Все строчки с $(3)$-ей по $(n-2)$ будут одинаковыми, поэтому сократим все кроме одной.
$$
\begin{pmatrix}
x&x&1&(n - 4)&x&x\\
1&1&1&(n-5+x)&x&x\\
1&1&1&(n-5+x)&1&1\\
1&1&x&(n-4)&1&x\\
1&x&1&(n-4)&1&x
\end{pmatrix}
$$
Вычтем из $(4)$-й строчки $(5)$-ю, из $(2)$-й $(3)$-ю и из $(1)$-й $(5)$-ю.
$$
\begin{pmatrix}
x-1&0&0&0&x-1&0\\
0&0&0&0&x-1&x-1\\
1&1&1&(n-5+x)&1&1\\
0&1-x&x-1&0&0&0\\
1&x&1&(n-4)&1&x
\end{pmatrix}
$$
А значит $y_1 = -y_5$, $y_5 = -y_6$ и $y_2 = y_3$. Сделаем еще одну замену
$$
\begin{aligned}
z_1 = y_1 = x_1\\
z_2 = y_2 = x_2\\
z_3 = y_4 = x_4
\end{aligned}
$$
И матрица новой системы будет
$$
\begin{pmatrix}
x&x+1&(n - 4)\\
1&2&(n-5+x)\\
1&2&(n-5+x)\\
x&1+x&(n-4)\\
x&1+x&(n-4)
\end{pmatrix}
$$
Вычеркнем одинаковые строки
$$
\begin{pmatrix}
x&x+1&(n - 4)\\
1&2&(n-5+x)\\
\end{pmatrix}
$$
Вычтем из $(1)$ строчки строчку $(2) \cdot x$
$$
\begin{aligned}
\begin{pmatrix}
1&2&(n-5+x)\\
0&1-x&n - 4 - nx + 5x - x^2
\end{pmatrix}
=
\begin{pmatrix}
1&2&(n-5+x)\\
0&1-x& -x^2 + (5-n)x + (n-4)
\end{pmatrix}
\\\\=
\begin{pmatrix}
1&2&(n-5+x)\\
0&1-x& (1-x)(x - 4 + n)
\end{pmatrix}
\end{aligned}
$$
При $x \ne 1$ это равносильно
$$
\begin{aligned}
\begin{pmatrix}
1&2&n-5+x\\
0&1-x& (1-x)(x - 4 + n)
\end{pmatrix}
=
\begin{pmatrix}
1&2&n-5+x\\
0&1&x - 4 + n
\end{pmatrix}
=
\begin{pmatrix}
1&0&n-5+x - 2x + 8 -2n\\
0&1&x - 4 + n
\end{pmatrix}
=
\begin{pmatrix}
1&0&n-5+x - 2x + 8 -2n\\
0&1&x - 4 + n
\end{pmatrix}
\end{aligned}
$$


##

#### в) Вычтем из строчки $(i)$ строчку $(n - i)$. Для нижней строчки будем вычитать последующую строчку

#### г) 


# 4

## $(i) \leftrightarrow (j)$

Тогда
$$
\begin{aligned}
x'_{i} = x_{j}\\
x'_{j} = x_{i}
\end{aligned}
$$
## $\lambda (i)$
$$
x'_{i} = \frac{x_{i}} {\lambda}
$$

## Если столбцы $(i)$ и $(j)$ одинаковы можно убрать столбец $(j)$

$$
y_i = x_i + x_j
$$
