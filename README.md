# Movies-ETL

## Purpose

This project was focused to on the ETL process of data cleaning. Our primary sources for the movie data was wikipedia and Kaggle. The wikipedia data came as a json file and the Kaggle was a csv. We read them into a jupyter notebook using pandas and json.load in order to convert them into dataframes so they would be easier to work with. Next, using lambda and regular expressions, and list comprehension we removed unnecessary data and cleaned up what we wanted to keep. Lastly, we loaded the cleaned data into a database in pgadmin 
