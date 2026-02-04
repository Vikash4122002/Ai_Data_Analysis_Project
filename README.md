# 📊 AI Data Analysis Agent

AI-powered data analysis assistant that converts natural language questions into SQL and analyzes CSV/Excel datasets automatically.

Built with:

- Streamlit
- OpenAI GPT
- DuckDB
- Pandas

---

## 🚀 Features

- Upload CSV & Excel
- Natural language queries
- Auto SQL generation
- DuckDB fast analytics
- Charts & summaries
- No SQL knowledge needed

---

## 🧠 How It Works

User Question → LLM → SQL → DuckDB → Results → Visualization

---

## 📁 Project Structure

ai_data_analyst.py — Streamlit UI  
agent.py — LLM SQL generator  
db_tools.py — DuckDB engine  
file_loader.py — File reader  
prompts.py — Prompt builder  

---

## ⚙️ Setup

### Clone Repo

git clone <your-repo>
cd ai-data-analysis-agent

### Install

pip install -r requirements.txt

---

## 🔑 API Key

Get OpenAI API key and paste into Streamlit sidebar.

---

## ▶️ Run

streamlit run ai_data_analyst.py

---

## 💬 Example Queries

- Average sales by region
- Top 5 customers
- Monthly trend
- Highest profit category

---

## 📊 Supported Files

CSV  
Excel (.xlsx)

---

## 📜 License

MIT
