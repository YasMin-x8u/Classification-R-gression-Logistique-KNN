#Classification : Régression Logistique & KNN
### Dataset : Breast Cancer Wisconsin


---

## Description

La classification binaire de tumeurs mammaires (malignes / bénignes) à l'aide du dataset **Breast Cancer Wisconsin** fourni par `scikit-learn`. Deux algorithmes sont implémentés et comparés : la **Régression Logistique** et le **K-Nearest Neighbors (KNN)**.

---

## StructureP

| Exercice | Contenu |
|----------|---------|
| **Exercice 1** | Chargement et exploration du dataset (statistiques, visualisations, corrélations) |
| **Exercice 2** | Implémentation manuelle de la régression logistique (sigmoid, descente de gradient, fonction de coût) + modèle scikit-learn |
| **Exercice 3** | Entraînement KNN, test de plusieurs valeurs de K, sélection du K optimal |
| **Exercice 4** | Évaluation : matrices de confusion, métriques manuelles (accuracy, precision, recall, F1), classification report |

---

## Prérequis

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

---

## Exécution

```bash
python TP7_breast_cancer.py
```

---

## Résultats principaux

- **Régression Logistique** : accuracy ~97%
- **KNN (K optimal)** : accuracy ~96%
- Métrique prioritaire : **Recall de la classe maligne (0)** — minimiser les faux négatifs est critique dans un contexte médical.

---

## Bibliothèques utilisées

- `scikit-learn` — modèles ML, métriques, preprocessing
- `numpy` / `pandas` — manipulation des données
- `matplotlib` / `seaborn` — visualisations
