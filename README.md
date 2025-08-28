# Financial Document Agent

## Description
Ce projet est un **agent financier intelligent** qui permet d’analyser automatiquement des rapports financiers (PDF) en utilisant les technologies **NLP**, **embeddings**, et **FAISS**.  

L’objectif est de :
- Convertir des documents financiers en **Markdown structuré**.
- Découper les contenus en **chunks** basés sur les titres.
- Créer une base vectorielle avec **FAISS** et **HuggingFace Embeddings**.
- Interroger les documents avec un **retriever intelligent** (RAG).

---

## Stack Technique
- Python 3.10+
- LangChain – pour la gestion du pipeline
- FAISS – pour la recherche vectorielle
- HuggingFace Transformers – pour les embeddings
- DocumentConverter (Unstructured) – pour la conversion PDF → Markdown

---

## Fonctionnalités
- 📄 Conversion PDF → Markdown  
- ✂️ Découpage intelligent par titres (#, ##, ###)  
- 📦 Stockage vectoriel avec FAISS  
- 🔍 Recherche de similarité et **retrieval MMR** (Maximal Marginal Relevance)  
- 🤖 Base pour construire un **RAG pipeline** (Retrieval-Augmented Generation)  

---

## Installation

```bash
# Cloner le projet
git clone https://github.com/<ton-user>/FinancialAgent.git
cd FinancialAgent


