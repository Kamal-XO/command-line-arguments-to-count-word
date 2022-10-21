# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: 
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words

### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM: 
### Program to sort the elements in the list using the Selection Sort algorithm.
```
Developed by: Kamalesh SV
RegisterNumber: 22001133

import sys
count = 0
with open (sys.argv[1],'r') as f1:
    for line in f1:
        word = line.split()
        count += len (word)
print("word count in file = ",count)
```
### OUTPUT:


<br>

<br>

<br>

<br>

<br>
<br>

<br>
<br>

![OUTPUT](./output.png)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
