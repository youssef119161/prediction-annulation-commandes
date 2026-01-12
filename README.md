# Prédiction de l'annulation des commandes

## 📌 Objectif du projet
Éviter les pertes d'argent en détectant les commandes susceptibles d'être annulées.

## 🎯 Méthodologie
- Modèle utilisé : **Régression Logistique**
- Analyse de l'historique de chaque client et des détails de la commande actuelle
- Calcul d'une probabilité de risque (en %) qu'une commande soit annulée

## 💡 But pratique
Si la probabilité est trop élevée, la commande est signalée pour vérification manuelle ou rejet, afin d'économiser les frais d'envoi et de retour.

## 🛠️ Librairies utilisées
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn (si visualisations)

## 📂 Contenu du projet
- `notebook.ipynb` → notebook principal
- `data/orders.csv` → dataset
- `models/logistic_model.pkl` → modèle sauvegardé (optionnel)
- `images/` → graphiques et visualisations

## 🚀 Comment exécuter
1. Cloner le repository
2. Installer les librairies
