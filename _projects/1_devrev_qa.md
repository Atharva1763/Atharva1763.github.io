---
layout: page
title: Domain-Specific Extractive QA
description: BM25 + distillation-trained re-rankers for closed-domain QA (DevRev, Inter-IIT Tech Meet)
img: assets/img/12.jpg
importance: 1
category: research
github: https://github.com/Atharva1763/Domain-Specific-Question-Answering-DevRev
---

**DevRev · Inter-IIT Tech Meet · Dec 2022 – Feb 2023**

We built a closed-domain extractive question-answering system using **domain-adaptable re-rankers** that were fine-tuned via **knowledge distillation** to re-rank passages retrieved by BM25.

### What I worked on

- Trained multiple readers and experimented with data-augmentation techniques.
- Owned the evaluation pipeline (scripts, metrics, ablations).
- Designed signals from the reader, ranker, and retriever to detect **unanswerable questions** — one technique reached **~97% accuracy**.

### Result

Our model outperformed all the other submissions on the leaderboard, contributing to a **1st-place finish** for our team in the NLP problem statement.

🔗 [Source code on GitHub](https://github.com/Atharva1763/Domain-Specific-Question-Answering-DevRev)
