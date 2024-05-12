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
program to find the number of words in a text file
Developed by :Vishnu Km
Register number : 212223240185

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:
![WhatsApp Image 2024-05-12 at 19 23 44_0535391d](https://github.com/vishnukayyala/Word-Count/assets/151489368/65398355-945b-4490-862c-2d4d3dc485c8)



## RESULT:
Thus the program is written to find the word count from a text.
