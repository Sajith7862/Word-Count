# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Take the text input from the user.

### Step 2: Split the input text into words using whitespace as a delimiter.
 
### Step 3: Split the input text into words using whitespace as a delimiter.

### Step 4: Display the count of words to the user.

## PROGRAM:
```
#program to find the number of words in a text file
#Developed by : MOHAMED HAMEEM SAJITH J
#Register number : 212223240090

def count_words(text):
    words = text.split()
    return len(words)

def main():
    text = input("Enter the text: ")
    word_count = count_words(text)
    print("Word count:", word_count)

if __name__ == "__main__":
    main()
```

### OUTPUT:
![image](https://github.com/Sajith7862/Word-Count/assets/145972360/87545a7b-e392-408b-9c7d-c69b33559ca5)



## RESULT:
Thus the program is written to find the word count from a text.
