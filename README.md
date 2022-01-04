# Project-Exploratory-Data-Analysis
Assess existing client base of  a company  to identify potential areas of leaking value


**Background Information:**
Access a large database and perform exploratory data analysis to answer business questions with about 4 year worth of transactional data. The data contains hundreds of thousands and millions of rows of transactions between clients, payors, Denial Code,	Charge, Denial Reason Code,	Denial Reason Descr, Total Charge etc

**Data Cleaning**

    Drop NaN values from DataFrame
    Removing rows based on a condition
    Change columns datatypes needed to be changed(to_numeric, to_datetime, astype)

**Using Data Exploratory Data Analysis to Answer Business Questions**

    Average Monthly Denial Rate?
    Monthly Denial Rate By Year?
    Reasons For High Denial per Year?
    Top Denials?
    Reasons For which Most Bill Patient Denial?
    etc

**Methods AApplied To Answer Business Questions**

    Concatenating multiple csvs together to create a new DataFrame (pd.concat)
    Adding columns
    Parsing cells as strings to make new columns (.str)
    Using the .apply() method
    Using groupby to perform aggregate analysis
    Plotting bar charts, pie charts and lines graphs to visualize our results
    Labeling our graphs
    etc
