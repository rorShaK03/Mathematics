## 1

#### а)
$$
\begin{align}
	\begin{pmatrix}
	1&3\\
	1&2
	\end{pmatrix}
	X
	=
	\begin{pmatrix}
	1&1\\
	1&1
	\end{pmatrix}
	\\\\
	X =
	\begin{pmatrix}
	1&3\\
	1&2
	\end{pmatrix}^{-1}
	\begin{pmatrix}
	1&1\\
	1&1
	\end{pmatrix}
	=
	\frac{1}{2-3}
	\begin{pmatrix}
	2&-3\\
	-1&1
	\end{pmatrix}
	\cdot
	\begin{pmatrix}
	1&1\\
	1&1
	\end{pmatrix}
	=
	\begin{pmatrix}
	-2&3\\
	1&-1
	\end{pmatrix}
	\cdot
	\begin{pmatrix}
	1&1\\
	1&1
	\end{pmatrix}
	=
	\begin{pmatrix}
	1&1\\
	0&0
	\end{pmatrix}
\end{align}
$$
#### д)
$$
\begin{pmatrix}
3&1\\
2&1
\end{pmatrix}
X
\begin{pmatrix}
1&3\\
1&2
\end{pmatrix}
=
\begin{pmatrix}
3&3\\
3&2
\end{pmatrix}
$$

$$
\begin{align}
X
=
\begin{pmatrix}
3&1\\
2&1
\end{pmatrix}^{-1}
\begin{pmatrix}
3&3\\
3&2
\end{pmatrix}
\begin{pmatrix}
1&3\\
1&2
\end{pmatrix}^{-1}
=
\frac{1}{3-2}
\begin{pmatrix}
1&-1\\
-2&3
\end{pmatrix}
\begin{pmatrix}
3&3\\
3&2
\end{pmatrix}
\frac{1}{2-3}
\begin{pmatrix}
2&-3\\
-1&1
\end{pmatrix}
\\\\=
\begin{pmatrix}
1&-1\\
-2&3
\end{pmatrix}
\begin{pmatrix}
3&3\\
3&2
\end{pmatrix}
\begin{pmatrix}
-2&3\\
1&-1
\end{pmatrix}
=
\begin{pmatrix}
0&1\\
3&0
\end{pmatrix}
\begin{pmatrix}
-2&3\\
1&-1
\end{pmatrix}
=
\begin{pmatrix}
1&-1\\
-6&9
\end{pmatrix}
\end{align}
$$

## 2
$$
A = 
\begin{pmatrix}
a&b\\
c&d
\end{pmatrix}
$$
$$
\begin{align}
A^2 - tr(A)A =
\begin{pmatrix}
a^2 + bc&ab + bd\\
ac + cd&bc + d^2
\end{pmatrix}
-
(a + d)
\begin{pmatrix}
a&b\\
c&d
\end{pmatrix}
=
\begin{pmatrix}
a^2 + bc&ab + bd\\
ac + cd&bc + d^2
\end{pmatrix}
-
\begin{pmatrix}
a^2 + ad&ab + bd\\
ac + cd&ad + d^2
\end{pmatrix}
\\\\=
\begin{pmatrix}
bc - ad & 0\\
0 & bc - ad
\end{pmatrix}
=
(bc- ad)E
\end{align}
$$
## 3
По свойству следа
$$
\begin{align}
tr(AB) = tr(BA) \\
tr(AB - BA) = tr(AB) - tr(BA) = 0
\end{align}
$$

а значит матрица $[A; B]$ имеет вид
$$
[A; B] = AB - BA =
\begin{pmatrix}
a & b \\
c & -a
\end{pmatrix}
$$
А значит
$$
[A; B]^2 = 
\begin{pmatrix}
a & b \\
c & -a
\end{pmatrix}^2
=
\begin{pmatrix}
a^2 + bc & ab - ab \\
ac - ac & bc + a^2
\end{pmatrix}
=
(a^2 + bc)E_2
$$
А такая матрица коммутирует с любой матрицей порядка $2$ и поэтому
$$
[[A; B]^2 ; C] = 0
$$
чтд

## 4
Пусть $AB = BA$ и существуют $n, m$ тч $A^n = 0$ и $B^m = 0$. Доказать что существует $k$ $(A + B)^k = 0$

