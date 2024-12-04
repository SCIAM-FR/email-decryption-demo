# Déchiffrement d'emails avec Python

Ce projet a pour but de déchiffrer des emails chiffrés avec une clé publique RSA.

- [Déchiffrement d'emails avec Python](#déchiffrement-demails-avec-python)
  - [Installation](#installation)
  - [Utilisation](#utilisation)
  - [Contribution](#contribution)

## Installation

Pour installer les dépendances, nous vous conseillons d'utiliser un environnement virtuel. Chez
SCIAM, nous utilisons généralement conda pour gérer nos environnements virtuels. Voici les commandes
à exécuter :

```bash
conda create -y -n decrypt-emails-py311 python=3.11
conda activate decrypt-emails-py311
pip install -r requirements.txt
```

## Utilisation

Ce repository contient un notebook Jupyter `email_decryption.ipynb` qui vous permettra de'étudier en
détail les différentes méthodes de déchiffrement d'un email. Lancer le notebook avec VS Code et
l'environnement créé devrait être largement suffisant.

## Contribution
