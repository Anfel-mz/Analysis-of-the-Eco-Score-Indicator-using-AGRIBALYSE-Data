# Analyse Eco-Score

Ce projet a pour but d'analyser l'impact écologique des aliments à l'aide de l'indicateur Eco-Score. 
Pour cela, on utilise les données de la base de données AGRIBALYSE pour évaluer chaque aliment de l'ensemble A selon 16 critères différents. Chaque aliment est alors représenté sous la forme d'un tuple de 16 éléments, où chaque élément correspond à la valeur de l'aliment pour un critère donné.

Voici la partie que vous pouvez ajouter à votre README pour les fonctionnalités du projet :

## Fonctionnalités
Le programme permet de réaliser les fonctionnalités suivantes :

- **Calcul de l'eco-score** : À partir des données de la base de données AGRIBALYSE, le programme calcule l'eco-score de chaque aliment de l'ensemble A en utilisant une moyenne pondérée des 16 critères, normalisée à l'aide d'une formule mathématique et ajustée avec des bonus-malus.
- **Classification des aliments** : Le programme permet de classer les aliments de l'ensemble A selon différents critères 
- **Comparaison des aliments** : Le programme permet de comparer deux aliments de l'ensemble A selon un ou plusieurs critères.
- **Visualisation des données** : Le programme permet de visualiser les données pour mieux comprendre les relations entre les différents critères.

## Pré-requis
* Python 3.8
* Bibliothèque NumPy, Pandas, google.colab, Matplotlib et mip

## Installation
- Téléchargez le fichier AGRIBALYSE3.1_partie_agriculture_conv.csv depuis le site de AGRIBALYSE (https://agribalyse.ademe.fr/telecharger-les-donnees) et mettez le dans votre drive
- Installez les dépendances nécessaires : pip install mip

## Contributeurs
* MAZOUZ Anfel
* MOUSSA Eya
* RABIARIVELO Mbolatiana

