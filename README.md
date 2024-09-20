# Skin Lens

## Description
Application Skin Lens qui permet de capturer une photo via webcam et de l'analyser en utilisant un modèle PyTorch pour la détection d'anomalies cutanées.

## Structure
- **Frontend** : Photomaton en HTML/CSS/JS pour capturer des photos et interagir avec le backend.
- **Backend** : API Flask pour analyser les photos avec un modèle PyTorch.

## Installation
1. Clonez le dépôt.
2. Installez les dépendances Python :
pip install -r backend/requirements.txt

3. Lancez le serveur Flask :
4. Ouvrez le fichier `frontend/index.html` dans un navigateur.
5. Utilisez l'interface pour capturer des photos et les analyser.

## Déploiement sur Google Cloud Platform
- Le backend peut être déployé sur **Google Cloud Run** ou **App Engine**.
- Utilisez **Google Cloud Storage** pour stocker des images si nécessaire.
"# skinlens" 
