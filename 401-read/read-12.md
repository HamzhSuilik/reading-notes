# pandas

pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.

**Add pandas library first time :**
- In Terminal write :
`Poetry add pandas`
- Then you can import the Library :
`import pandas as pd`

Create data frame using :
Series : 
`s = pd.Series([1, 3, 5, np.nan, 6, 8])`
NumPy array :
`df = pd.DataFrame(np.random.randn(6, 4), index=dates, columns=list("ABCD"))`


To check the data type for each column : 
`df.dtypes`

to view the top and bottom rows of the frame:
For top : `df.head()` , for bottom :`df.tail()`
You can use int argument to select limit to show data :
`df.tail(3)`

Display the index, columns: 
`df.index` , `df.columns`

Transposing the rows in the columns place :
`df.T`
Selecting a single column :  `df["A"]`
Selecting specific amount of  rows : `df[0:3]`
Select row via the position of the passed integers: `df.iloc[3]`
By integer slices rows and columns :
`df.iloc[3:5, 0:2]`


Setting a new column automatically aligns the data by the indexes :
1 – create new column :
`s1 = pd.Series([1, 2, 3, 4, 5, 6], index=pd.date_range("20130102", periods=6))`
2 – add new column to the data frame :
`df["F"] = s1`


Setting a new column automatically aligns the data by the indexes :
1 – create new column :
`s1 = pd.Series([1, 2, 3, 4, 5, 6], index=pd.date_range("20130102", periods=6))`
2 – add new column to the data frame :
`df["F"] = s1`

pandas primarily uses the value np.nan to represent missing data.

**Operations**
df.mean() : calculate the average of all columns 
Applying functions to the data:  `df.apply(function())`
