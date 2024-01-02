# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Initialize num, a count variable, as 0.
### Step 2: 
Open the text file from which the words need to be counted.
### Step 3: 
Use for loop for iteration.
### Step 4:  
Use the split function to split the line into separate words.
### Step 5: 
With the help of len() function add the number of words to the variable 'num'.
### Step 6: 
Print the output.
## PROGRAM:
```
#Developed by: Thaksha Rishi
#Register Number: 212223100058
num=0
with open("sample.txt",'r') as file:
    for i in file:
        word=i.split()
        print(word)
        num+=len(word)
print("The number of words in the text file is :",num)
```

### OUTPUT:
![Alt text](<Screenshot 2024-01-02 225556.png>)


## RESULT:
Thus the program is written to find the word count from a text.
