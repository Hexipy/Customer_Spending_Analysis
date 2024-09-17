# Customer_Spending_Analysis
**Context and Objective**

![Small Scale Data](/Assets)

The "Customer Spending Analysis" project aims to explore and analyze a dataset related to customer spending across various countries. The goal is to provide meaningful insights into customer spending habits by identifying trends and patterns in the data. The ultimate objective is to create a comprehensive report and visualizations that offer a better understanding of consumer behavior in different geographical contexts.
**Data**

The dataset used in this project is a CSV file containing the following information:

    Country: The country where the customer resides.
    Age: The age of the customer.
    Gender: The gender of the customer (Male/Female).
    Customer Spending: The total amount spent by the customer in euros.

***Sample Data***

Country	 Age  Gender  Customer_Spending<br>
France	 32	  Female	 150.50<br>
Germany	 45	  Male	     200.75<br>
Spain	 28	  Female	 75.25<br>
Italy	 39	  Male	     180.00<br>
UK	     52	  Female	 250.30<br>

***Project Steps***

    Data Preparation
        Loading Data: Import the CSV file into a DataFrame.
        Initial Exploration: Display a technical summary of the data, including data types and the number of non-null values.

    Data Cleaning
        Handling Missing Values: Identify and address NaN (Not a Number) values in the columns. Remove rows with critical missing values.
        Data Type Conversion: Convert ages to integers and spending amounts to floats if necessary.
        Removing Inaccurate Values: Clean rows with spending less than €10 and remove duplicates.

    Data Analysis
        Calculating Statistics: Compute the median and mean for the "Age" and "Customer Spending" columns.
        Spending Visualization: Create a bar chart to visualize customer spending by country, adjusting y-axis values for better readability.

    Exporting Cleaned Data
        Creating a Cleaned CSV File: Export the cleaned data into a new CSV file containing only the columns "Country", "Age", "Gender", and "Customer Spending".

    Documentation and Reporting
        Documentation: Write a report explaining the cleaning steps, analysis results, and visualizations produced.
        Preparing the Jupyter Notebook: Clean outputs and save the notebook with all project steps for submission.

**Tools and Technologies**

    Python: Programming language used for data manipulation and analysis.
    Pandas: Python library for data management.
    Matplotlib: Python library for creating graphical visualizations.
    Jupyter Notebook: Interactive development environment for documenting and executing code.

**Expected Results**

The project should provide a deep understanding of customer spending by country, with clear visualizations highlighting differences and similarities in spending behavior. The insights gained will inform recommendations for marketing strategies and market analysis.
