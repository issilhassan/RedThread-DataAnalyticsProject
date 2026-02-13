
# Dictionnaire de Données

Ce document décrit les datasets principaux utilisés dans le projet.

## Dataset : Churn_Modelling.csv

| Nom de la colonne | Type de données | Description | Valeurs possibles / Exemples |
| :--- | :--- | :--- | :--- |
| `RowNumber` | Entier | Index de ligne unique | 1, 2, 3, ... |
| `CustomerId` | Entier | Identifiant unique du client | 15634602, 15647311, ... |
| `Surname` | Chaîne de caractères | Nom de famille du client | "Hargrave", "Hill", ... |
| `CreditScore` | Entier | Score de crédit du client | 619, 608, ... |
| `Geography` | Chaîne de caractères | Pays de résidence du client | "France", "Spain", "Germany" |
| `Gender` | Chaîne de caractères | Sexe du client | "Male", "Female" |
| `Age` | Entier | Âge du client | 42, 41, ... |
| `Tenure` | Entier | Nombre d'années passées à la banque | 2, 1, ... |
| `Balance` | Décimal | Solde du compte bancaire | 0.00, 83807.86, ... |
| `NumOfProducts` | Entier | Nombre de produits bancaires détenus | 1, 2, ... |
| `HasCrCard` | Booléen (0/1) | Le client a-t-il une carte de crédit ? | 1 = Oui, 0 = Non |
| `IsActiveMember` | Booléen (0/1) | Le client est-il un membre actif ? | 1 = Oui, 0 = Non |
| `EstimatedSalary` | Décimal | Salaire estimé du client | 101348.88, 112542.58, ... |
| `Exited` | Booléen (0/1) | Le client a-t-il quitté la banque ? | **1 = Parti**, **0 = Resté** |

> **Note sur la variable cible :** `Exited` est la variable dépendante de notre analyse. Elle sera traitée comme une catégorie (Resté/Parti) dans Tableau et Python.

---

## Dataset : Bank-Customers-Demo.csv

*(À compléter selon la structure réelle de votre fichier)*
