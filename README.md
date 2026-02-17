# Netflix Titles Project — PostgreSQL Data Analysis

In this project, I analyzed Netflix’s global content catalog using PostgreSQL to uncover trends in genre distribution, international representation, release patterns, and content characteristics. My objective was to explore how Netflix’s library is structured across countries, content types, ratings, and time — and to identify patterns that reflect platform strategy and audience targeting.

Through advanced SQL querying and string-based analysis, I examined how content composition has evolved over time and how global contributions shape Netflix’s catalog.

--- 

## Project Objectives
In this analysis, I aimed to answer the following business questions:
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

--- 

## Tools & Technical Approach
In this project, I used:
- PostgreSQL
- Common Table Expressions (CTEs) for multi-step logic
- Subqueries for layered filtering and segmentation
- Aggregate functions (COUNT, AVG, SUM) for trend quantification
- String functions and regular expressions for keyword analysis
- UNNEST() and STRING_TO_ARRAY() to analyze multi-valued genre and country fields
- CASE expressions and FILTER clauses for conditional aggregations
- Date extraction functions to analyze monthly and yearly trends

Because several columns contained comma-separated values (genres, countries, cast), I normalized them dynamically using UNNEST() to enable accurate aggregation and comparison.

---

## Key Insights / Results
Through this analysis, I identified:
- The United States contributes the largest share of content, followed by India, the UK, and Canada.
- Movies dominate the catalog, though TV Shows represent a significant share with longer average durations (measured in seasons).
- International Dramas, Comedies, and Documentaries are among the most common genres.
- Content additions increased steadily over several years before showing a recent slowdown.
- Over 30% of the catalog consists of international content, reflecting Netflix’s global expansion strategy.
- TV-MA and PG-13 are the most common ratings, indicating a focus on mature audiences.
- July and October show spikes in title additions, suggesting seasonal release strategies.
- Thematic keywords such as “Love,” “Life,” and “The” are frequently used in titles, reflecting emotional or universal themes.
- India shows higher concentration in Action & Adventure genres, while the U.S. skews toward Drama and Comedy.

This analysis demonstrates how content metadata can be leveraged to understand platform strategy, audience segmentation, international expansion, and seasonal programming patterns.

---

## What I Learned
Through this project, I strengthened my ability to:
- Work with semi-structured string data in SQL
- Use PostgreSQL’s advanced functions like UNNEST() and regex
- Analyze multi-dimensional categorical data
- Perform text-based frequency analysis
- Identify growth and seasonality trends in time-series data

I also gained practical insight into how streaming platforms balance international content, genre mix, and rating 
distribution to target diverse audiences.- Title, Type (Movie or TV Show)

---

## Challenges I Encountered
One challenge I faced was handling multi-valued columns (such as genres and countries) stored as comma-separated strings. I addressed this by using STRING_TO_ARRAY() and UNNEST() to normalize values for accurate aggregation.

Another challenge involved parsing duration values (e.g., “90 min” vs. “3 Seasons”), which required conditional logic to separate movie duration from TV show season counts.

Additionally, performing keyword analysis required careful use of case-insensitive pattern matching and regex to avoid false positives.

---

## Dataset Overview
The dataset contains metadata for thousands of Netflix titles, including:
- Title and Type (Movie or TV Show)
- Director and Cast
- Country
- Date Added and Release Year
- Duration and Rating
- Genres (listed_in)
- Description
