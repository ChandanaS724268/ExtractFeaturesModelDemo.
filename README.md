# 📰 Agentic AI Lab 10 – Multi-Agent News Pipeline

A simple multi-agent AI workflow built using **LangChain**, **Groq Llama 3.1**, and **DuckDuckGo Search** in **Google Colab**.

This project demonstrates how multiple AI agents can work together to search for the latest news, summarize the information, and generate a formatted Markdown report automatically.

---

## 📌 Project Overview

This project implements a **three-agent pipeline**:

1. **Search Agent**
   - Searches the latest news on a given topic.
   - Uses DuckDuckGo Search.

2. **Summarizer Agent**
   - Summarizes the retrieved news into concise bullet points.
   - Uses Groq's Llama 3.1 model.

3. **Report Agent**
   - Formats the summary into a clean Markdown report.
   - Saves the report as `news_report.md`.

---

## 🚀 Technologies Used

- Python 3
- Google Colab
- LangChain
- LangChain Community
- LangChain Groq
- Groq API (Llama 3.1-8B Instant)
- DDGS (DuckDuckGo Search)
- Markdown

---

## 📂 Project Structure

```
Lab10_News_Pipeline/
│
├── Lab10_News_Pipeline.ipynb
├── news_report.md
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Install the required libraries:

```bash
pip install -U \
langchain \
langchain-community \
langchain-groq \
ddgs
```

---

## 🔑 API Key Setup

Create a free Groq API Key from:

https://console.groq.com/

In Google Colab:

1. Open **Secrets** (🔑 icon).
2. Create a new secret.

Name:

```
GROQ_API_KEY
```

Paste your API key as the value and enable **Notebook Access**.

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Add your Groq API Key.
4. Run all notebook cells sequentially.
5. Enter the topic for news search.
6. The pipeline will:
   - Search the web
   - Summarize the news
   - Generate a Markdown report
   - Save it as **news_report.md**

---

## 🔄 Workflow

```
          User Topic
               │
               ▼
      Search Agent
               │
               ▼
    Summarizer Agent
               │
               ▼
      Report Agent
               │
               ▼
      news_report.md
```

---

## 📄 Sample Output

```markdown
# News: Artificial Intelligence

- AI companies announced new language models.
- Researchers introduced more efficient AI systems.
- Governments continue working on AI regulations.

Overall, AI continues to evolve rapidly across industries.
```

---

## 🎯 Learning Outcomes

- Understand Multi-Agent AI workflows.
- Use LangChain with Groq LLMs.
- Integrate external search tools.
- Generate structured Markdown reports.
- Build sequential AI pipelines.

---

## 📚 Laboratory Information

**Course:** Agentic AI Laboratory

**Lab Program:** Lab 10 – Capstone: A 3-Agent News Pipeline

**Platform:** Google Colab

**Model:** Groq Llama 3.1 8B Instant

This project demonstrates a complete **Search → Summarize → Report** multi-agent workflow as described in the Agentic AI laboratory manual. :contentReference[oaicite:0]{index=0}

---

## 👩‍💻 Author

**Chandana S**

Computer Science Engineering Student

Garden City University

---

## 📜 License

This project is intended for educational and academic purposes.
