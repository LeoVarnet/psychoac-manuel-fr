
# Introduction

Ce second chapitre vise à donner un aperçu global de la hiérarchie de traitement du système auditif humain depuis l’oreille externe jusqu’au cortex auditif. Ceci nous permettra d'introduire certains concepts importants pour la suite du cours, notamment les notions de pattern d’excitation, de tonotopie et de codage temporel, et de représentation multirésolution.

## Une approche par la modélisation 

Appréhender le fonctionnement du système auditif humain est une étape assez ardue pour les psychoacousticien·nes en devenir. Cela nécessite en effet de se familiariser avec des systèmes organiques aussi divers que la cochlée et le cortex auditif, chacun assez complexe pour faire l'objet de manuels dédiés, et pour être encore à l'heure actuelle au cœur d'intenses recherches. En tant qu'étudiant, je me suis longtemps senti débordé par la complexité de cet objet. Ce n'est que lorsque j'ai commencé à essayer de le modéliser que l'organisation générale et les fonctions de chaque partie me sont apparues plus clairement. En effet, le travail de modélisation contraint à simplifier les traitements les plus complexes pour ne conserver que l'essentiel du système décrit. J'ai donc suivi ici le même principe : présenter chaque étape du traitement auditif de façon extrêmement succincte et en proposer un modèle simple. A l'issue de ce chapitre, nous aurons donc mis en place un modèle fonctionnel du système auditif humain. Bien que celui-ci omette bon nombre de non-linéarités et de boucles de rétroaction, il est suffisant pour rendre compte d'un certain nombre de phénomènes perceptifs comme on le verra au chapitre suivant.

Toutes les simulations présentées dans les sections suivantes ont été générées grâce à la [Auditory Modeling Toolbox](https://amtoolbox.org/) et la [Temporal Modulation Spectrum Toolbox](https://github.com/LeoVarnet/TMST), deux toolbox MATLAB *open source*.

## Ouvrir la boîte noire

Il peut sembler de prime abord contradictoire de consacrer le deuxième chapitre de ce manuel à la description de l'organisation du système auditif, alors que nous avons insisté au chapitre 1 sur l'approche spécifique de la psychophysique qui consiste à considérer l'esprit humain comme une boîte noire inviolable. Il ne s'agit pourtant pas d'une erreur. L'approche béhavioriste fondée sur l'étude des comportements observables demeure notre boussole dans l'exploration de l'audition humaine. En particulier, elle reste la seule source possible d'information quant au contenu des représentations mentales : aucune mesure de neurophysiologie ne peut déduire de façon définitive ce que le sujet perçoit réellement. Démontrer qu'une certaine caractéristique acoustique engendre une réponse particulière à tel niveau du système auditif ne signifie pas que cette réponse a un effet quelconque sur les sensations éprouvées par l'individu. En revanche, cette observation peut informer les modèles du système auditif et donc notre interprétation des phénomènes psychoacoustiques. Autrement dit, **la physiologie permet de montrer qu'une certaine caractéristique des sons environnants est disponible sous une certaine forme à un certain stade du traitement sensoriel** -- et il s'agit d'une information très utile pour interpréter les résultats des expériences comportementales.

S'appuyant sur une proposition de David Marr dans l'introduction philosophique de son ouvrage *Vision*, les scientifiques travaillant sur la perception et la cognition distinguent habituellement **trois niveaux de description** complémentaires pour appréhender les systèmes qu'ils étudient :

> Un système de traitement de l'information doit être compris à différents niveaux avant qu'il soit possible d'affirmer qu'on l'a compris parfaitement. À une extrémité, le niveau supérieur correspond à la théorie computationelle du système qui caractérise les performances de celui-ci en termes d'association entre une forme d'information et une autre. Les propriétés abstraites de cette association sont définies précisément et leur adéquation pour la tâche réalisée par le système est démontrée. Au centre correspond l'implémentation algorithmique, le choix d'une représentation pour l'entrée et la sortie, et l'algorithme qui permet de transformer la première en la seconde. À l'autre extrémité on trouve les détails de la réalisation physique de l'algorithme -- le *hardware* en quelque sorte. Ces trois niveaux sont couplés, mais de façon assez souple. Le choix d'un algorithme, par exemple, est contraint par la fonction qu'il doit réaliser et par le hardware avec lequel il est construit. Mais un large éventail de choix demeure disponible, et chaque niveau de description implique des problématiques assez indépendantes des deux autres. *(Marr, Vision, 1982)*

Pour l'exprimer dans les termes de Marr, ce cours s'intéresse en premier lieu à l'explication "abstraite" de la perception auditive -- néanmoins dans ce chapitre nous ferons un détour par les deuxièmes et troisièmes niveaux de description pour présenter les différentes parties du système auditif et comment chacune d'elle transforme l'information contenue dans le signal acoustique.

## Structure générale du système auditif humain 

Le plan de ce chapitre suit la structure du système auditif humain. Nous commencerons par décrire le **système auditif périphérique** (ou **externe**), qui va du pavillon -- le seul élément visible de l'extérieur -- au nerf auditif. Cet ensemble est très complexe et réalise plusieurs fonctions. On le décompose donc habituellement en trois grandes sous-parties : l'**oreille externe**, l'**oreille moyenne**, et l'**oreille interne**. 

```{figure} syst_ext.jpg
---
name: syst_ext.jpg
alt: Systeme auditif externe
height: 400px
align: center
---
*Schéma du système auditif périphérique.*
```

Le nerf auditif marque la frontière avec le **système auditif central**. Celui-ci possède une structure nettement moins linéaire, structuré par de nombreux relais interconnectés. Les voies auditives centrales (*auditory pathways*) remontent le long du tronc cérébral, à la base du cerveau, puis rejoignent sa couche la plus externe, le cortex. 

<br /> 

```{figure} syst_centr.jpg
---
name: syst_centr.jpg
alt: Systeme auditif central
height: 600px
align: center
---
*Schéma du système auditif central.*
```

<br />
