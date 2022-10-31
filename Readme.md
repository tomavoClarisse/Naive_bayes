##### Readme 

## La méthode Naive Bayes


La méthode naive bayes est une méthode de classification supervisée qui permet de trouver la classe d'une observation. Pour bien l'aborder, il est important de savoir ce qu'est colonnes ou variables explicatives et la colonne à prdire ou variable expliquer Ici, lorsque nous utilisons le mot classe de la variable dxpliquer, nous ferons réferences aux différentes valeurs de la variables expliquer Les classes d'une variable expliquer sont les différentes valeurs de la variable expliqué. Dans notre contexte, une obseravtion est une tuple de valeur pour les variables explicatives dans un ordre.

Fonctionnement

L'idéale est de répartir ce jeu de données de sorte à avoir un sous ensemble de ce jeu de données comme jeu de donnée d'entrainementn(échantillonnage d'apprentissage) et un autre sous ensemble de ce jeu de données comme echantillonage de test.

Si le jeu de données est très petit, nous pouvons tout le prendre comme jeu de donnée qui va subir d'entrainement (ou d'apprentissage)

Nous ferons souvent la répartition avec sklearn.model_selection import train_test_split

On prend une observation, et on calcule la probabilité pour qu'elle appartienne à chaque élément

## Comment manier et bien comprendre ce bout de code, qui crée un Model Naive Bayes GAUSSIAN
Il faut avoir un jeu de données (qui peut etre d'extension cvs, importer depuis une bdd)
Il faut que la variable que vous voulez expliquez soit quantitative.
Une Variable est dite expliquer, lorsque c'est sa valeur que nous predisons lorsqu'on nous fournissons un ensemble de valeur pour les parametres de notre modele.
Avoir un jeu de données avec un nombre de ligne un peu important
Bien comprendre son jeu de données