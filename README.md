
# Pandas - Operations and Filtering

Jupyter Notebook used to perform Exploratory Data Analysis (EDA).

- Perform basic Exploratory Data Analysis (EDA) on the Employee Information Dataset.
- Kyphosis is an abnormally excessive convex curvature of the spine.
- Dataset contains 81 rows and 4 columns representing data on children who have had corrective spinal surgery.
    - INPUTS: 1. Age: in months, 2. Number: the number of vertebrae involved, 3. Start: the number of the first (topmost) vertebra operated on.
    - OUTPUTS: Kyphosis which represents a factor with levels absent present indicating if a kyphosis (a type of deformation) was present after the operation.
- Using the “kyphosis.csv" included in the course package, write a python script to perform the following tasks:
    - Import the “kyphosis.csv" file using Pandas
    - Perform basic Exploratory Data Analysis (EDA) on the data
    - List the average, minimum and maximum age (in years) considered in this study using 2 methods
    - Plot the correlation matrix
    - Convert the age column datatype from int64 to float64
    - Define a function that converts age from months to years
    - Apply the function to the “Age” column and add the results into a new column entitled “Age in Years”
    - What are the features of the oldest and youngest child in this study?