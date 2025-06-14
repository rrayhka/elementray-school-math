### **1. Mengubah Akar Menjadi Pangkat (dan Sebaliknya)**

#### **Konsep**

Bentuk akar adalah cara lain untuk menulis pangkat dalam bentuk **pecahan**. Angka kecil di luar akar (jenis akar) menjadi **penyebut** (bagian bawah pecahan), dan pangkat di dalam akar menjadi **pembilang** (bagian atas).

#### **Rumus**

$$\sqrt[n]{a^m} = a^{\frac{m}{n}}$$

#### **Contoh Soal**

**Contoh 1: Mudah**

Ubahlah bentuk akar $\sqrt{5}$ ke dalam bentuk pangkat!

**Penyelesaian:**

- Akar kuadrat ($\sqrt{}$) berarti jenis akarnya (n) adalah 2.
- Pangkat dari 5 di dalam akar (m) adalah 1 (karena $5 = 5^1$).
- Maka, bentuk pangkatnya adalah $5^{\frac{1}{2}}$.

**Contoh 2: Sedang**

Ubahlah bentuk pangkat $6^{\frac{2}{3}}$ ke dalam bentuk akar!

**Penyelesaian:**

- Basisnya (a) adalah 6.
- Pembilang (m) adalah 2, ini akan menjadi pangkat di dalam akar.
- Penyebut (n) adalah 3, ini akan menjadi jenis akarnya.
- Maka, bentuk akarnya adalah $\sqrt[3]{6^2}$.

**Contoh 3: Sulit**

Sederhanakan dan ubah $\sqrt[4]{81x^8y^2}$ ke dalam bentuk pangkat!

**Penyelesaian:**

1. Ubah dulu 81 menjadi bentuk pangkat: $81 = 3^4$.

2. Persamaan menjadi: $\sqrt[4]{3^4 \cdot x^8 \cdot y^2}$.

3. Ubah setiap komponen ke bentuk pangkat pecahan:

   - $\sqrt[4]{3^4} = 3^{\frac{4}{4}} = 3^1 = 3$
   - $\sqrt[4]{x^8} = x^{\frac{8}{4}} = x^2$
   - $\sqrt[4]{y^2} = y^{\frac{2}{4}} = y^{\frac{1}{2}}$

4. Gabungkan hasilnya: $3x^2y^{\frac{1}{2}}$.

### **2. Operasi Hitung pada Bentuk Akar dan Pangkat**

#### **Konsep**

- **Penjumlahan/Pengurangan Akar:** Hanya bisa dilakukan pada akar yang "sejenis" (bilangan di dalam akar sama).
- **Perkalian Pangkat:** Jika basis sama, tambahkan pangkatnya ($a^m \times a^n = a^{m+n}$).
- **Pembagian Pangkat:** Jika basis sama, kurangkan pangkatnya ($a^m \div a^n = a^{m-n}$).
- **Pangkat dari Pangkat:** Kalikan pangkatnya ($(a^m)^n = a^{m \times n}$).

#### **Contoh Soal**

**Contoh 1: Mudah**

Hitunglah: $10\sqrt{7} + 2\sqrt{7} - 5\sqrt{7}$

**Penyelesaian:**

Karena semua akarnya sejenis ($\sqrt{7}$), kita tinggal operasikan koefisiennya.

$(10 + 2 - 5)\sqrt{7} = 7\sqrt{7}$

**Contoh 2: Sedang**

Sederhanakan: $\sqrt{50} + \sqrt{18}$

**Penyelesaian:**

1. Sederhanakan setiap akar terlebih dahulu.

   - $\sqrt{50} = \sqrt{25 \times 2} = \sqrt{25} \times \sqrt{2} = 5\sqrt{2}$
   - $\sqrt{18} = \sqrt{9 \times 2} = \sqrt{9} \times \sqrt{2} = 3\sqrt{2}$

2. Karena akarnya sudah sejenis, jumlahkan hasilnya.

   $5\sqrt{2} + 3\sqrt{2} = 8\sqrt{2}$

**Contoh 3: Sulit**

Hitunglah: $(3\sqrt{2})^2 \times (2^5 \div 2^2)$

**Penyelesaian:**

1. Kerjakan bagian pertama: $(3\sqrt{2})^2 = 3^2 \times (\sqrt{2})^2 = 9 \times 2 = 18$.

