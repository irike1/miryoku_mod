Encoder logic
if(a:0->1)
    then if(b=0)
        then volume up
    else //(b=1)                
        then volume down
if(a:1->0)
    then if(b=0)
        then volume down
    else //(b=1)
        then volume down

encoder pins:
    30A:p0.10
    30B:p0.02
    31A:p0.29
    31B:p0.31
LED
    P1.00
empty:
    P0.06
    P0.08
    p0.17
    p0.20
    