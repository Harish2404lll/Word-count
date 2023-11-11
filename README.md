# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file add sentence to it

### Step 2: 
Using open() open the .txt file in read mode in Python compiler
 
### Step 3:
Assign a variable for value zero

### Step 4:  
Using the for loop assigning the fp then use variable to split the content

### Step 5:
Iterate in nested loop to increment the variable

### Step 6: 
Print the variable

## PROGRAM:
'''
PROGRAM TO COUNT THE WORDS IN FILE
REGISTER NO : 23000630
NAME: HARISH G

fname=input("enter the file name:")
num_words=0
with open(fname,'r')as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)   


### OUTPUT:

![Screenshot 2023-11-11 092044](https://github.com/Harish2404lll/Word-count/assets/141472096/8f275880-736e-4b1e-a40a-0b1dacda99ec)



## RESULT:
Thus the program is written to find the word count from a text.
