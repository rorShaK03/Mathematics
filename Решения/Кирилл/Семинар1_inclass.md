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
![[Снимок экрана 2025-09-27 в 23.05.33.png]]
При $x \ne 0$ 


