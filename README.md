# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words is 0.

### Step 2:
open it with file1.txt file.

### Step 3:
Give range for i.

### Step 4:
Then next split the words.

### Step 5:
count the number of words.

### Step 6:
Giving print statement for getting output.

## PROGRAM:
```
NAME: SARWESHVARAN A
REGISTER NUMBER: 212223230198

num=0
with open("C:/Users/BSS/Documents/words.txt","r") as f1:
   for i in f1:
     word=i.split()
     num += len(word)
print("The number of words are in the file is ",num)
```

### OUTPUT:

![alt text](<Word count.png>)

![alt text](<Word count..png>) 

## RESULT:
Thus the program is written to find the word count from a text.
