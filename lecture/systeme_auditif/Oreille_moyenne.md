
# Oreille moyenne

```{warning}
Page en cours de construction
```

L'**oreille moyenne** est composée à chacune de ses extrémités de membranes tendues : le **tympan** situé au fond du conduit auditif, et la **fenêtre ovale** qui mène à l'oreille interne. Les deux sont reliés par une série d'**osselets** -- connus pour être les plus petits os du corps humain : le **marteau**, l'**enclume**, et l'**étrier**. 

```{figure} SysAudExt_ME.JPG
---
name: SysAudExt_ME.JPG
alt: Systeme auditif externe - oreille moyenne
height: 400px
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
alt: Osselets
height: 400px
align: center
---
*Schéma de l'oreille moyenne. (Source: [Gray's Anatomy](https://commons.wikimedia.org/wiki/File:Gray919.png))*
```

## Réflexe stapédien 

De même que la pupille de notre œil peut adapter son diamètre en fonction de l'intensité lumineuse ambiante, notre oreille moyenne dispose d'un mécanisme visant à atténuer la transmission des sons de trop haute intensité, protégeant ainsi l'oreille interne, plus fragile. Le muscle de l'étrier est capable de se tendre de façon réflexe pour raidir et bloquer partiellement le système de levier décrit ci-dessus : on parle alors de **réflexe stapédien**. Ce réflexe se déclenche en l'espace de quelques dizaines de millisecondes lorsque le niveau de stimulation dépasse ~80-90 dB SPL (bien que ce seuil dépende de plusieurs facteurs), mais également en anticipation lorsque nous nous apprêtons à émettre un son -- puisque notre propre voix est particulièrement forte à nos oreilles.

## Modélisation de l'oreille moyenne

Hormis le réflexe stapédien, l'oreille moyenne se comporte comme un système passif, communiquant l'onde sonore à un milieu liquide. 

Comme pour l'oreille externe, nous modéliserons l'oreille moyenne par un simple filtre linéaire -- ce qui revient à faire l'hypothèse que le réflexe stapédien ne se déclenche pas. Ce filtre est représenté en rouge dans la figure suivante. On peut noter que le système des osselets présente lui aussi une résonance particulière, autour de 500-1000 Hz.

```{figure} middleear_filter.bmp
---
name: middleear_filter.bmp
alt: middle ear filter.bmp
height: 200px
align: center
---
*Approximation du filtre d’oreille moyenne (trait rouge) et externe + moyenne combinées (trait noir). (Lopez-Poveda and Meddis, 2001; Goode et al., 1994)*
```

Plutôt que de modéliser l'oreille externe et moyenne par deux filtres successifs, il est également possible de les rassembler en un seul (en noir sur la figure ci-dessus).

## Références

Lopez-Poveda, E. A., Meddis, R. (2001) A human nonlinear cochlear filterbank. Journal of the Acoustical Society of America Dec;110(6):3107-18. doi: 10.1121/1.1416197.

Goode, R., Killion, M.,Nakamura,  K., & Nishihara, S. (1994). New knowledge about the function of the human middle ear: development of an improved analog model. The American journal of otology, 15(2):145--154. 

