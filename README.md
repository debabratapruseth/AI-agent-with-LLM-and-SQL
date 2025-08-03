# An intelligent AI-powered SQL assistant that transforms natural language into SQL queries — and executes them on a real database.

This project is built with beginners in mind and demonstrates how to integrate LLM (OpenAI’s GPT-4 API) with a structured dataset to simulate a real-world SQL data assistant — no SQL or AI expertise required!

---


# Designed for Beginner Python and AI/ML Learners

This self-paced, educational project helps learners explore:

- How to use OpenAI’s GPT-4 to generate SQL queries

- How to execute those queries on a real relational database (SQLite)

- How to validate SQL for safe execution (read-only)

- How to format and display results from database queries

- How to build a working LLM-powered data agent from scratch


---


# How It Works
User Input
Ask a question based on content stored in teh database.

LLM Translation
GPT-4 receives the database schema + question and generates a SQL query.

Validation
The query is scanned to block unsafe operations (DROP, DELETE, etc.).

Execution
The SQL query runs on the database using SQLite.

Output
The result is formatted and returned to the user — all within a single function.

---


# Educational Goals

By completing this project, you will:

- Understand how natural language can be transformed into structured queries

- Learn the basics of database schemas and SELECT statements

- Explore OpenAI API integration using Python and HTTP requests

- Practice safe SQL execution with validation logic

- Build their confidence in AI-assisted data tools

- Understand the architecture of AI-powered enterprise dashboards

---


# Technologies Used

Component >> Tool:

- LLM	OpenAI >> GPT-4 (via API)

- Database >>	SQLite (can upgrade to PostgreSQL/MySQL)

- HTTP Requests >>	requests

- Security >>	Read-only SQL validation

- Deployment >>	Google Colab 

---

# Limitations & Improvements

Current Limitations >>	Future Enhancements:

- Works only with SELECT statements >>	Add write/query mode switching

- Uses SQLite (local file-based) >>	Add PostgreSQL/MySQL connector

- Query is text-based only >> Add file upload or schema discovery

- No login/authentication	>> Add RBAC + user access control

- Prompt is fixed	>> Add prompt templates for fine-tuning

---


# Want More?

Once you’ve mastered this project, try:

- Building a full dashboard assistant with Streamlit

- Connecting to your organization’s real database

- Using GPT-4 with query explanation or data summarization


---


# License
This project is open-sourced under the MIT License.

---

# Blog Post

Blog URL : https://debabratapruseth.com/agentic-ai-llm-with-sql-beginner-bootcamp/

Website : https://debabratapruseth.com/

---

👋 If you find this helpful, don't forget to ⭐ the repo and follow for more beginner-friendly AI projects!
