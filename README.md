# Netflix-Data-Cleaning-Analysis-and-Visulization

# Introduction / Problem Statement:
Netflix is a popular streaming service that offers a vast catalog of movies,TV shows,and original contents.The data consist of contents added to Netflix from 2008 to 2021. The Oldest content isasoldas1925and the newest as 2021.
What type of content (Movies vs. TV Shows) dominates Netflix's catalog?
How has Netflix's content library evolved over time?
What are the most popular genres, and do they vary by country?
Which countries contribute the most content to Netflix?
What are the most common content ratings, and what do they reveal about Netflix’s target audience?
Who are the most frequent directors producing content for Netflix?
How does Netflix’s content distribution compare across different years?

# Tools and Technologies:
Programming Language: Python 
Libraries: pandas, numpy, seaborn, matplotlib, WordCloud
Visualization Tools: Tableau, Jupyter Notebook

# Data Cleaning:
We load and clean the data using python and check the columns data types.
And we check for null values in the data.
If null values are present we clean by adding the missing data or dropping the rows.
Changing the data types for better analysis of the data. For example this dataset has a column date_added with data type ‘object’ , so we have to change it to ‘datetime64[ns]’. 

# Exploratory Data Analysis
  # Distribution of Content by Type:
  ![1Capture](https://github.com/user-attachments/assets/f787b336-b009-4289-8c1d-f6c3529a22ed)

 # Most Common Genres on Netflix
 ![2Capture](https://github.com/user-attachments/assets/fdc1f720-292b-42d1-b348-111947bc9dcb)
 
 # Content Added Over Time
 ![3Capture](https://github.com/user-attachments/assets/05810235-bc7c-4517-b533-e18501e4e53e)

 # Top 10 Directors with the Most Titles
 ![4Capture](https://github.com/user-attachments/assets/b0cc4d7a-5839-4a83-a5c2-dc5d6b390aa9)

 # Word Cloud of Movie Titles
 ![5Capture](https://github.com/user-attachments/assets/cb7f0797-c8d1-434e-af71-f365c101e03b)

