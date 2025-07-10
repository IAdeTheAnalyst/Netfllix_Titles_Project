# 📺 Netflix Titles Project — PostgreSQL Data Analysis

This project explores Netflix's global content library using PostgreSQL to uncover trends in genre popularity, international reach, and keyword patterns in show descriptions. It demonstrates how SQL can be used for data cleaning, transformation, and insight generation to support content strategy and regional targeting.

---

## 📊 Project Overview

**Goal**: Analyze Netflix's catalog to discover genre trends, popular keywords, and international distribution patterns.  
**Dataset**: Netflix Titles Dataset from Kaggle  
**Tools Used**: PostgreSQL, SQL (CTEs, string_to_array, UNNEST, FILTER, ILIKE, COUNT, etc.)

---

## 🔍 Key Questions Answered

- Which genres are most popular in India vs. the United States?
- What percentage of titles are international (non-U.S.)?
- How often do keywords like "love", "war", or "crime" appear in descriptions?
- What country and content-type combinations are most common?
- What are the longest and shortest titles in the dataset?

---

## 🛠 Techniques & Concepts

- **String splitting** using `string_to_array()` and `UNNEST` for multi-value fields
- **Conditional aggregation** with `FILTER` and `COUNT`
- **Text pattern matching** using `ILIKE` for keyword discovery
- **Common Table Expressions (CTEs)** for layered query logic
- **Sorting & limiting** for summary insights (e.g. longest/shortest titles)

---

## 📈 Insights & Outcomes

- The U.S. dominates the content library, but India and the UK follow closely with diverse offerings
- Dramas and comedies were the most common genres globally
- “Love” appeared in over 1,000 title descriptions, showing a recurring theme in global storytelling
- International titles account for nearly 40% of the content — highlighting Netflix’s global footprint

---

## 💼 Business Applications

- Tailor content strategy to specific countries based on genre trends
- Improve keyword targeting for content recommendations
- Identify gaps or opportunities for original content in underserved regions
- Guide localization and dubbing decisions with regional content patterns

---

## 🔗 Related Projects

- [🛒 Instacart Orders Project](https://github.com/yourusername/instacart-project)
- [🍽️ Nova Restaurant Project](https://github.com/yourusername/nova-project)

---

## 👤 About Me

**Your Name**  
[Portfolio Website](https://yourwebsite.com) • [LinkedIn](https://linkedin.com/in/yourusername) • [Email](mailto:youremail@example.com)
