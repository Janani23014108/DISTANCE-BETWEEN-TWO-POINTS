# DISTANCE-BETWEEN-TWO-POINTS
Name:J.JANANI

Register no:212223230085

Department:B.Tech AIDS
## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1:
Using import math function,do the calculations
### Step 2: 
Take the two coordinates as l1 and l2

### Step 3: 
Substitute the values in the distance formula 

![formula](/formula.JPG)
### Step 4: 
using the print function, display the distance between the two points.
### Step 5: 
End the program.


### PROGRAM:
```
## DISTANCE-BETWEEN-TWO-POINTS
## Developed by:J.JANANI
## Register No:212223230085

import math

def calculate_distance(point1, point2):
    x1, y1 = point1
    x2, y2 = point2
    distance = math.sqrt((x2 - x1)**2 + (y2 - y1)**2)
    return distance


point1 = [4, 2]
point2 = [10, 6]


distance = calculate_distance(point1, point2)

print(f" {distance:.2f}")
```  


### OUTPUT:

![python exp 3](https://github.com/Janani23014108/DISTANCE-BETWEEN-TWO-POINTS/assets/146822085/2fbe8539-99aa-4ad3-9863-d6e5b28e8609)

### RESULT:
  Thus,DISTANCE BETWEEN TWO POINTS are successfully executed.
