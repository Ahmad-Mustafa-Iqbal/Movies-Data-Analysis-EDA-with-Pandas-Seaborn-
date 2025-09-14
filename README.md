Movies Data Analysis (EDA with Pandas & Seaborn)

This project explores and analyzes a movie dataset containing details such as release dates, titles, genres, popularity scores, votes, and ratings.  
The goal of this analysis is to clean the data, explore insights, and visualize trends** in the movie industry.  

Dataset
- Total rows: 9827
- Total columns: 9(reduced to 6 after cleaning)
- Columns included:
  - `Release_Date`
  - `Title`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average`
  - `Genre`

Steps Performed

1. Data Cleaning
   - Converted `Release_Date` into year format.
   - Dropped unnecessary columns (`Overview`, `Original_Language`, `Poster_Url`).
   - Checked for duplicates and null values (none found).
   - Converted `Genre` into categorical values.
   - Split and exploded `Genre` column so each row has a single genre.

2. Feature Engineering
   - Categorized `Vote_Average` into:
     - `not_popular`
     - `below_avg`
     - `average`
     - `popular`

3. Exploratory Data Analysis (EDA)
   - Distribution of genres
   - Distribution of votes
   - Most and least popular movies
   - Year-wise movie release trends

4. Visualization Tools
   - Matplotlib
   - Seaborn


Key Insights

- 🎭 Drama is the most frequent genre (~14% of dataset).  
- 🕸️ Spider-Man: No Way Home (2021) is the most popular movie.  
- 🎶 The United States vs. Billie Holiday (2021) and *Threads* (1984) have the lowest popularity.  
- 📅 Year **2020** had the highest number of filmed movies.  



Visualizations
---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movies-data-analysis.git

Install required libraries:
Python 
Pandas
NumPy
Matplotlib
Seaborn

Use jupyter notebook For Better insights

📚 Conclusion
This project highlights useful insights into the movie industry by analyzing genres, popularity, votes, and yearly trends. It demonstrates data cleaning, feature engineering, and visualization skills using Python.
