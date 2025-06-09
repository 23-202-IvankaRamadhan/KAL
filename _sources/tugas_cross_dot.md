---
title: Tugas_Cross_Dot

---

# CROSS PRODUCT 
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

# Tugas Cross Dot
## Soal 1
1. Tentukan luas jajaran genjang yang ditentukan oleh vektor $\vec{u}=\left[\begin{array}{l}1 \\ 2\end{array}\right]$ dan $\vec{v}=\left[\begin{array}{l}2 \\ 1\end{array}\right]$.
2. Tentukan luas jajaran genjang yang ditentukan oleh vektor $\vec{u}=\left[\begin{array}{l}2 \\ 0\end{array}\right]$ dan $\vec{v}=\left[\begin{array}{l}0 \\ 3\end{array}\right]$.
3. Tentukan luas segitiga dengan titik-titik sudut $(0,0,0),(1,3,-1)$, dan $(2,1,1)$.
4. Tentukan luas segitiga dengan titik-titik sudut $(5,2,-1),(3,6,2)$, dan $(1,0,4)$.

## Jawaban

### 1. Luas jajaran genjang dari vektor 

Kita diberikan dua vektor di ruang dua dimensi:

$$
\vec{u}=\left[\begin{array}{l}
1 \\
2
\end{array}\right], \quad \vec{v}=\left[\begin{array}{l}
2 \\
1
\end{array}\right]
$$

Untuk vektor 2D, luas jajaran genjang dapat dihitung menggunakan nilai absolut dari determinan matriks 2x2 yang terbentuk dari vektor-vektor tersebut:

$$
\text { Luas }=|\vec{u} \times \vec{v}|=\left|\begin{array}{ll}
1 & 2 \\
2 & 1
\end{array}\right|=|(1)(1)-(2)(2)|=|1-4|=3
$$

Jadi, luas jajaran genjang yang dibentuk oleh vektor $\vec{u}$ dan $\vec{v}$ adalah *3 satuan luas*.

---

### 2. Luas jajaran genjang dari vektor 

Diberikan vektor:

$$
\vec{u}=\left[\begin{array}{l}
2 \\
0
\end{array}\right], \quad \vec{v}=\left[\begin{array}{l}
0 \\
3
\end{array}\right]
$$

Seperti sebelumnya, luas jajaran genjang ditentukan oleh determinan dari matriks yang terdiri dari kedua vektor:

$$
\text { Luas }=\left|\begin{array}{ll}
2 & 0 \\
0 & 3
\end{array}\right|=|(2)(3)-(0)(0)|=|6|=6
$$

Jadi, luas jajaran genjang yang dibentuk oleh vektor $\vec{u}$ dan $\vec{v}$ adalah *6 satuan luas*.

---

### 3. Luas segitiga dengan titik-titik sudut 

Diberikan titik-titik sudut segitiga:

$$
A=(0,0,0), \quad B=(1,3,-1), \quad C=(2,1,1)
$$

Langkah pertama adalah menghitung vektor yang menghubungkan titik-titik ini:

$$
\overrightarrow{A B}=B-A=\left[\begin{array}{c}
1 \\
3 \\
-1
\end{array}\right], \quad \overrightarrow{A C}=C-A=\left[\begin{array}{l}
2 \\
1 \\
1
\end{array}\right]
$$

Selanjutnya, hitung perkalian silang antara vektor $\overrightarrow{AB}$ dan $\overrightarrow{AC}$:

$$
\begin{gathered}
\overrightarrow{A B} \times \overrightarrow{A C}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
1 & 3 & -1 \\
2 & 1 & 1
\end{array}\right|=\mathbf{i}(3 \cdot 1-(-1) \cdot 1)-\mathbf{j}(1 \cdot 1-(-1) \cdot 2)+\mathbf{k}(1 \cdot 1-3 \cdot 2) \\
=\mathbf{i}(3+1)-\mathbf{j}(1+2)+\mathbf{k}(1-6)=\left[\begin{array}{c}
4 \\
-3 \\
-5
\end{array}\right]
\end{gathered}
$$

Panjang vektor hasil cross product:

$$
|\overrightarrow{A B} \times \overrightarrow{A C}|=\sqrt{4^2+(-3)^2+(-5)^2}=\sqrt{16+9+25}=\sqrt{50}
$$

Karena luas segitiga diperoleh dari *setengah dari panjang vektor hasil perkalian silang*, maka:

$$
\text { Luas }=\frac{1}{2} \sqrt{50}=\frac{1}{2} \cdot 5 \sqrt{2}=\frac{5 \sqrt{2}}{2}
$$

Jadi, luas segitiga adalah *$\frac{5 \sqrt{2}}{2}$ satuan luas*.

---

### 4. Luas segitiga dengan titik-titik sudut 

Diberikan titik-titik sudut:

$$
A=(5,2,-1), \quad B=(3,6,2), \quad C=(1,0,4)
$$

Hitung vektor yang menghubungkan titik-titik tersebut:

$$
\overrightarrow{A B}=B-A=\left[\begin{array}{c}
-2 \\
4 \\
3
\end{array}\right], \quad \overrightarrow{A C}=C-A=\left[\begin{array}{c}
-4 \\
-2 \\
5
\end{array}\right]
$$

Lakukan perkalian silang:

$$
\begin{gathered}
\overrightarrow{A B} \times \overrightarrow{A C}=\left|\begin{array}{ccc}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
-2 & 4 & 3 \\
-4 & -2 & 5
\end{array}\right|=\mathbf{i}(4 \cdot 5-3 \cdot(-2))-\mathbf{j}(-2 \cdot 5-3 \cdot(-4))+\mathbf{k}(-2 \cdot(-2)-4 \cdot(-4)) \\
=\mathbf{i}(20+6)-\mathbf{j}(-10+12)+\mathbf{k}(4+16)=\left[\begin{array}{c}
26 \\
-2 \\
20
\end{array}\right]
\end{gathered}
$$

Panjang vektor:

$$
|\overrightarrow{A B} \times \overrightarrow{A C}|=\sqrt{26^2+(-2)^2+20^2}=\sqrt{676+4+400}=\sqrt{1080}
$$

Luas segitiga adalah:

$$
\text { Luas }=\frac{1}{2} \sqrt{1080}=\frac{\sqrt{1080}}{2}
$$

Sederhanakan bentuk akar:

$$
\sqrt{1080}=\sqrt{36 \cdot 30}=6 \sqrt{30}
$$

Jawaban akhir: 

$$
\text { Luas. } =3 \sqrt{30}
$$