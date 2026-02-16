# Football Data Analytics & Machine Learning Projects

This repository contains machine learning and data analytics projects focused on the beautiful game.

The objective of this repo is to explore quantitative methods for player analysis, similarity modelling, and data-driven insights within the game.

---

##  Projects Overview

This repository currently includes:

-  Web Data Scrapers: `datascrapper.ipynb`, `datacollection.ipynb`  
-  K-Means Player Clustering Analysis: `FA1.ipynb`  
-  Player Similarity Application: `playersimilarity.ipynb`
-  Additional Files (Work in Progress)

---

##  Web Data Scrapers

Custom-built web scraping tools to collect structured football data including:

- Player statistics  
- Match data  
- Performance metrics  

These scrapers serve as the data foundation for downstream modelling and analysis.

---

##  K-Means Player Clustering Analysis

An unsupervised machine learning project that applies **K-Means clustering** to group players with similar statistical profiles.

### Objective
Identify natural groupings of players based on:

- Offensive metrics  
- Defensive contributions  
- Possession statistics  
- Expected goals (xG)  
- Position-based attributes  

### Key Techniques
- Feature scaling & normalization  
- Dimensionality reduction
- Cluster evaluation and interpretation  

This project demonstrates how data-driven clustering can uncover hidden tactical or stylistic groupings among players.

---

##  Player Similarity Application

An interactive application designed to identify players most similar to a given target player.

### Core Concept

Similarity is computed using a **hybrid distance-based scoring system**, combining:

- Euclidean Distance  
- Cosine Similarity  
- Position-based filtering  
- Statistical weighting  

A composite point system aggregates multiple similarity metrics to rank players by overall likeness.

### Metrics Used

- Core performance statistics  
- Positional data  
- Expected Goals (xG)  


This allows users to explore comparable players across leagues and playing styles.

---

##  Pipeline & Methodology

- Data preprocessing and feature engineering  
- Statistical normalization  
- Distance-based modelling  
- Similarity scoring systems  
- Machine learning clustering techniques  

---

##  (WIP)

Projects include:

- Interactive dashboard deployment  
- Player valuation modelling  
- Tactical similarity modelling  
- Match-level predictive analytics  

---

##  Tech Stack

- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib / Seaborn  
- Web scraping libraries (e.g., BeautifulSoup, Selenium)  

---

##  Goal

To build scalable, data-driven tools that enhance player analysis and decision-making within football analytics.

---

*This project is intended for analytical and educational purposes.*
