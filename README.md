# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Open visual studio code.

### Step 2:
Create file with .py extension.

### Step 3:
Start the program.

### Step 4:
Write the code.

### Step 5:
Run terminal for output of the given program.

### Step 6:
End the program. 

## PROGRAM:
```
'''
Devoloped by : Praveen s
Register number : 22009060
'''
num_words = 0
with open('data.txt','r') as f1:
     for i in f1:
        words=i.split()
        num_words+= len(words)
print("Number of words in the files = {}".format(num_words))
```


### OUTPUT:

![5a data (1)](https://user-images.githubusercontent.com/120218611/214644408-552959a6-7802-4815-acdb-7c36e29325bb.png)

![5A Praveen (2)](https://user-images.githubusercontent.com/120218611/214644449-223984a5-2983-48ea-a1e3-0e67ed058030.png)

## RESULT:
Thus the program is written to find the word count from a text.
