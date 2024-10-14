---
title: HIMPUNAN

---

<div style="text-align: justify;">
    
### 1. De Morgan Laws
Ekspresi $\overline{A \cap B}=\bar{A}\cup \bar{B}$ dikenal sebagai **De Morgan Laws** dalam teori himpunan dan logika. Ini menyatakan bahwa komplemen dari irisan dua himpunan sama dengan gabungan dari komplemen keduanya.
#### Penjelasan:
1. $A\cap B$ adalah himpunan dari semua elemen      yang berada di $A$ dan $B$
2. $\overline{A \cap B}$ adalah himpunan semua      elemen yang **tidak** berada di $A$ dan $B$
3. $\bar{A}$ adalah himpunan semua elemen yang      **tidak** berada di $A$
4. $\bar{B}$ adalah himpunan semua elemen yang      **tidak** berada di $B$
5. $\bar{A}\cup \bar{B}$ adalah himpunan semua      elemen yang berada di luar $A$ atau $B$          (komplemen dari $A$ atau komplemen $B$)

Jadi, $\overline{A \cap B}$ mencangkup semua yang **tidak** ada di $A$ dan $B$ secara bersamaan, yang sama dengan elemen-elemen yang berada diluar $A$ atau di luar $B$, yaitu $\bar{A}\cup \bar{B}$. 
Contoh Soal:
Berikut contoh soal sederhana yang melibatkan hukum de Morgan $\overline{A \cap B} = \bar{A} \cup \bar{B}$:

**Soal:**
Diberikan dua himpunan sebagai berikut:
- A = {1, 2, 3, 4}
- B = {3, 4, 5, 6}

Tentukan apakah $\overline{A \cap B} = \bar{A} \cup \bar{B}$ berlaku.

**Penyelesaian:**

1. **Tentukan $A \cap B$:**
   $A \cap B = \{3, 4\}$
2. **Tentukan komplemen dari $A \cap B$ (yaitu $\overline{A \cap B}$):**
   Misalkan semesta S = {1, 2, 3, 4, 5, 6}. Maka:
   $\overline{A \cap B} = S - (A \cap B) = \{1, 2, 5, 6\}$
3. **Tentukan $\bar{A}$ dan $\bar{B}$:**
   - $\bar{A} = S - A = \{5, 6\}$
   - $\bar{B} = S - B = \{1, 2\}$
4. **Tentukan $\bar{A} \cup \bar{B}$:**
   $\bar{A} \cup \bar{B} = \{5, 6\} \cup \{1, 2\} = \{1, 2, 5, 6\}$
5. **Kesimpulan:**
   Karena $\overline{A \cap B} = \{1, 2, 5, 6\}$ dan $\bar{A} \cup \bar{B} = \{1, 2, 5, 6\}$, maka terbukti bahwa:
  $\overline{A \cap B} = \bar{A} \cup \bar{B}$
Jadi, hukum de Morgan berlaku untuk himpunan A dan B pada soal ini.

### 2. Absortion Laws 
Ekspresi $A \cup(A\cap B)=A$ dikenal sebagai **Absortion Laws** dalam teori himpunan dan logika, ada dua aturan yang menjelaskan bagaimana operasi himpunan (atau logika) dapat disederhanakan. Aturan-aturan ini menunjukkan bahwa operasi tertentu bisa "diserap" oleh himpunan atau proposisi lain, sehingga menghilangkan operasi yang tidak perlu.
    #### 1. Hukum Absorpsi Pertama (untuk irisan dan gabungan)
$A \cup(A\cap B)=A$
**Penjelasan:** Gabungan dari himpunan $A$ dengan irisan $A$ dan $B$ tetap menghasilkan $A$. Alasannya, elemen dalam $A\cap B$ pasti juga ada didalam $A$. Jadi, menambahkan irisan itu ke $A$ tidak mengubah $A$.
#### 2. Hukum Absorpsi Kedua (untuk gabungan dan irisan)
$A \cap(A\cup B)=A$
**Penjelasan:** Irisan dari himpunan $A$ dengan gabungan $A$ dan $B$ tetap menghasilkan $A$. Alasannya, setiap elemen yang ada di $A$ akan tetap ada pada irisan tersebut, karena $A$ sudah merupakan bagian dari $A\cup B$, sehingga $B$ tidak menambah elemen apapun ke hasil akhir.
    
