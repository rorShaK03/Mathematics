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
Вычтем из всех строк $(n)$-ю. Получим
$$
{\left(\begin{array}{l l l l}{x - 1}&{0}&{\cdots}&{1- x}\\ {0}&{x - 1}&{\cdots}&{1 - x}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {1}&{1}&{\cdots}&{x}\end{array}\right)}
$$
##### Пусть $x \ne 1$
Поделим все строки кроме последней на $x - 1$ и вычтем из последней

$$
{\left(\begin{array}{l l l l}{1}&{0}&{\cdots}&{-1}\\ {0}&{1}&{\cdots}&{-1}\\ {\vdots}&{\vdots}&{\ddots}&{\vdots}\\ {0}&{0}&{\cdots}&{x + n - 1}\end{array}\right)}
$$
###### Пусть $x = 1 - n$
Тогда последняя строчка зануляется и $n - 1$ главная переменная.

###### Пусть $x \ne 1 - n$
Тогда $n$ главных переменных

##### Пусть $x = 1$
Тогда исходная матрица состоит полностью из единиц и у нее одна главная переменная.

**Ответ:** 
- если $x = 1$, то $1$ главная переменная
- если $x = 1 - n$, то $n - 1$ главная переменная
- если $x \ne 1$ и $x \ne 1 - n$, то $n$ главных переменных

#### б)

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
\begin{pmatrix}
x_1\\
x_2\\
x_3\\
x_4\\
x_5\\
\vdots\\
x_{n-2}\\
x_{n - 1}\\
x_n
\end{pmatrix}
=
\begin{pmatrix}
y_1\\
y_2\\
y_3\\
y_4\\
y_4\\
\vdots\\
y_4\\
y_5\\
y_6
\end{pmatrix}
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
\begin{pmatrix}
y_1\\
y_2\\
y_3\\
y_4\\
y_5\\
y_6\\
\end{pmatrix}
=
\begin{pmatrix}
z_1\\
z_2\\
z_2\\
z_3\\
-z_1\\
z_1
\end{pmatrix}
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
##### При $x \ne 1$ 
это равносильно
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
\\\\=
\begin{pmatrix}
1&0&n-5+x - 2x + 8 -2n\\
0&1&x - 4 + n
\end{pmatrix}
=
\begin{pmatrix}
1&0&-n-x+3\\
0&1&x - 4 + n
\end{pmatrix}
\end{aligned}
$$
Решение
$$
\begin{pmatrix}
z_1\\
z_2
\end{pmatrix}
=
z_3
\begin{pmatrix}
n + x - 3\\
-x - n + 4
\end{pmatrix}
$$
То есть $z_3$, свободная переменная. А значит делая обратную замену получим, что $x_4 = z_3$ задает все остальные переменные, выражаемые через $z_1$, $z_2$ и $z_3$. 

Ответ:  $n - 1$ главных.

##### При $x = 1$ 
Исходная матрица до всех замен превращается в матрицу из единиц, в которой только одна главная переменная.

Ответ: 1 главная переменная.

**Ответ:** если $x \ne 1$, то $n - 1$ главная переменная, если $x = 1$, то $1$ главная переменная.

#### в)
Считаем что $n$ всегда четное (в условии есть на это намеки, но уточню дополнительно).

Для первых $\frac{n}{2}$ строк вычтем строку с номером $(n - i)$. Получится
$$
\begin{pmatrix}
x&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&x&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&x&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&x&0&\cdots&0&0&0&0\\
1&1&1&1&\cdots&1&x&\cdots&1&1&1&1\\
\vdots&&&&&&&&&&&\vdots\\
1&1&1&1&\cdots&1&1&\cdots&1&x&1&1\\
1&1&1&1&\cdots&1&1&\cdots&1&1&x&1\\
1&1&1&1&\cdots&1&1&\cdots&1&1&1&x\\
\end{pmatrix}
$$
Теперь вычтем $(n)$-ю строчку из строчек с $(\frac{n}{2} + 1)$ до $(n - 1)$:
$$
\begin{pmatrix}
x&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&x&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&x&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&x&0&\cdots&0&0&0&0\\
0&0&0&0&\cdots&0&x-1&\cdots&0&0&0&1-x\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&0&\cdots&0&x-1&0&1-x\\
0&0&0&0&\cdots&0&0&\cdots&0&0&x-1&1-x\\
1&1&1&1&\cdots&1&1&\cdots&1&1&1&x\\
\end{pmatrix}
$$
##### При $x = 1$
Строчки с номерами от $(\frac{n}{2} + 1)$ до $(n - 1)$ зануляются. Матрица имеет вид
$$
\begin{pmatrix}
1&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&1&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&1&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&1&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
1&1&1&1&\cdots&1&1&\cdots&1&1&1&1\\
\end{pmatrix}
$$
вычтем все строчки из последней
$$
\begin{pmatrix}
1&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&1&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&1&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&1&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&1&\cdots&1&1&1&1\\
\end{pmatrix}
$$
то есть $\frac{n}{2} + 1$ главная переменная.
##### При $x = 0$
Строчки с номерами от $(1)$ до $\frac{n}{2}$ зануляются. Матрица имеет вид
$$
\begin{pmatrix}
0&0&0&0&\cdots&0&-1&\cdots&0&0&0&1\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&0&\cdots&0&-1&0&1\\
0&0&0&0&\cdots&0&0&\cdots&0&0&-1&1\\
1&1&1&1&\cdots&1&1&\cdots&1&1&1&0\\
\end{pmatrix}
$$
Прибавим все предыдущие строчки к последней
$$
\begin{pmatrix}
0&0&0&0&\cdots&0&-1&\cdots&0&0&0&1\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&0&\cdots&0&-1&0&1\\
0&0&0&0&\cdots&0&0&\cdots&0&0&-1&1\\
1&1&1&1&\cdots&1&0&\cdots&0&0&0&\frac{n}{2}-1\\
\end{pmatrix}
$$
То есть $\frac{n}{2}$ главных переменных.
##### При $x \ne 1$ и $x \ne 0$

