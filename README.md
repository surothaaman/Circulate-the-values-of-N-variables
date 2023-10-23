# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
Step 1:
Get the values from the user

Step 2:
And also get the input for number of rotation

Step 3:
Get the value from the user for the number of rotation

Step 4:
Using the slicing concept rotate the list

Step 5:
Print the values after circulating it.

Step 6:
End the program
## Program:
```
#Program to circulate N values.
#Developed by: SUROTHAAMAN R
#RegisterNumber:23008504
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot (39)](https://github.com/surothaaman/Circulate-the-values-of-N-variables/assets/133313653/45db85ea-5e51-4e76-81a9-ef73c25b510e)

## Result:
