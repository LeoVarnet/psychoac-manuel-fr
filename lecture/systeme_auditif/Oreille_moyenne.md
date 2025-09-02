
# Oreille moyenne

L'**oreille moyenne** est composée à chacune de ses extrémités de membranes tendues : le **tympan** situé au fond du conduit auditif, et la **fenêtre ovale** qui mène à l'oreille interne. Les deux sont reliés par une série d'**osselets** -- connus pour être les plus petits os du corps humain : le **marteau**, l'**enclume**, et l'**étrier**. 

```{figure} SysAudExt_ME.JPG
---
name: SysAudExt_ME.JPG
alt: Même vue en coupe du systeme auditif externe humain qu'à la section précédente. L’oreille moyenne est mise en évidence en orange. Sont annotés le tympan, au fond du conduit auditif, les osselets (marteau, étrier et enclume) qui forment une sorte de levier allant appuyer contre une autre membrane, la fenêtre ronde.
width: 100%
align: center
---
*Schéma du système auditif périphérique mettant en évidence l’oreille moyenne. (Source : [Ivy Livingstone, Biodidac](https://omeka.uottawa.ca/biodidac/items/show/4603))*
```

## Rôle et fonctionnement de l'oreille moyenne 

La grande diversité des oreilles dans le règne animal se divise en deux grandes catégories : celles qui possèdent une oreille moyenne, et celles qui en sont dépourvues. Les premières, appelées "oreilles tympaniques" et présentes chez l'humain ainsi que de nombreux vertébrés et certains insectes, sont très sensibles et permettent de détecter des sons à grande distance. En revanche, les animaux sans oreille moyenne, comme les mouches, les moustiques et les abeilles, ne captent les sons qu'en champ proche, généralement à quelques centimètres de distance. La différence fondamentale est que, dans le premier cas, l'oreille moyenne permet de capter les variations de pression de l'air et de les amplifier en les transmettant à l'oreille interne, tandis que dans le second cas les cellules sensorielles sont directement exposées à l'air.

La fonction principale de l'oreille moyenne est donc de **convertir les vibrations de l'air parvenant au tympan en vibrations dans un liquide** au sein de l'oreille interne (la périlymphe). Si ce changement de milieu avait lieu directement, sans l'intermédiaire de l'oreille moyenne, il entraînerait une perte de 30 dB, soit 99.9% de la puissance du son, car la majeure partie de l'onde serait simplement réverbérée (comme on peut en faire l'expérience en écoutant, sous l'eau, des sons émis à l'extérieur de l'eau, qui nous parviennent de façon extrêmement atténuée). Ce système de transmission repose sur le principe du levier, et sur le rapport entre la large surface du tympan et la faible surface de la fenêtre ovale.

```{figure} Gray919.png
---
name: Gray919.png
alt: Illustration anatomique en noir et blanc représentant une vue détaillée de l’oreille moyenne, mettant en évidence les os de la chaîne des osselets.
width: 80%
align: center
---
*Schéma de l'oreille moyenne. (Source: [Gray's Anatomy](https://commons.wikimedia.org/wiki/File:Gray919.png))*
```

## Réflexe stapédien 

De même que la pupille de notre œil peut adapter son diamètre en fonction de l'intensité lumineuse ambiante, notre oreille moyenne dispose d'un mécanisme visant à atténuer la transmission des sons de trop haute intensité, protégeant ainsi l'oreille interne, plus fragile. Le muscle de l'étrier est capable de se tendre de façon réflexe pour raidir et bloquer partiellement le système de levier décrit ci-dessus : on parle alors de **réflexe stapédien**. Ce réflexe se déclenche en l'espace de quelques dizaines de millisecondes lorsque le niveau de stimulation dépasse ~80-90 dB SPL (bien que ce seuil dépende de plusieurs facteurs), mais également en anticipation lorsque nous nous apprêtons à émettre un son -- puisque notre propre voix est particulièrement forte à nos oreilles.

## Modéliser l'oreille moyenne

Hormis le réflexe stapédien, l'oreille moyenne se comporte comme un système passif, communiquant l'onde sonore à un milieu liquide. 

Comme pour l'oreille externe, nous modéliserons l'oreille moyenne par un simple filtre linéaire -- ce qui revient à faire l'hypothèse que le réflexe stapédien ne se déclenche pas. Ce filtre est représenté en rouge dans la figure suivante. On peut noter que le système des osselets présente lui aussi une résonance particulière, autour de 500-1000 Hz.

```{figure} middleear_filter.bmp
---
name: middleear_filter.bmp
alt: Ce graphique représente le gain (de -6 dB à +21 dB) en fonction de la fréquence (de 100 à 8000 Hz), avec une courbe rouge pointillée et une courbe noire. La courbe rouge est en forme de triangle avec un maximum à 800 Hz. La courbe noire suit le même profil, avec en addition des pics dans les hautes fréquences, correspondant aux pics du filtre d'oreille externe de la section précédente.
width: 80%
align: center
---
*Approximation du filtre d’oreille moyenne (trait rouge) et externe + moyenne combinées (trait noir) [[1](note1ormoy)]. (Lopez-Poveda and Meddis, 2001; Goode et al., 1994)*
```

Plutôt que de modéliser l'oreille externe et moyenne par deux filtres successifs, il est également possible de les rassembler en un seul (en noir sur la figure ci-dessus).

La figure suivante illustre l'effet de ce filtre sur le même son de brouhaha que précédemment.

```{figure} middle_ear_demo.bmp
---
name: middle_ear_demo.bmp
alt: L’image contient deux spectrogrammes placés côte à côte, représentant un signal audio sur 3 secondes. Le spectrogramme de droite est globalement moins lumineux que celui de gauche dans les hautes fréquences et dans les basses fréquences.
width: 100%
align: center
---
*Spectrogramme d’un brouhaha composé de 5 voix superposées, avant (gauche) et après (droite) passage par l’oreille externe et l'oreille moyenne. Cette figure a été obtenue par simulation grâce au filtre décrit ci-dessus*
```

## Notes

(note1ormoy)=

[1] Notez que le gain en dB doit être interprété avec précaution, car la fonction relie l'amplitude de l'onde en entrée au déplacement de l'étrier en sortie.

## Références

Lopez-Poveda, E. A., Meddis, R. (2001) A human nonlinear cochlear filterbank. Journal of the Acoustical Society of America Dec;110(6):3107-18. doi: 10.1121/1.1416197.

Goode, R., Killion, M.,Nakamura,  K., & Nishihara, S. (1994). New knowledge about the function of the human middle ear: development of an improved analog model. The American journal of otology, 15(2):145--154. 

