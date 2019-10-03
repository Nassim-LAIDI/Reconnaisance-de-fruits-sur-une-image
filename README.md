# Reconnaisance-de-fruits-sur-une-image
_____________________________________***_______________________________


Ce projet porte sur la reconnaissance de fruits sur une image.

J’ai traité un problème de classification multi-classes, parce que le réseau de neurones avec lequel j’ai utilisé mon système doit reconnaitre plusieurs types de fruits dans un panier.

Pour le jeu de données avec lequel j’ai travaillé une partie je l’ai extraite de la plateforme web pour les sciences des données google Image.

Pour cela j’ai utilisé une fonction de scraping sous PyCharm qui est un environnement de développement intégré en Python et avec l'aide de la bibliothèque python beautifulSoup. 

Pour les fruits j’ai choisi de travailler avec (Banane, Pomme, Ananas) pour cela nous avons parcouru la base de données et nous avons scrapper les données souhaitées sur des fchiers en locals spécifques pour chaque type de fruit; ajoutant à la base de la plateforme j’ai aussi fait le scrapping sur des google Images contenant des images de fruits. 

En faisant le scrapping des données sur Google j'ai rencontré un légé soucie de bruit qui pourra affecter l'apprentissage de mon algorithme de Deep Learning, j'ai remédié à ce problème grâce à un filtre que j’ai mis en place qui trie les images récoltées avec des mots-clés sur l'attribut (alt) de l'image.

