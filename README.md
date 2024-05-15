# Crime_data_2020_to_Present
Homework for Class CIS 4400. 

This dataset reflects incidents of crime in the City of Los Angeles dating back to 2020. T
his data is transcribed from original crime reports that are typed on paper and therefore there may be some inaccuracies within the data. 
Some location fields with missing data are noted as (0°, 0°).
 Address fields are only provided to the nearest hundred block in order to maintain privacy. 


Data Dictionary provided by Data Source, explaining the columns 

Transformation 
Deleted Columns such as Premis and Premis Cd which are not relevant. 
Unified the Date format for Date reported and Date Occured to YYYY-MM-DD.


Data Warehouse
Used Snowflake with integrated with Microsoft Azure to Load Data into Database. 
