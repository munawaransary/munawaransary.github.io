---
date: '2026-07-01'
title: 'MonCare — Trilingual Mental-Health Support Chatbot'
cover: './demo.png'
github: 'https://github.com/munawaransary/moncare'
external: ''
tech:
  - Python
  - RAG
  - FAISS
  - GPT-OSS-20B
  - FastAPI
---

A private, trilingual (Bangla · Banglish · English) mental-health support chatbot that runs entirely on one local GPU. It detects the user's language, screens every message through a two-stage crisis gate, and answers with retrieval-augmented generation over a 19K-item counseling knowledge base (bge-m3 embeddings, FAISS, cross-encoder rerank, local LLM). Crisis responses are deterministic and route to verified human helplines, with an output guard that strips any helpline number the model invents. Built as a Research Engineer Intern at UIU's AIMS Lab. Not a medical device.
