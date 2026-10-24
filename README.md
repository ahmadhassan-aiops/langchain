<div align="center">

# 🦜🔗 LangChain

**Build LLM applications with LangChain, step by step: models, prompts, chains, embeddings, RAG, memory and agents, with runnable Jupyter notebooks for OpenAI, Anthropic Claude, Google Gemini and open-source Hugging Face models.**

![LangChain](https://img.shields.io/badge/LangChain-1.x-1C3C3C?logo=langchain&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991?logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-D97757?logo=anthropic&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Open%20source-FFD21E?logo=huggingface&logoColor=black)
![Status](https://img.shields.io/badge/Status-Ongoing-0EA5A4)

</div>

---

## 🎯 About this course

Practical LangChain notes for anyone moving from calling an LLM API to building real applications with it. Each notebook explains the idea in plain English, shows the code for several providers, and keeps the real outputs from the runs. New notebooks are added regularly.

---

## 📚 Course contents

| # | Notebook | You'll learn |
|---|---|---|
| 01 | [LangChain Components](01.%20LangChain%20Components.ipynb) | Why LangChain exists; the six components (models, prompts, chains, indexes, memory, agents); dynamic, role-based and few-shot prompts |
| 02 | [LangChain Models](02.%20LangChain%20Models.ipynb) | LLMs vs chat models; OpenAI, Claude, Gemini and Hugging Face chat models; conversation history; OpenAI and open-source embeddings; semantic search over a PDF |

### 🔜 Coming next

Prompt templates in depth, structured output and output parsers, chains with LCEL, document loaders and text splitters, vector stores and retrievers, a complete RAG application, tools and agents, memory, and LangGraph.

---

## 🚀 How to use it

**In Google Colab (easiest)**

1. Open a notebook on GitHub and choose **Open in Colab** (or upload it to [colab.research.google.com](https://colab.research.google.com)).
2. Click the 🔑 **Secrets** icon in the left panel and add the keys you need: `OPENAI_API_KEY`, `ANTHROPIC_API_KEY`, `GOOGLE_API_KEY`, `HF_TOKEN`.
3. Run the cells from top to bottom.

**On your own machine**

```bash
git clone https://github.com/ahmadhassan-aiops/langchain.git
cd langchain
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
cp .env.example .env                                 # then paste your keys into .env
jupyter notebook
```

You only need keys for the providers you want to try. The Hugging Face embedding examples run locally for free.

> 🔐 Never paste API keys into a notebook or commit a `.env` file. The included [`.gitignore`](.gitignore) keeps `.env` out of Git.

---

## 👨‍🏫 About the author

**Ahmad Hassan** | AI/ML Engineer & Instructor with 5+ years of experience
1,500+ hours of live teaching, 100+ students mentored from medicine, business and engineering into data and AI roles.

[![Portfolio](https://img.shields.io/badge/Portfolio-ahmadhassan--aiops.github.io-0EA5A4)](https://ahmadhassan-aiops.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ahmad%20Hassan-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmad-hassan-79a44b1a3)
[![GitHub](https://img.shields.io/badge/GitHub-ahmadhassan--aiops-181717?logo=github&logoColor=white)](https://github.com/ahmadhassan-aiops)

⭐ If these notebooks help you build with LangChain, please star the repo. It helps other students find it!