2. Kerjakan bagian kedua: $(2^5 \div 2^2) = 2^{5-2} = 2^3 = 8$.

3. Kalikan hasil keduanya: $18 \times 8 = 144$.

### **3. Sistem Persamaan Linear Dua Variabel (SPLDV)**

#### **Konsep**

Menyelesaikan dua persamaan dengan dua variabel (**x** dan **y**) untuk menemukan nilai unik yang memenuhi kedua persamaan tersebut. Metode yang umum adalah **eliminasi** (menghilangkan satu variabel) dan **substitusi** (mengganti satu variabel).

#### **Contoh Soal**

**Contoh 1: Mudah**

Tentukan nilai x dan y dari:

$$
\begin{cases}
x + y = 10 \\
x - y = 4
\end{cases}
$$

**Penyelesaian (Eliminasi):**

1. Jumlahkan kedua persamaan untuk menghilangkan y.

   $(x + x) + (y - y) = 10 + 4$

   $2x = 14 \rightarrow x = 7$

2. Masukkan $x = 7$ ke persamaan pertama: $7 + y = 10 \rightarrow y = 3$.

3. Solusi: **x = 7, y = 3**.

**Contoh 2: Sedang**

Tentukan nilai x dan y dari:

$$
\begin{cases}
3x + 2y = 12 \\
x + y = 5
\end{cases}
$$

**Penyelesaian (Eliminasi & Substitusi):**

1. Kalikan persamaan kedua dengan 2 agar koefisien y sama.

   $x + y = 5 \rightarrow 2x + 2y = 10$

2. Kurangkan persamaan pertama dengan persamaan baru.

   $$
   \begin{array}{r}
   3x + 2y = 12 \\
   2x + 2y = 10 \\
   \hline
   x = 2
   \end{array}
   $$

3. Masukkan $x = 2$ ke persamaan $x + y = 5 \rightarrow 2 + y = 5 \rightarrow y = 3$.

4. Solusi: **x = 2, y = 3**.

**Contoh 3: Sulit**

Harga 2 buku dan 3 pensil adalah Rp 13.000. Harga 4 buku dan 1 pensil adalah Rp 19.000. Berapakah harga 1 buku dan 1 pensil?

**Penyelesaian:**

1. Buat model matematika: Misal buku = b dan pensil = p.

   $$
   \begin{cases}
   2b + 3p = 13.000 \\
   4b + p = 19.000
   \end{cases}
   $$

2. Kalikan persamaan kedua dengan 3 agar koefisien p sama.

   $4b + p = 19.000 \rightarrow 12b + 3p = 57.000$

3. Eliminasi p.

   $$
   \begin{array}{r}
   12b + 3p = 57.000 \\
   2b + 3p = 13.000 \\
   \hline
   10b = 44.000
   \end{array}
   $$

   $b = 4.400$ (harga 1 buku)

4. Masukkan $b = 4.400$ ke persamaan $4b + p = 19.000$.

   $4(4.400) + p = 19.000$

   $17.600 + p = 19.000 \rightarrow p = 1.400$ (harga 1 pensil)

5. Jadi, harga untuk 1 buku dan 1 pensil adalah Rp 5.800.

### **4. Menghitung Selisih Hari**

#### **Konsep**

Menghitung jumlah hari yang terlewat antara dua tanggal. Perlu diperhatikan jumlah hari pada setiap bulan. (Jan=31, Feb=28/29, Mar=31, Apr=30, Mei=31, Jun=30, Jul=31, Ags=31, Sep=30, Okt=31, Nov=30, Des=31).

#### **Contoh Soal**

**Contoh 1: Mudah**

Sebuah acara berlangsung dari 8 April hingga 21 April. Berapa hari lama acara tersebut?

**Penyelesaian:**

Lama acara = (Tanggal Selesai - Tanggal Mulai) + 1

$(21 - 8) + 1 = 13 + 1 = 14$ hari.

**Contoh 2: Sedang**

Ayah pergi ke luar kota dari tanggal 25 Mei hingga 10 Juni. Berapa malam ayah menginap?

**Penyelesaian:**

1. Hitung sisa hari di bulan Mei: $31 - 25 = 6$ hari. Jumlah malam di Mei adalah 6.

