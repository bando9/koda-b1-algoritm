# Algoritma Perhitungan

## Deskriptif

## Pseudo-code

```pseudo-code
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE HASIL : INTEGER

INPUT A
INPUT B

HASIL <- A+B

OUTPUT "Hasilnya = ", HASIL


```

### Loop 1-5

```mermaid

flowchart TD
    start((start))
    input[/i <- 1/]
    check{i <= 5 ?}
    output[/output i/]
    increment[i++]
    finish(((finish)))

start --> input
input --> check
check -- YES --> output
output --> increment
increment --> check

check -. NO .-> finish

```

```pseudo-code


FOR i <- 1 TO 5
    OUTPUT i
NEXT i

```
