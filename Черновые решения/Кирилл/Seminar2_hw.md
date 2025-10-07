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
X_{11} & X_{12} & \cdots & X_{1, k_1} & 0 & 0 & \cdots & 0 & \cdots \\
X_{21} & X_{22} & \cdots & X_{1, k_1} & 0 & 0 & \cdots & 0 & \cdots \\
\vdots&&&&&&&\vdots\\
X_{k_1, 1} & X_{k_1, 2} & \cdots & X_{k_1, k_1} & 0 & 0 & \cdots & 0 & \cdots \\
0 & 0 & \cdots & 0 & X_{k_1 + 1, k_1 + 1} & X_{k_1 + 1, k_1 + 2} & \cdots & X_{k_1 + 1, k_2} & \cdots \\
0 & 0 & \cdots & 0 & X_{k_1 + 2, k_1 + 1} & X_{k_1 + 2, k_1 + 2} & \cdots & X_{k_1 + 2, k_2} & \cdots \\
\vdots&&&&\vdots&&&\vdots\\
0 & 0 & \cdots & 0 & X_{k_2, k_1 + 1} & X_{k_2, k_1 + 2} & \cdots & X_{k_2, k_2} & \cdots \\
\vdots&&&&\vdots&&&\vdots\\
\end{pmatrix}
$$

Значения обозначенные $X_{ij}$ могут принимать любые числовые значения. Можно заметить, что первый случай просто вырожденный второй (размер "подквадрата" равен $n$)

## 4
![[Снимок экрана 2025-10-05 в 19.09.47.png]]
##### a)
Пусть
$$
SHIFT_n = 
\begin{pmatrix}
0&1&0&0&\cdots&0\\
0&0&1&0&\cdots&0\\
0&0&0&1&\cdots&0\\
\vdots&&&&&\vdots\\
0&0&0&0&\cdots&1\\
0&0&0&0&\cdots&0\\
\end{pmatrix}
$$

Тогда
$$
\begin{aligned}
J(\lambda) = \lambda E + SHIFT \\
AJ(\lambda) = \lambda A + A\cdot SHIFT \\
J(\lambda)A = \lambda A + SHIFT \cdot A
\end{aligned}
$$
а значит
$$
AJ(\lambda) - J(\lambda)A = A \cdot SHIFT - SHIFT \cdot A = 0
$$
По материалу семинара матрица $A$ может иметь только такой вид
$$
A = 
\begin{pmatrix}
a_1&a_2&a_3&\cdots&a_{n-1}&a_n\\
0&a_1&a_2&\cdots&a_{n-2}&a_{n-1}\\
\vdots&&&&&\vdots\\
0&0&0&\cdots&a_1&a_2\\
0&0&0&\cdots&0&a_1
\end{pmatrix}
$$


##### b)

В силу того что матрицы $(\lambda E)^{p_1}$ и $SHIFT^{p_2}$ коммутативны по умножению $\forall p_1, p_2$, мы можем применить бином Ньютона
$$
J(\lambda)^k = (\lambda E + SHIFT)^k = \sum_{i = 0}^k C_k^i (\lambda E)^i SHIFT^{k - i} = \sum_{i = 0}^k C_k^i \lambda^i SHIFT^{k - i}
$$
Посмотрим из чего состоит выражение

- $C_k^i \lambda^i$ - числовое выражение
- $SHIFT^{k - i}$ - матрица сдвига. Она соответствует сдвигу единичной матрицы на $k - i$ столбцов вправо. Иными словами
$$
\begin{align}
SHIFT^0 =
\begin{pmatrix}
1&0&0&0&\cdots&0&0\\
0&1&0&0&\cdots&0&0\\
0&0&1&0&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&1&0\\
0&0&0&0&\cdots&0&1\\
\end{pmatrix} \\\\

SHIFT^1 =
\begin{pmatrix}
0&1&0&0&\cdots&0&0\\
0&0&1&0&\cdots&0&0\\
0&0&0&1&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&0&1\\
0&0&0&0&\cdots&0&0\\
\end{pmatrix} \\\\

SHIFT^2 =
\begin{pmatrix}
0&0&1&0&\cdots&0&0\\
0&0&0&1&\cdots&0&0\\
0&0&0&0&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&0&0\\
0&0&0&0&\cdots&0&0\\
\end{pmatrix} \\\\
\end{align}
$$
и тд.

Таким образом $k$-й член суммы, например, равен
$$
\begin{pmatrix}
C_k^k \lambda^k&0&0&0&\cdots&0&0\\
0&C_k^k \lambda^k&0&0&\cdots&0&0\\
0&0&C_k^k \lambda^k&0&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&C_k^k \lambda^k&0\\
0&0&0&0&\cdots&0&C_k^k \lambda^k\\
\end{pmatrix}
$$
а $k-1$-й равен
$$
\begin{pmatrix}
0&C_k^{k-1} \lambda^{k-1}&0&0&\cdots&0&0\\
0&0&C_k^{k-1} \lambda^{k-1}&0&\cdots&0&0\\
0&0&0&C_k^{k-1} \lambda^{k-1}&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&0&C_k^{k-1} \lambda^{k-1}\\
0&0&0&0&\cdots&0&0\
\end{pmatrix}
$$
и общая сумма имеет вид, описанный в условии. При это для $k - i \ge n$ будет верно $SHIFT^{k - i} = 0$ (сдвиг выйдет за границы матрицы), поэтому эти члены суммы будут просто нулевыми.