2. Jumlah hari di bulan Juni hingga tanggal 10: 10 hari. Berarti ada 9 malam sebelum pulang di tanggal 10.

3. Total malam: $6$ malam (Mei) $+ 9$ malam (Juni) $= 15$ malam.

**Contoh 3: Sulit**

Sebuah proyek dimulai pada 15 Desember 2023 dan selesai pada 5 Maret 2024. Berapa hari kerja proyek tersebut berlangsung (tidak termasuk hari Minggu)? (Asumsi 15 Des 2023 adalah Jumat).

**Penyelesaian:**

1. **Desember 2023 (15-31):** 17 hari. Minggu jatuh pada tanggal 17, 24, 31 (3 hari). Hari kerja: $17 - 3 = 14$ hari.

2. **Januari 2024:** 31 hari. Ada 4 hari Minggu. Hari kerja: $31 - 4 = 27$ hari.

3. **Februari 2024:** 29 hari (tahun kabisat). Ada 4 hari Minggu. Hari kerja: $29 - 4 = 25$ hari.

4. **Maret 2024 (1-5):** 5 hari. Minggu jatuh pada tanggal 3 (1 hari). Hari kerja: $5 - 1 = 4$ hari.

5. Total hari kerja: $14 + 27 + 25 + 4 = 70$ hari kerja.

### **5. Mencari Nilai Suku ke-n**

#### **Konsep**

Sebuah barisan bilangan sering mengikuti "resep" atau rumus umum ($U_n$). Untuk menemukan nilai suku tertentu (misal suku ke-10), masukkan angka posisi ($n = 10$) ke dalam rumus.

#### **Contoh Soal**

**Contoh 1: Mudah**

Rumus suku ke-n adalah $U_n = 7n - 3$. Berapakah nilai suku ke-10?

**Penyelesaian:**

Ganti n dengan 10.

$U_{10} = 7(10) - 3 = 70 - 3 = 67$.

**Contoh 2: Sedang**

Rumus suku ke-n adalah $U_n = n^2 + 2n - 1$. Berapakah nilai suku ke-8?

**Penyelesaian:**

Ganti n dengan 8.

$U_8 = (8)^2 + 2(8) - 1$

$U_8 = 64 + 16 - 1 = 79$.

**Contoh 3: Sulit**

Suku ke-5 sebuah barisan aritmetika adalah 17 dan suku ke-10 adalah 32. Tentukan rumus suku ke-n ($U_n$)!

**Penyelesaian:**

1. Rumus umum barisan aritmetika: $U_n = a + (n-1)b$.

   - $U_5 = a + 4b = 17$
   - $U_{10} = a + 9b = 32$

2. Eliminasi kedua persamaan tersebut.

   $$
   \begin{array}{r}
   a + 9b = 32 \\
   a + 4b = 17 \\
   \hline
   5b = 15
   \end{array}
   $$

   Jadi $b = 3$

3. Cari a (suku pertama): $a + 4(3) = 17 \rightarrow a + 12 = 17 \rightarrow a = 5$.

4. Masukkan a dan b ke rumus umum.

   $U_n = 5 + (n-1)3 = 5 + 3n - 3 = 3n + 2$.

   Jadi, rumusnya adalah $U_n = 3n + 2$.

### **6. Pertumbuhan Eksponensial**

#### **Konsep**

Pertumbuhan yang terjadi secara perkalian berulang. Kenaikannya bukan tetap, melainkan semakin cepat seiring waktu.

#### **Rumus**

$$\text{Jumlah Akhir} = \text{Jumlah Awal} \times (\text{Faktor Pengali})^{\text{Jumlah Periode}}$$

#### **Contoh Soal**

**Contoh 1: Mudah**

Sebuah koloni bakteri berjumlah 1.000. Setiap jam, jumlahnya membelah diri menjadi dua kali lipat. Berapa jumlahnya setelah 3 jam?

**Penyelesaian:**

Jumlah Akhir $= 1.000 \times (2)^3 = 1.000 \times 8 = 8.000$ bakteri.

**Contoh 2: Sedang**

Uang sebesar Rp 10.000.000 diinvestasikan dengan bunga majemuk 10% per tahun. Berapa total uang setelah 2 tahun?

**Penyelesaian:**

1. Faktor pengali = 100% + 10% = 110% = 1,1.

