# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2: 
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1].
 
### Step 3: 
Read the file using read() method.

### Step 4:  
Use split() method to split the file content into words.

### Step 5: 
Use len() to find the total words.

### Step 6: 
Run the program to determine the number of words in the file created.

## PROGRAM:
~~~python 
import sys
count=0
with open(sys.argv[1],'r') as f:
    for line in f:
        word = line.split()
        count += len(word)
print("Word Count in File = ",count)
~~~
### OUTPUT:

![word3](https://user-images.githubusercontent.com/93978702/154787204-02b5b4eb-dccc-49cb-b6f6-984c4209b120.jpg)

![python](https://user-images.githubusercontent.com/93978702/154787209-8183bd76-ed9c-4383-b742-ea11d23f619c.jpg)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
