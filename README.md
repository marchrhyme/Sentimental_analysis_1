# Sentimental_analysis_1 (not completed)
Our objective was to conduct Sentiment Analysis on a given dataset. To achieve this, we followed the following steps:

1. Imported the necessary CSV file.
2. Created a new dataset containing only the relevant columns.
3. Filtered the dataset to create two subsets: one containing null values in the 'reviews.rating' column, and the other without any null values in the same column.
4. Replaced all the null values in the non-null dataset's 'reviews.rating' column.
5. Introduced a new column called 'Rate', where ratings equal to or above 4 were labeled as 'pos', and ratings below 4 were labeled as 'neg'.
6. Cleaned the 'reviews.text' column in both datasets (null and non-null) using regular expressions, retaining only lowercase characters while filtering out numbers and symbols.
7. Created two new datasets from the original non-null dataset. The first dataset, named 'Train', comprised 80% of the non-null data, while the second dataset, named 'Test', contained the remaining 20% of the data.
8. 