2. Jumlah Akhir $= 10.000.000 \times (1,1)^2$

   Jumlah Akhir $= 10.000.000 \times 1,21 = \text{Rp } 12.100.000$.

**Contoh 3: Sulit**

Jumlah penduduk suatu kota adalah 500.000 jiwa dan bertambah 2% setiap tahun. Dalam berapa tahun kira-kira jumlah penduduk akan melebihi 550.000 jiwa?

**Penyelesaian:**

1. Faktor pengali = 102% = 1,02.

2. Kita cari n: $550.000 = 500.000 \times (1,02)^n$.

   $\frac{550.000}{500.000} = (1,02)^n \rightarrow 1,1 = (1,02)^n$.

3. Gunakan metode coba-coba:

   - Tahun ke-1: $500.000 \times 1,02 = 510.000$
   - Tahun ke-2: $510.000 \times 1,02 = 520.200$
   - Tahun ke-3: $520.200 \times 1,02 = 530.604$
   - Tahun ke-4: $530.604 \times 1,02 = 541.216$
   - Tahun ke-5: $541.216 \times 1,02 = 552.040$

4. Jadi, dibutuhkan **5 tahun** agar jumlah penduduk melebihi 550.000 jiwa.

### **7. Operasi Bentuk Aljabar**

#### **Konsep**

Menggabungkan atau mengoperasikan suku-suku aljabar. Ingat, hanya suku **sejenis** (variabel dan pangkatnya sama) yang bisa dijumlahkan atau dikurangkan.

#### **Contoh Soal**

**Contoh 1: Mudah**

Sederhanakan: $(5x + 3y) + (2x - y)$

**Penyelesaian:**

$(5x + 2x) + (3y - y) = 7x + 2y$

**Contoh 2: Sedang**

Kurangkan $(2p - 4q)$ dari $(8p + q)$.

**Penyelesaian:**

Ini berarti $(8p + q) - (2p - 4q)$. Hati-hati dengan tanda negatif.

$8p + q - 2p + 4q = (8p - 2p) + (q + 4q) = 6p + 5q$

**Contoh 3: Sulit**

Jabarkanlah: $(2x + 3)(x - 5)$

**Penyelesaian:**

Gunakan metode FOIL (First, Outer, Inner, Last).

- **F**irst: $2x \times x = 2x^2$
- **O**uter: $2x \times (-5) = -10x$
- **I**nner: $3 \times x = 3x$
- **L**ast: $3 \times (-5) = -15$

Gabungkan semuanya: $2x^2 - 10x + 3x - 15 = 2x^2 - 7x - 15$.

### **8. Konsep Himpunan: Irisan dan Gabungan**

#### **Konsep**

- **Irisan (∩):** Anggota yang dimiliki **bersama** oleh kedua himpunan.
- **Gabungan (∪):** **Semua** anggota dari kedua himpunan digabung, yang sama ditulis sekali.
- **Diagram Venn:** Cara visual untuk menggambarkan hubungan antar himpunan.

#### **Contoh Soal**

**Contoh 1: Mudah**

$A = \{1, 2, 3, 4\}$, $B = \{3, 4, 5, 6\}$. Tentukan $A \cap B$ dan $A \cup B$.

**Penyelesaian:**

- $A \cap B$ (yang sama): **{3, 4}**
- $A \cup B$ (semua digabung): **{1, 2, 3, 4, 5, 6}**

**Contoh 2: Sedang**

$P = \{x | x < 10, x \text{ adalah bilangan prima}\}$, $Q = \{x | 1 < x < 10, x \text{ adalah bilangan ganjil}\}$. Tentukan $P \cap Q$.

**Penyelesaian:**

1. Daftar anggota P: $\{2, 3, 5, 7\}$

2. Daftar anggota Q: $\{3, 5, 7, 9\}$

3. $P \cap Q$ (anggota yang sama): **{3, 5, 7}**

**Contoh 3: Sulit**

Dari 40 siswa, 25 siswa suka basket, 20 siswa suka voli, dan 8 siswa suka keduanya. Berapa banyak siswa yang tidak suka keduanya?

**Penyelesaian:**

1. Gunakan Diagram Venn atau rumus:

   Total = (Suka Basket) + (Suka Voli) - (Suka Keduanya) + (Tidak Suka Keduanya)

2. Siswa yang hanya suka basket: $25 - 8 = 17$

