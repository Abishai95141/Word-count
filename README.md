# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file in read mode and handle it in test mood.
### Step 2: 
 Read the text using read() function.
### Step 3: 
Split the text using space separator.We assume that words in a sentance are separted by a space character.
### Step 4:  
The length of the split list should equal the numbers of words in the test file.
### Step 5: 
Print the output
### Step 6: 
End the program
## PROGRAM:
```
# Developed by: Abishai K C
Register Number: 23001564
f = open("C:\\Users\\abish\\Desktop\\sample\\Hello world.txt","r")
data = f.read()
lst = data.split()
print(len(lst))
```
### OUTPUT:
![file handiling](https://github.com/Abishai95141/Word-count/assets/139335314/8163c92b-ca05-4859-be0b-55cd21481c2c)

## RESULT:
Thus the program is written to find the word count from a text.
