# annotation_project
Ce projet convertit des masques binaires de segmentation en fichiers .txt contient labels

# Segmentation to Polygon Labels

Ce projet convertit des masques binaires de segmentation en fichiers de polygones compatibles avec des frameworks d'annotation.

## But du Projet

Transformer des masques de segmentation en coordonnées de polygones normalisées dans des fichiers txt  pour des tâches de labellisation dans le domaine de la vision par ordinateur.

## Technologies Utilisées

- **Python** : Langage principal.
- **OpenCV** : Pour le traitement des images et l'extraction des contours.
- **Google Drive** : Pour gérer les fichiers d'entrée et de sortie via Google Colab.

## Comment l'Exécuter

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/yasmine1log/annotation_project
   cd annotation_project

2. Assurez-vous que les répertoires masks et labels existent dans votre Google Drive

3. Exécutez le script dans Google Colab: 

Chargez le fichier annotation_data.py

Modifiez les chemins d'accès input_dir et output_dir pour qu'ils pointent vers vos répertoires sur Google Drive.

Exécutez le script.


## Résultats

Fichiers texte générés : Chaque masque génère un fichier .txt contenant les coordonnées du polygone.
