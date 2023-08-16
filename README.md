# Recommendation-system-User-based-
This is a recommendation system that gives recommendation based on user similarity.
## Repository Contents

- **fashion.csv**: The input CSV file containing fashion product data.
- **sample_1.csv**: The output CSV file with replicated and shuffled data to achieve a target number of rows.
- **Dataset.csv**: The output CSV file with added customer IDs to the data.
- **Data.csv**: The final dataset used for analysis and recommendations.
- **analysis_script.py**: The Python script for data preprocessing, exploratory data analysis, and recommendation system implementation.
- **README.md**: This README file, providing a concise overview of the analysis script and its functionality.

## Analysis Steps

1. **Data Replication and Shuffling**: The script starts by loading the 'fashion.csv' file, removing duplicate product titles, and replicating rows to achieve a target number of rows (5000 in this case). The resulting data is saved as 'sample_1.csv'.

2. **Adding Customer IDs**: The script generates a list of unique customer IDs and assigns them randomly to the dataset. The updated dataset is saved as 'Dataset.csv'.

3. **Exploratory Data Analysis (EDA)**: The script explores the dataset through various analyses, including:
   - Purchase history for specific users.
   - Visualization of product quantities using bar plots.
   - Visualizing highly purchased categories and genders.

4. **User-Item Recommendation System**: The script implements a basic user-item collaborative filtering recommendation system using Singular Value Decomposition (SVD). It predicts user-item ratings and provides recommendations based on similarity scores. Users can input a Customer ID to get personalized recommendations.

## How to Use

1. Clone the repository and navigate to the directory.
2. Place your fashion product data in a CSV file named 'fashion.csv' with appropriate columns.
3. Run the 'analysis_script.py' script using a Python interpreter (e.g., `python analysis_script.py`).
4. Follow the prompts to interact with the analysis and get recommendations.

## Conclusion

The 'analysis_script.py' script offers insights into customer behavior and preferences in the fashion retail domain. It includes data preprocessing, exploratory analysis, and a basic user-item recommendation system. By following the instructions in this README, users can run the script and gain valuable insights from the provided fashion retail dataset.
