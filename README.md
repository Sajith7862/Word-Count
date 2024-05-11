# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Open the file "word.txt" in read mode.

### Step 2: Set a variable num to 0 to keep track of the total number of words.
 
### Step 3: Iterate Through Each Line: Loop through each line in the file.
### a. Split the Line into Words: Use the split() method to split the line into words. This will create a list of words.
### b. Update Counter: Increment the num variable by the number of words found on the current line.

### Step 4: After processing all lines, print the total number of words counted.

## PROGRAM:
```
#program to find the number of words in a text file
#Developed by : MOHAMED HAMEEM SAJITH J
#Register number : 212223240090

num = 0
with open("word1.txt", "r") as f1:
    for line in f1:
        words = line.split()  # Split by any whitespace
        num += len(words)
print("The total number of words in the file is", num)

```

### OUTPUT:
![image](https://github.com/Sajith7862/Word-Count/assets/145972360/0005c67f-16b2-4b5f-a5de-758175b5102a)

## RESULT:
Thus the program is written to find the word count from a text.
