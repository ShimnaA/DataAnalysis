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
      