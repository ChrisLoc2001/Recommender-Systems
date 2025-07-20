# Recommender-Systems

# 🎬 Hybrid Movie Recommender System

Un sistema di raccomandazione di film basato su un **approccio ibrido**, che combina **User-Based Collaborative Filtering** con tecniche di **clustering** per affrontare il problema del **cold start**.

## 🧱 Architettura

RECOMMENDER-SYSTEM/
│
├── Clustering/
| |
│ ├── item cluster old/
│ ├── item cluster new/
│ └── user cluster/
│
├── Hybrid-User-Based/
|
├── Image/
│
├── Prove Iniziali Collaborative/
│
├── User-Based/
│
├── datasets/
├── requirements.txt
└── README.md

## 🧠 Descrizione del progetto

Questo progetto implementa un sistema di raccomandazione ibrido, costruito combinando:

- 📌 **User-Based Collaborative Filtering**  
  Basato sulla similarità tra utenti per raccomandare film che utenti simili hanno apprezzato.

- 📌 **Clustering su utenti e film**  
  Tecniche come K-Means, Agglomerative e Word2Vec per raggruppare utenti/film e affrontare il problema del **cold start**, assegnando raccomandazioni basate sulla vicinanza nel cluster.

---


```bash
pip install -r requirements.txt