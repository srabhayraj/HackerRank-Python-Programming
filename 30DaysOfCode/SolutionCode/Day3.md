```
#!/bin/python3

import math
import os
import random
import re
import sys



if __name__ == '__main__':
    N = int(input())
if N % 2 != 0:
    print("Weird")
else:
    if N in range(2,5):
        print("Not Weird")
    elif N in range(6,21): 
        print("Weird")
    elif N >= 21: 
        print("Not Weird")
    else:
        print("Wrong Input")
```

```
###Output:

Congratulations!

You have passed the sample test cases. Click the submit button to run your code against all the test cases.

Sample Test case 0
Sample Test case 1

Input (stdin)
3

Your Output (stdout)
Weird

Expected Output
Weird
```
