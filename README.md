# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```
# program to find the number of words in a text file
# Developed by : KISHORE NARAYANAN S R
# Register number : 212223110023
num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)  
```
### OUTPUT:
![110](https://github.com/KISHORENARAYANANSR/Word-Count/assets/148202102/123b684f-e363-4eb9-a945-f7f45222f51f)

## RESULT:
Thus the program is written to find the word count from a text.
