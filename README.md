# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the values from the user
### Step 2: 
Assign the value of variable to a temporary variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list
### Step 5: 
Print both the values it would be interchanged
### Step 6: 
End the program
## Program:
```
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n:]+l[:n]
    print("After circulating the values are:",l)
```
## Output:
![Screenshot 2024-04-06 201601](https://github.com/SanjaiOfficial/Circulate-the-values-of-N-variables/assets/151763180/afeb6419-b4cf-484d-9923-22a4c8d8fea1)
![Screenshot 2024-04-06 201611](https://github.com/SanjaiOfficial/Circulate-the-values-of-N-variables/assets/151763180/9271e58d-3a50-4a09-8877-2c2d898e2887)

## Result:
The output for circulate the values of n variables is successfull.
