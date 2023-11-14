# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1: Define the variable to count the number of words in the file and defined with 0.

### Step 2:  Open the text file using the with open keyword.
 
### Step 3: Using r command i.e:read mode.

### Step 4: Using for loop iterate the file to split the space in the words.

### Step 5: The splited and stored in the variable, use len() function of the splited word variable.

### Step 6: End the program.

## PROGRAM:
```
'''
Developed by: UDHAYA SANKARAN M
Register number: 212222110051
'''
num_words=0
with open('text.txt','r') as f1:         
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in a file = {}".format(num_words))
```
### OUTPUT:
![image](https://github.com/Udhayasankaran04/Word-count/assets/119393933/b65df536-2ba6-49cf-886a-7553db219e40)

## RESULT:
Thus the program is written to find the word count from a text.
