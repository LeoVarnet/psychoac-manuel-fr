
# Introduction

Ce second chapitre vise à donner un aperçu global de la hiérarchie de traitement du système auditif humain depuis l’oreille externe jusqu’au cortex auditif. Ceci nous permettra d'introduire certains concepts importants pour la suite du cours, notamment les notions de pattern d’excitation, de tonotopie et de codage temporel, et de représentation multirésolution.

# Une approche par la modélisation 

Appréhender le fonctionnement du système auditif humain est une étape assez ardue pour les psychoacousticien·nes en devenir. Cela nécessite en effet de se familiariser avec des systèmes organiques aussi divers que la cochlée et le cortex auditif, chacun assez complexe pour bénéficier de manuels intégralement dédiés, et pour faire encore l'objet à l'heure actuelle d'intenses recherches. En tant qu'étudiant, je me suis longtemps senti débordé par la complexité de cet objet. Ce n'est que lorsque j'ai commencé à essayer de le modéliser que l'organisation générale et les fonctions de chaque partie me sont apparues plus clairement. En effet, le travail de modélisation contraint à simplifier les traitements les plus complexes pour ne conserver que l'essentiel du système décrit. J'ai donc suivi ici le même principe : présenter chaque étape du traitement auditif de façon extrêmement succincte et en proposer un modèle simple. A l'issue de ce chapitre, nous aurons donc mis en place un modèle fonctionnel du système auditif humain. Bien que celui-ci ommette bon nombre de boucles de feedback et de non-linéarités, il est suffisant pour rendre compte d'un certain nombre de phénomènes perceptifs comme on le verra au chapitre suivant.

## Ouvrir la boîte noire

Il peut sembler de prime abord contradictoire de consacrer le deuxième chapitre de ce manuel à la description de l'organisation du système auditif, alors que nous avons insisté en introduction du chapitre 1 sur l'approche spécifique de la psychophysique qui consiste à considérer l'esprit humain comme une boîte noire inviolable. Il ne s'agit pourtant pas d'une erreur. L'approche behavioriste fondée sur l'étude des comportements observables demeure notre boussole dans l'exploration de l'audition humaine. En particulier, elle reste la seule source possible d'information quant au contenu des représentations mentales : aucune mesure de neurophysiologie ne peut deduire de façon définitive ce que le sujet perçoit réellement. Démontrer qu'une certaine caractéristique acoustique engendre une réponse particulière à tel niveau du système auditif ne signifie pas que cette réponse a un effet quelconque sur les sensations éprouvées par l'individu. En revanche, cette observation peut informer les modèles du système auditif et donc notre interprétation des phénomènes psychoacoustiques. Autrement dit, la physiologie permet de montrer qu'une certaine caractéristique des sons environnants est disponible sous une certaine forme à un certain stade du traitement sensoriel -- et il s'agit d'une information très utile pour interpréter les résultats des expériences comportementales.

Plan:
1 Système auditif externe
	(ou périphérique)
	       oreille externe-moyenne,                       cochlée, membrane basilaire, 	
	                   cellules ciliées, nerf auditif


<br /> 

```{figure} syst_ext.jpg
---
name: syst_ext.jpg
alt: Systeme auditif externe
height: 400px
align: center
---
*...*
```

<br />

2 Système auditif central
Colliculus inférieur, 
         corps genouillé médian,
                 cortex auditif, …

<br /> 

```{figure} syst_centr.jpg
---
name: syst_centr.jpg
alt: Systeme auditif central
height: 400px
align: center
---
*...*
```

<br />

Simulations dans ce cours générées grâce aux toolboxes AMT (https://amtoolbox.org/) et TMST (https://github.com/LeoVarnet/TMST)

