# intel-image-classification
Utilisation du deep learning pour reconnaître automatiquement des environnements sur images satellites (urbanisme, climat, logistique).


# Classification d’images satellites – Projet DU Data Analytics (Paris 1 Panthéon-Sorbonne)

Ce projet a été réalisé dans le cadre du **Diplôme Universitaire Data Analytics** à l’Université Paris 1 Panthéon-Sorbonne.  
Il repose sur le dataset **Intel Image Classification**, qui contient environ 25 000 images satellites réparties en 6 catégories :  

- Buildings  
- Forest  
- Glacier  
- Mountain  
- Sea  
- Street  

---

## 🎯 Sujet du projet

L’objectif est de construire un modèle de **classification d’images** capable de reconnaître automatiquement le type d’environnement présent sur une image satellite.  

Un tel projet a de nombreuses applications dans le monde professionnel et académique :  

- **Urbanisme et aménagement du territoire** : suivi de l’expansion urbaine et détection des zones de construction.  
- **Environnement** : surveillance des forêts, glaciers et littoraux dans le cadre du changement climatique.  
- **Transport et logistique** : analyse automatique des routes et infrastructures pour optimiser les flux.  
- **Cartographie** : mise à jour de cartes numériques à grande échelle grâce à l’IA.  

Ce travail illustre ainsi comment les techniques de **vision par ordinateur** et de **deep learning** peuvent être mises au service d’analyses stratégiques pour les entreprises et les institutions publiques.  

---

## 🛠️ Méthodologie

1. **Préparation des données**  
   - Chargement et exploration des images.  
   - Normalisation et mise à l’échelle des données.  
   - Séparation entre ensembles d’entraînement, validation et test.  

2. **Modélisation**  
   - Utilisation de réseaux de neurones convolutionnels (**CNN**) pour la reconnaissance d’images.  
   - Tests de plusieurs architectures (modèle simple vs architectures pré-entraînées comme VGG, ResNet).  

3. **Évaluation**  
   - Mesure des performances avec l’accuracy et la matrice de confusion.  
   - Analyse des classes les mieux et les moins bien prédites.  

4. **Résultats**  
   - Visualisation des courbes d’apprentissage (loss/accuracy).  
   - Exemple de prédictions correctes et erreurs de classification.  

---

## 📂 Organisation du projet

- `notebooks/analysis.ipynb` : Notebook principal avec code, visualisations et résultats.  
- `data/` : Contiendra le dataset téléchargé.  
- `README.md` : Présentation du projet.  
- `requirements.txt` : Liste des librairies utilisées.  

---

## 🚀 Lancer le projet

1. Télécharger le dataset directement sur Kaggle :  
   [Intel Image Classification Dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  

2. Extraire les données dans le dossier `data/`.  

3. Installer les dépendances nécessaires (voir `requirements.txt`).  

4. Lancer le notebook Jupyter et exécuter les cellules pour reproduire l’analyse.  

---

## 🔗 Ressources

- Dataset Kaggle : [Intel Image Classification](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)  
- Introduction aux CNN : [https://cs231n.github.io/convolutional-networks/](https://cs231n.github.io/convolutional-networks/)  

---

## 👩‍🎓 Auteur

Projet réalisé par Diop Alioune dans le cadre du **DU Data Analytics – Université Paris 1 Panthéon-Sorbonne**.  
