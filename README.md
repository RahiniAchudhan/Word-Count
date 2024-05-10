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
Developed by : RAHINI.A
Register number : 212223230165

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![image](https://github.com/RahiniAchudhan/Word-Count/assets/145742838/e2fa5efe-e43b-4737-b6d3-617ed66eaa97)
![image](https://github.com/RahiniAchudhan/Word-Count/assets/145742838/f76b2dbb-f329-4492-9cca-ba42133077c6)


## RESULT:
Thus the program is written to find the word count from a text.
