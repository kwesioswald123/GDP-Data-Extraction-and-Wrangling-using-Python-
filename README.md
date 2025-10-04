# GDP-Data-Extraction-and-Wrangling-using-Python-
Data wrangling is turning messy, raw data into clean, structured data you can actually use.



ABOUT THE PROJECT

A website URL was provided and i was Scrape the data from this URL and prove my Data Wrangling capabilities. Thus, if I'm capable or not. I was also strictly given how the data should finally look like.


STEPS I TOOK


Data Collection – I extracted tables from the webpage using Pandas and retain table number 3 as the required dataframe.

Data Cleaning – I replace the column headers with column numbers, retained columns with index 0 and 2 (name of country and value of GDP quoted by IMF), and also retained the Rows with index 1 to 10, indicating the top 10 economies of the world.

Data Transformation – I assigned column names as "Country" and "GDP (Million USD)".
Changed the data type of the 'GDP (Million USD)' column to integer. Using astype() method.
Converted the GDP value in Million USD to Billion USD
Used numpy.round() method to round the value to 2 decimal places.
Renamed the column header from 'GDP (Million USD)' to 'GDP (Billion USD)'


Validation – Making sure the cleaned dataset is accurate, consistent, and ready for analysis.
