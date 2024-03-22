# Tugas Praktikum Analisis Kompleksitas

## Bilangan Agak Prima

### Deskripsi

Suatu bilangan bulat positif disebut "agak prima" apabila bilangan tersebut hanya habis dibagi oleh 1, 
bilangan itu sendiri, dan sebanyak-banyaknya dua bilangan bulat positif lainnya.

Pak Dengklek memberikan Anda N buah bilangan bulat. Untuk setiap bilangan, 
tentukan apakah bilangan tersebut bilangan agak prima atau bukan.

### Format Masukan

Baris pertama berisi sebuah bilangan bulat N. N baris berikutnya masing-masing berisi sebuah bilangan bulat.

### Format Keluaran

Untuk setiap bilangan, cetak sebuah baris berisi **YA** apabila bilangan tersebut agak prima, atau **BUKAN** jika bukan.

### Contoh Masukan

```cpp
4
1
17
51
52
// ...
```

### Contoh Keluaran

```cpp
BUKAN
YA
YA
YA
BUKAN
// ...
```

### Penjelasan

Faktor-faktor dari 51 adalah 1, 3, 17, dan 51, sedangkan faktor dari 52 adalah 1, 2, 4, 13, 26, 52. 
Oleh karena itu, 51 "agak prima" sedangkan 52 tidak "agak prima". Sesuai definisi di atas, 
bilangan prima secara langsung adalah bilangan "agak prima" juga.

### Batasan 

- 1 ≤ N ≤ 1.000
- 1 ≤ (setiap bilangan bulat) ≤ 1.000.000

Note :
- Gunakan bahasa C++
- Gunakan header `<math.h>` atau `<cmath>` sesuai kebutuhan dan supaya program lebih cepat dan efisien
- Buat laporan pdf (template bebas) kemudian lakukan analisis kompleksitas dari algoritma yang sudah dibuat 
  dan masukkan juga screenshot code yang disertai juga dengan penjelasan.
- Kumpulkan semua source code dan laporan Pdf pada assignment Google Classroom (jangan di-ZIP), 
  diberi format: NamaKelas_PSDA03_NIM_NamaLengkap.cpp,
	contoh: A_PSDA03_L0122003_AddinHadiRizal.cpp / A_PSDA03_L0122003_AddinHadiRizal.pdf 
