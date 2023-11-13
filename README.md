# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with txt file 
### Step 3: 
Give range for i
### Step 4:  
Then nxt split the words
### Step 5: 
Count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```PYTHON
# REGISTER NO : 212222240029
# NAME: GANESH R

fname=input("enter the file name:")
num_words=0
with open(fname,'r')as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)   
```
### OUTPUT:
![PY9](https://github.com/ganesha360/Word-count/assets/120884552/7374583c-4332-424d-a698-9cd764fce074)

## RESULT:
Thus the program is written to find the word count from a text.
