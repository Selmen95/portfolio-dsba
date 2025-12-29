# 📊 CryptoPortfolio  
**Projet Python modulaire – Développement incrémental (v0 / v1 / v2 / v3)**

## 1. Introduction

**CryptoPortfolio** est une application de gestion et d’analyse de portefeuille de cryptomonnaies.  
Le projet a été réalisé dans le cadre d’un enseignement de **programmation Python et génie logiciel**, avec pour objectif de concevoir et implémenter une application **non triviale**, en mettant l’accent sur l’analyse du problème, la conception logicielle, la modularité et la qualité du code.

Le développement du projet suit une **approche incrémentale**, structurée en plusieurs versions successives (**v0, v1, v2, v3**), toutes exécutables et illustrant l’évolution progressive de l’application.

---

## 2. Problématique et objectifs

La gestion d’un portefeuille de cryptomonnaies implique :
- le suivi des actifs détenus,
- l’accès à des données de marché,
- l’analyse de la valeur et de la répartition du portefeuille.

Les objectifs du projet sont les suivants :

- Modéliser le problème de la gestion d’un portefeuille crypto
- Concevoir une architecture logicielle **claire, modulaire et évolutive**
- Implémenter une application en **Python**, respectant les bonnes pratiques
- Mettre en œuvre un **développement incrémental** (V0 → V1 → V2 → V3)
- Fournir une application fonctionnelle et documentée

---

## 3. Contraintes techniques respectées

Le projet respecte les contraintes imposées par la consigne :

- Application développée principalement en **Python**
- Code réparti sur **plusieurs fichiers et modules**
- Respect des bonnes pratiques :
  - PEP 8
  - docstrings pour les classes et fonctions publiques
  - commentaires explicatifs
- Utilisation d’outils adaptés selon les versions :
  - interface en ligne de commande (CLI)
  - persistance des données
  - appels à des API externes
  - interface web en version finale

---

## 4. Organisation du projet

```text
portfolio-dsba/
├── v0/
├── v1/
├── v2/
├── v3/
├── src/
├── README.md
├── REPORT.md
├── portfolio.json
├── package.json
└── requirements.txt
````

* `v0/`, `v1/`, `v2/`, `v3/` : versions successives et exécutables du projet
* `src/` : code source principal
* `portfolio.json` : données du portefeuille
* `REPORT.md` : rapport détaillé du projet

---

## 5. Développement incrémental

### 🔹 Version v0 – MVP

* Mise en place du squelette du projet
* Modélisation des entités principales (portefeuille, actifs)
* Fonctionnalités minimales de gestion
* Première version exécutable

### 🔹 Version v1 – Extensions fonctionnelles

* Ajout de nouvelles fonctionnalités
* Amélioration de la structure modulaire
* Gestion plus avancée des données
* Extension de l’interface utilisateur en ligne de commande

### 🔹 Version v2 – Robustesse et enrichissement

* Amélioration de la logique métier
* Gestion des erreurs
* Ajout de fonctionnalités d’analyse
* Préparation à l’intégration de services externes

### 🔹 Version v3 – Version finale

* Intégration de données de marché via des API externes
* Ajout d’une interface web pour la visualisation
* Amélioration de l’expérience utilisateur
* Version la plus complète et la plus robuste du projet

Chaque version **s’appuie sur la précédente**, sans réécriture complète du code.

---

## 6. Technologies utilisées

* **Python** : logique métier, gestion du portefeuille
* **JavaScript / React** : interface web (version finale)
* **API externes** : récupération de données de marché
* **Outils et bibliothèques** :

  * argparse (CLI)
  * JSON (persistance des données)
  * ESLint, outils de build frontend

---

## 7. Installation

### Prérequis

* **Python 3.9 ou supérieur**
* **Node.js** (pour l’interface web en v3)

### Installation des dépendances Python

```bash
pip install -r requirements.txt
```

### Installation des dépendances frontend (v3)

```bash
npm install
```

---

## 8. Exécution

Chaque version peut être lancée indépendamment.

### Exemple (version finale) :

```bash
cd v3
python main.py
```

Pour lancer l’interface web :

```bash
npm run dev
```

---

## 9. Données

Les données du portefeuille sont stockées dans le fichier :

```text
portfolio.json
```

Ce fichier est utilisé pour la persistance et l’analyse des actifs.

---

## 10. Rapport

Un rapport détaillé est fourni dans le fichier :

```text
REPORT.md
```

Il présente :

* le contexte et la problématique
* les spécifications informelles
* le plan de développement
* l’architecture logicielle
* l’évaluation des différentes versions
* les limites et pistes d’amélioration

Conformément aux consignes, le rapport ne contient pas de listing complet de code et renvoie aux docstrings lorsque nécessaire.

---

## 11. Auteurs

Projet réalisé par un **groupe de 3 étudiants**,
dans le cadre d’un cours de **programmation Python / génie logiciel**.

---

## 12. Conclusion

Ce projet illustre une démarche complète de développement logiciel :

* analyse du problème,
* conception modulaire,
* implémentation incrémentale,
* documentation et réflexion critique.

Il met en évidence l’importance de la structure, de la lisibilité et de l’évolutivité dans un projet Python de taille intermédiaire.
