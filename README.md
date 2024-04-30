# Home Sales Analysis with PySpark

## Project Overview
This project leverages PySpark to analyze home sales data and predict market trends. Using a dataset provided by the nonprofit foundation Alphabet Soup, we aim to create a series of analytical queries to determine the average prices of homes based on various criteria. This analysis assists in identifying properties with the best potential for investment or development.

## Files
- `Home_Sales.ipynb`: Main project notebook.
- `home_sales_revised.csv`: Dataset containing details on over 34,000 organizations that received funding.

## Instructions
- The original notebook, `Home_Sales_starter_code.ipynb`, was renamed to `Home_Sales.ipynb`.
- Essential PySpark SQL functions were imported to facilitate data handling.
- Data from `home_sales_revised.csv` was read into a Spark DataFrame and stored in a temporary table named `home_sales`.

## Analytical Queries
1. **Average Price for Four-Bedroom Homes**: Determined the average selling price for four-bedroom homes for each year, rounded to two decimal places.
2. **Average Price Based on Year Built (Three Bedrooms, Three Bathrooms)**: Calculated the average price of homes built each year, featuring three bedrooms and three bathrooms, rounded to two decimal places.
3. **Detailed Criteria Pricing**: Computed the average price for homes with three bedrooms, three bathrooms, two floors, and a minimum size of 2,000 square feet for each year they were built.
4. **View-Based Pricing Analysis**: Analyzed the average price of homes per "view" rating with prices starting at $350,000, including performance timing for queries.

## Performance Optimization
- The dataset was cached to improve query performance.
- Comparison of query runtimes with cached and uncached data.
- Data was partitioned by the "date_built" field to optimize the storage and retrieval.

## Technology Stack
- **PySpark**: Used for data processing and running SQL queries.
- **Jupyter Notebook**: For interactive code development and testing.

## Usage
- Clone the repository and ensure you have PySpark installed.
- Execute the `Home_Sales.ipynb` notebook to reproduce the analysis and view query outputs.

## Support and Resources
- Support provided during class hours, office hours, and through access to learning assistants and tutors.

## Project Evaluation
The project meets various requirements set forth in the grading rubric, including data preprocessing, query development, performance analysis, and data management practices.


