## 1
![[Снимок экрана 2025-10-05 в 00.40.20.png]]

#### а)
$$
\begin{pmatrix}
1&n\\
0&1
\end{pmatrix}
\cdot
\begin{pmatrix}
1&m\\
0&1
\end{pmatrix}
=
\begin{pmatrix}
1&m+n\\
0&1
\end{pmatrix}
$$
##### б) Матрица поворота
$$
\begin{aligned}
\begin{pmatrix}
\cos \alpha & -\sin \alpha\\
\sin \alpha & \cos \alpha
\end{pmatrix}
\cdot
\begin{pmatrix}
\cos \beta & -\sin \beta\\
\sin \beta & \cos \beta
\end{pmatrix}
=
\begin{pmatrix}
\cos \alpha \cos \beta - \sin \alpha \sin \beta & -(\sin \beta \cos \alpha + \sin \alpha \cos \beta)\\
\sin \alpha \cos \beta + \sin \beta \cos \alpha & \cos \alpha \cos \beta - \sin \alpha \sin \beta
\end{pmatrix}
\\\\=
\begin{pmatrix}
\cos (\alpha + \beta) & -\sin (\alpha + \beta)\\
\sin (\alpha + \beta) & \cos (\alpha + \beta)
\end{pmatrix}
\end{aligned}
$$
## 2

##### в)
$$
\begin{aligned}
\left(
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}
\right)^n
\end{aligned}
$$


$$
\begin{aligned}
\left(
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}
\right)^n
\\\\=
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\left(
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}
	\cdot
	\begin{pmatrix}
	3&-1\\
	-5&2
	\end{pmatrix}
	\cdot
	\begin{pmatrix}
	2&1\\
	5&3
	\end{pmatrix}
\right)^{n-1}
\cdot
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}
	\cdot
	\begin{pmatrix}
	3&-1\\
	-5&2
	\end{pmatrix}
\\\\=
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}^n
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}

\end{aligned}
$$


Рассмотрим несколько первых степеней
$$
\begin{aligned}
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}
	=
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}
	\\\\
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}^2
	=
	\begin{pmatrix}
	1&0\\
	2&1
	\end{pmatrix}
	\\\\
	\begin{pmatrix}
	1&0\\
	1&1
	\end{pmatrix}^3
	=
	\begin{pmatrix}
	1&0\\
	3&1
	\end{pmatrix}
\end{aligned}
$$
Можно заметить общее правило
$$
\begin{pmatrix}
a&b\\
c&d
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}
=
\begin{pmatrix}
a+b&b\\
c+d&d
\end{pmatrix}
$$
из которого следует, что
$$
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}^n
=
\begin{pmatrix}
1&0\\
n&1
\end{pmatrix}
$$

и продолжая исходное равенство
$$
\begin{aligned}
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}^n
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}
=
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
n&1
\end{pmatrix}
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}
\\\\=
\begin{pmatrix}
2+n&1\\
5 + 3n&3
\end{pmatrix}
\cdot
\begin{pmatrix}
3&-1\\
-5&2
\end{pmatrix}
=
\begin{pmatrix}
1 + 3n&-n\\
9n&1 - 3n
\end{pmatrix}
\end{aligned}
$$
## 3
![[Снимок экрана 2025-10-05 в 02.11.09.png]]

Найдем матрицу $X$ такую что $AX = XA$.

$$
\begin{aligned}
AX = 
\begin{pmatrix}
\lambda_1 X_{11}&\lambda_1 X_{12}&\cdots&\lambda_1 X_{1n}\\
\lambda_2 X_{21}&\lambda_2 X_{22}&\cdots&\lambda_2 X_{2n}\\
\vdots&&&\vdots\\
\lambda_{n-1} X_{n-1,1}&\lambda_{n-1} X_{n-1,2}&\cdots&\lambda_2 X_{n-1,n}\\
\lambda_n X_{n1}&\lambda_n X_{n2}&\cdots&\lambda_2 X_{nn}\\
\end{pmatrix}
\\\\
XA = 
\begin{pmatrix}
\lambda_1 X_{11}&\lambda_2 X_{12}&\cdots&\lambda_n X_{1n}\\
\lambda_1 X_{21}&\lambda_2 X_{22}&\cdots&\lambda_n X_{2n}\\
\vdots&&&\vdots\\
\lambda_1 X_{n-1,1}&\lambda_2 X_{n-1,2}&\cdots&\lambda_n X_{n-1,n}\\
\lambda_1 X_{n1}&\lambda_2 X_{n2}&\cdots&\lambda_n X_{nn}\\
\end{pmatrix}
\end{aligned}
$$

Получается $\forall i, j: \,\,\, \lambda_i X_{ij} = \lambda_j X_{ij}$.

То есть на главной диагонали ($i = j$) могут быть любые элементы.

Для остальных элементов ($i \ne j$) либо $\lambda_i = \lambda_j$, либо $X_{ij} = 0$.

Рассмотрим два случая матрицы $A$.

### 1 случай: $\lambda_1 = \lambda_2 = ... = \lambda_n = \lambda$

В таком случае матрица $A = \lambda 1$, а значит любая матрица $X$ коммутирует с $A$

### 2 случай: существует множество индексов $\{k_i \in [1; n - 1]: \lambda_{k_i} > \lambda_{k_i + 1}\}$

Иными словами лямбды имеют вид $\lambda_1 = \lambda_2 = ... = \lambda_{k_1} > \lambda_{k_1 + 1} = ... = \lambda_{k_2} > \lambda_{k_2 + 1} = ...$

Рассмотрим первую строчку. Cледуя принципу
$$
\forall i, j: \,\,\, \lambda_i X_{ij} = \lambda_j X_{ij}
$$
в ней могут быть произвольными ненулевыми только элементы в столбцах с $1$ по $k_1$ так как $\lambda_1$ не равен любому значений $\lambda_i$, где $i > k_1$ и равен любому $\lambda_i$, где $i \le k_1$.

Аналогично в строчках с номерами с $2$ по $k_1$ могут быть ненулевыми только элементы в тех же столбцах. При этом они могут все еще быть произвольными.

Для строчек с номерами с $k_1 + 1$ до $k_2$ аналогично могут быть произвольными ненулевыми элементы в столбцах с $k_1 + 1$ до $k_2$ и тд.

В общем виде матрица $X$ имеет вид
$$
X = 
\begin{pmatrix}
X_{11} & X_{12} & \cdots & X_{1, k_1} & 0 & 0 & \cdots & 0 & 0 \\
X_{21} & X_{22} & \cdots & X_{1, k_1} & 0 & 0 & \cdots & 0 & 0 \\
\vdots&&&&&&&&\vdots\\
X_{k_1, 1} & X_{k_1, 2} & \cdots & X_{k_1, k_1} & 0 & 0 & \cdots & 0 & 0 \\
0 & 0 & \cdots & 0 & X_{k_1 + 1, k_1 + 1} & X_{k_1 + 1, k_1 + 2} & \cdots & X_{k_1 + 1, k_1 + 2} & 0 \\
\end{pmatrix}
$$
