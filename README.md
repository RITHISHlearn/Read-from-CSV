# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:

```
To write a python program for reading content from a CSV file.
Developed by:RITHISH P
Register Number: 212223230173
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:


![Screenshot 2024-05-08 213030](https://github.com/RITHISHlearn/Read-from-CSV/assets/145446645/a7753fa6-ad37-4c0d-a4da-e62a9af1f923)


## RESULT:
Thus the program is written to read the csv file.
