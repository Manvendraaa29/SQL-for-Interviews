# The Complete SQL Curriculum for Data Science and AI Interviews

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT) ![GitHub issues](https://img.shields.io/github/issues/your-username/your-repo-name)
![GitHub forks](https://img.shields.io/github/forks/your-username/your-repo-name)
![GitHub stars](https://img.shields.io/github/stars/your-username/your-repo-name)

[cite_start]This repository hosts a comprehensive, job-focused curriculum designed to build expert-level SQL proficiency for Data Scientist, Senior Data Scientist, and AI/ML Engineer roles[cite: 3].

---

## 🎯 Why This Curriculum?

[cite_start]This guide is not an exhaustive list of every SQL command[cite: 5]. [cite_start]It is a **strategically prioritized learning path** that reflects the realities of the modern data science interview[cite: 6].

[cite_start]The curriculum de-emphasizes database administration (like server configuration or permissions) and focuses intensely on what interviewers for analytical roles *actually* test[cite: 7]:
* Advanced Data Querying
* Complex Data Manipulation
* Analytical Pattern Recognition
* Performance Optimization

[cite_start]The objective is to move beyond simple memorization and develop the ability to **"think in SQL"** as an analyst[cite: 8].

## 🚀 Repository Structure

This project is a one-stop-shop for mastering SQL and is organized into three main areas:

1.  **Core Curriculum:** A 12-module, step-by-step roadmap covering all essential SQL topics, from database fundamentals to advanced performance tuning and applied analytics.
2.  **Curated Resources:** Each module in the curriculum is (or will be) supplemented with a hand-picked list of high-quality resources (YouTube videos, Medium articles, Substack newsletters, etc.) to provide alternative explanations and deeper dives.
3.  **Practice & Interview Hub:** A dedicated section to apply your knowledge, featuring:
    * **General Practice:** A large bank of questions to solidify your skills by topic.
    * **Company-Wise Questions:** A collection of real-world questions reportedly asked at top product-based companies.

## 🗺️ How to Use This Guide

1.  **Follow the Path:** Start with Module 1 and move sequentially. The concepts are designed to build upon each other.
2.  **Use the Resources:** If a topic is unclear, dive into the supplementary resources linked in that module's folder.
3.  **Do the Practice:** After completing a module, go to the Practice Hub and work on problems related to that topic.
4.  **Contribute:** Find a great resource, a broken link, or a new practice question? Please open an issue or pull request!

---

## 📚 Core Curriculum Roadmap

### Module 1: The SQL Landscape and Database Fundamentals
* [cite_start]**Objective:** Build a foundational "map" of the SQL language and database structures[cite: 10].
* [cite_start]**Topics:** The five categories of SQL (DQL, DDL, DML, TCL, DCL) [cite: 12, 13][cite_start], Core Data Types [cite: 45][cite_start], and Data Integrity Constraints (Primary Key, Foreign Key, NOT NULL, etc.)[cite: 53, 54].
* [cite_start]**Interview Focus:** Differentiating `DELETE`, `TRUNCATE`, and `DROP`[cite: 26].

### Module 2: The Core: Data Query Language (DQL)
* [cite_start]**Objective:** Master the `SELECT` statement, the single most-used command for all data roles[cite: 64].
* [cite_start]**Topics:** The SQL Order of Operations (a critical mental model) [cite: 65, 67][cite_start], `SELECT` [cite: 71][cite_start], `WHERE` [cite: 75][cite_start], specialized operators (`IN`, `BETWEEN`, `LIKE`, `IS NULL`) [cite: 79][cite_start], and `ORDER BY`[cite: 90].

### Module 3: Aggregation and Grouping
* [cite_start]**Objective:** Move from retrieving individual rows to summarizing and analyzing data[cite: 104].
* [cite_start]**Topics:** Aggregate Functions (`COUNT`, `SUM`, `AVG`, `MIN`, `MAX`) [cite: 105, 106][cite_start], the `GROUP BY` clause [cite: 114][cite_start], and the `HAVING` clause[cite: 126].
* [cite_start]**Interview Focus:** The critical distinction between `WHERE` and `HAVING`[cite: 119, 120].

### Module 4: Essential SQL Functions for Data Analysis
* [cite_start]**Objective:** Master scalar functions for data cleaning, transformation, and feature engineering[cite: 133].
* [cite_start]**Topics:** String Functions (`CONCAT`, `SUBSTRING`, `TRIM`, `REPLACE`) [cite: 135][cite_start], Date/Time Functions (`EXTRACT`, `DATE_TRUNC`, `DATEDIFF`) [cite: 144][cite_start], and Conditional Functions (`CAST`, `COALESCE`, `NULLIF`)[cite: 151].
* [cite_start]**Interview Focus:** Using `NULLIF` to prevent division-by-zero errors[cite: 157, 159].

### Module 5: Combining Disparate Data Sets
* [cite_start]**Objective:** Combine data from multiple tables—the most essential practical skill[cite: 161].
* [cite_start]**Topics:** Relational `JOIN`s (Inner, Left, Right, Full Outer) [cite: 162, 163][cite_start], the `SELF JOIN` technique [cite: 173, 174][cite_start], and Set Operators (`UNION`, `UNION ALL`, `INTERSECT`, `EXCEPT`)[cite: 178].
* [cite_start]**Interview Focus:** `UNION` vs. `UNION ALL` and performance implications[cite: 183, 184].

### Module 6: Advanced Query Constructs for Readability
* [cite_start]**Objective:** Master the constructs that separate junior from senior candidates[cite: 188].
* [cite_start]**Topics:** Subqueries (Scalar, Multi-row, Correlated) [cite: 190, 191][cite_start], `VIEW`s [cite: 221][cite_start], and **Common Table Expressions (CTEs)**[cite: 200].
* [cite_start]**Interview Focus:** Using CTEs with the `WITH` keyword to refactor complex, nested subqueries into clean, readable, and maintainable steps[cite: 201, 204, 205].

### Module 7: The Analyst's Toolkit: Window Functions
* [cite_start]**Objective:** Master what is arguably the **single most-tested advanced SQL topic** in data science interviews[cite: 227].
* [cite_start]**Topics:** The `OVER()` [cite: 229] [cite_start]and `PARTITION BY` [cite: 231] clauses.
* **Functions:**
    * [cite_start]**Ranking:** `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`[cite: 235, 237, 238, 240].
    * [cite_start]**Analytic:** `LEAD()` and `LAG()` for time-series analysis[cite: 245, 246, 247].
* [cite_start]**Interview Focus:** "Find the Nth highest salary" [cite: 236][cite_start], and filtering window results using the `QUALIFY` clause or a CTE[cite: 250, 254].

### Module 8: Advanced Traversal and Data Generation
* [cite_start]**Objective:** Handle complex hierarchical data (like org charts) or graph data[cite: 258].
* [cite_start]**Topics:** **Recursive CTEs** [cite: 259][cite_start], understanding the Anchor Member [cite: 261][cite_start], Recursive Member [cite: 263][cite_start], and the implicit termination condition[cite: 267].

### Module 9: Performance Tuning and Database Internals
* [cite_start]**Objective:** Answer the senior-level question: "Your query is slow. How do you speed it up?"[cite: 272].
* [cite_start]**Topics:** Database **Indexing** (B-Tree, Hash, Bitmap) [cite: 273, 275, 277, 279][cite_start], and how to read an `EXPLAIN` / `EXPLAIN ANALYZE` plan[cite: 283, 284].
* [cite_start]**Interview Focus:** Identifying bottlenecks like a `Seq Scan` and replacing it with an `Index Scan`[cite: 288, 289].

### Module 10: Transaction Control and Concurrency
* [cite_start]**Objective:** Understand the theoretical guarantees and performance trade-offs that make databases reliable[cite: 294].
* [cite_start]**Topics:** The four **ACID Properties** (Atomicity, Consistency, Isolation, Durability) [cite: 296, 297][cite_start], concurrency problems (Dirty Reads, Phantom Reads) [cite: 305, 308, 312][cite_start], and Transaction Isolation Levels[cite: 315].

### Module 11: Applied SQL for Data Science and AI
* [cite_start]**Objective:** A capstone module applying all previous concepts to real-world DS/AI interview problems[cite: 319].
* **Analytical Patterns:**
    1.  [cite_start]**Funnel Analysis:** Tracking user conversion through a multi-step process[cite: 320, 321].
    2.  [cite_start]**Cohort Analysis:** Tracking user retention over time grouped by join date[cite: 327, 328].
    3.  [cite_start]**Time-Series Analysis:** Calculating moving averages and period-over-period growth using `LAG()` and window aggregates[cite: 336, 337, 340].
    4.  [cite_start]**Feature Engineering for ML:** Using SQL to generate features (e.g., `EXTRACT(dayofweek)`, rolling aggregates, binarization with `CASE`)[cite: 341, 342, 343].

### Module 12: Acing the SQL Interview
* [cite_start]**Objective:** A meta-framework for approaching the SQL interview itself[cite: 349].
* [cite_start]**Topics:** Canonical Q&A for rapid recall (e.g., "Nth highest salary," [cite: 352] [cite_start]"duplicates," [cite: 354] [cite_start]"A but not B" [cite: 356]).
* **Core Content:** A 5-Step Framework for SQL Case Studies:
    1.  [cite_start]Clarify the Objective [cite: 373]
    2.  [cite_start]Plan Your Approach [cite: 375]
    3.  [cite_start]Define Metrics and Data [cite: 376]
    4.  [cite_start]Analyze (Write the Code) [cite: 378]
    5.  [cite_start]Communicate Impact [cite: 380]

## 🤝 Contributing

Contributions are welcome and encouraged! If you find a broken link, have a great resource to add, or want to contribute a new practice problem, please feel free to:
1.  **Open an Issue** to discuss the change.
2.  **Submit a Pull Request** with your improvements.

## ⚖️ License

This project is licensed under the **[Your License Here]** License - see the `LICENSE` file for details.
