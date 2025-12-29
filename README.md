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
