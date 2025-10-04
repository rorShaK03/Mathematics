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
3&1\\
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
3&1\\
-5&2
\end{pmatrix}
\cdot
\begin{pmatrix}
2&1\\
5&3
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
3&1\\
-5&2
\end{pmatrix}
\end{aligned}
$$






$$
\begin{pmatrix}
3&1\\
-5&2
\end{pmatrix}
\cdot
\begin{pmatrix}
2&1\\
5&3
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}
=
\begin{pmatrix}
11&6\\
0&1
\end{pmatrix}
\cdot
\begin{pmatrix}
1&0\\
1&1
\end{pmatrix}
=
\begin{pmatrix}
17&6\\
1&1
\end{pmatrix}
$$
