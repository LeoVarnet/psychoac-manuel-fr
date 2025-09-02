
# Introduction

Abandonnons temporairement les expériences de psychoacoustique pour nous intéresser à la biologie de l'audition humaine. Ce second chapitre vise à donner un aperçu global de la hiérarchie de traitements réalisés par le système auditif humain depuis l'oreille externe jusqu'au cortex auditif. Ceci nous permettra de comprendre certains phénomènes perceptifs que nous rencontrerons dans la suite du cours, et d'introduire certains concepts importants, notamment les notions de pattern d'excitation, de tonotopie et de codage temporel, et de représentation multirésolution. 

## Ouvrir la boîte noire

Comme on l'a vu, la spécificité de l'approche psychophysique consiste à considérer l'esprit humain comme une boîte noire inviolable, et de mesurer la relation qui lie le stimulus perçu au comportement observable. Ce cadre béhavioriste, bien que puissant, n'est pas suffisant pour démêler la grande complexité des traitements auditifs. C'est la raison pour laquelle il est nécessaire de le compléter par une description des systèmes biologiques impliqués. La psychoacoustique demeure néanmoins notre boussole dans l'exploration de l'audition humaine et notre seule source d'information quant au contenu des représentations mentales : aucune mesure de neurophysiologie ne peut nous permettre de déduire de façon définitive ce que le sujet perçoit réellement. Démontrer qu'une certaine caractéristique acoustique engendre une réponse particulière dans le cerveau ne signifie pas que cette réponse a, *in fine*, un quelconque effet sur les sensations éprouvées par l'individu. En revanche, cette observation peut informer les modèles du système auditif et donc notre interprétation des phénomènes psychoacoustiques.

S'appuyant sur une proposition de David Marr dans l'introduction philosophique de son ouvrage *Vision*, les scientifiques travaillant sur la perception et la cognition distinguent habituellement **trois niveaux de description** complémentaires pour appréhender les systèmes qu'ils étudient :

> Un système de traitement de l'information doit être compris à différents niveaux avant qu'il soit possible d'affirmer qu'on l'a compris parfaitement. À une extrémité, le niveau supérieur correspond à la théorie computationelle du système qui caractérise les performances de celui-ci en termes d'association entre une forme d'information et une autre. Les propriétés abstraites de cette association sont définies précisément et leur adéquation pour la tâche réalisée par le système est démontrée. Au centre correspond l'implémentation algorithmique, le choix d'une représentation pour l'entrée et la sortie, et l'algorithme qui permet de transformer la première en la seconde. À l'autre extrémité on trouve les détails de la réalisation physique de l'algorithme -- le *hardware* en quelque sorte. Ces trois niveaux sont couplés, mais de façon assez souple. Le choix d'un algorithme, par exemple, est contraint par la fonction qu'il doit réaliser et par le hardware avec lequel il est construit. Mais un large éventail de choix demeure disponible, et chaque niveau de description implique des problématiques assez indépendantes des deux autres. *(Marr, Vision, 1982)*

Pour l'exprimer dans les termes de Marr, ce cours s'intéresse en premier lieu à l'explication "de niveau supérieur" de la perception auditive -- néanmoins dans ce chapitre nous ferons un détour par les deuxièmes et troisièmes niveaux de description pour présenter les différentes parties du système auditif et comment chacune d'elle transforme l'information contenue dans le signal acoustique.

## Structure générale du système auditif humain 

Le plan de ce chapitre suit la structure du système auditif humain. Nous commencerons par décrire le **système auditif périphérique** (ou **externe**), qui va du pavillon -- le seul élément visible de l'extérieur -- au nerf auditif. Cet ensemble d'éléments réalise plusieurs fonctions, notamment l'amplification du son, son analyse spectrale et sa transduction. On le décompose donc habituellement en trois grandes sous-parties : l'**oreille externe**, l'**oreille moyenne**, et l'**oreille interne**. 

```{figure} SysAudExt.jpg
---
name: SysAudExt.jpg
alt: Schéma en noir et blanc représentant une coupe anatomique du système auditif externe humain. L’image montre les différentes parties de l’oreille depuis l’extérieur jusqu’à l’intérieur. De gauche à droite, on distingue : L’oreille externe, avec le pavillon et le conduit auditif externe. L’oreille moyenne, contenant le tympan (membrane circulaire tendue) et la chaîne des osselets (marteau, enclume, étrier). L’oreille interne, représentée par une cochlée (structure en spirale) ainsi que les canaux semi-circulaires (structures en boucle). À droite de la cochlée, on voit également le nerf auditif qui prolonge l’oreille interne en direction du cerveau.
height: 400px
align: center
---
*Schéma du système auditif périphérique. (Source : [Ivy Livingstone, Biodidac](https://omeka.uottawa.ca/biodidac/items/show/4603))*
```

Le nerf auditif marque la frontière avec le **système auditif central**. Celui-ci possède une structure nettement moins linéaire, structuré par de nombreux relais interconnectés. Les voies auditives centrales (*auditory pathways*) remontent le long du tronc cérébral, à la base du cerveau, puis rejoignent sa couche la plus externe, le cortex. 

```{figure} syst_centr.jpg
---
name: syst_centr.jpg
alt: Systeme auditif central
height: 700px
align: center
---
*Schéma du système auditif central.*
```

## Une approche par la modélisation 

Appréhender le fonctionnement du système auditif humain est une étape assez ardue pour les psychoacousticien·nes en devenir. Cela nécessite en effet de se familiariser avec des systèmes organiques aussi divers que la cochlée et le cortex auditif, chacun assez complexe pour faire l'objet de manuels dédiés, et pour être encore à l'heure actuelle au cœur d'intenses recherches. En tant qu'étudiant, je me suis longtemps senti débordé par la complexité de cet objet. Ce n'est que lorsque j'ai commencé à essayer de le modéliser que l'organisation générale et les fonctions de chaque partie me sont apparues plus clairement. En effet, le travail de modélisation contraint à simplifier les traitements les plus complexes pour ne conserver que l'essentiel du système décrit. J'ai donc suivi ici le même principe : présenter chaque étape du traitement auditif de façon extrêmement succincte et en proposer un modèle simple. A l'issue de ce chapitre, nous aurons donc mis en place un modèle fonctionnel du système auditif humain. Bien que celui-ci omette bon nombre de non-linéarités et de boucles de rétroaction, il est suffisant pour rendre compte d'un certain nombre de phénomènes perceptifs comme on le verra au chapitre suivant.

Toutes les simulations présentées dans ce chapitre ont été générées grâce à la [Auditory Modeling Toolbox](https://amtoolbox.org/) et la [Temporal Modulation Spectrum Toolbox](https://github.com/LeoVarnet/TMST), deux toolbox MATLAB *open source*.

## Références

Marr, D. (1982). Vision: A Computational Investigation into the Human Representation and Processing of Visual Information. The MIT Press.

