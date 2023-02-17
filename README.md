# Weather_project
Cleaning &amp; querying weather data
About the project:
Weather prediction is one of the most certainly required information in all over the regions It involves collecting global meteorological surface and upper-air observations, preparing global surface and upper air pressure, temperature, moisture, and wind analyses at frequent time intervals based upon these observations we predict some data for upcoming days weather conditions.

This data contains day wise weather attributes from 2022 to July 2033 (predicted data)
Columns are as follows :
Date	
Average temperature (°F)
Average humidity (%)	
Average dewpoint (°F)
Average barometer (in)	
Average windspeed (mph)
Average gust speed (mph)	
Average direction (°degree)
Rainfall for month (in)	
Rainfall for year (in)
Maximum rain per minute	
Maximum temperature (°F)
Minimum temperature (°F)
Maximum humidity (%)
Minimum humidity (%)	
Maximum pressure
Minimum pressure	
Maximum wind speed (mph)
Maximum gust speed (mph)
Maximum heat index (°F)
NOTE:the given data requires cleaning and analysis to proceed further for any analysis.

## Data pre-processing 
This is one of the important steps in data analytics because data that is not processed can lead to different unwanted results when the data is used for further applications. This task includes sub-tasks such as handling null values, deletion or transformation of irrelevant values, data type transformation, removing duplicates, etc. The tasks to be performed for cleaning the data set are given below:

** Subtask 1: Correct years for given data set
** Subtask 2: removal of duplicate rows and duplicate Columns
** Subtask 3: fix a few labels in the given data set
** Subtask 4: Encoding data into suitable format

The dataset we used in this project was populated using a scraping technique, the encoding method may be different we prefer UTF-8 encoding as it is majorly used in all the database servers. To do so, perform the below tasks:

1. In the menu bar of excel, select option data. Then select from text/CSV and choose the file in which you made changes using excel

2. The default file origin will be UTF -8. Keep all the field as it is and select load

3. Save the file as CSV(comma-delimited) file.

4. Import the file into your SQL database (Analyze the dataset with respect to your database system and then change it, if necessary).

