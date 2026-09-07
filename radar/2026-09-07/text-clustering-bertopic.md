---
title: "Кластеризация текстов (BERTopic-подход)"
ring: confident
quadrant: ai-ml
tags: [other]
---

**Знаком с:** 2026-09

Практика на своих данных: 1571 сообщение из личного чата, кластеризация за один день.
Собрал пайплайн вручную по подходу BERTopic (саму библиотеку не ставил): sentence-transformers
+ USER-bge-m3 — эмбеддинги локально на MPS; UMAP — понижение размерности, подбирал
`n_neighbors`; HDBSCAN — кластеризация, подбирал `min_cluster_size`/`min_samples`;
c-TF-IDF — ключевые слова кластеров, формулу реализовал сам. Инструментарий:
scikit-learn, pandas, Jupyter.
