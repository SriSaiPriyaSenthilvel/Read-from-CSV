# Read-from-CSV

## AIM:  To develop a python program to read a file rom csv.

## ALGORITHM:
### Step 1: Import the pandas function as pd.
### Step 2: Read the file and store it in the variable f.
### Step 3: Print the head and tail.
### Step 4: Print the number of rows using the length function(len).
### Step 5: Print the number of coloumns using the same length function(len).

## PROGRAM:
```
Program developed by:Samyuktha.S
Reference number:22005276
Python program to read a file from csv.

import pandas as pd
f=pd.read_csv('car.csv')
print(f.head(10))
print(f.tail())
print("Row:",len(f.axes[0]))
print("Col:",len(f.axes[1]))
```

## OUTPUT:
![output](/Screenshot%20from%202023-01-28%2012-44-02.png)

## RESULT:
Thus the program is successfully executed.