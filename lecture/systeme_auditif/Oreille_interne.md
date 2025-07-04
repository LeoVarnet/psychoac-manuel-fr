# Oreille interne

```{warning}
Page en cours de construction
```

L'oreille interne constitue l'élément central du système auditif périphérique. Tandis que l'oreille externe et moyenne peut se réduire, en première approximation, à un simple filtre, l'oreille interne réalise plusieurs transformations essentielles des vibrations qui lui parviennent par la fenêtre ovale. Sa fonction est de d'analyser les sons en fréquence, mais également d'amplifier les sons faibles et de compresser les sons forts. Enfin, elle réalise une transduction, en convertissant les vibrations physiques en signaux électriques.

L'oreille interne se décompose en trois parties : 
- la cochlée, petit bijou de l'évolution qui comme nous le verrons est lui-même constitué de plusieurs éléments en interaction
- le nerf auditif, qui assure la jonction entre la cochlée et le système auditif central
- le système vestibulaire. Ce dernier ne sera pas traité ici puisqu'il ne contribue pas à l'audition. 

```{figure} SysAudExt_IE.JPG
---
name: SysAudExt_IE.JPG
alt: Systeme auditif externe - oreille interne 
height: 400px
align: center
---
*Schéma du système auditif périphérique mettant en évidence l’oreille interne. (Source : [Ivy Livingstone, Biodidac](https://omeka.uottawa.ca/biodidac/items/show/4603))*
```

## La cochlée 

La cochlée est l’organe qui réalise la décomposition du son en fréquence, c'est-à-dire son analyse spectrale. Sans celle-ci, notre audition serait similaire à celle des insectes qui sont en mesure de percevoir les sons mais non de distinguer les aigus des graves.

Joseph-Guichard Du Verney (1648-1730) Traité de l'organe de l'ouie

Hermann von Helmholtz (1821 –1894) + resonnateurs

Georg von Békésy (1899 –1972)


L’onde sonore parcourt la cochlée et fait vibrer la membrane basilaire. Une fréquence donnée excite une région particulière de la membrane : codage tonotopique (= codage de place).

Mesurer la tonotopie et la sélectivité fréquentielle de la cochlée :
Tuning curves : chaque courbe correspondant à une position sur la membrane basilaire. On mesure l’excitation de la cochlée en réponse à une intensité acoustique donnée.

Une position sur la cochlée correspond à une fréquence d’accordage (tuning frequency) particulière. Chaque fréquence excite aussi les régions adjacentes : la sélectivité fréquentielle est limitée. 

Mapping quasi-logarithmique entre fréquence d’accordage et position sur la membrane basilaire.

## Modéliser la cochlée (part 1)

Le banc de filtres gammatones : 
Banc de filtres passe-bande espacés quasi-logarithmiquement entre 20 Hz et 20.000 Hz.
Largeur des filtres proportionnelle à la fréquence centrale (i.e. facteur de qualité constant)

Le pattern d’excitation

Représentation de l’amplitude en sortie d’un banc de filtres gammatone : Pour un stimulus donné, niveau de sortie de chaque gammatone en fonction de sa fréquence d’accordage

Une modélisation de l’excitation de la cochlée par le stim

Calcul du pattern d’excitation en réponse à un ton pur à 1 kHz

Quelques propriétés : 
Le pattern d’excitation d’un ton pur a une certaine largeur (= résolution en fréquence du système auditif humain)
Il est asymétrique (= upward spread of excitation) car la largeur des filtres gammatone est proportionnelle à leur fréquence.
Cette asymétrie est plus marquée pour les sons plus forts.
La largeur (= résolution) croît avec la fréquence.
Par conséquent, dans un complexe harmonique, seules les premières harmoniques sont clairement séparées sur le pattern d’excitation (= « harmoniques résolues »)
Au contraire, dans les hautes fréquences, les harmoniques sont non-résolues : on ne les distingue plus sur le pattern d’excitation.

## Cellules cilliées




