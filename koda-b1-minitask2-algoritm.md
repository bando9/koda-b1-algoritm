# Minitask Algoritma 2

## Algoritma Deskriptif

```
1. Mulai
2. angka dimulai dari 0 dengan variabel num
3. angka didalam num dibagi 2
4. jika hasil dibagi 2 adalah 0, maka dinyatakan angka genap
5. jika hasil dibagi 2 tersisa 1, maka dinyatakan angka ganjil
6. Selesai
```

## Algoritma Flowchart

```mermaid

flowchart TD

    start((Start))

    input[/input angka/]

    dec{angka dibagi 2, % = 0 ?}

    out1[/sisa 0/]
    out2[/sisa 1/]

    print1[angka = GENAP]
    print2[angka = GANJIL]

    finish(((Finish)))



    start --> input
    input --> dec
    dec -. yes .-> out1
    dec -. no .-> out2
    out1 --> print1
    out2 --> print2
    print1 -->finish
    print2-->finish



```
