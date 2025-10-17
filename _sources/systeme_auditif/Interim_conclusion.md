
# Conclusion intermédiaire

```{warning}
Page en cours de construction
```

Parvenu·es au niveau du nerf auditif, qui marque la frontière entre le système auditif périphérique et le système auditif central, il est temps de marquer une pause pour récapituler ce que nous avons vu jusqu'ici, mais également pour développer certaines notions que nous avons seulement esquissées plus tôt.

## Structure du modèle du système auditif périphérique

Dans les sections qui précèdent, nous avons listé les différentes étapes de traitement du signal sonore à travers le système auditif périphérique en en proposant des modélisations simples. Si ces modules peuvent être enrichis, jusqu'à devenir extrêmement complexes pour tenir compte des effets de spatialisation, de feedback, ou des nombreuses non-linéarités, la structure générale du modèle est quant à elle relativement stable. En effet, chaque étape décrite ici est un "passage obligé" pour l'information sonore. En conséquence, les différents modèles auditifs proposés dans la littérature scientifique possèdent tous la même organisation, même si certains modules peuvent être omis en première approximation. La figure suivante illustre la structure de 8 modèles "classiques" du système auditif périphérique, en faisant apparaitre les correspondances entre modules de traitement. On retrouve les différentes étapes (*stages*) décrites précédemment : 
- **étape 1** : filtre d'oreille externe
- **étape 2** : filtre d'oreille moyenne
- **étape 3** : décomposition en fréquence par la membrane basilaire, modélisée par un banc de filtres (incluant éventuellement l'amplification/compression par les cellules ciliées externes). *P.ex. banc de filtres gammatones*.
- **étape 4** : modèle de la transduction par les cellules ciliées. *P.ex. rectification demie-onde suivie d'un filtre passe-bas de fréquence de coupure 1 kHz.*
- **étape 5** : modèle des synapses du nerf auditif. A minima, ce module réalise une compression supplémentaire du signal. Il peut également prendre en compte les différents types de fibres, et/ou produire une série de potentiels d'action.
- **étape 6** : modèles du noyau cochléaire et du colliculus inférieur. Nous envisagerons ce module dans la section suivante.
La figure fait également apparaître, en bleu, des modifications pouvant être apportées aux modèles pour simuler diverses formes de pertes auditives.

```{figure} models.png
---
name: models.png
alt: modélisation
width: 75%
align: center
---
*Structure de huit modèles "classiques" du système auditif périphérique humain. faisant apparaitre les différentes étapes de traitement (stages, voir description dans le texte). Les modules annotés en bleu permettent également une simulation des pertes auditives. (figure issue de Osses et al. 2022)*
```

Cette structure relativement "rectiligne" du système auditif périphérique, formée par une série de modules successifs, contraste avec le système auditif central, constitué quant à lui de nombreuses voies parallèles et facultatives, comme nous le verrons plus loin.

## Codage d'un complexe harmonique 

Les exemples choisis pour illustrer le principe du spectrogramme auditif ([ref]) se sont concentrés principalement sur des sons composés d'un ou deux tons purs. Il est néanmoins utile pour les chapitres suivants de se pencher sur le cas des complexes harmoniques. Comme nous l'avons expliqué ({numref}`pattern3.png` et {numref}`pattern4.png`), du point de vue du codage tonotopique les harmoniques dans les basses fréquences sont résolues (elles correspondent à des pics dans le pattern d'excitation) tandis que les harmoniques plus hautes sont non-résolues. Qu'en est-il du point de vue du codage temporel ?

Considérons à nouveau la figure suivante :

```{figure} pattern4bis.png
---
name: pattern4.png
alt: Sortie temporelle des filtres gammatones
width: 75%
align: center
---
*Modélisation des vibrations en différents points de la membrane basilaire, en réponse à un complexe harmonique de fréquence fondamentalementale 300 Hz. Le spectre de ce signal est représenté dans le panneau supérieur. Comme pour la {numref}`pattern.png`, on a tracé en-dessous les fonctions de transfert de six gammatones, de fréquences d'accordage 300 Hz, 600 Hz, 1270 Hz, 3460 Hz, 5060 Hz et 7350 Hz, puis le pattern d'excitation. Les trois derniers gammatones ont des bandes passantes très larges qui englobent un grand nombre d'harmoniques, et effectivement ils correspondent à la région des harmoniques non résolues. La partie inférieure de la figure présente la sortie temporelle de chacun des six gammatones identifiés plus haut. Du fait de phénomènes de battement entre harmoniques, on observe une périodicité à 300 Hz dans la réponse des trois filtres gammatones accordé à 3460 Hz, 5060 Hz et 7350 Hz. (Inspiré de Plack, 2023)*
```

Nous avons détaillé précédemment le cas des trois gammatones accordés aux fréquences les plus basses. Ceux-ci sont suffisamment étroits pour isoler une seule composante harmonique (ils sont situés dans la région des harmoniques résolues) et leur sortie fluctue donc à la fréquence de cette harmonique. En revanche, les filtres gammatones de fréquence d'accordage plus élevée sont, comme on l'a vu précédemment, beaucoup plus larges et englobent au contraire plusieurs harmoniques proches (qui sont donc non-résolues). Il en découle un phénomène de battement à la fréquence fondamentale dans leur réponse temporelle : la superposition de plusieurs tons purs espacés de ∆f engendre un signal modulé à la fréquence ∆f. Ainsi, pour un complexe harmonique, **les gammatones accordés dans les hautes fréquences ont une réponse présentant des battements réguliers -- c'est à dire des fluctuations -- à la fréquence fondamentale du signal**.

Les cellules ciliées internes accordées dans les hautes fréquences agissant, on l'a vu, comme des extracteurs d'enveloppe, elles extraient les modulations à la fréquence fondamentalementale et les transmettent aux fibres du nerf auditif. Ce phénomène est clairement visible dans le spectrogramme auditif comme illustré par la figure suivante. Pour le complexe harmonique comme pour le son de la voyelle "è", les cellules ciliées accordées sur les fréquences aiguës présentent des fluctuations très claires à la fréquence fondamentalementale (300 Hz ou 250 Hz, respectivement). Ainsi, Pour des sons harmoniques, la fréquence fondamentalementale est codée de trois façons différentes au niveau du nerf auditif : un code tonotopique (pic dans le pattern d'excitation), un code temporel dans les basses fréquences, et un code temporel dans les hautes fréquences dû au phénomène de battement.

```{figure} AuditorySpectrograms2.png
---
name: AuditorySpectrograms2.png
alt: Spectrogramme auditif
width: 80%
align: center
---
*Deux exemples de spectrogramme auditif, en réponse à un complexe harmonique de fréquence fondamentale 300 Hz (panneau gauche), et à un enregistrement de la voyelle "é" prononcée par une voix avec une fréquence fondamentalementale à 250 Hz (panneau droit). A droite de chaque spectrogramme est représenté le pattern d'excitation correspondant, et au dessus la réponse électrique simulée d'une cellule ciliée particulière (c'est-à-dire une ligne du spectrogramme, identifiée par la flèche rouge) : cellule accordée à 7000 Hz (panneau gauche) ou à 3370 Hz (panneau droit).*
```

## Le paradoxe du système auditif 

Selon Richard Warren, le système auditif présente un "paradoxe" : c'est un mauvais instrument de mesure mais qui fournit néanmoins une excellente précison.

> Pour qu'un microphone soit dit "haute-fidélité", il faut qu'il génère un signal électrique qui reproduise précisément l'onde sonore, sans introduire de distorsions. Si l'on suit ce critère, la configuration et les performances de l'oreille sont extrêmement mauvaises. [...] Le pavillon produit des résonnance et des délais qui modifient l'amplitude et la phase des composantes spectrales en fonction de l'azimut et de l'élévation de la source. Le canal auditif opère comme un tube résonnant qui amplifie sélectivement les fréquences autour de 3000 ou 4000 Hz. Les muscles [des osselets] produisent des réductions d'amplitude sur certaines bandes de fréquences lorsqu'ils se contractent. L'oreille moyenne et interne sont connues pour introduire des distorsions avant la transduction, de sorte que les stimuli de faible intensité produisent des vibrations suffisantes au niveau des récepteurs sensoriels. *(Richard Warren, Auditory Perception)*

Ainsi, le signal est filtré et transformé à chaque étape du système auditif à tel point que certaines informations sont perdues tandis que d'autres sont codées de façon redondante. Comment se fait-il que, malgré tout, notre perception soit aussi incroyablement performante ? La résolution de ce "paradoxe" repose sur le système auditif central, pour lequel ces imperfections sont en réalité autant de sources d'information. Comme nous le verrons par la suite, le cerveau est capable de s'appuyer sur les redondances du code auditif pour former des représentations extrêmement robustes, ou d'analyser les distortions causées par l'oreille pour en inférer des propriétés du son (comme le filtrage directionnel du pavillon, qui permet de localiser la source sonore). Le paradoxe n'en est donc en réalité pas un : notre oreille ne joue pas le rôle de microphone, et ne vise donc pas la "haute-fidélité". Au contraire, elle "pré-traite" les sons pour les coder d'une façon pertinente et efficace pour le système auditif central.

## Systèmes afférent et efférent

Au sein du système auditif, l'information suit généralement un chemin ascendant (***bottom-up***) depuis les récepteurs sensoriels jusqu'au cortex auditif : elle est dite **afférente**. Nous avons cependant noté au cours de ce chapitre que certaines informations transitent en sens inverse, depuis les étages supérieurs vers le système périphérique. Ainsi, la détection d'un niveau sonore trop important au niveau du [xxx] déclenche le réflexe stapédien qui immobilise les osselets ; de même, les cellules ciliées externes reçoivent un feedback du [xxx] qui leur permet d'amplifier les sons trop faibles. Ces informations descendantes (***top-down***) sont dites **efférentes**.

La fonction principale du nerf auditif étant de transmettre l'information depuis les récepteurs sensoriels aux étages supérieurs, il est naturel qu'il soit composé majoritairement de fibres afférentes connectées aux cellules ciliées internes. Néanmoins, il contient également 5% de fibres efférentes, connectées pour la plupart aux cellules ciliées externes. 

Ainsi non seulement le système auditif périphérique n'est pas un simple capteur mais plutôt un premier module de pré-traitement de l'information, en vue de son analyse par les étages supérieurs, mais ces pré-traitements impliquent des mécanismes de feedback depuis les étages supérieurs. Nous verrons à la section suivante que le rôle de l'information efférente et des mécanismes de feedback sont encore plus critiques au sein du système auditif central.

## Références

