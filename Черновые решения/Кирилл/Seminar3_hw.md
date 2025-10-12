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
$$

