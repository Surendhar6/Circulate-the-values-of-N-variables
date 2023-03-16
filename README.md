# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Define a function (for example:'circulate') that takes a variable number of arguments
### Step 2: 
Inside the function, create a list that contains all the arguments passed to the function.
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
 
## Program:
#Program to circulate N values.
#Developed by: Surendhar A
#RegisterNumber: 212222110090
def circulate():
    l=eval(input())
    n=int(input())
    result=l[n:]+l[:n]
    print("After circulating the values are:",result)
    
## Output:
![image](https://user-images.githubusercontent.com/118352907/225654474-e4fde943-7114-411a-bf53-e4c4a146a001.png)

## Result:
Thus the program for circulate n variable is executed successfully.
