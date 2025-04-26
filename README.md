# GenData
# 📦 Projet de Génération de Datasets et d'Images IA

Bienvenue dans notre application web combinant **génération de datasets** et **création d'images IA** !

## 🚀 Description du Projet

Notre application propose deux fonctionnalités principales accessibles après authentification :

1. **Génération de Dataset à partir d'une Description (Fluxx + Defocus)**  
   - L'utilisateur saisit une description comprenant :
     - Le **nombre de classes** souhaité.
     - Le **nom des classes**.
   - Le système génère automatiquement un **dataset structuré** (au format `.zip`) conforme aux standards de dataset d'images.

2. **Génération d'une Image à partir d'une Description Simple (Defocus uniquement)**  
   - L'utilisateur fournit une **courte description textuelle**.
   - Le modèle IA génère une **image unique et réaliste** correspondant à cette description.

## 🛠️ Technologies Utilisées

- **Frontend** : React.js
- **Backend** : Python (Flask / FastAPI ou autre)
- **Modèles IA** : 
  - **Fluxx** (génération avancée de datasets multi-classes)
  - **Defocus** (génération d'images à partir d'une description)

## 🔑 Fonctionnalités principales

- Authentification sécurisée des utilisateurs
- Interface intuitive pour entrer les descriptions
- Génération et téléchargement des datasets compressés (.zip)
- Visualisation et téléchargement des images générées
- Architecture frontend-backend séparée pour plus de modularité