3. Siswa yang hanya suka voli: $20 - 8 = 12$

4. Total siswa yang suka setidaknya satu olahraga: $17$ (basket saja) $+ 12$ (voli saja) $+ 8$ (keduanya) $= 37$

5. Siswa yang tidak suka keduanya: Total Siswa - (Yang suka) $= 40 - 37 = 3$ siswa.

### **9. Fungsi Linear (f(x) = ax + b)**

#### **Konsep**

Sebuah "mesin" matematika yang mengubah input (**x**) menjadi output (**f(x)**) melalui aturan perkalian (**a**) dan penjumlahan (**b**).

#### **Contoh Soal**

**Contoh 1: Mudah**

Jika $f(x) = 5x + 4$, berapakah nilai $f(3)$?

**Penyelesaian:**

$f(3) = 5(3) + 4 = 15 + 4 = 19$.

**Contoh 2: Sedang**

Jika $g(x) = 6x - 7$ dan $g(a) = 17$, berapakah nilai a?

**Penyelesaian:**

1. $g(a) = 6a - 7$

2. Kita tahu $g(a) = 17$, maka:

   $6a - 7 = 17$

   $6a = 17 + 7 = 24$

   $a = \frac{24}{6} = 4$.

**Contoh 3: Sulit**

Suatu fungsi linear $f(x) = ax + b$. Jika $f(2) = 1$ dan $f(4) = 7$, tentukan rumus fungsi tersebut!

**Penyelesaian:**

1. Buat dua persamaan dari informasi yang ada.

   - $f(2) = a(2) + b = 1 \rightarrow 2a + b = 1$
   - $f(4) = a(4) + b = 7 \rightarrow 4a + b = 7$

2. Eliminasi kedua persamaan untuk mencari a.

   $$
   \begin{array}{r}
   4a + b = 7 \\
   2a + b = 1 \\
   \hline
   2a = 6
   \end{array}
   $$

   Jadi $a = 3$

3. Cari b: $2a + b = 1 \rightarrow 2(3) + b = 1 \rightarrow 6 + b = 1 \rightarrow b = -5$.

4. Rumus fungsinya adalah **f(x) = 3x - 5**.

### **10. Volume Limas Alas Persegi**

#### **Konsep**

Volume (isi) limas dihitung dengan mengalikan luas alasnya dengan tinggi, lalu dibagi tiga. Untuk alas persegi, luasnya adalah sisi × sisi.

#### **Rumus**

- Luas Alas ($L_a$): $L_a = s \times s$
- Volume Limas ($V$): $V = \frac{1}{3} \times L_a \times t$

#### **Contoh Soal**

**Contoh 1: Mudah**

Sebuah limas alas persegi memiliki panjang sisi 6 cm dan tinggi 10 cm. Berapa volumenya?

**Penyelesaian:**

1. Luas Alas: $L_a = 6 \times 6 = 36$ cm².

2. Volume: $V = \frac{1}{3} \times 36 \times 10 = 12 \times 10 = 120$ cm³.

**Contoh 2: Sedang**

Volume sebuah limas alas persegi adalah 384 cm³. Jika tingginya 8 cm, berapa panjang sisi alasnya?

**Penyelesaian:**

1. $V = \frac{1}{3} \times L_a \times t$

   $384 = \frac{1}{3} \times L_a \times 8$

   $384 \times 3 = 8 \times L_a$

   $1152 = 8 \times L_a \rightarrow L_a = \frac{1152}{8} = 144$ cm².

2. Karena $L_a = s^2$, maka $s = \sqrt{144} = 12$ cm.

**Contoh 3: Sulit**

Alas sebuah limas berbentuk persegi dengan panjang diagonal 10 cm. Jika tinggi limas 12 cm, hitunglah volumenya!

**Penyelesaian:**

1. Cari panjang sisi (s) alas menggunakan Pythagoras. Pada persegi, $d^2 = s^2 + s^2 = 2s^2$.

   $10^2 = 2s^2 \rightarrow 100 = 2s^2 \rightarrow s^2 = 50$.

2. Luas alas ($L_a$) adalah $s^2$, jadi $L_a = 50$ cm².

3. Hitung Volume:

   $V = \frac{1}{3} \times L_a \times t = \frac{1}{3} \times 50 \times 12 = 50 \times 4 = 200$ cm³.
