---
{"dg-publish":true,"permalink":"/pandoc/"}
---



Pandoc (https://pandoc.org) est un logiciel libre, développé par John McFarlane qui permet de convertir des fichiers écrits dans une multitude de formats différents vers une multitude d'autres formats. 

Attention, si Pandoc peut bien convertir des textes en PDF, la réciproque n'est pas vraie. 
Pour cela il faut utiliser un logiciel propriétaire, du type Adobe pro ou Foxit. 

Pour savoir comment utiliser Pandoc en ligne de commande pour convertir une note dans un autre format depuis le terminal, voir [[Consignes]]

Il est possible d'utiliser [Pandoc en tant que plugin dans Obsidian](https://github.com/OliverBalfour/obsidian-pandoc) pour convertir rapidement des notes dans le format voulu (opendocument, word, PDF) 
Pour une conversion en PDF, on peut préférer convertir la note en utilisant une version de LaTeX préalablement installée sur son ordinateur. 
Pandoc Plugin permet de paramétrer cette installation pour que la conversion se fasse bien. 
Une fois qu'on a entraîné les arguments concernant les sources pour la biblio et la feuille de style ainsi que le parseur (citeproc) et le moteur utilisé (pdflatex), la conversion d'un texte en markdown en PDF avec une biblio correctement formatée se fait en un clic. 

![](img/usr/images/pandoc_plugin.png)
