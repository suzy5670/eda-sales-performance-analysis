# 📊 Analyse des performances commerciales

Analyse exploratoire (EDA) de l'activité commerciale d'une entreprise e-commerce à partir de ses données **clients**, **commandes** et **produits**, afin d'identifier les leviers de performance et des opportunités d'amélioration basées sur les données.

> Projet réalisé par **Suz Didolène Massamouna** — Data Analyst
> 🌐 Portfolio : [suzy5670.github.io](https://suzy5670.github.io/) · 🔗 [LinkedIn](https://www.linkedin.com/in/suz-didolene-massamouna/)

---

## 🎯 Objectifs de l'analyse

Cette étude vise à répondre aux questions suivantes :

- Quelles sont les villes les plus performantes en termes de chiffre d'affaires ?
- Quels produits et catégories génèrent le plus de ventes ?
- Quels sont les clients les plus actifs et les plus rentables ?
- Comment évoluent les ventes selon les périodes observées ?
- Quels indicateurs permettent de mesurer la performance commerciale globale ?

## 🗂️ Jeux de données

Le projet repose sur trois sources de données (année **2025**) :

| Table | Contenu | Volume |
|---|---|---|
| **Customers** | Informations clients et localisation (ville) | 200 clients |
| **Orders** | Historique des commandes et quantités | 1 000 commandes |
| **Products** | Catalogue produits, catégories et prix | 50 produits |

## 🛠️ Démarche analytique

**1. Contrôle qualité des données** — valeurs manquantes, doublons, clés primaires, cohérence inter-tables (aucune anomalie détectée).
**2. Préparation** — nettoyage, harmonisation des formats, fusion des trois tables, création des indicateurs.
**3. Analyse exploratoire** — géographique, par catégorie, par produit et par client.

---

## 🔑 Indicateurs clés (KPI)

| Indicateur | Valeur |
|---|---|
| 💰 Chiffre d'affaires total | **671 768,59 €** |
| 👥 Nombre total de clients | **200** |
| ✅ Nombre de clients actifs | **199** |
| 🧾 Nombre total de commandes | **1 000** |
| 📦 Nombre d'articles vendus | **3 037** |
| 🛒 Panier moyen | **671,77 €** |
| 🔢 Quantité moyenne par commande | **3,04 articles** |

---

## 📈 Principaux résultats

### 🌍 Géographie
- Villes générant le plus de chiffre d'affaires : **Lyon (142 145 €)**, **Marseille (135 829 €)**, **Toulouse (115 049 €)**.
- Ville présentant le panier moyen le plus élevé : **Lille (712,20 €)** — peu de commandes mais à forte valeur.
- Ville avec le plus de commandes : **Lyon (213 commandes)**.
- Les 5 premières villes représentent **89,5 %** du chiffre d'affaires total.

| Ville | CA | Commandes | Panier moyen |
|---|---|---|---|
| Lyon | 142 145 € | 213 | 667 € |
| Marseille | 135 829 € | 195 | 697 € |
| Toulouse | 115 049 € | 180 | 639 € |
| Bordeaux | 106 639 € | 167 | 639 € |
| Paris | 101 599 € | 146 | 696 € |
| Lille | 70 507 € | 99 | **712 €** |

### 📦 Produits et catégories
- Catégorie la plus performante (CA) : **Electronics (186 025 €)**.
- Catégorie vendant le plus d'unités : **Electronics (745 articles)**.
- Produit le plus vendu (en quantité) : **Product_43 (94 unités)**.
- Produit générant le plus de chiffre d'affaires : **Product_5 (39 975 €)**.

| Catégorie | Chiffre d'affaires |
|---|---|
| Electronics | 186 025 € |
| Books | 171 891 € |
| Sports | 131 442 € |
| Home | 120 267 € |
| Toys | 62 143 € |

### 👤 Clients
- Client le plus actif : **client n°111 (12 commandes)**.
- Client le plus rentable : **client n°28 (9 965 €)**.
- Sur 200 clients, **199 sont actifs** (au moins une commande).

---

## 📊 Visualisations

Les graphiques (CA par ville, par catégorie, top produits, panier moyen…) sont disponibles dans le notebook [`Untitled2(1).ipynb`](Untitled2(1).ipynb).

---

## 💡 Recommandations

À l'issue de cette analyse, plusieurs axes d'amélioration peuvent être envisagés :

- **Renforcer les actions commerciales** dans les villes les plus performantes (Lyon, Marseille, Toulouse).
- **Fidéliser les clients à forte valeur** : les meilleurs clients concentrent une part importante du chiffre d'affaires.
- **Valoriser Lille et Paris**, qui affichent un panier moyen élevé malgré un volume plus faible — un potentiel de croissance.
- **Mettre en avant la catégorie Electronics**, n°1 en CA et en volume.
- **Étudier les produits peu performants** (catégorie Toys notamment) afin d'optimiser l'offre.

---

## 🧰 Technologies utilisées

`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Jupyter Notebook`

## 👩‍💻 Auteur

**Suz Didolène Massamouna** — Data Analyst
📧 mdane230@gmail.com · 🌐 [Portfolio](https://suzy5670.github.io/) · 🔗 [LinkedIn](https://www.linkedin.com/in/suz-didolene-massamouna/)
