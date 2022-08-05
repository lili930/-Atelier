# Projet - Atelier
Ce projet contient principalement les trois parties, trois directions différentes que j'ai pris à travers le thème de " health care " dans le domaine médical.

## 1. Maladies cardiovasculaires
Le dataset se compose de 70 000 enregistrements de données de patients dans 12 caractéristiques, telles que l'âge, le sexe, la pression sanguine systolique, la pression sanguine diastolique, etc. La variable cible "cardio" est égale à 1, lorsque le patient a une maladie cardiovasculaire, sinon elle est égale à 0.

La tâche consiste à prédire la présence ou l'absence de maladie cardiovasculaire (MCV) à l'aide des résultats d'examen du patient. On construit les trois modèles en utilisant l'arbre de décision, random forest et KNN, et puis on les compare avec la courbe ROC, d'après la graphique, le meilleur modèle est la modèle KNN dans ce cas pour prédire la maladie cardiovasculaires avec un AUC étant 0.79.

## 2. Charges des patiens
Le jeu de données se compose de l'âge, du sexe, de l'IMC (indice de masse corporelle), des enfants, des fumeurs et de la région, qui sont des variables caractéristiques indépendantes, et des charges comme une variable numérique dépendante, donc on le prend comme la variable cible. On va prédire les coûts médicaux individuels facturés par l'assurance maladie.

On a construit quatre modèles à comparer, ils sont la regréssion linéaire, l'arbre de décision, Random forest et Gradient Boosting, comparé aux modèles de bagging, le modèle de Gradient boosting est meilleure avec une prédiction 89%, supérieur à la prédiction 87% de modèle Random forest.

## 3. Varicelle d'Hongrie
Cette base de données représente les situations de cases de varicelle des principales villes d'Hongrie de l'année 2005 à l'année 2015 en format des séries chronologiques. Après avoir fait l'analyse d'exploration des data, on a construit le modèle XgBoost pour mieux comprendre profondément les principles de Boosting.

On s'appuye ici sur les résultats de Mean square error (MSE) pour déterminer les prédictions du modèle, le résultat de total MSE est égale à 0.16, proche de 0，on peut donc dire que le modèle a été bien entraîné.



 
