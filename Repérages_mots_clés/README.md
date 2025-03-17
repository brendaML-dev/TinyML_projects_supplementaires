# Repérage de mots-clés avec Edge Impulse

Ce projet utilise l'apprentissage automatique pour créer un système capable de reconnaître des événements audibles, en particulier des mots-clés, grâce à la classification audio. Il fonctionne de manière similaire à "Hey Siri" ou "OK Google" et permet de détecter des mots-clés même en présence de bruit de fond.


# Objectifs du projet

Collecter des données audio à partir d'un microphone de téléphone connecté à Edge impulse.

Traiter les signaux audio pour extraire les informations utiles sur Edge impulse.

Entraîner un modèle de réseau neuronal profond avec Edge Impulse.

Déployer le modèle sur un dispositif embarqué (téléphone).

Tester et évaluer la reconnaissance des mots-clés en temps réel.


# Matériel et outils utilisés

Appareil de capture audio : Smartphone (Edge Impulse Mobile Client)

Plateforme d'apprentissage : Edge Impulse


# Principales 

# 1. Collecte des données audio

Utilisation de l'application Edge Impulse Mobile Client pour enregistrer des échantillons de mots-clés.

Capture des données en plusieurs sessions pour obtenir un ensemble de données varié.

Stockage des fichiers audio au format .wav.


# 2. Prétraitement et extraction de caractéristiques

Conversion des fichiers audio en spectrogrammes.

Réduction du bruit et normalisation des données.

Division du jeu de données en ensembles d'entraînement et de test.


# 3. Entraînement du modèle

Chargement des données sur Edge Impulse.

Conception d'une impulsion avec un bloc de traitement du signal et un classificateur neuronal.

Définition des hyperparamètres (nombre d'époques, taux d'apprentissage, etc.).

Entraînement et évaluation du modèle.


# 4. Déploiement du modèle

Test du modèle en temps réel avec un microphone intégré via l'application Edge Impulse Mobile Client.
