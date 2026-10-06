# fizzbuzz muncul di bilangan genap

## FLowchart

```mermaid

flowchart TD
    start((Start))

    input[/i <- 1/]

    check1{i <= 10 ?}

    increment[i++]

    check2{i % 2 == 0 ?}
    fizzbuzz[/output fizzbuzz/]
    nofizzbuzz[/output i/]



    finish(((finish)))

start --> input
input --> check1
check1 -- YES --> check2

check2 -- YES --> fizzbuzz
check2 -- NO --> nofizzbuzz

fizzbuzz --> increment
nofizzbuzz --> increment

increment --> check1

check1 -- NO --> finish




```

## Pseudo Code

```pseudo-code

DECLARE i : INTEGER
i <- 1

FOR i <- 1 TO 10
    IF i % 2 = 0 THEN
        OUTPUT "fizzbuzz"
    ELSE
        OUTPUT i
    ENDIF
NEXT i

```
