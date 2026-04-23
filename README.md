# 🔍 Natural Language to SQL

A Streamlit app that converts plain English questions into SQL queries using **Groq's LLaMA 3.3 70B** model — and visualizes the results with charts.

## Features

- 💬 Ask questions in plain English
- ⚡ Instant SQL generation via Groq API
- 📊 Auto-generated charts (bar, line, pie) based on query context
- 📁 Upload any SQLite `.db` file
- 🔒 API key entered securely in the sidebar

## How to Use

1. Get a free Groq API key at [console.groq.com](https://console.groq.com)
2. Upload your `.db` file (SQLite database)
3. Type a question like *"Top 10 selling items last month"*
4. Click **Run Query** — see SQL + table + chart!

## Running Locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploying on Streamlit Cloud

1. Fork this repo
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub and select this repo
4. Set `app.py` as the main file
5. Deploy!
