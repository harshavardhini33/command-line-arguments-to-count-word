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
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created. 

## PROGRAM:
~~~
#NAME : HARSHAVARDHINI M
#REG NO : 212221240015
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
~~~

### OUTPUT:
![doc](https://user-images.githubusercontent.com/93427208/153631614-ea0929e2-9543-4617-aed6-bf94b216464a.png)


![doc](https://user-images.githubusercontent.com/93427208/153631657-9147a347-8ceb-4c6d-a7c3-7f73ccf87c33.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
