# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
import math file
### Step 2: 
Get the values of two list from the user l1 and l2.
### Step 3: 
Substitute the values in the distance formula ![image](https://user-images.githubusercontent.com/118680361/230822060-3e09a537-d90b-4693-838a-3ff659d333ed.png)


### Step 4: 
distance=math.sqrt(((l2[0]-l1[0])**2+((l2[1]-l1[1])**2)))
### Step 5: 
print the distance in two decimal.

### PROGRAM:
```
#Program to find the distance between two points.
#Developed by:BALASUDHAN P 
#RegisterNumber:212222240017
import math
l1=[4,2]
l2=[10,6]
distance=math.sqrt(((l2[0]-l1[0])**2)+((l2[1]-l1[1])**2))
print("{:.2f}".format(distance))
```

### OUTPUT:
![Annotation 2023-04-16 142000](https://user-images.githubusercontent.com/118807740/232287969-a7c02bb6-f8a3-428c-960e-c2033f908f03.png)

### RESULT:
The program to find the distance between two points executed successfully.
