# projet-tal1
explication du résultats d'embedding: 
Les résultats sont les représentations vectorielles des tweets après avoir été encodées par le modèle BERT. Chaque tweet est représenté par un tenseur de nombres réels. le premier tweet de la première paire encodée pour les données d'entraînement est représenté par un tenseur de dimension 1x768.
explication de tenseur :
Il s'agit d'un tenseur de 1 ligne et 768 colonnes, ce qui signifie qu'il représente un seul tweet avec 768 caractéristiques.
Chaque nombre dans le tenseur est une valeur réelle qui représente une caractéristique particulière du tweet, apprise par le modèle BERT lors de l'entraînement.
Ces caractéristiques peuvent inclure des informations telles que le contexte sémantique, la syntaxe et d'autres aspects du texte.
Les valeurs dans le tenseur sont des nombres réels qui peuvent être positifs ou négatifs, et leur magnitude et leur signe sont significatifs pour la représentation du tweet.
-Ce qui permet au modèle d'apprentissage automatique de comprendre et de comparer leur contenu de manière significative.
