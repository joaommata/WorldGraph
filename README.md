# 🌍 WorldGraph

> *Using Wikipedia as a lens to study historical, cultural, and political ties between countries through network science.*

---

## 📖 Overview

WorldGraph constructs and analyses networks of countries derived from Wikipedia article cross-references. By treating countries as nodes and their Wikipedia interlinkages as edges, the project uncovers latent structures in how the world is connected — through shared history, geography, culture, and politics.

The analysis combines **network topology**, **sentiment analysis**, and **community detection** to surface meaningful clusters and relationships that go beyond conventional geopolitical boundaries.

---

## 🔬 Methods

- **Graph Construction** — Country networks built from Wikipedia cross-link data using the Wikipedia API
- **Network Analysis** — Degree distribution, centrality measures, and structural properties of the world graph
- **Community Detection** — Louvain / modularity-based algorithms to identify clusters of historically or culturally related countries
- **Sentiment Analysis** — Sentiment scoring of Wikipedia article content to characterise how countries describe one another
- **Visualisation** — Interactive and static graph visualisations of detected communities and link weights

---

## 🛠️ Stack

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![NetworkX](https://img.shields.io/badge/NetworkX-013243?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

**Key libraries:** `networkx` · `wikipedia-api` · `community` (python-louvain) · `nltk` / `TextBlob` · `pandas` · `matplotlib` · `seaborn`


---

## 📊 Key Questions Explored

- Which countries form tight clusters based on Wikipedia cross-references?
- Do detected communities align with geopolitical blocs, historical empires, or linguistic groups?
- How do countries portray one another in sentiment — and does this correlate with real-world relations?
- What are the most central and most peripheral countries in the world graph?

---

## 📚 Context

Developed as the final assignment for **02467 – Social Graphs and Interactions** at DTU – Technical University of Denmark (Autumn 2025).

---

## 👤 Authors

Maria Vendas, João Mata and Rita Silva.
