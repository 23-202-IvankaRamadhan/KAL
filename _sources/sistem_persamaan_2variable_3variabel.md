---
title: sistem_persamaan_2variable_3variabel
---

# Penyelesaian Sistem Linear dengan Menggunakan Sistem Persamaan Linear Gauss

## Sistem Persamaan Linear dengan 2 Persamaan dan 2 Variabel
Saya memiliki sistem persamaan berikut:

\[
2x+3y=5
\]
\[
4x-y=1
\]

Langkah 1: Membuat Matriks Augmented

Tulis sistem persamaan dalam bentuk matriks augmented:

\[
\left[\begin{array}{cc|c}
2 & 3 & 5 \\
4 & -1 & 1
\end{array}\right]
\]

Langkah 2: Operasi Baris Elementer

Langkah 2.1: Membuat elemen pertama pada baris pertama menjadi 1.
Bagi baris pertama dengan 2:

\[
\left[\begin{array}{cc|c}
1 & 1.5 & 2.5 \\
4 & -1 & 1
\end{array}\right]
\]

Langkah 2.2: Eliminasi elemen di bawah pivot pertama.
Gunakan operasi baris: \( R_2=R_2-4 R_1 \)

\[
\left[\begin{array}{rr|r}
1 & 1.5 & 2.5 \\
0 & -7 & -9
\end{array}\right]
\]

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -7:

\[
\left[\begin{array}{cc|c}
1 & 1.5 & 2.5 \\
0 & 1 & \frac{9}{7}
\end{array}\right]
\]

Langkah 2.4: Eliminasi elemen di atas pivot kedua.
Gunakan operasi baris: \( R_1=R_1-1.5 R_2 \)

\[
\left[\begin{array}{ll|l}
1 & 0 & \frac{1}{7} \\
0 & 1 & \frac{6}{7}
\end{array}\right]
\]

Langkah 3: Solusi
Dari matriks terakhir, kita dapat membaca solusinya:

\[
x=\frac{1}{7}, \quad y=\frac{9}{7}
\]

## Sistem Persamaan Linear dengan 3 Persamaan dan 3 Variabel

\[
\begin{cases}
x+2y+z=9 \\
2x+y-z=3 \\
3x-y+2z=8
\end{cases}
\]

Langkah 1: Membuat Matriks Augmented

\[
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
2 & 1 & -1 & 3 \\
3 & -1 & 2 & 8
\end{array}\right]
\]

Langkah 2: Eliminasi Gauss

Gunakan operasi baris:
\[
R_2=R_2-2 R_1, \quad R_3=R_3-3 R_1
\]
Hasilnya:

\[
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & -3 & -3 & -15 \\
0 & -7 & -1 & -19
\end{array}\right]
\]

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -3:

\[
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & 1 & 1 & 5 \\
0 & -7 & -1 & -19
\end{array}\right]
\]

Gunakan operasi baris:
\[
R_1=R_1-2 R_2, \quad R_3=R_3+7 R_2
\]
Hasilnya:

\[
\left[\begin{array}{ccc|c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 6 & 16
\end{array}\right]
\]

Bagi baris ketiga dengan 6:

\[
\left[\begin{array}{ccc|c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 1 & \frac{8}{3}
\end{array}\right]
\]

Gunakan operasi baris:
\[
R_1=R_1+R_3, \quad R_2=R_2-R_3
\]
Hasilnya:

\[
\left[\begin{array}{ccc|c}
1 & 0 & 0 & \frac{5}{3} \\
0 & 1 & 0 & \frac{7}{3} \\
0 & 0 & 1 & \frac{8}{3}
\end{array}\right]
\]

Langkah 3: Solusi

\[
x=\frac{5}{3}, \quad y=\frac{7}{3}, \quad z=\frac{8}{3}
\]
