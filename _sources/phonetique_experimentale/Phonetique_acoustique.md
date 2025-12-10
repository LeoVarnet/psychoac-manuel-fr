
```{warning}
Page en cours de construction
```

# Phonétique acoustique

Nous sommes constamment exposé·es à des sons de parole, que notre cerveau comprend quasi-instantanément et sans effort apparent. Le processus semble aller de soi, à tel point qu'il est difficile a priori d'imaginer que ce mécanisme de décodage fasse l'objet de recherches approfondies depuis maintenant plus d'un siècle. Après tout, ne suffit-il pas à notre cerveau de mémoriser la table d'association entre chaque phonème et le son correspondant pour décoder la parole -- de la même manière que nous déchiffrerions un message en morse en consultant l'alphabet que qu'il nous suffit de disposer d'une copie de l'alphabet morse pour être en mesure de déchiffrer un message codé en morse ? Pour le dire crûment : nous entendons le son "b", et nous en déduisons qu'il s'agit de la consonne /b/, qu'y a t'il de sorcier là dedans ? Si chaque consonne et chaque voyelle est associée à un son particulier et spécifique, il est assez simple d'imaginer un mécanisme de décodage. Dans cette section, nous examinerons en détail des sons de parole pour tenter d'établir cet "alphabet acoustico-phonétique". Ceci nous amènera à identifier les problèmes théoriques auquel se trouve confrontée cette explication intuitive.

## Qu’est-ce qu’un phonème ?

Une étape préalable consiste bien sûr à identifier quels sont les phonèmes de la langue étudiée, ici le français. Les linguistes définissent le **phonème** comme le **plus petit élément porteur de sens dans le son de parole**, c'est-à-dire en quelque sorte comme l' "atome", ou la "brique de base", du langage parlé.

> Quels sont exactement les rapports entre les sons et le sens à l’intérieur du mot et de la langue en général ? Finalement, il s'agit de dégager le plus petit élément phonique chargé d'une valeur significative, ou -- en termes métaphoriques -- il s'agit de trouver les quanta de la langue. *(Jakobson, Six leçons sur le son et le sens, 1942)*

Une approche pour identifier les phonèmes d’une langue donnée :
« bagage » vs. « bagarre »  en français l’opposition g/r est porteuse de sens

On peut ainsi construire des tables des phonèmes et de leurs relations


**Système phonologique**  
linguiste contemporain Nicolas Troubetzkoy (1890-1938) a voué les dix dernières années de sa vie presque uniquement aux recherches phono logiques. Parmi une série de brillantes découvertes, nous lui devons surtout le premier essai d'un classement phonologique des voyelles et par conséquent une typo logie des systèmes vocaliques du monde entier. Ce sont des découvertes d'une puissante envergure, et c'est à bon droit qu'on les a comparé au célèbre système des éléments chimiques établi par Mendeleev. […] C'est surtout dans les Travaux du Cercle linguistique de Prague, du premier volume au huitième (1929-1939), qu'on trouve maintes contribu tions phonologiques dues aux linguistes de divers pays

```{figure} IPA.png
---
name: IPA.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Le phonème, tout en étant un élément au service de la signification, est en lui-même dépourvu de propre signification. Ce qui le distingue de toutes les autres valeurs linguistiques et sémiotiques en général, c'est qu'il n'a qu'une charge négative. […] Saussure identifie ce train des choses avec le jeu d'échecs qui permet de remplacer une pièce détruite ou même égarée par une figure tout à fait dissemblable pourvu qu'on lui attribue le même rôle dans le jeu. [[Jakobson, 6 lecons]]

…mais qu’est-ce qui caractérise acoustiquement un phonème ? Comment le cerveau procède-t-il pour distinguer un phonème d’un autre ?

## Les voyelles

Phonétique acoustique
Etude systématique d’enregistrements de parole pour identifier les similarités entre différentes productions d’un même phonème.

Le spectre des voyelles présente des formants à des fréquences relativement stables… 

```{figure} Vowels.png
---
name: Vowels.png
alt: XXXXX
width: 70%
align: center
---
*Spectrogrammes de 3 voyelles du français : "i", "a" et "ou". Deux enregistrements de chaque voyelle sont présentés, ce qui permet de remarquer une caractéristique frappante : la présences de quatre formants (F1, F2, F3 et F4) correspondant à des maxima d'énergies relativement stables dans le temps, et dont les fréquences semblent caractéristiques de la voyelle.*
```

Les formants correspondent aux résonances de la cavité orale pour une configuration particulière des articulateurs (langue, lèvres, palais…)

```{figure} Boeetal2019.jpg
---
name: Boeetal2019.jpg
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

<video controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/Reson.mp4" type="video/mp4">
</video>

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

## Conclusions temporaires

La phonétique acoustique cherche à identifier des similarités entre différentes productions d’un même phonème. 
Les formants et transitions de formants sont un élément important du son de parole.
Mais impossible de tracer une correspondance bijective entre phonèmes et formants.
 Seule l’expérimentation psychoacoustique peut permettre de résoudre ce problème (i.e. la phonétique expérimentale)

la phonétique est une illusion 



