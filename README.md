# Circulate-the-values-of-N-variables
## Aim:
To write a python program to circulate the n variables using function concept
## Equipment’s required:
PC
Anaconda - Python 3.7
## Algorithm: 
### Step 1: 
Get the list inputs from the user
### Step 2: 
Assign the list to a variable
### Step 3: 
Get the value from the user for the number of rotation
### Step 4: 
Using the slicing concept rotate the list

### Step 5: 
Print the newly created list.
### Step 6: 
End the program
## Program:
```
#Program to circulate N values.
#Developed by: Cynthia Mehul J
#RegisterNumber: 23009725
def circulate():
    l=eval(input())
    n=int(input())
    l=l[n: ]+l[ :n]
    print("After circulating the values are:", l)
```

## Output:
![label](/Output%20Circulate.jpg)

## Result:
Thus the circulation of a list of values are successfully executed.
