# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name from the user.
### Step 2:
Assign num_words equal to 0.
### Step 3:
open the file by with open(fname,"r") as f: for handling.
### Step 4:
Iterate through each line in the file and separate them into words using space('')
### Step 5:
Find the number of words using num_words+=len(words)
### Step 6:
End the program by orinting the output

## PROGRAM:
```
#DEVELOPED BY: ROSHINI S
#REGISTER NUMBER : 212223240142

fname=input("Enter the file name: ")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
print("Number of words: ",num_words)
```
## OUTPUT:

![Screenshot 2024-05-10 191707](https://github.com/Roshini2201/Command--line-arguments-to-count-word/assets/154105318/5802be8b-46ac-42c9-99bb-4a2ff15659ee)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