**Absorption Laws:**
1. $( A \cup (A \cap B) = A)$
2. $( A \cap (A \cup B) = A)$

**Soal:**
Diberikan dua himpunan sebagai berikut:
- A = {1, 2, 3}
- B = {2, 3, 4}

Tentukan apakah hukum absorpsi berlaku untuk himpunan A dan B.

### **Penyelesaian:**

#### 1. **Buktikan $( A \cup (A \cap B) = A)$:**
   - **Langkah 1:** Tentukan \( A \cap B \):
     $A \cap B = \{2, 3\}$
   - **Langkah 2:** Tentukan $( A \cup (A \cap B) )$:
     $A \cup (A \cap B) = \{1, 2, 3\} \cup \{2, 3\} = \{1, 2, 3\}$
   - **Kesimpulan:** $( A \cup (A \cap B) = A)$, jadi hukum absorpsi **berlaku**.

#### 2. **Buktikan $( A \cap (A \cup B) = A)$:**
   - **Langkah 1:** Tentukan \( A \cup B \):
     $A \cup B = \{1, 2, 3, 4\}$
   - **Langkah 2:** Tentukan $( A \cap (A \cup B))$:
     $A \cap (A \cup B) = \{1, 2, 3\} \cap \{1, 2, 3, 4\} = \{1, 2, 3\}$
   - **Kesimpulan:** $( A \cap (A \cup B) = A)$, jadi hukum absorpsi **berlaku**.

### **Jawaban:**
Hukum absorpsi berlaku untuk himpunan $A$ = {1, 2, 3} dan $B$ = {2, 3, 4}, baik untuk $( A \cup (A \cap B) = A)$ maupun $( A \cap (A \cup B) = A )$
    
### 3. Complement Laws
Hukum komplemen dalam teori himpunan dan logika menjelaskan hubungan antara suatu himpunan dengan komplemennya. Hukum ini mengatur bagaimana suatu himpunan berinteraksi dengan komplemennya, baik melalui gabungan (*union*) maupun irisan (*intersection*).
#### 1. Hukum Komplemen Gabungan
$A\cup \bar{A}=U$
**Penjelasan:** $A$ adalah suatu himpunan yang merupakan bagian dari himpunan semesta $U$. $\bar{A}$ adalah komplemen dari himpunan $A$, yang terdiri dari semua elemen dalam $U$ yang **tidak ada** di $A$. $\cup$ adalah operasi gabungan (*union*), yang menggabungkan dua himpunan dan menghasilkan himpunan baru yang berisi semua elemen yang ada di kedua himpunan tersebut.
**Contoh:** Misalkan semesta $U$ = {1,2,3,4,5} dan himpunan $A$ = {1,2}. Maka:
1. Komplemen $\bar{A}$ = {3,4,5}
2. Gabungan $A\cup \bar{A}$ = {1,2} $\cup$ {3,4,5} = {1,2,3,4,5} = $U$.
#### 2. Hukum Komplemen Irisan
$A \cap \overline{A} = \emptyset$
**Penjelasan:** Hukum ini menyatakan bahwa jika kita mengambil suatu himpunan $A$ dan melakukan irisan (*intersection*) dengan komplemennya $\overline{A}$, hasilnya adalah himpunan kosong  $\emptyset$. Ini karena tidak ada elemen yang bisa berada di $A$ sekaligus di komplemen $\overline{A}. Elemen yang berada di $A$ tidak mungkin berada diluar $A$ (yaituu di $\overline{A}$) pada saat yang sama.
**Contoh:** Mengambil contoh yang sama, jika $A$ = {1,2} dan $\overline{A}$ = {3,4,5}, maka irisan $A \cap \overline{A}$ adalah himpunan kosong kerena tidak ada elemen yang terdapat di kedua himpunan tersebut. Sehingga $A \cap \overline{A} = \emptyset$.

</div>