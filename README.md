# Read-from-CSV

## AIM:
To write a program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using cif.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your sustems maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```python
Developed by:shakthi kumar s
Register Number:22009242
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
## OUTPUT:
![](Read_from_csv_SK.png)
## RESULT:
Thus the program executed successfully for read csv file.
