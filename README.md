***Data Analysis with Pandas***

    - DataFrames similar to SpreadSheet
    - Fast as it wraps around C operations
    - Works with all types of data (csv, mysql, json...)
    - Incorporate other dataanalysis modules, (matplotlib, numpy, scikitlearn)

    - Pandas is a third party module.
    - 2 Types of data - Series (Single Column DataFrame), DataFrame.

    - Default datatype is int64,. String is Object datatype
    - WE reference an item through column and index
    - Can do negative indexing on Pandas Series like Python list.

**IO Operations**

    - read_csv(), to_csv()
    - read_excel()
    - Heirarchical Data Format (hdf) Massive Size and Peer Number Data 
    - eg: stock price datas
    - Can put multiple tables to an hdf file, so while reading we need to specify the table

    - Pickle saves info in binary form, very compressed
    - Pickle is used to save any object in python
    - Pickle function in python and in pandas
    
**Pandas Operations**

      - Column Manipulation
  
      - Read data from web using pandas_datareader.data
      - Create New columns and operating on columns
      - Applying Logical operation on Column and Dataframe
      - Statistical Function on dataframe
      - Moving or rolling statistics
      - Rolling Apply - we can write our own function and apply rolling
      
**Handling Missing Data or Outliers**

      - In real world when you collect data there will be missing datas
      - Q1. How do we handle missing data
      - Q2. How do we detect Erroneous data
      - Q3. How we differentiate between Erroneous data and Outliers
      - If you are 100% sure the data is an outlier, can delete, else dont delete
      - dropna() - how ="all"
      
      - 3 Major choice of filling data
      - 1:Fill in with as Static number, 2:Fill forward, Backward 3:Totally get rid of rows
      - We can limit the number of fills to 1%
      
      - detecting Outliers
      - describe the data and get the standard deviation
      - If we have high standard deviation, it can be due to some outliers
      - create the rolling standard deviation for the column
      - filter out the rows with standard deviation > 50 (some threshold)
      - You should remove outlier if you are 100% certain that it is an outlier
      
**Combining DataFrames**

      - Concatenation 
      - Appending
      - Merging  (On a shared column)
      - Join (on index)
      
**Advanced Operations**

       - Read from quandl and create a pickle and save.
       - Sort with respect to columns
       - Sorting by Multiple rules
       - Resampling - generally with time series
       - if we have data updated every millisecond, we can convert to every minute (take mean)
       - ohlc resampling (open high low close)
       - Correlation and Covariance
       - Mapping
       - Buffering - without pandas and with pandas
       - Buffering in and out hdf5
       - Buffering is about sacrificing storage for ram.
       - Instead of reading the whole data at a strech, read in chunks
       
**Working with Database**

       - Push data to a sqlite3 database from a csv file using pandas
       - Read from database to a dataframe  
       - Resample the data
     
     
       
