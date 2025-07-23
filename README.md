# 📊 LeetCode SQL Solutions

Welcome to my **SQL practice repository**, where I solve problems from [LeetCode's Database section](https://leetcode.com/problemset/database/).  
This collection demonstrates my understanding of SQL concepts such as `JOINs`, `Aggregation`, `Window Functions`, and more — essential for **Data Science**, **Data Analytics**, and **Backend Development** roles.

---

## 🗂️ Folder Structure

LeetCode-SQL-Solutions/
│
├── Easy/
│ ├── 175_Combine_Two_Tables.sql
│ ├── 176_Second_Highest_Salary.sql
│ └── ...
│
├── Medium/
│ ├── 177_Nth_Highest_Salary.sql
│ └── ...
│
├── Hard/
│ └── ...
│
└── README.md

yaml
Copy
Edit

---

## 🧠 Concepts Practiced

| 💡 Concept              | ✅ Covered |
|------------------------|------------|
| SQL Joins              | ✅         |
| Subqueries             | ✅         |
| Grouping & Aggregation | ✅         |
| Filtering & Conditions | ✅         |
| Window Functions       | ✅         |
| Ranking Techniques     | ✅         |
| CTEs & Nested Queries  | ✅         |

---

## 🔍 Sample Problem: [Second Highest Salary](https://leetcode.com/problems/second-highest-salary/)

**SQL Query:**
```sql
SELECT MAX(Salary) AS SecondHighestSalary
FROM Employee
WHERE Salary < (SELECT MAX(Salary) FROM Employee);
🧰 Tools Used
🛢️ MySQL / PostgreSQL

🧑‍💻 LeetCode SQL Editor

📝 Markdown (for formatting)

🧩 Git + GitHub

🚀 How to Use
Clone this repo:

bash
Copy
Edit
git clone https://github.com/your-username/LeetCode-SQL-Solutions.git
Explore the categorized folders: Easy, Medium, Hard

Open .sql files and run them in any SQL environment like:

DB Fiddle

LeetCode Playground

Local MySQL/PostgreSQL

🌟 Highlights
✨ Clean & Structured Code
✨ Consistent Naming Convention
✨ Commented for Clarity (if needed)
✨ Growing Weekly with New Problems

🔗 Connect with Me


💫 Thank You!
Thank you for visiting this repository. If you find it helpful, ⭐️ star this repo and follow me for more data-driven content!

"Consistency in solving small problems leads to big growth in skills." 💪



