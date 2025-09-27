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
=

\end{aligned}
$$