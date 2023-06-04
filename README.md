# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: import os

Step 2: Open file using open().

Step 3: Use for loop

Step 4: Use len to count number of words.

Step 5: Give print.

Step 6: End of the program

## PROGRAM:
```python
#Developed by: DEVADARSHAN A S
#Register number: 212222110007
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```
## OUTPUT:
![image](https://github.com/DEVADARSHAN2/Word-count/assets/119432150/3709e70b-d34c-4dfd-9ae4-4e800a07b9a9)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
