
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
*Schéma du système auditif périphérique mettant en évidence l’oreille moyenne.*
```

## Rôle et fonctionnement de l'oreille moyenne 

La fonction principale de l'oreille moyenne est de **convertir les vibrations de l'air parvenant au tympan en vibrations dans un liquide** au sein de l'oreille interne (la périlymphe). Si ce changement de milieu avait lieu directement, sans l'intermédiaire de l'oreille moyenne, il entraînerait une perte de 30 dB, soit 99.9% de la puissance du son, car la majeure partie de l'onde serait simplement réverbérée (comme on peut en faire l'expérience en écoutant, sous l'eau, des sons émis à l'extérieur de l'eau, qui nous parviennent de façon extrêmement atténuée). Ce système de transmission repose sur le principe du levier, et sur le rapport entre la large surface du tympan et la faible surface de la fenêtre ovale.

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

De même que la pupille de notre œil peut adapter son diamètre en fonction de l'intensité lumineuse ambiante, notre oreille moyenne dispose d'un mécanisme visant à atténuer la transmission des sons de trop haute intensité, protégeant ainsi l'oreille interne, plus fragile. Le muscle de l'étrier est capables de se tendre de façon réflexe pour raidir et bloquer partiellement le système de levier décrit ci-dessus : on parle alors de **réflexe stapédien**. Ce réflexe se déclenche en l'espace de quelques dizaines de millisecondes lorsque le niveau de stimulation dépasse ~80-90 dB SPL (bien que ce seuil dépende de plusieurs facteurs), mais également en anticipation lorsque nous nous apprêtons à émettre un son -- puisque notre propre voix est particulièrement forte à nos oreilles.

## Modélisation de l'oreille moyenne

Hormis le réflexe stapédien, l'oreille moyenne se comporte comme un système passif, communiquant l'onde sonore à un milieu liquide. 

Comme pour l'oreille externe, nous modéliserons l'oreille moyenne par un simple filtre -- ce qui revient à faire l'hypothèse que le réflexe stapédien ne se déclenche pas.

```{figure} middleear_filter.bmp
---
name: middleear_filter.bmp
alt: middle ear filter.bmp
height: 200px
align: center
---
*Approximation du filtre d’oreille moyenne (trait rouge) et externe + moyenne combinées (trait noir). (Lopez-Poveda and Meddis, 2001; Goode et al., 1994)*
```



Modélisation par deux filtres successifs : filtre d’oreille externe / filtre d’oreille moyenne 

Modélisation par un seul filtre d’oreille externe-moyenne

## Références

Lopez-Poveda, E. A., Johannesen, P. T., Pérez-González, P., Blanco, J. L., Kalluri, S., & Edwards, B. (2017). Predictors of Hearing-Aid Outcomes. Trends in Hearing, 21, 2331216517730526. https://doi.org/10.1177/2331216517730526

Goode, R., Killion, M.,Nakamura,  K., & Nishihara, S. (1994). New knowledge about the function of the human middle ear: development of an improved analog model. The American journal of otology, 15(2):145--154. 

