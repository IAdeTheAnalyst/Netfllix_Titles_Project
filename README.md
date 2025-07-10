# 📺 Netflix Titles Project — PostgreSQL Data Analysis

This project uses PostgreSQL to explore Netflix's global content library. It uncovers trends in genre popularity, country-wise content distribution, and recurring themes in show descriptions. The analysis also highlights changes in release patterns over time and audience content preferences based on region and type.

---

## 📊 Project Overview

**Goal**: Analyze Netflix's title catalog to identify genre trends, global reach, content characteristics, and user-facing patterns.  
**Dataset**: Netflix Titles Dataset from Kaggle  
**Tools Used**: PostgreSQL, SQL (CTEs, window functions, UNNEST, string_to_array, FILTER, ILIKE, COUNT, subqueries)

---

## 🔍 Key Questions Answered

- Which country has produced the most Netflix content?
- How many total movies vs. TV shows are on Netflix?
- What are the top 5 most common genres across all content?
- What is the average movie duration and average number of TV show seasons?
- Which year had the most titles added? How has content volume changed over time?
- Who are the most featured directors and actors?
- What % of Netflix content is international (non-U.S.)?
- Which countries produce more TV shows than movies?
- What are the most frequent combinations of country and content type?
- What are the most used words in Netflix title names?
- Which titles are the longest and shortest?
- How many titles include keywords like “love,” “war,” or “crime”?
- Are there duplicate entries or suspicious data records?

---

## 🛠 Techniques & Concepts

- **Multi-value field parsing** using `string_to_array()` + `UNNEST`
- **Conditional aggregation** with `FILTER`, `COUNT`, and `ILIKE`
- **Regex-based extraction** of numerical values from string durations
- **Window functions** for ranking titles and latest additions
- **Subqueries & CTEs** for intermediate calculations and reusability
- **Data validation** via duplicate checks and data consistency reviews

---

## 📈 Insights & Outcomes

- The United States has the highest content volume, followed by India and the UK.
- "Drama" and "International Movies" are the most frequent genres.
- Average movie length is around 100 minutes; TV shows average 2–3 seasons.
- Content additions peaked around 2019–2020.
- Top actors and directors appear in 50+ titles each.
- Over **40%** of content is international, showcasing Netflix’s global focus.
- Sundays and July are peak release times historically.
- Titles with themes like "love" and "war" are highly prevalent.
- Duplicate titles and unusual entries were found, prompting potential data cleaning.

---

## 🔗 Related Projects

- [🛒 Instacart Orders Project](https://github.com/yourusername/instacart-project)
- [🍽️ Nova Restaurant Project](https://github.com/yourusername/nova-project)

---

## 👤 About Me

**Your Name**  
[Portfolio Website](https://yourwebsite.com) • [LinkedIn](https://linkedin.com)
