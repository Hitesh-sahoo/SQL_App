## 📌 Project: Gemini SQL Assistant with Streamlit
###🔹 Description
This project demonstrates how to integrate Google Gemini LLM with SQLite inside a Streamlit web app.
It allows users to type natural language questions (English) and automatically generates SQL queries to run on a sample employee database. The app also displays query results and explains the SQL step-by-step in simple terms.

🔹 Features

SQLite Database Setup (sql.py)

Creates a database Naresh_it_employee1.db with employee details (name, role, salary).

Inserts sample employee records.

Streamlit App (app.py)

Accepts English questions from the user.

Uses Google Gemini API to convert text into valid SQL queries.

Executes SQL on the local database.

Displays results in a table format.

Provides an AI-generated explanation of the SQL query.

Example Queries:

"List all employees"

"Who earns more than 60,000?"

"Show all Data Engineers"

"Provide the average salary based on job role"

🔹 Tech Stack

Python

SQLite

Streamlit

Google Generative AI (Gemini)

Pandas
