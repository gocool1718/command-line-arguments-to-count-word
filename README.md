# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:import sys

### Step 2: Then declare count is equal to 0
 
### Step 3: read the file with python file name

### Step 4:  Spilitting the word

### Step 5: After spilitting count the number of words in the line

### Step 6: In last statement give the print statement.

## PROGRAM:
'''
Developed by: GOKUL S
Reference number: 22008488

import sys
count = 0
with open(sys.argv[1], 'r') as f:
    for line in f:
        word =line.split()
        count+=len(word)
print("Word count in file: ",count)

### OUTPUT:

![Screenshot from 2023-01-27 14-12-21](https://user-images.githubusercontent.com/121148715/215276063-1dba7b40-b0ee-40c3-ac2a-b8bd4f0b9a81.png)





## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
