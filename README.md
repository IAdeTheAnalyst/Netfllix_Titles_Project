# 📺 Netflix Titles Project — PostgreSQL Data Analysis

This project analyzes Netflix’s global content catalog to uncover trends in genre popularity, international distribution, seasonal release patterns, and viewer-targeted content. The analysis focuses on identifying what types of content dominate the platform and how different countries contribute to Netflix’s library.

## 🧠 Key Business Questions
1. Which countries have contributed the most content to Netflix?
2. What’s the total number of Movies vs. TV Shows?
3. What are the most common genres on Netflix?
4. What is the average duration of a movie or TV show?
5. How has content addition changed over the years?
6. Who are the top directors and most frequent actors?
7. How much of Netflix’s library is international content?
8. What are the most popular country–content type combinations?
9. Which countries produce more TV shows compared to movies?
10. How many titles are released each month?
11. What is the distribution of content ratings?
12. Which genres are more popular in India vs. the U.S.?
13. How many titles mention key words like “love,” “war,” or “crime”?
14. What are the longest and shortest titles?
15. Are there any duplicate or suspicious entries?
16. What are the most common words used in Netflix titles?
17. What are the 5 most recently added titles?

## 📊 Tools Used
- **SQL (PostgreSQL)**
- **String Functions & Regex**
- **CTEs and Subqueries**
- **Aggregate Functions**
- **UNNEST & STRING_TO_ARRAY**
- **CASE & FILTER Clauses**

## 📌 Key Insights
- **Country Trends:** The United States leads in content count, but countries like India, the UK, and Canada have strong representation.
- **Content Mix:** Movies dominate the platform, but TV shows make up a significant share with longer durations (measured in seasons).
- **Popular Genres:** International Dramas, Comedies, and Documentaries are among the top genres globally.
- **Growth Over Time:** The number of titles added has steadily increased until a slight decline in recent years.
- **Top Contributors:** Certain directors and actors appear frequently, offering opportunities for targeted promotion or content acquisition.
- **Global Reach:** Over 30% of Netflix’s content is international, indicating strong global expansion.
- **Regional Preferences:** India tends to feature more content in genres like Action & Adventure, while the U.S. leans toward Dramas and Comedies.
- **Content Ratings:** TV-MA and PG-13 are the most prevalent ratings, highlighting the platform’s focus on mature audiences.
- **Seasonality:** July and October show spikes in new content releases, aligning with strategic seasonal drops.
- **Title Analysis:** Common title words include "Love", "Life", and "The", revealing emotional or universal themes.

## 📂 Dataset Overview
This dataset contains metadata for thousands of Netflix titles and includes:
- Title, Type (Movie or TV Show)
- Director, Cast, Country
- Date Added, Release Year
- Duration, Rating
- Genres (listed_in)
- Description

> **Source:** [Netflix Movies and TV Shows Dataset | Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
