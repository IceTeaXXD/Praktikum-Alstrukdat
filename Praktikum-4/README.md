# Soal

```
Ambillah ADT Matriks yang sudah Anda buat pada tugas pra-praktikum sebelumnya dan

tambahkan beberapa primitif berkaitan dengan operasi berbasis baris dan kolom

matriks sebagai berikut:


/* Operasi berbasis baris dan per kolom */


float AvgRow(Matrix M, IdxType i);

/* Menghasilkan rata-rata dari elemen pada baris ke-i */

/* Prekondisi: i adalah indeks baris efektif dari M */


float AvgCol(Matrix M, IdxType j);

/* Menghasilkan rata-rata dari elemen pada kolom ke-j */

/* Prekondisi: j adalah indeks kolom efektif dari M */


void MinMaxRow(Matrix M, IdxType i, ElType * max, ElType * min);

/* I.S. i adalah indeks baris efektif dari M, M terdefinisi */

/* F.S. max berisi elemen maksimum pada baris i dari M

min berisi elemen minimum pada baris i dari M */


void MinMaxCol(Matrix M, IdxType j, ElType * max, ElType * min);

/* I.S. j adalah indeks kolom efektif dari M, M terdefinisi */

/* F.S. max berisi elemen maksimum pada kolom j dari M

min berisi elemen minimum pada kolom j dari M */


int CountNumRow(Matrix M, IdxType i, ElType X);

/* Menghasilkan banyaknya kemunculan X pada baris i dari M */


int CountNumCol(Matrix M, IdxType j, ElType X);

/* Menghasilkan banyaknya kemunculan X pada kolom j dari M */


void RotateMat(Matrix *m);

/* I.S. m terdefinisi dan IsSquare(m) */

/* F.S. m "di-rotasi" searah jarum jam

   untuk semua "lapisan" elemen mulai dari yang terluar

   Contoh matrix 3x3 sebelum dirotasi:

   1 2 3

   4 5 6

   7 8 9


   Contoh matrix 3x3 setelah dirotasi:

   4 1 2

   7 5 3

   8 9 6

   Contoh matrix 4x4 sebelum dirotasi:

   1 2 3 4

   5 6 7 8

   9 10 11 12

   13 14 15 16

   Contoh matrix 4x4 setelah dirotasi:

   5 1 2 3

   9 10 6 4

   13 11 7 8

   14 15 16 12

*/


Kumpulkan file matrix.c.

```

![](Soal/submatrix.png)