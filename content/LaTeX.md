---
title: "LaTeX"
---

# définition

(se prononce lateque)
programme d'édition de textes (pas seulement scientifiques) né dans les années 80. 
Ce langage de programmation orienté édition est l'outil d'édition de référence dans plusieurs disciplines scientifiques. Il est également utilisé par les éditeurs dans le domaine universitaire. 

# inclusion d'environnements LaTeX dans Obsidian

Le markdown est une syntaxe souple qui permet d'inclure du HTML et d'autres langages tels que le $\LaTeX$ au moyen d'un paquet appelé Mathjax. Ce paquet a été installé en 2021 dans les livraisons ultérieures d'Obsidian.

Pour inclure une commande dans ce langage, il faut l'entourer avec des dollars (\$)

Par exemple, pour représenter LaTeX avec la graphie propre à ce langage : 

\$\LaTeX\$

cela donne : $\LaTeX$

\$67\\sqrt{\\prod_{67}^{4}}\\Rightarrow \\mathrm{C}_{56}^{'}\$

donne :

$67\sqrt{\prod_{67}^{4}}\Rightarrow \mathrm{C}_{56}^{'}$

pour centrer la formule, il faut redoubler les \$

$$67\sqrt{\prod_{67}^{4}}\Rightarrow \mathrm{C}_{56}^{'}$$

Utiliser $\LaTeX$ pour réaliser les exposants : 

- le mebioctet ou Mi parfois écrit Mio correspond à \$2\^\{20\}\$ octets 
- le gibioctets ou Gi parfois écrit Gio correspond à   \$2\^\{30\}\$ octets

donne :

- le mebioctet ou Mi parfois écrit Mio correspond à $2^{20}$ octets 
- le gibioctets ou Gi parfois écrit Gio correspond à   $2^{30}$ octets

#### Formules chimiques

La formule de l'eau peut-être notée de la manière suivante : \$\ce\{H2O}\$ cela donne $\ce{H2O}$

Etat d'oxidation :  \$\ce{Fe^{II}Fe^{III}2O4}\$ 
donne : $\ce{Fe^{II}Fe^{III}2O4}$

# Gestion des polices
le [[package\|package]] fontspec permet d'ajouter des polices
la commande setmainfont peut aller chercher des polices chargées dans le système de l'utilisateur ([source](https://twitter.com/LaurentDietric2/status/1489141309961080832))

# Gestion des références bibliographiques

voir [[bibtex\|bibtex]]