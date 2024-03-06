Encoder logic
if(a:0->1)
    then if(b=0)
        then ->
    else //(b=1)
        then <-
if(a:1->0)
    then if(b=0)
        then <-
    else //(b=1)
        then ->

encoder pins:
    30A:p0.10
    30B:p0.02
    31A:p0.329
    31B:p0.31
LED
    P1.00
empty:
    P0.06
    P0.08
    p0.17
    p0.20
    