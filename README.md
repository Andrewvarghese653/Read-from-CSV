# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.

## PROGRAM:
```python
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
<img width="829" alt="Screenshot 2023-11-18 at 11 14 10 AM" src="https://github.com/Andrewvarghese653/Read-from-CSV/assets/145822115/6ad5545d-71b3-44da-9898-45d0b4d15b7f">


## RESULT:
Thus python program for reading content from a CSV file is successful.
