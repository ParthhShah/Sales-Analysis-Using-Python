# Sales-Analysis-Using-Python
Set of real world data science tasks completed using the Python Pandas library.


We initiate the data cleaning process by performing various tasks:
- Eliminating NaN values from the DataFrame
- Filtering rows based on specific conditions
- Adjusting column types (using functions like `to_numeric`, `to_datetime`, `astype`)

Once the data is refined, we transition to the data exploration phase. Here, we address five key business questions related to our dataset:
- Identifying the most lucrative month in terms of sales and determining the corresponding revenue
- Pinpointing the city with the highest product sales
- Deciding the optimal time for displaying advertisements to maximize customer purchases
- Investigating products that are frequently sold together

To address these questions, we leverage various pandas and matplotlib methods:
- Merging multiple CSV files into a new DataFrame using `pd.concat`
- Introducing additional columns
- Parsing cell values as strings to create new columns (using `.str`)
- Employing the `.apply()` method
- Utilizing `groupby` for aggregate analysis
- Generating bar charts and line graphs to visually represent our findings
- Adding labels to enhance the clarity of our visualizations