> [!tip] Почему бином выполняется для любых коммутирующих матриц?
> По идее нам для доказательства бинома надо чтобы для любых натуральных (и нулевых) степеней $l$ и $r$ было верно что $A^l B^r = B^r A^l$,  но если известно что $AB = BA$ мы можем просто сделать "сортировку пузырьком" выдвинув вперед множители $A$ и из $B^r A^l$ получить $A^l B^r$

По биному Ньютона (выполняется для коммутирующих матриц)
$$
(A + B)^k = \sum_{i = 0}^k C_k^{i} A^i B^{k - i}
$$
Возьмем $k = n + m$, тогда для первых $n$ слагаемых $k - i \ge m$, а для следующих $i \ge n$. А значит в каждом слагаемом есть нулевой множитель. Поэтому сумма равна нулю.

Доказали что сумма нильпотентна.

Для некоммутирующих матриц это неверно. Пример
$$
\begin{align}
A =
\begin{pmatrix}
0&1\\
0&0
\end{pmatrix}
\\\\
B =
\begin{pmatrix}
0&0\\
1&0
\end{pmatrix}
\end{align}
$$
Они обе нильпотентны
$$
\begin{align}
A^2 = 0\\
B^2 = 0
\end{align}
$$
при этом
$$
\begin{align}
A + B = 
\begin{pmatrix}
0&1\\
1&0
\end{pmatrix}
\\\\
(A + B)^2 =
\begin{pmatrix}
1&0\\
0&1
\end{pmatrix}
= E
\\\\
(A + B)^3 =
\begin{pmatrix}
0&1\\
1&0
\end{pmatrix}
\end{align}
$$
Таким образом матрица никогда не зануляется, а значит она не нильпотента.
## 5

Рассмотрим многочлен со свободным ненулевым членом от матрицы $A$
$$
\begin{align}
f(A) = a_0 + a_1 A + a_2 A^2 + ... + a_n A^n = a_0 + A(a_1 + a_2 A + a_3 A^2 + ... + a_n A^{n - 1}) \\\\
= a_0(E + A(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1}))
\end{align}
$$
тогда если мы докажем, что 
$$
E + A(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1})
$$
обратима, то и $f(A)$ будет обратима (потому что можно просто домножить обратную матрицу к выражению выше на $\frac{1}{a_0}$).

Заметим, что множители $A$ и "скобка" в выражении
$$
A(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1}) \,\,\, (1)
$$
коммутируют (потому что каждое слагаемое в скобке коммутирует с $A$). А раз так, то если для некоторого $m$ верно что $A^m = 0$, то
$$
(A(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1}))^m = A^m(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1})^m = 0
$$
а значит выражение $(1)$ тоже нильпотентно. А в прошлом семинарском дз мы доказали, что для любой нильпотентной матрицы $X$, верно что
$$
X + E 
$$
обратима. А значит матрица
$$
f(A) = E + A(\frac{a_1}{a_0} + \frac{a_2}{a_0}A + ... + \frac{a_n}{a_0}A^{n - 1})
$$
обратима чтд

## 6
$A$ - нильпотентна
$$
AX + X + A = 0
$$

$$
\begin{align}
AX + X + A = 0 \\
(A + E)X = -A \\
X = -(A + E)^{-1}A
\end{align}
$$
Пусть $A^m = 0$. По доказанному в задании прошлого семинара
$$
\begin{align}
(A + E)^{-1} = \sum_{i = 0}^{m-1} (-1)^i A^i \\
X = \sum_{i = 1}^{m} (-1)^i A^i
\end{align}
$$

## 7
>[!warn]
> На самом деле конструкцию $E - BXA$ я придумал с помощью гпт, я плохо понимаю какая за ней стоит интуиция


Пусть $X$ - обратная к $E - AB$, тогда
$$
\begin{align}
(E - BXA)(E + BA) = E + BA - BXA - BXABA = E + BA - BX(E + AB)A \\= E + BA - BA = E
\end{align}
$$
Значит $E - BXA$ - обратная к $E + BA$
## 8

#### а)
Если мы покажем, что $\# \text{главных} \,\, A \le \# \text{главных} \,\, A^t$, то так как $A^T$






