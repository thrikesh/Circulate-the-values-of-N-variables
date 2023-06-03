# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1:

Assume the keyword to run the program
### Step 2:

Assing the value of the first variable
### step 3:

Get the value from the user for the number of rotation
### Step 4:

Using the slicing concept rotate the list
### Step 5:

using the slicing concept rotate the list withthe denote of the first variable
### Step 6:

print the values of the first variable

## Program:
```
#Program to circulate N values.
#Developed by: Thrikeswar P
#RegisterNumber:212222230162
def circulate():
    list1=eval(input())
    n=int(input())
    result=list1[n:]+list1[:n]
    print("After circulating the values are:",result)
```
## Output:

![Screenshot from 2023-04-15 11-22-06](https://user-images.githubusercontent.com/119831303/232187165-0630d0d6-0091-482b-93a2-1da68310c68f.png)


## Result:
The result was excuted sucessfully.
