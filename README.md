# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
#Step 1:
Import the sys module.

# Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

# Step 3:
Read the file using read() method

# Step 4:
Use split() method to split the file content into words.

# Step 5:
Use len() to find the total words.

# Step 6:
Run the program to determine the number of words in the file created.
## PROGRAM:
```
'''
#Developed by: marella dharanesh
#RegisterNumber: 22000785
'''
import sys
count= 0
with open(sys.argv[1],'r') as f1:
    for line in f1:
        word= line.split()
        count += len(word)
print("word count in file = ",count)
```
### OUTPUT:
# TextFile:
![cmd output](https://user-images.githubusercontent.com/118707669/215251597-11409c58-730a-4924-bfd3-42ed25edcd57.png)

# Pythonflie:
![215007347-aca69f43-cfff-4ea8-83d6-e51538cf06cc](https://user-images.githubusercontent.com/118707669/215252921-ae92e07e-aa27-486a-a650-aef58b6f556a.png)

![214853117-e07ba12c-ccbd-4383-822b-7f309869b434](https://user-images.githubusercontent.com/118707669/215252926-acc2b509-779a-46cf-924e-b22bd354e321.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
