---
title: sistem_persamaan_2variable_3variabel

---

# penyelesaian sistem linear dengan menggunakan sistem persamaan linear gaus

## Sistem Persamaan Linear dengan 2 Persamaan dan 2 Variabel
saya memiliki sistem persamaan berikut:
 $2 x+3 y=5$
$4 x-y=1$

Langkah 1: Membuat Matriks Augmented

Tulis sistem persamaan dalam bentuk matriks augmented:
$$
\left[\begin{array}{cc|c}
2 & 3 & 5 \\
4 & -1 & 1
\end{array}\right]
$$

Langkah 2: Operasi Baris Elementer

Langkah 2.1: Membuat elemen pertama pada baris pertama menjadi 1.
Bagi baris pertama dengan 2:
$$
\left[\begin{array}{cc|c}
1 & 1.5 & 2.5 \\
4 & -1 & 1
\end{array}\right]
$$

Langkah 2.2: Eliminasi elemen di bawah pivot pertama.
Gunakan operasi baris: $R_2=R_2-4 R_1$ :
$$
\left[\begin{array}{rr|r}
1 & 1.5 & 2.5 \\
0 & -7 & -9
\end{array}\right]
$$

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -7 :
$$
\left[\begin{array}{cc:c}
1 & 1.5 & 2.5 \\
0 & 1 & \frac{9}{7}
\end{array}\right]
$$

Langkah 2.4: Eliminasi elemen di atas pivot kedua.
Gunakan operasi baris: $R_1=R_1-1.5 R_2$ :
$$
\left[\begin{array}{ll|l}
1 & 0 & \frac{1}{7} \\
0 & 1 & \\
\frac{6}{7}
\end{array}\right]
$$

Langkah 3: Solusi
Dari matriks terakhir, kita dapat membaca solusinya:
$$
x=\frac{1}{7}, \quad y=\frac{9}{7}
$$

### Geogebra Persamaan Linear dengan 2 Persamaan dan 2 Variabel

<iframe src="https://www.geogebra.org/calculator/mb3yhtr8?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

## Sistem Persamaan Linear dengan 3 Persamaan dan 3 Variabel
$$
\left\{\begin{array}{lc}
x+2 y+z=9 & (\text { Persamaan 1) } \\
2 x+y-z=3 & \text { (Persamaan 2) } \\
3 x-y+2 z=8 & (\text { Persamaan 3) }
\end{array}\right.
$$

Langkah 1: Membuat Matriks Augmented
Tulis sistem persamaan dalam bentuk matriks augmented:
$$
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
2 & 1 & -1 & 3 \\
3 & -1 & 2 & 8
\end{array}\right]
$$

Langkah 2: Eliminasi Gauss
Tujuan: Mengubah matriks menjadi bentuk eselon baris (row echelon form).

Langkah 2.1: Membuat elemen pertama pada baris pertama menjadi 1 (sudah 1, lanjut).
Langkah 2.2: Eliminasi elemen di bawah pivot pertama.
Gunakan operasi baris:
- $R_2=R_2-2 R_1$
- $R_3=R_3-3 R_1$

Hasilnya:
$$
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & -3 & -3 & -15 \\
0 & -7 & -1 & -19
\end{array}\right]
$$

Langkah 2.3: Membuat elemen kedua pada baris kedua menjadi 1.
Bagi baris kedua dengan -3 :
$$
\left[\begin{array}{ccc|c}
1 & 2 & 1 & 9 \\
0 & 1 & 1 & 5 \\
0 & -7 & -1 & -19
\end{array}\right]
$$

Langkah 2.4: Eliminasi elemen di atas dan di bawah pivot kedua.
Gunakan operasi baris:
* $R_1=R_1-2 R_2$
- $R_3=R_3+7 R_2$

Hasilnya:
$$
\left[\begin{array}{ccc:c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 6 & 16
\end{array}\right]
$$
Langkah 2.5: Membuat elemen ketiga pada baris ketiga menjadi 1.
Bagi baris ketiga dengan 6:
$$
\left[\begin{array}{ccc:c}
1 & 0 & -1 & -1 \\
0 & 1 & 1 & 5 \\
0 & 0 & 1 & \frac{16}{6}=\frac{8}{3}
\end{array}\right]
$$

Langkah 2.6: Eliminasi elemen di atas pivot ketiga.
Gunakan operasi baris:
- $R_1=R_1+R_3$
- $R_2=R_2-R_3$

Hasilnya:
$$
\left[\begin{array}{lll:l}
1 & 0 & 0 & \frac{5}{3} \\
0 & 1 & 0 & \frac{7}{3} \\
0 & 0 & 1 & \frac{8}{3}
\end{array}\right]
$$

Langkah 3: Solusi
Dari matriks terakhir, kita dapat membaca solusinya:
$$
x=\frac{5}{3}, \quad y=\frac{7}{3}, \quad z=\frac{8}{3}
$$
Verifikasi Solusi
Substitusikan nilai $x, y, z$ ke dalam persamaan asli untuk memverifikasi kebenaran solusi:
1. Persamaan 1:
$$
x+2 y+z=9
$$

Substitusi:
$$
\frac{5}{3}+2 \cdot \frac{7}{3}+\frac{8}{3}=\frac{5}{3}+\frac{14}{3}+\frac{8}{3}=\frac{27}{3}=9
$$
2. Persamaan 2:
$$
2 x+y-z=3
$$

Substitusi:
$$
2 \cdot \frac{5}{3}+\frac{7}{3}-\frac{8}{3}=\frac{10}{3}+\frac{7}{3}-\frac{8}{3}=\frac{9}{3}=3
$$
3. Persamaan 3:
$$
3 x-y+2 z=8
$$

Substitusi:
$$
3 \cdot \frac{5}{3}-\frac{7}{3}+2 \cdot \frac{8}{3}=\frac{15}{3}-\frac{7}{3}+\frac{16}{3}=\frac{24}{3}=8
$$

Kesimpulan
Solusi sistem persamaan linear tersebut adalah:
$$
x=\frac{5}{3}, \quad y=\frac{7}{3}, \quad z=\frac{8}{3}
$$
### Geogebra Persamaan Linear dengan 3 Persamaan dan 3 Variabel
<iframe src="https://www.geogebra.org/calculator/deg5zxxg?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>