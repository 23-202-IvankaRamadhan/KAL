---
title: 'Perkalian_Titik '
---

# Perkalian Titik (Dot Product)

**Pengertian:**  
Perkalian titik (dot product) adalah operasi matematika antara dua vektor yang menghasilkan satu bilangan skalar (real). Operasi ini digunakan untuk mengukur seberapa sejajar arah kedua vektor serta terkait erat dengan besar sudut di antara keduanya.

## Rumus Dot Product

### 1. Berdasarkan Komponen Vektor (Aljabar)
- Untuk vektor 2D: $\mathbf{A} = (a_1, a_2)$ dan $\mathbf{B} = (b_1, b_2)$

$$
\mathbf{A} \cdot \mathbf{B} = a_1 b_1 + a_2 b_2
$$

- Untuk vektor 3D: $\mathbf{A} = (a_1, a_2, a_3)$ dan $\mathbf{B} = (b_1, b_2, b_3)$

$$
\mathbf{A} \cdot \mathbf{B} = a_1 b_1 + a_2 b_2 + a_3 b_3
$$

### 2. Berdasarkan Sudut Antara Vektor (Geometri)

$$
\mathbf{A} \cdot \mathbf{B} = \|\mathbf{A}\| \|\mathbf{B}\| \cos \theta
$$

- Jika $\theta = 90^\circ$ (tegak lurus), hasilnya nol karena $\cos 90^\circ = 0$.

<iframe src="https://www.geogebra.org/classic/c4zfkmhf?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

### Contoh-Contoh

1. Vektor $\mathbf{a} = (0,0)$ dan $\mathbf{b} = (2,1)$

$$
\mathbf{a} \cdot \mathbf{b} = (0)(2) + (0)(1) = 0 + 0 = 0
$$

*Penjelasan:*  
Vektor nol $(0,0)$ akan selalu menghasilkan dot product = 0 dengan vektor lain, karena tidak memiliki panjang maupun arah.

2. Vektor $\mathbf{a} = (0,0)$ dan $\mathbf{c} = (-1,2)$

$$
\mathbf{a} \cdot \mathbf{c} = (0)(-1) + (0)(2) = 0 + 0 = 0
$$

*Penjelasan:*  
Sama seperti sebelumnya, dot product tetap nol karena melibatkan vektor nol yang tidak menyumbang nilai apa pun.

3. Vektor $\mathbf{b} = (2,1)$ dan $\mathbf{c} = (-1,2)$

$$
\mathbf{b} \cdot \mathbf{c} = (2)(-1) + (1)(2) = -2 + 2 = 0
$$

*Penjelasan:*  
Hasil dot product nol menunjukkan bahwa kedua vektor saling tegak lurus ($\theta = 90^\circ$), karena $\cos 90^\circ = 0$.

<iframe src="https://www.geogebra.org/classic/hddxzurw?embed" width="800" height="600" allowfullscreen style="border: 1px solid #e4e4e4;border-radius: 4px;" frameborder="0"></iframe>

---

### Hubungan dengan Sudut Antara Dua Vektor

$$
\mathbf{A} \cdot \mathbf{B} = \|\mathbf{A}\| \|\mathbf{B}\| \cos \theta
$$

- $\|\mathbf{A}\|$: panjang vektor A  
- $\|\mathbf{B}\|$: panjang vektor B  
- $\theta$: sudut di antara A dan B

*Interpretasi:*
- Jika A dan B searah ($\theta = 0^\circ$), maka:

$$
\mathbf{A} \cdot \mathbf{B} = \|\mathbf{A}\| \|\mathbf{B}\| \quad \text{(maksimum)}
$$

- Jika A dan B berlawanan arah ($\theta = 180^\circ$):

$$
\mathbf{A} \cdot \mathbf{B} = -\|\mathbf{A}\| \|\mathbf{B}\| \quad \text{(minimum)}
$$

- Jika A dan B tegak lurus ($\theta = 90^\circ$):

$$
\mathbf{A} \cdot \mathbf{B} = 0 \quad \text{(karena } \cos 90^\circ = 0)
$$

