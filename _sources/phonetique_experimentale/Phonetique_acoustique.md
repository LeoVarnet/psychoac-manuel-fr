
```{warning}
Page en cours de construction
```

# Phonétique acoustique

Nous sommes constamment exposé·es à des sons de parole, que notre cerveau comprend quasi-instantanément et sans effort apparent. Le processus semble aller de soi, à tel point qu'il est difficile a priori d'imaginer que ce mécanisme de décodage puisse faire l'objet de recherches approfondies depuis maintenant plus d'un siècle. Après tout, ne suffit-il pas à notre cerveau de mémoriser l'association entre chaque phonème et le son correspondant pour décoder la parole -- de la même manière que nous pouvons déchiffrer un message en morse en consultant l'alphabet morse ? Pour le dire crûment : nous entendons le son "b", et nous en déduisons qu'il s'agit de la consonne /b/, qu'y-a-t'il de sorcier là-dedans ? Si chaque consonne et chaque voyelle est associée à un son particulier et spécifique, il est assez simple d'imaginer un mécanisme de décodage. Dans cette section, nous examinerons en détail des sons de parole pour tenter d'établir cet "alphabet acoustico-phonétique". Ceci nous amènera à identifier les problèmes théoriques auquel se trouve confrontée cette explication intuitive.

## Qu’est-ce qu’un phonème ?

Une étape préalable consiste bien sûr à identifier quels sont les phonèmes de la langue étudiée, ici le français. À la suite des travaux fondateurs du Cercle de Prague au début du XXe siècle, les linguistes définissent le **phonème** comme le **plus petit élément porteur de sens dans le son de parole**, c'est-à-dire en quelque sorte comme l' "atome", ou la "brique de base", du langage parlé.

> Quels sont exactement les rapports entre les sons et le sens à l’intérieur du mot et de la langue en général ? Finalement, il s'agit de dégager le plus petit élément phonique chargé d'une valeur significative, ou -- en termes métaphoriques -- il s'agit de trouver les quanta de la langue. *(Jakobson, Six leçons sur le son et le sens, 1942)*

Jakobson et les autres linguistes du Cercle de Prague ne proposent pas seulement une définition théorique, mais également une méthode pratique pour recenser l'ensemble des phonèmes d’une langue donnée. Elle consiste à identifier des **paires minimales**, des couples de mots ne différant que par un son unique. Ainsi, en français, les mots "bagage" et "bagarre" ont des sens radicalement distincts, pourtant seul leur tout dernier son, /j/ ou /r/ est différent. Ceci indique que, dans notre langue, l’opposition /j/-/r/ est porteuse de sens, et donc que /j/ et /r/ constituent deux phonèmes distincts. De la même façon, "malle" et "mille" forment une paire minimale en français, séparée uniquement par les phonèmes /a/ et /i/.

En appliquant cette approche de façon systématique, il devient possible de dresser l'inventaire des phonèmes d'une langue donnée, et par extension d'établir une typologie des systèmes phonologiques du monde entier. Ce travail méticuleux est résumé dans les tables de l'alphabet phonétique international (*International Phonetic Alphabet*, IPA). [Notez que cette présentation sous forme de table plutôt que de simple liste suggère une organisation particulière des phonèmes entre eux. Bien que cette perspective dite "structuraliste" -- car elle met en lumière la structure des relations entre les phonèmes -- soit fondamentale en phonologie, nous ne la détaillerons pas dans ce chapitre par souci de concision.]. On peut faire analogie entre ces tableaux, énumèrant les phonèmes dont sont composés tous les sons parlés, au célèbre système des éléments chimiques établi par Mendeleev.

