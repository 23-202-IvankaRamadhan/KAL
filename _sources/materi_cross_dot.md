---
title: Materi_Cross_Dot

---

 CROSS PRODUCT 
## Hasil Perkalian Silang (Cross Product)

### Pengertian
Perkalian silang adalah operasi vektor dalam ruang tiga dimensi yang menghasilkan vektor baru yang tegak lurus terhadap kedua vektor asalnya.

Jika terdapat dua vektor:
$$
\vec{A} = \langle a_1, a_2, a_3 \rangle \quad \text{dan} \quad \vec{B} = \langle b_1, b_2, b_3 \rangle
$$

Maka hasil dari $\vec{A} \times \vec{B}$ diperoleh dari:

$$\vec{A} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3 \\
\end{vmatrix} $$

$$= (a_2 b_3 - a_3 b_2)\hat{i} - (a_1 b_3 - a_3 b_1)\hat{j} + (a_1 b_2 - a_2 b_1)\hat{k}$$

### Contoh

Misalnya diberikan dua vektor:
$$
\vec{A} = \langle 2, 3, 4 \rangle, \quad \vec{B} = \langle 5, 6, 7 \rangle
$$

$$
\vec{A} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & 3 & 4 \\
5 & 6 & 7 \\
\end{vmatrix} $$
$$= (3 \cdot 7 - 4 \cdot 6)\hat{i} - (2 \cdot 7 - 4 \cdot 5)\hat{j} + (2 \cdot 6 - 3 \cdot 5)\hat{k}$$


$$ = (21 - 24)\hat{i} - (14 - 20)\hat{j} + (12 - 15)\hat{k}$$
$$= -3\hat{i} + 6\hat{j} - 3\hat{k}$$


$$
\vec{A} \times \vec{B} = \langle -3, 6, -3 \rangle
$$

## Rumus Perkalian Silang Menggunakan Determinan

Jika dua vektor berada dalam ruang berdimensi tiga:

$$
\vec{A} = \langle a_1, a_2, a_3 \rangle, \quad
\vec{B} = \langle b_1, b_2, b_3 \rangle
$$

Maka untuk menentukan $\vec{A} \times \vec{B}$, digunakan determinan sebagai berikut:

$$
\vec{A} \times \vec{B} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
a_1 & a_2 & a_3 \\
b_1 & b_2 & b_3 \\
\end{vmatrix}
$$


$vec{A} \times \vec{B} = (a_2 b_3 - a_3 b_2)\hat{i}$
- $(a_1 b_3 - a_3 b_1)\hat{j}$
+ $(a_1 b_2 - a_2 b_1)\hat{k}$


Atau bisa juga dituliskan dalam bentuk vektor:

$$
\vec{A} \times \vec{B} = 
\langle a_2 b_3 - a_3 b_2,\ 
-(a_1 b_3 - a_3 b_1),\ 
a_1 b_2 - a_2 b_1 \rangle
$$

## Soal: Perkalian Silang Dua Vektor

Diketahui dua vektor berikut:

$$
\vec{u} = \langle 1, 1, 1 \rangle, \quad \vec{v} = \langle 2, 1, 1 \rangle
$$

### Langkah 1: Susun dalam bentuk determinan 3x3}

$$ 
\vec{u} \times \vec{v} =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
1 & 1 & 1 \\
2 & 1 & 1 \\
\end{vmatrix}
$$

### Langkah 2: Hitung setiap komponen dengan ekspansi kofaktor

Komponen arah $\hat{i}$:

$$\hat{i} \cdot
\begin{vmatrix}
1 & 1 \\
1 & 1 \\
\end{vmatrix} = \hat{i}(1 \cdot 1 - 1 \cdot 1) = \hat{i}(1 - 1) = 0\hat{i}$$

Komponen arah $\hat{j}$:
$$
\hat{j} \cdot
\begin{vmatrix}
1 & 1 \\
2 & 1 \\
\end{vmatrix} = -\hat{j}(1 \cdot 1 - 1 \cdot 2) = -\hat{j}(1 - 2) = -\hat{j}(-1) = \hat{j}$$

Komponen arah $\hat{k}$:

$$\hat{k} \cdot
\begin{vmatrix}
1 & 1 \\
2 & 1 \\
\end{vmatrix} = \hat{k}(1 \cdot 1 - 1 \cdot 2) = \hat{k}(1 - 2) = -\hat{k}$$

### Langkah 3: Gabungkan seluruh komponen

$$
\vec{u} \times \vec{v} = 0\hat{i} + \hat{j} - \hat{k}
$$

Hasil Akhir dalam Bentuk Vektor.:

$$
\vec{u} \times \vec{v} = \langle 0,\ 1,\ -1 \rangle
$$



## Hasil Vektor dari soal di atas.
<iframe src="https://www.geogebra.org/classic/uupkhszd?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>