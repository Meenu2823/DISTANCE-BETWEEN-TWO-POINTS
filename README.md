# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance between two points
## ALGORITHM:
### Step 1: 
Start the program by importing math module for doing calculations using the builtin functions
### Step 2: 
Assign the 2 points as two lists
### Step 3: 
Substitute the values in the distance formula
![formula](/formula.JPG)  
### Step 4: 
Print the distance calculated using format() function
### Step 5:
End the program 
### PROGRAM:
~~~
#Program to find the distance between two points.
#Developed by:Meenu.S 
#RegisterNumber:23003303
import math
list1=[4,2]
list2=[10,6]
distance=math.sqrt((list2[0]-list1[0])**2+(list2[1]-list1[1])**2)
print("{:.2f}".format(distance))
~~~
  
### OUTPUT:
![output](<python exp-1c.png>)

### RESULT:
Thus the python program to find the distance between two points has been executed successfully.