---

### Proyeksi Vektor

Dot product juga dapat digunakan untuk mencari proyeksi vektor $\mathbf{A}$ ke arah $\mathbf{B}$:

$$
\text{Proyeksi A ke B} = \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{B}\|}
$$

*Hasil proyeksi* menunjukkan seberapa besar komponen vektor A yang terletak sepanjang arah B.

**Contoh:**

Misal $\mathbf{A} = (3,4)$ dan $\mathbf{B} = (1,0)$:

$$
A \cdot B = 3 \cdot 1 + 4 \cdot 0 = 3
$$

Proyeksi A ke B:

$$
\frac{3}{\sqrt{1^2 + 0^2}} = 3
$$

---

### Contoh Kasus Geometris

- $\mathbf{A} = (2,1)$ dan $\mathbf{B} = (-1,2)$  
  Dot Product:
  $$
  A \cdot B = (2)(-1) + (1)(2) = -2 + 2 = 0
  $$
  Interpretasi: kedua vektor tegak lurus.

- $\mathbf{C} = (3,4)$ dan $\mathbf{D} = (3,0)$  
  Dot Product:
  $$
  C \cdot D = (3)(3) + (4)(0) = 9 + 0 = 9
  $$
  Interpretasi: hasil positif berarti sudut di antara keduanya kurang dari $90^\circ$.

- $\mathbf{F} = (0,0)$ dan $\mathbf{F} = (2,5)$  
  Dot Product:
  $$
  E \cdot F = 0 \cdot 2 + 0 \cdot 5 = 0
  $$
  Interpretasi: vektor nol tidak menghasilkan arah, sehingga dot product-nya selalu 0.

---

### Menghitung Sudut Antara Dua Vektor

Untuk menghitung $\theta$:

$$
\cos \theta = \frac{\mathbf{A} \cdot \mathbf{B}}{\|\mathbf{A}\| \|\mathbf{B}\|}
$$

**Contoh:**  
$\mathbf{A} = (1,0)$ dan $\mathbf{B} = (1, \sqrt{3})$:

- $A \cdot B = 1 \cdot 1 + 0 \cdot \sqrt{3} = 1$
- $\|A\| = 1, \|B\| = \sqrt{1^2 + (\sqrt{3})^2} = 2$

$$
\cos \theta = \frac{1}{1 \cdot 2} = 0.5 \implies \theta = 60^\circ
$$

---

### Sifat-Sifat Perkalian Titik

1. **Sifat Komutatif**

$$
\mathbf{A} \cdot \mathbf{B} = \mathbf{B} \cdot \mathbf{A}
$$

*Penjelasan:*  
Urutan tidak mempengaruhi hasil dot product.

2. **Sifat Distributif**

$$
\mathbf{A} \cdot (\mathbf{B} + \mathbf{C}) = \mathbf{A} \cdot \mathbf{B} + \mathbf{A} \cdot \mathbf{C}
$$

*Penjelasan:*  
Dot product bisa didistribusikan ke penjumlahan vektor.

3. **Kompatibilitas dengan Skalar**

$$
(c\mathbf{A}) \cdot \mathbf{B} = c (\mathbf{A} \cdot \mathbf{B})
$$

*Penjelasan:*  
Faktor skalar dapat dikeluarkan dari dot product.

4. **Hubungan dengan Panjang Vektor**

$$
\mathbf{A} \cdot \mathbf{A} = \|\mathbf{A}\|^2
$$

*Penjelasan:*  
Dot product vektor dengan dirinya sendiri sama dengan kuadrat panjangnya.

5. **Ortogonalitas**

$$
\mathbf{A} \cdot \mathbf{B} = 0 \implies \theta = 90^\circ
$$

*Penjelasan:*  
Jika hasil dot product nol, kedua vektor tegak lurus.

6. **Perkalian dengan Vektor Nol**

$$
\mathbf{A} \cdot \mathbf{0} = 0
$$

*Penjelasan:*  
Dot product antara vektor apa pun dengan vektor nol selalu 0.
