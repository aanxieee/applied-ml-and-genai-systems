# Applied ML & GenAI Systems

This repository contains a collection of **hands-on machine learning, NLP, and GenAI systems** that I’ve built while working on real-world problem statements.

The focus is not on toy models or academic demos, but on:
- understanding messy data,
- designing the right ML / GenAI approach,
- and building systems that could realistically move towards production.

---

## What This Repo Demonstrates

- Strong fundamentals in **ML, NLP, and statistics**
- Practical use of **LLMs, RAG, and agent-style workflows**
- Ability to think in **systems**, not isolated notebooks
- End-to-end mindset: **data → logic → output → iteration**

---

## Project Overview

### 1️⃣ RAG-based Semantic Skill Retriever
📄 `RAG_based_semantic_skill_retriever.ipynb`

- Built a Retrieval-Augmented Generation (RAG) pipeline
- Semantic search over unstructured skill data using embeddings
- Designed to retrieve relevant context before LLM reasoning
- Focus: improving relevance, grounding, and response quality

**Concepts:** RAG, embeddings, semantic search, GenAI pipelines

---

### 2️⃣ Agent-based Reasoning Experiments
📄 `agent_code.ipynb`  
📄 `Agent_trial_code.ipynb`

- Experiments with LLM-driven agents for task reasoning and execution
- Explores prompt design, tool calling, and step-by-step reasoning
- Focus on control, reliability, and failure modes of agents

**Concepts:** LLM agents, orchestration, reasoning flows

---

### 3️⃣ NLP Topic Modeling with BART
📄 `BART_News_Topic.ipynb`

- Topic extraction and summarization using transformer-based models
- Applied to real text corpora instead of curated datasets
- Focus on interpretability and downstream usability

**Concepts:** NLP, transformers, text summarization

---

### 4️⃣ Inventory Forecasting & Optimization
📄 `inventory_training.ipynb`

- ML-based demand estimation for inventory planning
- Focus on understanding trends, seasonality, and business constraints
- Designed with decision-support use cases in mind

**Concepts:** forecasting, ML optimization, business analytics

---

## Design Philosophy

I approach ML and GenAI as **decision-enabling tools**, not magic models.

My typical workflow:
Messy data
→ clean signals
→ simple but strong ML logic
→ automation / system thinking
→ measurable impact


When patterns are complex or scale demands it, I use ML / GenAI.
Otherwise, I prefer clarity, reliability, and maintainability.

---

## Tech Stack

- Python
- Pandas, NumPy, scikit-learn
- PyTorch / Transformers (where relevant)
- LangChain & LLM APIs
- Jupyter / Colab

---

## Note

These notebooks are intentionally kept **transparent and exploratory** to show my thinking, trade-offs, and iteration process — similar to how real ML systems evolve in startups.

##AUTHOR : https://www.aanxiee.com/
