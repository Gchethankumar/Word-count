# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Create a text file add sentence to it.
### Step 2:

Using open() open the .txt file in read mode in Python compiler.
### Step 3:

Assign a variable for value zero.
### Step 4:

Using the for loop assigning the fp then use variable to split the content.
### Step 5:

Iterate in nested loop to increment the variable.
### Step 6:

Print the variable.

## PROGRAM:
```
Python program to count the words in file
Programmed By: G.Chethan Kumar
Ref. No. : 212222240022
```
```
fname=input("enter the file name:")
num_words=0
with open(fname,'r')as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)    
```
### OUTPUT:
![Screenshot 2023-05-31 220213](https://github.com/Gchethankumar/Word-count/assets/118348224/addfb342-6d00-4a8c-9453-31f9bf403a16)

![Screenshot 2023-05-31 220200](https://github.com/Gchethankumar/Word-count/assets/118348224/e4337b02-6d7d-4f07-b5f6-b6b39d42cd7c)

## RESULT:
Thus the program is written to find the word count from a text.
