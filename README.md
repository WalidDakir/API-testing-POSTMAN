# 🧪 Projet de Tests API - Gestion des Utilisateurs

Ce projet montre comment tester une API REST simulée pour la gestion des utilisateurs avec **Postman** et **JSON Server**.

## 🔧 Outils utilisés
- [Postman](https://www.postman.com/) : pour écrire et exécuter les requêtes API
- [JSON Server](https://github.com/typicode/json-server) : pour simuler une API REST (backend fake)
- JavaScript : utilisé dans les scripts de tests Postman

## 🔁 Fonctionnalités testées
- Création d'utilisateur (POST)
- Récupération de la liste des utilisateurs (GET)
- Récupération d'un utilisateur par ID (GET)
- Mise à jour des données utilisateur (PUT)
- Suppression d'utilisateur (DELETE)

## 📂 Fichiers du projet
- `db.json` : contient les données simulées (fake DB)
- `User_Management_Collection.json` : collection Postman des requêtes

## ▶️ Comment exécuter le projet

1. **Installer JSON Server**
   ```bash
   npm install -g json-server
   
   json-server --watch db.json --port 5000

L'API sera accessible ici : http://localhost:5000/users

