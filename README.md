

# Classification-textes-et-images

En tant que Data Scientist au sein de l'entreprise "Place de marché", j'ai été **chargée d'étudier la faisabilité d'un moteur de classification d'articles basé sur des images et des descriptions**. 

L'objectif est **d'automatiser l'attribution des catégories aux articles**, améliorant ainsi l'expérience utilisateur des vendeurs et des acheteurs.

Ma mission consiste à **analyser le jeu de données** en effectuant un prétraitement des descriptions et des images, une **réduction de dimension**, puis un **clustering**. 

Les résultats de la réduction de dimension et du clustering seront présentés sous forme de graphiques en deux dimensions, accompagnés d'un **calcul de similarité entre les catégories réelles et les clusters**. Ces résultats démontreront que les caractéristiques extraites permettent de regrouper des produits de même catégorie.

Plusieurs approches de modélisation :

**Extraction des features texte :**

* Deux approches de type "bag-of-words" : **comptage simple de mots et Tf-idf**.
* Une approche de type word/sentence embedding avec **Word2Ve**.
* Une approche de type word/sentence embedding avec **BERT**.
* Une approche de type word/sentence embedding avec **USE** (Universal Sentence Encoder).

**Extraction des features image :**

* Un algorithme de type **SIF**.
* Un algorithme de type **CNN Transfer Learning**.

L'objectif est de **démontrer que nous pouvons regrouper automatiquement des produits de même catégorie en utilisant ces approches de modélisation**.
