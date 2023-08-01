# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys module
## Step 2:
using sys module,open a file with read mode
## Step 3:
read the file and split the file and stor in the variable
## Step 4:
print the length of the variable
## Step 5:
End the program

## PROGRAM:
DEVELOPED BY: V.THAANESH

REGISTER.NO 23003843

f = open('/content/drive/MyDrive/Colab Notebooks/thanesh.txt','r')


import sys

s=open(sys.argv[0],"r")

a=f.read().split()

print(len(a))

### OUTPUT:
![output](/Screenshot%202023-07-31%20094103.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
