# Recalbox-blog

Theme : [material](https://github.com/brijeshb42/bitwiser-material)
Plugin-Trad : [Doc](https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin)
Travis-build : [kickster](https://github.com/nielsenramon/kickster) 

# Comment ajouter un article

* Forker le repo

* Le fichier doit être nommé : YYYY-MM-DD-Titre-du-sujet.md ->  2016-11-23-Titre-du-sujet.md 

* La tête du fichier doit comporter ces éléments :

	```
	---
	layout: post			
	color: purple
	title:  "Color Choices"
	date:   2016-11-13 00:00:00
	cover: /img/cover.jpg		// Important pour avoir une image associer au post
	---

	```

* Ajouter les images dans /img/

* Ajouter les articles en fonction de la langue dans _i18n/[en][fr]/_posts/2016-11-23-Titre-du-sujet.md

* Optionnel tester en local...

* Faire une pr sur la branche master 


La doc est minimaliste, des ajouts seront fait par la suite.
