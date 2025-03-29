# Détection d'Émotions en Temps Réel avec OpenCV et TensorFlow

## Description
Ce projet utilise OpenCV pour la détection de visages en temps réel via une webcam, ainsi que TensorFlow et un modèle pré-entraîné pour la reconnaissance d'émotions. Le modèle est capable de prédire les émotions telles que la joie, la tristesse, la colère, etc., à partir des visages détectés.

## Fonctionnalités
- **Détection de visages** : Utilisation du classificateur en cascade Haar d'OpenCV pour détecter les visages dans une image capturée par une webcam.
- **Prédiction d'émotions** : Après la détection du visage, l'image du visage est passée à un modèle de classification des émotions pré-entraîné avec TensorFlow pour prédire l'émotion affichée.
- **Affichage en temps réel** : Le programme affiche la vidéo en temps réel avec des rectangles autour des visages détectés et l'émotion prédite affichée sur l'écran.

## Prérequis
Avant de commencer, assurez-vous d'avoir installé les dépendances suivantes :

- **Python 3.x**
- **OpenCV** : Pour la gestion des images et la détection de visages.
- **TensorFlow** : Pour charger le modèle de détection des émotions.
- **Keras** : Bibliothèque utilisée pour les modèles de réseaux neuronaux.

### Installation des dépendances
```bash
pip install opencv-python tensorflow numpy
