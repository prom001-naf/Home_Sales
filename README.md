# Home Sales

This project utilizes **PySpark** to analyze home sales data stored in an **AWS S3 bucket**.

## Instructions

Follow these steps to set up and execute the analysis:

### Rename the Notebook
Rename the provided Jupyter Notebook file:

`Home_Sales_starter_code.ipynb` → `Home_Sales.ipynb`

### Import Required Libraries
Import the necessary PySpark SQL functions for the assignment.

### Read the Dataset
Read the `home_sales_revised.csv` file from the provided AWS S3 bucket into a PySpark DataFrame.

### Create a Temporary Table
Create a temporary table called `home_sales`.

### What is the average price for a four-bedroom house sold for each year?
- Round off the answer to two decimal places.

### What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
- Round off the answer to two decimal places.

### What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
- Round off the answer to two decimal places.

### What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?
- Determine the run time for this query and round off the answer to two decimal places.

### Cache your temporary table `home_sales`.

### Check if your temporary table is cached.

### Using the cached data, run the last query:
- Calculate the **average price of a home per "view" rating** where the **average home price is greater than or equal to $350,000**.
- Determine the **runtime** and compare it to the uncached runtime.

### Partition the formatted Parquet home sales data:
- Partition the data by the **"date_built"** field.

### Create a temporary table for the Parquet data.

### Run the last query again:
- Calculate the **average price of a home per "view" rating** where the **average home price is greater than or equal to $350,000**.
- Determine the **runtime** and compare it to the uncached runtime.

### Uncache the `home_sales` temporary table.

### Verify that the `home_sales` temporary table is uncached using PySpark.

### Upload Notebook to GitHub:
- **Download** the `Home_Sales.ipynb` file.
- **Upload** it to the `"Home_Sales"` GitHub repository.
