---
title: sistem_persamaan_2variable_3variabel
---

# penyelesaian sistem linear dengan menggunakan sistem persamaan linear gaus

## Sistem Persamaan Linear dengan 2 Persamaan dan 2 Variabel
saya memiliki sistem persamaan berikut:
```latex
\begin{equation}
2x+3y=5
\end{equation}
\begin{equation}
4x-y=1
\end{equation}
```

Langkah 1: Membuat Matriks Augmented

Tulis sistem persamaan dalam bentuk matriks augmented:
```latex
\begin{equation}
\left[\begin{array}{cc|c}
2 & 3 & 5 \\
4 & -1 & 1
\end{array}\right]
\end{equation}
```

Langkah 2: Operasi Baris Elementer

Langkah 2.1: Membuat elemen pertama pada baris pertama menjadi 1.
Bagi baris pertama dengan 2:
```latex
\begin{equation}
\left[\begin{array}{cc|c}
1 & 1.5 & 2.5 \\
4 & -1 & 1
\end{array}\right]
\end{equation}
```

Langkah 2.2: Eliminasi elemen di bawah pivot pertama.
Gunakan operasi baris: \( R_2=R_2-4 R_1 \)
```latex
\begin{equation}
\left[\begin{array}{rr|r}
1 & 1.5 & 2.5 \\
0 & -7 & -9
\end{array}\right]
\end{equation}
```

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -7:
```latex
\begin{equation}
\left[\begin{array}{cc|c}
1 & 1.5 & 2.5 \\
0 & 1 & \frac{9}{7}
\end{array}\right]
\end{equation}
```

Langkah 2.4: Eliminasi elemen di atas pivot kedua.
Gunakan operasi baris: \( R_1=R_1-1.5 R_2 \)
```latex
\begin{equation}
\left[\begin{array}{ll|l}
1 & 0 & \frac{1}{7} \\
0 & 1 & \frac{6}{7}
\end{array}\right]
\end{equation}
```
```

Langkah 3: Solusi
Dari matriks terakhir, kita dapat membaca solusinya:
```latex
\begin{equation}
x=\frac{1}{7}, \quad y=\frac{9}{7}
\end{equation}
```

## Sistem Persamaan Linear dengan 3 Persamaan dan 3 Variabel
```latex
\begin{equation}
\begin{cases}
x+2y+z=9 \\
2x+y-z=3 \\
3x-y+2z=8
\end{cases}
\end{equation}
```

Langkah 1: Membuat Matriks Augmented
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
2 & 1 & -1 & 3 \\
3 & -1 & 2 & 8
\end{array}\right]
\end{equation}
```

Langkah 2: Eliminasi Gauss

Gunakan operasi baris:
```latex
\begin{equation}
R_2=R_2-2 R_1, \quad R_3=R_3-3 R_1
\end{equation}
```
Hasilnya:
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & -3 & -3 & -15 \\
0 & -7 & -1 & -19
\end{array}\right]
\end{equation}
```

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -3:
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & 1 & 1 & 5 \\
0 & -7 & -1 & -19
\end{array}\right]
\end{equation}
```

Gunakan operasi baris:
```latex
\begin{equation}
R_1=R_1-2 R_2, \quad R_3=R_3+7 R_2
\end{equation}
```
Hasilnya:
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 6 & 16
\end{array}\right]
\end{equation}
```

Bagi baris ketiga dengan 6:
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 1 & \frac{8}{3}
\end{array}\right]
\end{equation}
```

Gunakan operasi baris:
```latex
\begin{equation}
R_1=R_1+R_3, \quad R_2=R_2-R_3
\end{equation}
```
Hasilnya:
```latex
\begin{equation}
\left[\begin{array}{ccc|c}
1 & 0 & 0 & \frac{5}{3} \\
0 & 1 & 0 & \frac{7}{3} \\
0 & 0 & 1 & \frac{8}{3}
\end{array}\right]
\end{equation}
```

Langkah 3: Solusi
```latex
\begin{equation}
x=\frac{5}{3}, \quad y=\frac{7}{3}, \quad z=\frac{8}{3}
\end{equation}
```
