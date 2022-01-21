# 8-bit-ALU

Currently supporting 6 operations:

|     | invert  B |  Op |
|-----|:---------:|:---:|
| AND | 0/1       | 000 |
| OR  | 0/1       | 010 |
| XOR | 0/1       | 100 |
| ADD | 0         | 110 |
| SUB | 1         | 110 |
| MUL | 0/1       | 001 |

* Bitwise Operations use 1s compliment for inverting B
* Arithmetic Operations use 2s compliment for negating B
