# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Clone the repository from github
### Step 2: 
Assign the function command in the program
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the round(d,2)
### Step 5: 
End the program
### PROGRAM:
  #Program to find the distance between two points.
#Developed by:ALLEN JOVETH P 
#RegisterNumber:23009582
import math
def distance(x1,y1,x2,y2):
    dx=x2-x1
    dy=y2-y1
    d=math.sqrt(dx**2+dy**2)
    return d
x1=4
y1=2
x2=10
y2=6
d=distance(x1,y1,x2,y2)
print(round(d,2))
### OUTPUT:
![image](https://github.com/allenjoveth/DISTANCE-BETWEEN-TWO-POINTS/assets/139422287/8bfc992a-475d-4f6d-a950-407a6695b13e)


### RESULT:
 Thus the distance between two points are successfully executed
