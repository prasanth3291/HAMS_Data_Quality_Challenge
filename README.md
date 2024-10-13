# HAMS Data Quality Challenge

This repository contains my analysis for the HAMS Data Quality Challenge. The objective of this challenge is to analyze the provided data and identify potential data quality issues.

## Challenge Overview

The challenge involves analyzing a SQLite database containing information about e-commerce purchases made by Company X. The data includes various tables related to conversions, session sources, and advertising costs, among others.

## Steps to Complete the Assignment

1. **Download the Database:**
   - Download the challenge database from the following link: [challenge.db](https://github.com/haensel-ams/recruitment_challenge/tree/master/Data_Quality_202108).

2. **Set Up Your Environment:**
   - Ensure you have Python installed on your machine.
   - Install the necessary libraries for data analysis. You can use the following command:
     ```bash
     pip install pandas sqlite3 matplotlib seaborn
     ```

3. **Load the Database:**
   - Use Python and SQLite to load the `challenge.db` file and access the data within the tables.

4. **Data Analysis:**
   - Conduct an analysis based on the following questions:
     - Are the costs in the `api_adwords_costs` table fully covered in the `session_sources` table?
     - Are the conversions in the `conversions` table stable over time? Identify any patterns.
     - Verify the accuracy of conversions in the `conversions` table against the `conversions_backend` table.
     - Assess the consistency of attribution results and check for any irregularities in the `ihc` values.
     - (Bonus) Evaluate the stability of session counts per channel over time.
     - (Bonus) Identify any additional data quality issues.

5. **Document Findings:**
   - Document your findings and insights in a Jupyter Notebook (`assignment.ipynb`), including visualizations and explanations of your analysis process.

6. **Submit Your Work:**
   - Once you have completed the analysis and documented your findings, ensure that all files are committed to your local Git repository and push the changes to your remote repository.

## Conclusion

This repository reflects my approach to the HAMS Data Quality Challenge, showcasing my skills in data analysis and interpretation. I hope you find the insights valuable!

