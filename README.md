Netflix Data Analysis
This project provides an in-depth analysis of a Netflix dataset. The goal is to clean the data, perform exploratory data analysis, and gain insights into various attributes of Netflix content.

Project Overview
This analysis focuses on the following steps:

#DataExploration: The dataset consists of 9827 rows and 9 columns. It contains no missing or duplicate values, making it ready for analysis.
#DataCleaning: Key steps include:
Casting the #ReleaseDate column into a proper date format and extracting the year.
Removing columns such as #Overview, #OriginalLanguage, and #PosterUrl that are not useful for analysis.
Handling the #Genre column, which has comma-separated values and extra whitespaces.
Identifying and addressing outliers, particularly in the #Popularity column.
Categorizing the #VoteAverage column for better analysis.
Features of the Dataset
#Genres: Multiple genres are separated by commas and whitespaces.
#Popularity and #Voting: There are notable outliers in the popularity column, and the vote averages are categorized for detailed analysis.
