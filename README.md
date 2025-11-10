# The Complete SQL Curriculum for Data Science Interviews

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/Manvendraaa29/SQL-for-Interviews)](https://github.com/Manvendraaa29/SQL-for-Interviews/issues)
[![GitHub forks](https://img.shields.io/github/forks/Manvendraaa29/SQL-for-Interviews)](https://github.com/Manvendraaa29/SQL-for-Interviews/network/members)
[![GitHub stars](https://img.shields.io/github/stars/Manvendraaa29/SQL-for-Interviews)](https://github.com/Manvendraaa29/SQL-for-Interviews/stargazers)

This repository hosts a comprehensive curriculum designed to build expert-level SQL proficiency for Data Scientist, Senior Data Scientist, and AI/ML Engineer roles.

This is **not** an exhaustive list of every SQL command. It is a strategically prioritized learning path that reflects the realities of the data science interview. The curriculum de-emphasizes database administration tasks and focuses intensely on what interviewers test: **advanced data querying, complex data manipulation, analytical pattern recognition, and performance optimization**.

The objective is to move beyond simple command memorization and develop the ability to **"think in SQL"**.

---

## 🚀 How to Use This Repository (Get Started)

This repository is built for a step-by-step learning experience. Here is the recommended path:

1.  **Start with the Curriculum:** Open and read **`The Complete SQL Curriculum for Interviews.md`**. This is the core 12-module textbook for this entire repo. Start with Module 1.
2.  **Practice by Module:** After you finish a module in the curriculum file, navigate to the **`./General Practice Questions/`** folder. Find the matching module sub-folder (e.g., `Module-03-Aggregation/`) and work through the practice questions in the text files.
3.  **Prepare for Interviews:** Once you feel confident, go to the **`./Company Wise Questions/`** folder. Pick a company you're targeting and test your skills against real-world questions.
4.  **Repeat the Process:** Once you are done with a module's theory and questions proceed to the next module and repeat the process.

---

---

## 🚀 How to Practice Questions

To make your practice sessions hands-on and interactive, we will use a "Guided Teacher" method powered by any free Gen-AI service (like Gemini, ChatGPT, Claude, etc.).

### 1. The Prompt File
Inside each practice module folder (e.g., `./General-Practice-Questions/Module-03-Aggregation/`), you will find a pre-defined prompt file, likely named `AI-Teacher-Prompt.txt`.

* **Action:** Open this file and **copy the entire prompt** text.

### 2. The Guided Teacher
Once you have the prompt copied, your interactive session is ready to begin.

1.  **Paste the Prompt:** Go to your preferred Gen-AI service and paste the copied text as your very first message.
2.  **Start Practicing:** The AI will immediately take on the role of a "Guided Teacher." It will present you with the first question from that module, along with any necessary details (like table schemas).
3.  **Submit Your Solution:** Think through the problem and paste your SQL query as a response.
4.  **Get Instant Feedback:** The AI will check your solution:
    * **If Correct:** It will confirm your answer is right and then present the next question.
    * **If Incorrect:** It will notify you and give you the option to **retry the question** or **ask for the correct solution** and explanation.

---

## 🧭 Repository Structure

This repository is organized into three main components:

### 1. The Core Curriculum File
* **Location:** **`The Complete SQL Curriculum for Interviews.md`** (The main file in this repo)
* **Purpose:** This single file contains the complete, 12-module curriculum. It's your primary textbook, covering everything from fundamentals to advanced query tuning and applied data science patterns.

### 2. General Practice Questions
* **Location:** **`./General Practice Questions/`**
* **Purpose:** This folder contains practice problems organized by topic, allowing you to solidify your skills one module at a time.
* **Structure:**
    ```
    General-Practice-Questions/
    ├── Module-01-Fundamentals/
    │   ├── questions.md
    │   └── module-1-prompt.md
    ├── Module-02-DQL/
    │   ├── questions.md
    │   └── ...
    └── (...and so on for all 12 modules)
    ```

### 3. Company-Wise Questions
* **Location:** **`./Company-Wise-Questions/`**
* **Purpose:** This folder contains a specialized collection of SQL interview questions reportedly asked at various product-based companies. This is for targeted, late-stage interview prep.
* **Structure:**
    ```
    Company-Wise-Questions/
    ├── Google/
    │   ├── questions.md
    │   └── prompt-google.md
    ├── Microsoft/
    │   ├── questions.md
    │   └── ...
    └── (...and so on for other companies)
    ```

---

## 📚 Curriculum at a Glance (Module Overview)

The core curriculum file covers these 12 modules in detail:

* **Module 1:** The SQL Landscape and Database Fundamentals
* **Module 2:** The Core: Data Query Language (DQL)
* **Module 3:** Aggregation and Grouping
* **Module 4:** Essential SQL Functions for Data Analysis
* **Module 5:** Combining Disparate Data Sets (Joins & Unions)
* **Module 6:** Advanced Query Constructs (CTEs, Subqueries, Views)
* **Module 7:** The Analyst's Toolkit: Window Functions
* **Module 8:** Advanced Traversal and Data Generation (Recursive CTEs)
* **Module 9:** Performance Tuning and Database Internals (Indexing, `EXPLAIN`)
* **Module 10:** Transaction Control and Concurrency (ACID)
* **Module 11:** Applied SQL for Data Science and AI (Funnels, Cohorts, Time-Series)
* **Module 12:** Acing the SQL Interview (Frameworks & Canonical Questions)

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn and grow. We welcome contributions of all kinds:
* Adding new practice questions (both general and company-wise).
* Correcting typos or errors in the curriculum.
* Suggesting new resources to be added.
* Improving the clarity of existing explanations.

Please feel free to **open an issue** to discuss a change or **submit a pull request** with your improvements.

## ⚖️ License

This project is licensed under the **MIT License** - see the `LICENSE` file for details.
