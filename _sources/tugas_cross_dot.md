---
title: Tugas_Cross_Dot

---

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