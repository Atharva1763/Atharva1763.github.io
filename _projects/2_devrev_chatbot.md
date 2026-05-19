---
layout: page
title: API-driven Multi-Step Query Chatbot
description: A LangChain + ChromaDB chatbot capable of multi-step queries over dynamic APIs
img: assets/img/11.jpg
importance: 2
category: research
github: https://github.com/IIT-Patna-Inter-IIT-Tech-Meet/DevRev-chatbot-frontend
---

**DevRev · Inter-IIT Tech Meet · Oct 2023 – Dec 2023**

I led a team building a chatbot that handles **multi-step user queries** by orchestrating a set of APIs, with first-class support for adding, deleting, and updating those APIs at runtime.

### Pipeline

1. **Multi-query retrieval & re-ranking** over a ChromaDB index of API descriptions.
2. **Output generation** using a dynamic, few-shot prompting strategy.
3. **Feedback loop** that detects unanswerable queries and routes them appropriately.

### Stack

LangChain · ChromaDB · HuggingFace · custom retriever-reranker stack.

🔗 [Source code on GitHub](https://github.com/IIT-Patna-Inter-IIT-Tech-Meet/DevRev-chatbot-frontend)
