SQL Data Analysis Lab
📌 Overview

This project demonstrates how to use SQL queries with Python to analyze data from multiple databases. The lab focuses on filtering, sorting, grouping, and aggregating data using SQLite and pandas.

You will work with three databases:

planets.db → Data about planets in the solar system
dogs.db → Data about fictional dogs
babe_ruth.db → Baseball statistics for Babe Ruth
🎯 Objectives

In this lab, you will learn how to:

Filter data using WHERE
Use conditional operators
Apply aggregate functions (COUNT, SUM, AVG)
Sort results using ORDER BY
Limit results using LIMIT
Group data using GROUP BY and HAVING
🛠️ Technologies Used
Python 3
SQLite
pandas
Pipenv (optional)
📂 Project Structure
project-folder/
│── main.py
│── planets.db
│── dogs.db
│── babe_ruth.db
│── README.md
⚙️ Setup Instructions
1. Clone or download the project
git clone <your-repo-url>
cd project-folder
2. Install dependencies

Using Pipenv:

pipenv install pandas
pipenv shell

Or using pip:

pip3 install pandas
▶️ Run the Project
python main.py
🧪 Running Tests

If tests are provided:

pytest
📊 Key Features
🔹 Basic Filtering
Retrieve planets with no moons
Filter planets by name length
🔹 Advanced Filtering
Filter by mass and moon count
Search using partial text (LIKE)
🔹 Ordering & Limiting
Sort dogs by age or name
Retrieve top results using LIMIT
🔹 Aggregation
Calculate total years played
Sum total home runs
🔹 Grouping
Group stats by team
Calculate averages with conditions
📌 Example Query
SELECT name, mass
FROM planets
WHERE mass <= 1.00
ORDER BY mass;
❗ Troubleshooting
pandas not found
ModuleNotFoundError: No module named 'pandas'

Fix:

pipenv install pandas

or

pip3 install pandas
👨‍💻 Author

Joseph Mokaya