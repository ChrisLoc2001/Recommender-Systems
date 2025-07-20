# Recommender-Systems

# 🎬 Hybrid Movie Recommender System

Un sistema di raccomandazione di film basato su un **approccio ibrido**, che combina **User-Based Collaborative Filtering** con tecniche di **clustering** per affrontare il problema del **cold start**.

## 🧱 Architettura

RECOMMENDER-SYSTEM/
│
├── Clustering: Contiene i vari notebook di prova utilizzati per trovare la miglior tecnica di clustering per item e user.
├── Hybrid-User-Based: Contiene il sistema di raccomandazione con approccio ibrido
|
├── Image: Cartella che contiene le immagini dei grafici
│
├── Prove Iniziali Collaborative: Contiene tutte le prove iniziali del Collaborative filtering user-based e item-based
│
├── User-Based: Cartella contenente il sistema di raccomandazione con approccio Collaborative Filtering User-based
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

È stato utilizza anche un approccio ibrido:

- 🔀 **Approccio Ibrido (User-Based + Item-Based)**  
  In scenari ideali (senza cold start), il sistema sfrutta **sia User-Based che Item-Based Collaborative Filtering** per migliorare la qualità delle raccomandazioni.
  
---

```bash
pip install -r requirements.txt