```{figure} IPA.png
---
name: IPA.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Si cette définition phonologique constitue un point de départ indispensable, elle est néanmoins peu informative sur les propriétés acoustiques des phonèmes, qui nous préoccupent dans ce chapitre. Comme le souligne Ferdinand de Saussure, la phonologie considère le phonème comme une unité abstraite, dont l'association avec un son concret particulier est purement contingente et arbitraire. Autrement dit, les phonèmes sont définis ici avant tout par leur fonction (celle de structurer les mots) plutôt que par leurs caractéristiques acoustiques. On pourrait les comparer aux pièces d’un jeu d’échecs, qu'il est possible de remplacer par n'importe quels autres petits objets pourvu que les joueur·euses se mettent d'accord sur leur rôle dans le jeu. 

Cette définition laisse donc en suspens nos questions initiales : quelles sont les caractéristiques sonores qui permettent de distinguer un phonème d’un autre ? Comment le cerveau interprète-t-il ces signaux pour en extraire du sens ? Pour y répondre, il devient indispensable d’examiner d'un peu plus près la forme acoustique des phonèmes.

## Les voyelles

Rappelons que notre objectif dans ce chapitre est de percer le code acoustico-phonétique. Nous cherchons à découvrir les signatures sonores des phonèmes : quelles propriétés physiques les caractérisent, et permettent de les différencier de manière systématique ? Une approche assez intuitive pour répondre à cette question consiste à examiner des enregistrements de parole afin d'y repérer des régularités acoustiques. 

La figure suivante présente les spectrogrammes de 3 voyelles du français : "i", "a" et "ou". Deux enregistrements de chaque voyelle sont présentés, ce qui permet de remarquer une caractéristique frappante : la présences de bandes d'énergies relativement stables dans le temps, et dont les fréquences semblent dépendre de la voyelle prononcée. Ces maxima spectraux sont appelés **formants** et numérotés des basses fréquences vers les hautes : le premier formant (F1) est le plus grave, puis vient le deuxième formant (F2), etc. Notez que les spectrogrammes présentent également des raies verticales régulièrement espacées. Celles-ci correspondent à la périodicité du son et donc à la hauteur de la voix (appelée **fréquence fondamentale**), et elles sont globalement indépendantes des formants.

```{figure} Vowels.png
---
name: Vowels.png
alt: XXXXX
width: 70%
align: center
---
*Spectrogrammes de 3 voyelles du français : "i", "a" et "ou". Deux enregistrements de chaque voyelle sont présentés, et les positions des quatre premiers formants (F1, F2, F3 et F4) sont indiqués par des flèches.*
```

L'origine physique des formants est directement liée à la structure anatomique de l'appareil phonatoire, et notamment de la bouche du locuteur ou de la locutrice. En effet, lorsque nous parlons, l’air en provenance des poumons traverse notre larynx, puis entre en vibration dans notre cavité buccale. Cette cavité agit comme un résonateur naturel, dont les propriétés acoustiques dépendent directement de sa forme et de ses dimensions à un instant donné.
La configuration de la cavité buccale est elle-même déterminée par la position des **articulateurs** -- c’est-à-dire notre langue, nos lèvres, notre palais et notre mâchoire. Comme l'illustre la figure suivante, chaque voyelle correspond à une position spécifique des articulateurs, et donc à une certaine forme de la "caisse de résonance" formée par la bouche. Lorsque la langue se soulève vers l’arrière de la bouche et que les lèvres s'avancent pour produire la voyelle "ou", la cavité buccale se rétrécit et s’allonge, ce qui produit des fréquences de résonance plutôt graves XXXX. À l’inverse, pour un son comme "a", la bouche s’ouvre largement, créant une cavité plus grande et plus uniforme, qui favorise des résonances différentes.
Chaque configuration des articulateurs produit ainsi un filtre acoustique particulier, amplifiant certaines fréquences tout en atténuant d’autres. Ces fréquences renforcées sont les formants, et peuvent être déterminées mathématiquement ou par des simulations informatiques (voir figure XXx, ligne inférieure) ou des modèles physiques (voir vidéo plus loin xxxx). le premier formant (F1) est généralement lié au degré d’ouverture de la bouche, tandis que le second (F2) est principalement influencé par la position antérieure ou postérieure de la langue. 

```{figure} Boeetal2019.jpg
---
name: Boeetal2019.jpg
alt: XXXXX
width: 70%
align: center
---
*Illustration du lien entre forme de la cavité buccale et fréquence des formants. La ligne supérieure schématise les positions des articulateurs correspondant à trois voyelles. En dessous est représentée la forme de la "caisse de résonance" ainsi formée, depuis la gorge jusqu'aux levres. Enfin, la dernière ligne présente le spectre des résonances produites par cette cavité (obtenues par simulation informatique). Ces spectres présentent des pics très marqués, correspondant aux formants. Figure issue de Boë et al. (2019)*
```

Ainsi, de subtiles variations dans la position des articulateurs se traduisent par des différences perceptibles dans les sons de parole. On peut se rendre compte facilement du fait que les résonances de la cavité orale sont déterminantes pour l'identité de la voyelle : dans la vidéo ci-dessous, différents tubes ont été conçus pour imiter la forme de la cavité buccale pour différentes voyelles (comme illustré dans la seconde ligne de la figure Xxxx). Un buzzer est placé à l'entrée de chacun de ces tubes, de façon à ce que le son résonne dans cette structure. À l'autre extrémité du tube, on entend clairement la voyelle correspondant à la forme de la cavité, ce qui indique que les résonances sont essentielles pour la compréhension. 

<video controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/Reson.mp4" type="video/mp4">
</video>

Ainsi, le son des phonèmes est une "empreinte" acoustique des mouvements des articulateurs. Autrement dit, le langage parlé est une sorte de langage des signes, à ceci près que les signes sont réalisés par la langue, les lèvres, le palais et la mâchoire, plutôt que par les mains, et que ces mouvements étant en grande partie cachés à l'oeil de l'interlocuteur·ice, il sont rendus perceptible en sculptant un son.

en faites deux premiers formants sont suffisants 

Triangle vocalique : Mesure des valeurs de F1 et F2 pour un grand nombre de productions de voyelles. 

```{figure} Hillen1.png
---
name: Hillen1.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Répartition des voyelles dans l’espace F1-F2

