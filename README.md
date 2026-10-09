# 📚 Web Scraping — TP Formation Python

> Projet académique de formation au web scraping en Python : extraction de données depuis des sites web avec `requests` et `BeautifulSoup`.

[![Python](https://img.shields.io/badge/Python-3.14-blue.svg)](https://www.python.org/)
[![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4-8A2BE2.svg)](https://www.crummy.com/software/BeautifulSoup/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Licence](https://img.shields.io/badge/Licence-Projet%20académique-lightgrey.svg)]()

---

## 📖 Description

Ce projet regroupe trois notebooks Jupyter progressifs pour apprendre le **web scraping** en Python. Il couvre les techniques fondamentales d’extraction de données web, de la requête HTTP simple au respect des bonnes pratiques (User-Agent, robots.txt, limitation de débit).

Les exercices s’appuient sur des sites d’entraînement dédiés : `books.toscrape.com` et `quotes.toscrape.com`.

---

## ✨ Fonctionnalités

- **Scraping classique** — Extraction de données depuis une page HTML avec `requests` + `BeautifulSoup`
- **Crawling** — Navigation automatique entre les pages via les liens « suivant »
- **Extraction de fiches détaillées** — Visite des pages individuelles pour enrichir les données
- **Bonnes pratiques** — Gestion du User-Agent, lecture du fichier `robots.txt`, pauses entre requêtes
- **Export CSV** — Sauvegarde des données collectées au format CSV avec `pandas`

---

## 🛠️ Prérequis

- **Python 3.14** (ou supérieur)
- **Jupyter Notebook** ou **JupyterLab**
- Bibliothèques : `requests`, `beautifulsoup4`, `pandas`

> [!IMPORTANT]
> Installez les dépendances dans un environnement virtuel : `pip install requests beautifulsoup4 pandas jupyter`

---

## 📓 Utilisation

Les notebooks sont conçus pour être suivis **dans l’ordre** :

| Ordre | Notebook | Objectif |
|:-----:|----------|----------|
| 1 | `1-scraping-classique.ipynb` | Scraper et crawler `books.toscrape.com` — 1 000 livres sur 50 pages |
| 2 | `2-user-agent-et-robots-enonce.ipynb` | Comprendre le User-Agent et le fichier `robots.txt` — test sur Wikipédia |
| 3 | `3-mission-adaptation-enonce.ipynb` | Mission autonome : adapter le scraping à `quotes.toscrape.com` |

---

## 🗂️ Structure du projet

```text
WebScraping/
├── 1-scraping-classique.ipynb          # TP 1 — Scraping classique (requests + BeautifulSoup)
├── 2-user-agent-et-robots-enonce.ipynb # TP 2 — User-Agent et robots.txt
├── 3-mission-adaptation-enonce.ipynb   # TP 3 — Mission d’adaptation (quotes.toscrape.com)
├── livres.csv                          # Données extraites (40 livres)
└── README.md                           # Ce fichier
```

---

## 📦 Dépendances

| Bibliothèque | Version | Rôle |
|--------------|---------|------|
| `requests` | 2.34.2 | Requêtes HTTP |
| `beautifulsoup4` | 4.15.0 | Parsing HTML |
| `pandas` | 3.0.6 | Manipulation et export des données |
| `jupyter` | — | Environnement notebook |

---

## 🌐 Sites utilisés

| Site | Usage | Description |
|------|-------|-------------|
| [books.toscrape.com](https://books.toscrape.com) | TP 1 & 2 | Librairie fictive de 1 000 livres — site d’entraînement officiel |
| [quotes.toscrape.com](https://quotes.toscrape.com) | TP 3 | Citations célèbres — mission d’adaptation |
| [en.wikipedia.org](https://en.wikipedia.org) | TP 2 | Test du User-Agent sur un site réel (lecture seule) |

> [!TIP]
> Ces sites sont **créés spécifiquement** pour l’entraînement au scraping. N’utilisez jamais ces techniques sur des sites qui ne vous y autorisent pas.

---

## ✍️ Auteur

[TheRealRPI](https://github.com/TheRealRPI) — 🧙 Sorcier de la Data | Data Engineer en formation — Simplon.co

---

## 📜 Licence

Projet académique — Simplon.co
