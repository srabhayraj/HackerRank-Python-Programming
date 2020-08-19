```
#!/bin/python3

import math
import os
import random
import re
import sys

# Complete the solve function below.
def solve(meal_cost, tip_percent, tax_percent):
    tip = meal_cost * tip_percent / 100
    tax = meal_cost * tax_percent / 100
    total_cost = meal_cost + tip + tax
    final_cost = round(total_cost)      
    print(final_cost)

if __name__ == '__main__':
    meal_cost = float(input())
    tip_percent = int(input())
    tax_percent = int(input())
    solve(meal_cost, tip_percent, tax_percent)
```

```
Output:

Congratulations!

You have passed the sample test cases. Click the submit button to run your code against all the test cases.

Sample Test case 0
Sample Test case 1
### Input (stdin)
12.00
20
8
### Your Output (stdout)
15
### Expected Output
15
```