```{figure} Hillen2.png
---
name: Hillen2.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

1er problème : subdivision
Nécessité d’un mécanisme pour découper l’espace acoustique en régions correspondant aux différents phonèmes

```{figure} Hillen3.png
---
name: Hillen3.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

2nd problème : « problème du manque d’invariance »
Recouvrement des régions correspondant aux différents phonèmes. F1 et F2 ne suffisent pas à identifier les voyelles de façon univoque.

```{figure} Hillen4.png
---
name: Hillen4.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

## Les consonnes

```{figure} Consonants.png
---
name: Consonnes.bmp
alt: XXXXX
width: 100%
align: center
---
*Spectrogrammes de 12 consonnes du français, précédées et suivies d'un "a" : "aba", "ada", "aga", "apa", "ata", "aka", "afa", "asa", "aʃa", "ama", "ana" et "ala".*
```

Les consonnes présentent des caractéristiques acoustiques plus complexes et plus diversifiées que les voyelles. 
Les plosives /p/, /t/, /k/, /b/, /d/, /g/ correspondent à des caractéristiques transitoires.
À nouveau, difficile d’associer transition et plosive de façon univoque (manque d'invariance)

```{figure} VdV2.png
---
name: VdV2.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

```{figure} VdV.png
---
name: VdV.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Pas d'alphabet. Pas conséquent, impossible de synthétiser de la parole en collant des phonèmes les uns avec les autres. (Simone Signoret)

```{figure} SimoneSignoret.png
---
name: SimoneSignoret.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

<video controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/SimoneSignoret.wav" type="video/wav">
</video>

## Conclusions temporaires

La phonétique acoustique cherche à identifier des similarités entre différentes productions d’un même phonème. 
Les formants et transitions de formants sont un élément important du son de parole.
Mais impossible de tracer une correspondance bijective entre phonèmes et formants.
 Seule l’expérimentation psychoacoustique peut permettre de résoudre ce problème (i.e. la phonétique expérimentale)

la phonétique est une illusion 



