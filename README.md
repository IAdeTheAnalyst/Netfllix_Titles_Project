# 📺 Netflix Titles Project — PostgreSQL Data Analysis

This project explores the Netflix content catalog using PostgreSQL to uncover trends in genre popularity, international distribution, and common themes in show descriptions. It showcases data cleaning, transformation, and query optimization to generate insights valuable for content strategy and global market analysis.

---

## 📊 Project Overview

- **Goal:** Analyze Netflix's global content library to identify regional genre trends, keyword patterns, and content type distribution.
- **Dataset:** Sourced from [Kaggle’s Netflix Titles Dataset](https://www.kaggle.com/shivamb/netflix-shows)  
- **Tools Used:** PostgreSQL, SQL functions (`unnest`, `string_to_array`, `filter`, `COUNT`, `ILIKE`, etc.)

---

## 🔍 Key Questions Answered

- Which genres are most popular in India vs. the United States?
- What percentage of titles are international (non-U.S.)?
- How often do themes like "love", "war", or "crime" appear in descriptions?
- What are the most frequent combinations of country and content type?

---

## 🛠 Techniques & Concepts

- Data transformation with `string_to_array()` and `unnest()`
- Conditional aggregation with `FILTER` and `COUNT`
- Text search with `ILIKE`
- Grouping and sorting to derive insights
- Data cleaning for multi-country and multi-genre fields

--- 

