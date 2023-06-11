# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
##ALGORITHEM
Step 1:
To write a python program for getting the word count from a text file

Step 2:
Open the required file by using the function "with".

Step 3:
Then use the laptop to assign the i value in the file.

Step 4:
Using split function to spilt the words

Step 5:
Finding the given length of the words by using len() fuction.

Step 6:
Calling the function and Printing the number of words


## PROGRAM:
```
'''Program to count the words in a file
Developed by: Kthiravan.p
Register Number: 212222230063
'''
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:

![7c6e0a44-f9de-47a5-b038-f8d36b72ac49](https://github.com/kathiravan13/Word-count/assets/119831303/f73e4ae1-e203-4337-83fb-e36f5af6f69c)


## RESULT:
Thus the program is written to find the word count from a text.