Поделим первые $\frac{n}{2}$ строчек на $x$, а строчки с $(\frac{n}{2} + 1)$ по $(n - 1)$ на $x$.
$$
\begin{pmatrix}
1&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&1&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&1&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&1&0&\cdots&0&0&0&0\\
0&0&0&0&\cdots&0&1&\cdots&0&0&0&-1\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&0&\cdots&0&1&0&-1\\
0&0&0&0&\cdots&0&0&\cdots&0&0&1&-1\\
1&1&1&1&\cdots&1&1&\cdots&1&1&1&x\\
\end{pmatrix}
$$
И вычтем все предыдущие строчки из последней
$$
\begin{pmatrix}
1&0&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&1&0&0&\cdots&0&0&\cdots&0&0&0&0\\
0&0&1&0&\cdots&0&0&\cdots&0&0&0&0\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&1&0&\cdots&0&0&0&0\\
0&0&0&0&\cdots&0&1&\cdots&0&0&0&-1\\
\vdots&&&&&&&&&&&\vdots\\
0&0&0&0&\cdots&0&0&\cdots&0&1&0&-1\\
0&0&0&0&\cdots&0&0&\cdots&0&0&1&-1\\
0&0&0&0&\cdots&0&0&\cdots&0&0&0&x+\frac{n}{2}-1\\
\end{pmatrix}
$$
Получается при $x \ne 1 - \frac{n}{2}$ $n$ главных переменных.

При $x = 1 - \frac{n}{2}$ $n - 1$ главная переменная.

**Ответ:** 
- при $x = 0$ $\frac{n}{2}$ главных переменных
- при $x = 1$ $\frac{n}{2} + 1$ главная переменная
- при $x \notin \{0; 1\}$ и $x = 1 - \frac{n}{2}$ $n - 1$ главная переменная
- при других $x$ $n$ главных переменных

#### г) 
Вычтем из $(1)$-ой строчки $(2)$-ю и потом вычтем строчки: $(3) - (1)$, $(4) - 2(1)$, $(5) - 3(1)$, ..., $(n) - [n - 3 + 1](1)$:
$$
\begin{pmatrix}
1&1&1&\cdots&1&1&1\\
-1&0&1&\cdots&n-3&n-2&n-1\\
-1&0&1&\cdots&n-3&n-2&n-1\\
\vdots&&&&&&\vdots\\
-1&0&1&\cdots&n-3&n-2&n-1\\
\end{pmatrix}
$$
Уберем одинаковые строчки
$$
\begin{pmatrix}
1&1&1&\cdots&1&1&1\\
-1&0&1&\cdots&n-3&n-2&n-1\\
\end{pmatrix}
$$
Прибавим $(1)$ ко $(2)$
$$
\begin{pmatrix}
1&1&1&\cdots&1&1&1\\
0&1&2&\cdots&n-2&n-1&n\\
\end{pmatrix}
$$
Вычтем $(2)$ из $(1)$:
$$
\begin{pmatrix}
1&0&-1&\cdots&3-n&2-n&1-n\\
0&1&2&\cdots&n-2&n-1&n\\
\end{pmatrix}
$$

**Ответ**: 2 главных переменных.


# 4

## Поменять столбцы местами: $(i) \leftrightarrow (j)$

Тогда
$$
\begin{aligned}
x'_{i} = x_{j}\\
x'_{j} = x_{i}
\end{aligned}
$$
## Умножение столбца: $\lambda (i)$
$$
x'_{i} = \frac{x_{i}} {\lambda}
$$

## Прибавить к столбцу $(i)$ произведение $\lambda(j)$

$$
y_i = x_i + x_j
$$
