# Python If-Else

**Task**<br/>
Given an integer, n, perform the following conditional actions:

- If n is odd, print Weird
- If n is even and in the inclusive range of 2 to 5, print Not Weird
- If n is even and in the inclusive range of 6 to 20, print Weird
- If n is even and greater than 20, print Not Weird

**Input Format**<br/>

A single line containing a positive integer, n.

**Constraints**<br/>

- 1 < n < 100

**Output Format**<br/>

Print Weird if the number is weird. Otherwise, print Not Weird.

**Sample Input 0**<br/>
```
3
```
**Sample Output 0**<br/>
```
Weird
```
**Explanation 0**<br/>

n = 3

n is odd and odd numbers are weird, so print Weird.

**Sample Input 1**<br/>
```
24
```
**Sample Output 1**<br/>
```
Not Weird
```
**Explanation 1**<br/>

n = 24

n > 20 and is even, so it is not weird.

## Answer
```python
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    n = int(input().strip())
    if n % 2 != 0:
        print("Weird")
    elif n % 2 == 0 and n in [2,3,4,5]:
        print("Not Weird")
    elif n % 2 == 0 and n in [6,7,8,9,10,11,12,13,14,15,16,17,18,19,20]:
        print("Weird")
    elif n % 2 == 0 and n >= 21:
        print("Not Weird")
```
