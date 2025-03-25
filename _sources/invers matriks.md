---
title: INVERS MATRIK

---

# INVERS MATRIK 
### Definisi Matriks Invers

Matriks invers adalah matriks yang jika dikalikan dengan matriks aslinya menghasilkan matriks identitas.

Secara matematis, jika ${A}$ adalah sebuah matriks persegi, maka inversnya, yang ditulis sebagai $A^{-1}$, memenuhi persamaan:

$$
A \times A^{-1}=A^{-1} \times A=I
$$

di mana $I$ adalah matriks identitas, yaitu matriks dengan angka 1 di diagonal utama dan $\mathbf{0}$ di tempat lainnya.
Contoh matriks identitas untuk ukuran $2 \times 2$ : 

$$
I=\left[\begin{array}{ll}
1 & 0 \\
0 & 1
\end{array}\right]
$$

dan untuk ukuran $3 \times 3$ : 

$$
I=\left[\begin{array}{lll}
1 & 0 & 0 \\
0 & 1 & 0 \\
0 & 0 & 1
\end{array}\right]
$$
### Syarat Suatu Matriks Memiliki Invers

Tidak semua matriks memiliki invers. Suatu matriks $A$ bisa memiliki invers $A^{-1}$ jika memenuhi dua syarat berikut:
1. Matriks harus berbentuk persegi $\rightarrow$ jumlah baris harus sama dengan jumlah kolom.
2. Determinan tidak boleh nol $\rightarrow|A| \neq 0$.

Jika determinannya nol $(|A|=0)$, maka matriks disebut singular dan tidak memiliki invers.

## Contoh Penerapan Invers Matriks

### Sistem Persamaan Linear dalam Bentuk Matriks    
$$
\left\{\begin{array}{l}
3x + 2y - z = 1 \\
2x - 4y + 3z = 0 \\
-x + y + 2z = 0
\end{array}\right.
$$

Bentuk matriks:
$$
A = \left[\begin{array}{ccc}
3 & 2 & -1 \\
2 & -4 & 3 \\
-1 & 1 & 2
\end{array}\right],\quad
B = \left[\begin{array}{c}
1 \\
0 \\
0
\end{array}\right]
$$

### Langkah-langkah Mencari Invers Matriks

#### Langkah 1: Bentuk Augmented Matrix $[A \mid I]$
Gabungkan matriks $A$ dengan matriks identitas:
$$
[A \mid I] = \left[\begin{array}{ccc|ccc}
3 & 2 & -1 & | & 1 & 0 & 0 \\
2 & -4 & 3 & | & 0 & 1 & 0 \\
-1 & 1 & 2 & | & 0 & 0 & 1
\end{array}\right]
$$

#### Langkah 2: Buat Elemen (1,1) Menjadi 1
$$
R_1 \leftarrow \frac{1}{3} R_1
$$
Hasilnya:
$$
\left[\begin{array}{ccc|ccc}
1 & \frac{2}{3} & -\frac{1}{3} & | & \frac{1}{3} & 0 & 0 \\
2 & -4 & 3 & | & 0 & 1 & 0 \\
-1 & 1 & 2 & | & 0 & 0 & 1
\end{array}\right]
$$

#### Langkah 3: Nol-kan Elemen di Bawah (1,1)
Gunakan operasi baris untuk membuat elemen di bawah (1,1) menjadi nol:
$$
R_2 \leftarrow R_2 - 2R_1,\quad R_3 \leftarrow R_3 + R_1
$$
Hasilnya:
$$
\left[\begin{array}{ccc|ccc}
1 & \frac{2}{3} & -\frac{1}{3}  	& |\,  	&  	&  	\\
0  	& -\frac{14}{3} & \frac{11}{3}  	& |\,  	&  	&  	\\
0  	& \frac{5}{3}  	& \frac{5}{3}  	& |\,  	&  	&  
\end{array}\right]
$$

#### Langkah-langkah Selanjutnya:
- Lakukan operasi baris untuk membuat elemen diagonal menjadi satu.
- Nol-kan elemen di atas dan di bawah diagonal utama.

#### Langkah Akhir: Hitung $A^{-1}$
Setelah menyelesaikan semua langkah, kita akan mendapatkan invers dari matriks $A$.

### Langkah Verifikasi: Hitung $A^{-1} B$
Dengan $B=\left[\begin{array}{c}
1 \\ 
0 \\ 
0 
\end{array}\right]$, kita hitung:
$$
A^{-1} B = 
\left[\begin{array}{ccc}
a_{11}   	& a_{12}   	& a_{13}\\ 
a_{21}   	& a_{22}   	& a_{23}\\ 
a_{31}   	& a_{32}   	& a_{33}
\end{array}\right] 
\times 
\left[\begin{array}{c}
1 \\ 
0 \\ 
0 
\end{array}\right]
$$

Hasil akhirnya adalah:
$$
A^{-1} B = 
\left[\begin{array}{c}
\boxed{1} \\ 
\boxed{0} \\ 
\boxed{0} 
\end{array}\right]
$$

*(Operasi perkalian matriks akan menghasilkan $\begin{bmatrix}1\\0\\0\end{bmatrix}$ setelah kalkulasi lengkap)*
