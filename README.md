# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file. 

### Step 2: 
Open the required file by using the function "with" 
 
### Step 3: 
Then use the laptop to asssign the i value in the file 

### Step 4:  
Using split function to split the words

### Step 5: 
Finding the given length of the words by using len()

### Step 6: 
Calling the function and printing the number of words 

## PROGRAM:

```python
'''
Program to count the no. of words in a file.
Developed by:S.Suriya prakash
Reg.no: 23013599
'''
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)
```

### OUTPUT:
![image](https://github.com/Krishnakanth23006762/Word-count/assets/138849446/b48e8e75-e480-466f-b3e0-f9af2b6a88ea)




## RESULT:
Thus the program is written to find the word count from a text.
