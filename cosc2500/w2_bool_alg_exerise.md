## Simplify Expressions


# 4
(A + B + C)' . (ABC)'
    = A'B'C' . (A' + B' + C')
    = A'A'B'C' + A'B'B'C' + A'B'C'C'
    = A'B'C + A'B'C' + A'B'C'
    = A'B'C'


## Problem Solving

Knob 1 - A
Know 2 - B
Button - X
isLocked(Door) - Y

A B X | Y
------+---
0 0 0 | 0
0 0 1 | 0
0 1 0 | 0
0 1 1 | 1
1 0 0 | 0
1 0 1 | 1
1 1 0 | 1
1 1 1 | 1

Y   = A'BX + AB'X + ABX' + ABX
    = ...


## Mock test


# 1
Find C & V of this signed operation:
    1de3 - 2af2

    0001 1101 1110 0011
  - 0010 1010 1111 0010


--> 
 C 00 11 1 10 0  1 11  
    0001 1101 1110 0011
  + 1101 0101 0000 1110
    -------------------
    1111 0010 1111 0001 f2f1

--> C=0, V=0

# 2
Simplify:
F(a, b, c)
    = a'b + bc' + bc + ab'c'
    = (a'b + bc) + (bc' + ab'c')
    = b(a' + c) + c'(b + ab')
    = b(a' + c) + c'(a + b)
    = a'b + bc + ac' + bc'
    = a'b + ac' + (bc + bc')
    = a'b + ac' + b(c + c')
    = a'b + ac' + b
    = (b + a'b) + ac'
    = b(1 + a') + ac'
    = b + ac'
