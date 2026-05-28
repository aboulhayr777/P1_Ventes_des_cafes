# Projet : Analyse des ventes de café

## Présentation du projet
Ce projet consiste à analyser les ventes d'un café durant l'année 2023 afin de comprendre les performances commerciales.  
Le projet a été réalisé avec python dans Jupyter Notebook et comprend :
- le nettoyage des données,
- l'analyse exploratoire des données,
- la création de visualisations,
- l'extraction d'insights business.

---

## Objectifs du projet

Les principaux objectifs sont : 
- Comprendre les performances globales du café
- Identifier les produits les plus vendus et les plus rentables
- Analyser les habitudes des clients
- Etudier les moyens de paiement utilisés
-  Etudier les modes de consommation
- Identifier les périodes les plus actives et rentables.

## Informations sur les données
- Source des données : Kaggle
- Pour accéder aux données [cliquez ici.](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training/data)
- Taille initiale du dataset : 10000 lignes
- Taille après nettoyage : 9 942 lignes
---

## Outils et bibliothèques utilisés

- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- Seaborn

## Structure du projet

```
P1_Ventes_des_cafes/
│
├── data/
│   ├── raw/
│   │   └── dirty_cafe_sales.csv
│   │
│   ├── processed/
│       └── cleaned_cafe_sales.csv
│
├── notebooks/
│   ├── 01_exploration_et_nettoyage.ipynb
│   ├── 02_analyse_des_donnees.ipynb
│
├── src/
│   └── (scripts Python éventuels)
│
└── README.md
```

---

## KPI (Indicateurs clés)

- Nombre total de transactions : 9 942
- Chiffre d'affaires total : 88 800.5 €
- Panier moyen : 8.93 €

---

## Produits vendus

- Jus
- Café
- Salade
- Gâteau
- Sandwich
- Smoothie
- Cookie
- Thé

### Prix unitaires des produits

| Produit | Prix |
|---|---|
| Salade | 5 € |
| Sandwich | 4 € |
| Smoothie | 4 € |
| Gâteau | 3 € |
| Jus | 3 € |
| Café | 2 € |
| Thé | 1.5 € |
| Cookie | 1 € |

---
## Résultats et insights
### Produit le plus vendu
- Le jus est le produit le plus vendu avec 1 167 ventes.

### Produit le plus rentable
- La salade est le produit le plus rentable avec 17 315 € de chiffre d'affaires.

---

## 💳 Moyens de paiement

| Moyen de paiement | Nombre d'utilisations |
|---|---|
| Digital Wallet | 2280 |
| Credit Card | 2260 |
| Cash | 2244 |

Les différents moyens de paiement présentent des fréquences d’utilisation très proches, ce qui montre un comportement équilibré des clients.

---

## 🏪 Modes de consommation

| Mode | Nombre |
|---|---|
| Takeaway | 3004 |
| In-store | 2998 |

Le café présente un équilibre presque parfait entre les commandes à emporter et les consommations sur place.

---

## 📅 Tendances d’activité

### Mois les plus fréquentés
- Octobre
- Mars
- Juin
- Janvier
- Août

### Mois les plus rentables
- Juin
- Octobre
- Janvier
- Mars
- Avril

### Jours les plus fréquentés
- Vendredi
- Dimanche
- Lundi
- Jeudi
- Samedi

### Jours les plus rentables
- Jeudi
- Vendredi
- Dimanche
- Lundi
- Mardi

---

## 📌 Conclusion

L’analyse montre que le café possède une activité globalement stable avec une répartition équilibrée des modes de consommation et des moyens de paiement.

Les revenus sont principalement générés par des produits à forte valeur comme les salades, tandis que les boissons représentent le plus gros volume de ventes.

Ce projet montre comment l’analyse de données permet de mieux comprendre les performances commerciales et le comportement des clients.

---
## 👤 Auteur

- DJAH ABOULHAYR Abacar Bounou
- Étudiant en Data Analysis