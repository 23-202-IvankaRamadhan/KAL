\documentclass[12pt]{article}
\usepackage{amsmath}
\usepackage{geometry}
\geometry{margin=1in}

\title{Latihan Matriks Transformasi.}
\date{}

\begin{document}

\maketitle

\section*{Soal Latihan}

Diberikan:
\[
\hat{x} = \begin{bmatrix}1 \\ 1\end{bmatrix}, \quad
\hat{y} = \begin{bmatrix}-1 \\ 2\end{bmatrix}
\]

Gambarkan vektor- vektor $\hat{x}$, $\hat{y}$, $A\hat{x}$ dan $A\hat{y}$ pada bidang yang sama!

\subsection*{Soal 1}

\[
A = \begin{bmatrix}1 & 1 \\ 2 & 3\end{bmatrix}
\]

\[
A\hat{x} = \begin{bmatrix}1 & 1 \\ 2 & 3\end{bmatrix}
\begin{bmatrix}1 \\ 1\end{bmatrix} = 
\begin{bmatrix}2 \\ 5\end{bmatrix}
\]

\[
A\hat{y} = \begin{bmatrix}1 & 1 \\ 2 & 3\end{bmatrix}
\begin{bmatrix}-1 \\ 2\end{bmatrix} = 
\begin{bmatrix}1 \\ 4\end{bmatrix}
\]

\subsection*{Soal 2}

\[
A = \begin{bmatrix}2 & 0 \\ -1 & 3\end{bmatrix}
\]

\[
A\hat{x} = \begin{bmatrix}2 & 0 \\ -1 & 3\end{bmatrix}
\begin{bmatrix}1 \\ 1\end{bmatrix} = 
\begin{bmatrix}2 \\ 2\end{bmatrix}
\]

\[
A\hat{y} = \begin{bmatrix}2 & 0 \\ -1 & 3\end{bmatrix}
\begin{bmatrix}-1 \\ 2\end{bmatrix} = 
\begin{bmatrix}-2 \\ 7\end{bmatrix}
\]

\subsection*{Catatan}

\begin{itemize}
  \item Matriks $2 \times 2$ dapat mengubah basis standar vektor $\hat{x} = \begin{bmatrix}1 \\ 0\end{bmatrix}$ dan $\hat{y} = \begin{bmatrix}0 \\ 1\end{bmatrix}$
  \item Vektor hasil transformasi $A\hat{x}$ dan $A\hat{y}$ menjadi kolom pertama dan kolom kedua dari matriks transformasi $A$
\end{itemize}

\section*{Soal 5}

Diketahui:
\[
A\hat{x} = \begin{bmatrix}1 \\ 2\end{bmatrix}, \quad
A\hat{y} = \begin{bmatrix}2 \\ 3\end{bmatrix}
\]

Maka matriks $A$ adalah:
\[
A = \begin{bmatrix}1 & 2 \\ 2 & 3\end{bmatrix}
\]

\section*{Soal 6}

Diketahui:
\[
A\hat{x} = \begin{bmatrix}1 \\ 1\end{bmatrix}, \quad
A\hat{y} = \begin{bmatrix}-1 \\ 1\end{bmatrix}
\]

Maka matriks $A$ adalah:
\[
A = \begin{bmatrix}1 & -1 \\ 1 & 1\end{bmatrix}
\]

\end{document}
