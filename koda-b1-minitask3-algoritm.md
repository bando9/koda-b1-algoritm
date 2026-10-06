# Menghitung luas & keliling lingkaran

## Algoritma Deskriptif

1. Mulai
2. Masukkan nilai jari-jari lingkaran
3. Jika jari" lingkaran habis dibagi 7, gunakan phi = 22/7
4. Jika tidak, gunakan phi = 3,14
5. Hitung luas Lingkaran = phi x jari" lingkaran x jari" lingkaran
6. Hitung keliling lingkaran = 2 x 3,14 x jari" lingkaran
7. Tampilkan hasil perhitungan luas & keliling lingkaran
8. Selesai

## Flowchart

```mermaid

flowchart TD

    start((Start))

    input[/input r /]

    dec1{r habis dibagi 7?}

    proc3[phi = 3,14]
    proc4[phi = 22/7]

    proc1["L= phi x r x r"]


    proc2[K=2 x phi x r]

    out1[/output L & K/]

    finish(((Finish)))


start --> input
input --> dec1
dec1 -. yes .->proc4
dec1 -. no .->proc3
proc4-->proc1
proc3-->proc1
proc1 --> proc2
proc2 --> out1
--> finish


```
