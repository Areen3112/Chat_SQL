# 💬 ChatSQL – AI-Powered Database Assistant

ChatSQL is an end-to-end AI application that allows users to interact with SQL databases using natural language. Instead of writing SQL queries manually, users can ask questions in plain English, and the AI agent generates, validates, executes, and explains SQL queries automatically.

Built using **LangChain Agents**, **SQL Toolkit**, and **open-source LLMs**, ChatSQL supports both **SQLite** and **MySQL** databases.

---

## 🚀 Features

- 💬 Chat with your SQL database using natural language
- 🤖 AI-powered SQL query generation using LangChain Agents
- 🛡️ SQL query validation before execution
- 📊 Retrieve and summarize database records
- 🔍 Automatic table and schema discovery
- 🗄️ Supports SQLite and MySQL databases
- ⚡ Uses open-source LLMs through Groq API
- 🧠 Built with LangChain SQL Toolkit

---

## 🛠️ Tech Stack

- Python
- LangChain
- LangChain SQL Toolkit
- Groq API
- SQLite
- MySQL
- SQLAlchemy
- Streamlit (UI)

---

## 📂 Project Structure

```
ChatSQL/
│
├── app.py
├── requirements.txt
├── database/
│   ├── student.db
│   └── ...
├── utils/
├── agents/
├── prompts/
└── README.md
```

---

## ⚙️ How It Works

1. Connect to a SQLite or MySQL database.
2. Enter your Groq API key.
3. Ask questions in natural language.
4. LangChain Agent:
   - Detects available tables
   - Reads database schema
   - Generates SQL query
   - Validates the query
   - Executes it
5. AI returns the results in an easy-to-understand format.

---

## 💡 Example Queries

- Show all students.
- Display all records in the student table.
- Find students whose name is Krish.
- Count the total number of students.
- Show students with marks greater than 80.
- List all available tables.
- What columns exist in the student table?

---

## 🧠 AI Workflow

```
User Question
      │
      ▼
LangChain Agent
      │
      ▼
SQL Toolkit
      │
      ▼
Schema Detection
      │
      ▼
SQL Generation
      │
      ▼
Query Validation
      │
      ▼
Database Execution
      │
      ▼
Natural Language Response
```

---

## 🔑 Supported Databases

- SQLite
- MySQL

More SQL databases can be integrated through SQLAlchemy.

---

## 📦 Installation

```bash
git clone https://github.com/Areen3112/ChatSQL.git

cd ChatSQL

pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
streamlit run app.py
```

---

## 🔐 Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key
```

---

## 📈 Future Improvements

- PostgreSQL support
- SQL Server support
- Database visualization
- Query history
- Multi-agent architecture
- Authentication
- CSV & Excel upload
- Chart generation
- Voice-based querying
- Conversation memory

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project useful, consider giving it a star!
