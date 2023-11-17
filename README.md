## Read-from-CSV
## AIM:
## TO Read-from-CSV
## ALGORITHM:
## Step 1:Import pandas module as pd.
## Step 2:Using pd.read_csv() method read the CSV file
## Step 3:Using df.head() print the first 10 rows of the CSV file.
## Step 4:Using df.tail() print the last 5 of the CSV file.
## Step 5:Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print(f.head())
print('Row: ',len(f.axes[0]))
print('Col: ',len(f.axes[1]))
```
## OUTPUT:
![282804400-1ac58296-d928-4db0-a4e9-edb78213abcf](https://github.com/hariprasath5106/Read-from-CSV/assets/111515488/a678b86e-accf-47bd-a43e-7b7fe9d53571)

## RESULT:
Hence the program is executed successfully!
