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
       
       For Categorical Data Missing values treatment we will use 'Mode'
       
       For the Measured or numarical columns we will use 'Mean'  or 'Median' 
       
       When we have an outlier in the data then 'Median' and if there is no outlier then 'Mean'
       
       There are multiple ways to identify the outliers ( Which i will cover it as a separate topic but for now we will look at one approch )
       
            1. Box Plot
            2. Stadard Deviation 
            3. DBScan Clustering
            4. isolation forest
            5.Robust Random Cut Forest
   
   BoxPlot is the most widely used methode. 
   
   Box plots are a graphical depiction of numerical data through their quantiles. It is a very simple but effective way to visualize outliers. Think about the lower and upper whiskers as the boundaries of the data distribution. Any data points that show above or below the whiskers, can be considered outliers or anomalous
       
    2) Encoding the Categorical Variables 
       
       In General Categorical variables are Objet datatype ( String's) data , Whcih occupy more space in the memory while reading a huge 
       dataset into a dataframe  ,By encoding the Categorical variables to int will reduce the size of the datrame and wihch will              improve performance of the ML Model calculations on the data. So this step is very important and a thumb rule to encode the data        before we go with any model build. 
       

4. Exploratory Data Analyis (EDA) using Panadas

6. Data Visualization using matplotlib