## 5
$$
СSHIFT =
\begin{pmatrix}
0&1&0&0&\cdots&0&0\\
0&0&1&0&\cdots&0&0\\
0&0&0&1&\cdots&0&0\\
\vdots&&&&&&\vdots\\
0&0&0&0&\cdots&0&1\\
1&0&0&0&\cdots&0&0\\
\end{pmatrix}
$$
это матрица циклического сдвига.

Рассмотрим
$$
\begin{align}
A \cdot CSHIFT =
\begin{pmatrix}
A_{1n}&A_{11}&A_{12}&\cdots&A_{1, n - 1}\\
A_{2n}&A_{21}&A_{22}&\cdots&A_{2, n - 1}\\
\vdots&&&&\vdots\\
A_{nn}&A_{n1}&A_{n2}&\cdots&A_{n, n - 1}\\
\end{pmatrix}
\\\\
CSHIFT \cdot A = 
\begin{pmatrix}
A_{21}&A_{22}&A_{23}&\cdots&A_{2n}\\
A_{31}&A_{32}&A_{33}&\cdots&A_{3n}\\
\vdots&&&&\vdots\\
A_{11}&A_{12}&A_{13}&\cdots&A_{1n}
\end{pmatrix}
\end{align}
$$

*Ограничение 1*: Таким образом в зависимости от порядка множителей $\forall i \in [1; n -1], j \in [2; n]$ на место $(i, j)$ может прийти либо элемент бывший в $A$ в позиции $(i + 1, j)$ (снизу), либо в позиции $(i, j - 1)$ (слева).

*Ограничение 2: Для $i = n$  $\forall j \in [2; n]$ на место $(i, j)$ может прийти элемент с позиции $(i, j - 1)$ или $(1, j)$.

*Ограничение 3*: Для $j = 1 \,\, \forall i \in [1; n - 1]$ на место $(i, j)$ может прийти элемент с позиции $(i, n)$ или $(i + 1, j)$.

*Ограничение 4*: Для $i = n \land j = 1$ на место $(i, j)$ может прийти элемент $(n, n)$ или $(1, 1)$.

Построим такую матрицу с левого верхнего угла (обозначим его за $a_1$ и применим *Ограничение 1*)
$$
\begin{pmatrix}
a_1&?&?&?&\cdots&?&?&?\\
?&a_1&?&?&\cdots&?&?&?\\
\vdots&&&&&&&\vdots\\
?&?&?&?&\cdots&?&a_1&?\\
?&?&?&?&\cdots&?&?&a_1\\
\end{pmatrix}
$$
теперь пометим второй элемент в первом ряду за $a_2$ и применим *Ограничение 1*
$$
\begin{pmatrix}
a_1&a_2&?&?&\cdots&?&?&?\\
?&a_1&a_2&?&\cdots&?&?&?\\
?&?&a_1&a_2&\cdots&?&?&?\\
\vdots&&&&&&&\vdots\\
?&?&?&?&\cdots&a_1&a_2&?\\
?&?&?&?&\cdots&?&a_1&a_2\\
?&?&?&?&\cdots&?&?&a_1\\
\end{pmatrix}
$$
там можно заметить что *Ограничение 1* "левый элемент равен нижнему" дает равенство элементов на всех диагоналях выше главной
$$
\begin{pmatrix}
a_1&a_2&a_3&a_4&\cdots&a_{n-2}&a_{n-1}&a_n\\
?&a_1&a_2&a_3&\cdots&a_{n-3}&a_{n-2}&a_{n-1}\\
?&?&a_1&a_2&\cdots&a_{n-4}&a_{n-3}&a_{n-2}\\
\vdots&&&&&&&\vdots\\
?&?&?&?&\cdots&a_1&a_2&a_3\\
?&?&?&?&\cdots&?&a_1&a_2\\
?&?&?&?&\cdots&?&?&a_1\\
\end{pmatrix}
$$

Теперь используя Ограничения 2, 3, 4 однозначно заполним первый столбец и последнюю строку
$$
\begin{pmatrix}
a_1&a_2&a_3&a_4&\cdots&a_{n-2}&a_{n-1}&a_n\\
a_{n-1}&a_1&a_2&a_3&\cdots&a_{n-3}&a_{n-2}&a_{n-1}\\
a_{n-2}&?&a_1&a_2&\cdots&a_{n-4}&a_{n-3}&a_{n-2}\\
\vdots&&&&&&&\vdots\\
a_3&?&?&?&\cdots&a_1&a_2&a_3\\
a_2&?&?&?&\cdots&?&a_1&a_2\\
a_1&a_2&a_3&a_4&\cdots&a_{n-2}&a_{n-1}&a_1\\
\end{pmatrix}
$$

и теперь используя *Ограничение 1* однозначно задаются элементы ниже главной диагонали.
$$
\begin{pmatrix}
a_1&a_2&a_3&a_4&\cdots&a_{n-2}&a_{n-1}&a_n\\
a_{n-1}&a_1&a_2&a_3&\cdots&a_{n-3}&a_{n-2}&a_{n-1}\\
a_{n-2}&a_{n-1}&a_1&a_2&\cdots&a_{n-4}&a_{n-3}&a_{n-2}\\
\vdots&&&&&&&\vdots\\
a_3&a_4&a_5&a_6&\cdots&a_1&a_2&a_3\\
a_2&a_3&a_4&a_5&\cdots&a_{n-1}&a_1&a_2\\
a_1&a_2&a_3&a_4&\cdots&a_{n-2}&a_{n-1}&a_1\\
\end{pmatrix}
$$

Можно проверить что полученная матрица удовлетворяет всем ограничениями. По построению нельзя построить другую матрицу удовлетворяющую ограничениям (мы в процессе построения не накладывали дополнительных ограничений).

## 6












