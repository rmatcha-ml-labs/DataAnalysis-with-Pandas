# DataAnalysis-with-Pandas

1. Read the Data into a Data frame from varous sources like 
    1) CSV/Tab delimiter file 
    2) JASON File 
    3) Exel File
    4) Hive Database 
    5) HDFS
2. Manipulation and transformation of data in the DataFrame using Pandas series. 

3. Data PreProcessing 

    1) Null Value Handling or Missing Value Treatment (Measured Variables / Categorical Variables) 
       This step is pefromed based on business needs , If the data has less have 25% of data with missing values then we will pefrom
       the missing value treatment operation , If the missing values are more than 25% it toally depends on business what to do with the
       Dataset, They might ask to ignore the missign data rows from the data set  or fill the data if it is around 25%.
       
       For to handle the missing value treatment we need to understand the following
       
            1. Mean    ( Average )
            2. Median  ( The center Value )
            3. Mode    ( Most Accured Value ) 
       
       For Categorical Data Missing values treatment we will use the 'Mode' value of that column 
       For the Measured or numarical columns we will use the 'Mean' of the column  
       
    2) Encoding the Categorical Variables etc

4. Exploratory Data Analyis (EDA) using Panadas

6. Data Visualization using matplotlib
