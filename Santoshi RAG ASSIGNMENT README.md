<!--
  GitHub profile README for Santoshi
  Create a public repository whose name exactly matches your GitHub username,
  then place this file in it as README.md.
-->

<div align="center">

# Hi, I'm Santoshi 👋

### Building practical, privacy-first AI tools that turn information into answers.

I’m interested in **Retrieval-Augmented Generation (RAG)**, local LLMs, and intelligent document systems. I enjoy building tools that make dense PDFs, notes, and technical documents easier to explore—without sending sensitive content to the cloud.

<p>
  <img src="https://img.shields.io/badge/Focus-Local%20AI%20%26%20RAG-6C63FF?style=for-the-badge" alt="Focus: Local AI and RAG" />
  <img src="https://img.shields.io/badge/Build%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Built with Python" />
  <img src="https://img.shields.io/badge/Privacy-Local--first-1F6FEB?style=for-the-badge&logo=shield&logoColor=white" alt="Privacy: local-first" />
</p>

</div>

---

## What I’m working on

### 📚 Local RAG Document Question Answering System

A local-first application for asking grounded questions about PDF and text documents. It retrieves the most relevant passages before generating a response, helping keep answers tied to the source material.

**How it works**

```text
PDF / TXT document
       ↓
Load & split into contextual chunks
       ↓
Create embeddings with Ollama
       ↓
Store and search with ChromaDB
       ↓
Retrieve the most relevant context
       ↓
Llama 3.1 generates a grounded answer
```

**Why it matters**

- 🔒 Keeps document processing and AI inference on your machine
- 🎯 Grounds answers in retrieved document context
- 📄 Supports PDFs and plain-text files
- 🔎 Shows retrieved passages, similarity scores, and source pages
- 🧠 Makes research notes, manuals, and study materials searchable by question

<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/ChromaDB-Vector%20Search-FF6F61?style=flat-square" alt="ChromaDB" />
  <img src="https://img.shields.io/badge/Llama%203.1-Local%20LLM-0467DF?style=flat-square" alt="Llama 3.1" />
</p>

> **Project goal:** turn static documents into a private, interactive knowledge base.

---

## My toolkit

| Area | Technologies |
| --- | --- |
| **Language** | Python |
| **AI orchestration** | LangChain, LCEL |
| **Local AI runtime** | Ollama, Llama 3.1, nomic-embed-text |
| **Retrieval** | ChromaDB, similarity search |
| **Document processing** | PyPDFLoader, TextLoader, RecursiveCharacterTextSplitter |

---

## Principles I build by

**Grounded over guessed.** AI answers should be traceable to relevant source context.

**Private by default.** Useful AI does not always require handing documents to a third-party API.

**Simple, inspectable systems.** Retrieval, context, and sources should be visible—not hidden behind a black box.

---

## Currently exploring

- Source citations and confidence-aware answers for RAG
- Multi-document and conversational document search
- Better retrieval strategies: reranking, metadata filtering, and hybrid search
- Friendly interfaces for local AI tools

---

## Let’s connect

I’m always interested in thoughtful projects around local AI, document intelligence, and practical machine learning.

<!-- Replace these placeholders once you have the relevant links. -->

- 💼 LinkedIn: `add-your-link`
- 📫 Email: `add-your-email`
- 🌐 Portfolio: `add-your-website`

<div align="center">

### Thanks for visiting ✨

*Making knowledge easier to find, understand, and trust.*

</div>
