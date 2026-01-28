
```{warning}
Page en cours de construction
```

# Caractérisation acoustique des phonèmes 

Nous sommes constamment exposé·es à des sons de parole, que notre cerveau comprend quasi-instantanément et sans effort apparent. Le processus semble aller de soi, à tel point qu'il est difficile a priori d'imaginer que ce mécanisme de décodage puisse faire l'objet de recherches approfondies depuis maintenant plus d'un siècle. À premièe vue, on pourrait imaginer que le cerveau se contente d'associer chaque phonème à un son spécifique, comme on déchiffre un message en morse en consultant un tableau de correspondance (l'alphabet Morse) ? Pour le dire crûment : si nous entendons le son "b" nous en déduisons qu'il s'agit de la consonne /b/, si nous entendons le son "a" nous en déduisons qu'il s'agit de la voyelle /a/, qu'y a-t-il de sorcier là-dedans ? En d'autres termes, si chaque consonne et chaque voyelle est associée à un son particulier et spécifique, imaginer un mécanisme de décodage est assez aisé. Dans cette section, nous examinerons en détail les propriétés acoustiques des sons de parole pour tenter d'établir cet "alphabet acoustico-phonétique". Cette exploration nous amènera à identifier les problèmes théoriques auquel se trouve confrontée cette explication intuitive.

## Qu’est-ce qu’un phonème ?

Avant d’étudier les caractéristiques acoustiques des phonèmes, il est essentiel de clarifier ce que l’on entend par ce terme. À la suite des travaux fondateurs du Cercle de Prague au début du XXe siècle, les linguistes définissent le **phonème** comme le **plus petit élément porteur de sens dans le son de parole**, c'est-à-dire en quelque sorte comme l' "atome", ou la "brique de base", du langage parlé.

> Quels sont exactement les rapports entre les sons et le sens à l’intérieur du mot et de la langue en général ? Finalement, il s'agit de dégager le plus petit élément phonique chargé d'une valeur significative, ou -- en termes métaphoriques -- il s'agit de trouver les quanta de la langue. *(Jakobson, Six leçons sur le son et le sens, 1942)*

Jakobson et les autres linguistes du Cercle de Prague ne proposent pas seulement une définition théorique, mais également une méthode pratique pour recenser l'ensemble des phonèmes d’une langue donnée. Elle consiste à identifier des **paires minimales** : des couples de mots ne différant que par un son unique. Ainsi, en français, les mots "bagage" et "bagarre" ont des sens radicalement distincts, pourtant seul leur tout dernier son, /j/ ou /r/, est différent. Cette paire suffit à prouver que, dans notre langue, l’opposition /j/-/r/ est porteuse de sens, et donc que /j/ et /r/ constituent deux phonèmes distincts. De la même façon, "malle" et "mille" forment une paire minimale en français, séparée uniquement par les phonèmes /a/ et /i/.

En appliquant cette approche de façon systématique, il devient possible de dresser l'inventaire des phonèmes d'une langue donnée, et par extension d'établir une typologie des systèmes phonologiques du monde entier. Ce travail méticuleux est compilé dans les tables de l'alphabet phonétique international (*International Phonetic Alphabet*, IPA). [Notez que cette présentation sous forme de table plutôt que de simple liste suggère une organisation particulière des phonèmes entre eux. Bien que cette perspective dite "structuraliste" -- car elle met en lumière la structure des relations entre les phonèmes -- soit fondamentale en phonologie, nous ne la détaillerons pas dans ce chapitre par souci de concision.]. On peut faire analogie entre ces tableaux, énumérant les phonèmes dont sont composés tous les sons parlés, au célèbre système des éléments chimiques établi par Mendeleev.

```{figure} IPA.png
---
name: IPA.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Cette définition phonologique, bien qu’indispensable, reste abstraite. Comme le souligne Ferdinand de Saussure, la phonologie considère le phonème comme une unité abstraite, dont l'association avec un son concret particulier est purement contingente et arbitraire. Autrement dit, les phonèmes sont définis ici avant tout par leur fonction (celle de structurer les mots) plutôt que par leurs caractéristiques acoustiques. On pourrait les comparer aux pièces d’un jeu d’échecs, qu'il est possible de remplacer par n'importe quels autres petits objets pourvu que les joueur·euses se mettent d'accord sur leur rôle dans le jeu. 

Cette approche laisse donc en suspens les questions qui nous préoccupent dans ce chapitre : quelles sont les caractéristiques acoustiques qui permettent de distinguer un phonème d’un autre ? Comment le cerveau interprète-t-il ces signaux pour en extraire du sens ? Pour y répondre, il est nécessaire d’examiner d'un peu plus près la forme acoustique des phonèmes, en commençant par les voyelles.

## Les voyelles

Pour découvrir les signatures sonores des phonèmes, une approche assez intuitive consiste à examiner des enregistrements de parole afin d'y repérer des régularités acoustiques. C'est le programme de la **phonétique acoustique**.

La figure ci-dessous présente les spectrogrammes de trois voyelles du français : "i", "a" et "ou". Deux enregistrements de chaque voyelle sont présentés, ce qui permet de remarquer une caractéristique frappante : la présences de bandes d'énergies relativement stables dans le temps, et dont les fréquences semblent dépendre de la voyelle prononcée. Ces maxima spectraux, appelés **formants**, sont numérotés des basses vers les hautes fréquences : le premier formant (F1) est le plus grave, suivi du deuxième (F2), et ainsi de suite. Notez que les spectrogrammes présentent également des raies verticales régulièrement espacées, reflétant la périodicité du son et donc la hauteur de la voix (appelée **fréquence fondamentale**). Ces raies sont indépendantes des formants et ne jouent pas de rôle direct dans la distinction des voyelles.

```{figure} Vowels.png
---
name: Vowels.png
alt: XXXXX
width: 70%
align: center
---
*Spectrogrammes de 3 voyelles du français : "i", "a" et "ou". Deux enregistrements de chaque voyelle sont présentés, et les positions des quatre premiers formants (F1, F2, F3 et F4) sont indiqués par des flèches.*
```

L'origine physique des formants est directement liée à la structure anatomique de l'appareil phonatoire, et plus précisément à la configuration de la bouche du locuteur ou de la locutrice. Lorsque nous parlons, l’air en provenance des poumons traverse notre larynx, où il entre en vibration, puis progresse jusque dans notre cavité buccale. Cette cavité agit comme un résonateur naturel, dont les propriétés acoustiques dépendent de sa forme et de ses dimensions à un instant donné.
La position des articulateurs -- langue, lèvres, palais et mâchoire -- permet de modifier cette configuration et, par conséquent, les fréquences de résonance produites. La figure suivante illustre ce lien entre la forme de la cavité buccale et les fréquences des formants. Chaque voyelle correspond à une position spécifique des articulateurs, modifiant ainsi la "caisse de résonance" que forme la bouche. Lorsque la langue se soulève vers l’arrière de la bouche et que les lèvres s'avancent pour produire la voyelle "ou", la cavité buccale se rétrécit et s’allonge, ce qui produit des fréquences de résonance plutôt graves (F1 = 400 Hz, F2 = 900 Hz). À l’inverse, pour un son comme "a", la bouche s’ouvre largement, créant une cavité plus grande et plus uniforme, qui favorise des résonances différentes (F1 = 800 Hz, F2 = 1400 Hz).

```{figure} Boeetal2019.jpg
---
name: Boeetal2019.jpg
alt: XXXXX
width: 70%
align: center
---
*Illustration du lien entre forme de la cavité buccale et fréquence des formants. La ligne supérieure schématise les positions des articulateurs correspondant à trois voyelles. En dessous est représentée la forme de la "caisse de résonance" ainsi formée, depuis la gorge jusqu'aux levres. Enfin, la dernière ligne présente le spectre des résonances produites par cette cavité (obtenues par simulation informatique). Ces spectres présentent des pics très marqués, correspondant aux formants. Figure issue de Boë et al. (2019)*
```

Chaque configuration des articulateurs produit ainsi un filtre acoustique particulier, amplifiant certaines fréquences tout en atténuant d’autres. Ces fréquences renforcées sont les formants, et peuvent être déterminées mathématiquement ou par des simulations informatiques (voir {numref}`Boeetal2019.jpg`, ligne inférieure) ou des modèles physiques (voir vidéo suivante). le premier formant (F1) est généralement lié au degré d’ouverture de la bouche, tandis que le second (F2) est principalement influencé par la position antérieure ou postérieure de la langue. Ainsi, de subtiles variations dans la position des articulateurs se traduisent par des différences perceptibles dans les sons de parole. Pour illustrer l’importance des résonances formantiques, la vidéo ci-dessous montre des tubes conçus pour imiter la forme de la cavité buccale associée à différentes voyelles. Un buzzer, placé à l’entrée de chaque tube, fait résonner un son dans la structure. À l’autre extrémité, on entend clairement la voyelle correspondant à la forme du tube, démontrant que les résonances suffisent à identifier la voyelle.

<video controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/Reson.mp4" type="video/mp4">
</video>

Ainsi, le son des phonèmes est une "empreinte" acoustique de la position de la langue, des lèvres, du palais et de la mâchoire. Autrement dit, le langage parlé peut être comparé à une langue des signes invisible : les gestes ne sont pas exécutés par les mains mais par les articulateurs de la bouche. Ceux-ci n'étant pas directement visibles à l'œil de l'interlocuteur·ice, ils doivent être rendus audibles par le phénomène de résonance, transformant des mouvements articulatoires en signaux sonores.

Des experiences en synthèse vocale suggèrent que les deux premiers formants sont suffisants pour identifier les voyelles, même lorsque les formants 3 et 4 sont fixés à des valeurs intermédiaires. Cette observation a conduit les scientifiques à représenter les voyelles dans un espace à deux dimensions, appelé **triangle vocalique** ou espace vocalique (*vowel space*), où chaque axe correspond aux fréquences de F1 et F2. La figure ci-dessous présente les résultats d’une étude menée par Hillenbrand et ses collègues (1995), qui ont enregistré un grand nombre de productions de la voyelle "è" par différents locuteurs et locutrices anglophones. Pour chaque enregistrement, les valeurs de F1 et de F2 ont été mesurées et reportées sur un graphe. Chaque point (indiqué par le symbole æ) représente un enregistrement particulier de la voyelle, avec les valeurs de F2 et de F1 en x et en y, respectivement.

```{figure} Hillen1.png
---
name: Hillen1.png
alt: XXXXX
width: 70%
align: center
---
*Répartition des valeurs de F1 et F2 pour différentes réalisations de la voyelle "è" par des locuteurs et locutrices anglophones. Chaque point correspond à un enregistrement spécifique. (Adapté de Hillenbrand et al., 1995).*
```

Comme attendu d'après nos premières observations ({numref}`Vowels.png`), les fréquences des formants F1 et F2 pour différentes réalisations d'une même voyelle (ici "è") sont très similaires (environ 700 Hz pour F1 et 2200 Hz pour F2), bien qu’elles présentent une certaine variabilité. Cette dispersion reflète l’impossibilité pour l’appareil phonatoire humain de produire un son strictement identique à différentes reprises. Néanmoins, la concentration des points autour de valeurs centrales confirme que les formants sont une propriété déterminante de l’identité des voyelles.

En répétant cette analyse pour les voyelles "a", "i" et "ou", on obtient une répartition caractéristique dans l’espace vocalique, comme illustré ci-dessous.

```{figure} Hillen2.png
---
name: Hillen2.png
alt: XXXXX
width: 70%
align: center
---
*Répartition des voyelles "è", "a", "i" et "ou" dans l'espace vocalique défini par F1 et F2. Chaque couleur correspond à une voyelle distincte.*
```

On constate que les voyelles se répartissent dans l’espace vocalique -- ce qui est, là encore, cohérent avec l'idée que chaque voyelle est définie par ses valeurs de F1 et F2. 

Cette représentation met en évidence un **premier problème théorique** (le **problème de la discrétisation**) posé par la compréhension des phonèmes : le cerveau doit subdiviser un espace acoustique continu, où une infinité de sons est possible, en un nombre fini de catégories distinctes, chacune associée à un phonème. Autrement dit, une information acoustique initialement très détaillée (comme les valeurs exactes de F1 et F2) est réduite à une représentation discrète et opérationnelle (le phonème correspondant). Comme nous le verrons plus loin, ce processus de discrétisation évacue une information non pertinente pour la compréhension (le détail des valeurs des formants) pour ne garder que l'information cruciale, l'identité du phonème entendu.

Schématiquement, résoudre ce problème revient à placer des frontières (les **frontières phonémiques**) dans l'espace acoustique pour délimiter les régions correspondant à chaque voyelle, comme illustré sur la figure suivante. Lorsque nous percevons un son de voyelle, il suffirait alors à notre cerveau de mesurer les valeurs de F1 et F2 et de déterminer dans quelle région de l'espace vocalique se situe ce son [Notez cependant que d'autres mécanismes de catégorisation sont envisageables, par exemple en calculant la distance du son perçu au centre de chaque catégorie].

```{figure} Hillen3.png
---
name: Hillen3.png
alt: XXXXX
width: 70%
align: center
---
*Exemple de frontières phonémiques hypothétiques dans l'espace F1-F2, délimitant les régions associées à chaque voyelle.*
```

Malheureusement, cette solution se heurte à un second problème. En continuant à remplir l'espace vocalique avec l'ensemble des voyelles de l'anglais, nous constatons rapidement que celles-ci se recouvrent dans une large mesure. Ainsi, par exemple, la région de l'espace F1-F2 correspondant à la voyelle /ɪ/ (comme dans "kit") est entièrement superposée à celles des voyelles /i/ (comme dans "happy") et "e" (comme dans "dress"). Autrement dit, pour un grand nombre de sons (c'est-à-dire de points sur la figure), il est impossible d'identifier la voyelle de façon univoque, c'est à dire de déterminer avec certitude, sur la base de F1 et F2, s’il s’agit d’une voyelle plutôt que d’une autre.

```{figure} Hillen4.png
---
name: Hillen4.png
alt: XXXXX
width: 70%
align: center
---
*Répartition de toutes les voyelles de l'anglais dans l'espace vocalique défini par F1 et F2. Chaque couleur correspond à une voyelle distincte.*
```

Ce **second problème** est appelé **problème du manque d’invariance** (*lack of invariance problem*) : la variabilité dans le signal de parole semble à première vue trop grande pour permettre au cerveau de décoder les phonèmes de manière robuste. Le très large recouvrement entre les régions correspondant aux différentes voyelles semble en contradiction avec notre grande facilité à différencier une voyelle d'une autre.

## Les consonnes

Le tableau n'apparaît pas moins complexe du côté des consonnes. La figure suivante représente les spectrogrammes de 12 sons "aXa", où X représente l'une des consonnes suivantes : "b", "d", "g", "p", "t", "k", "f", "s", "ch", "m", "n" et "l".

```{figure} Consonants.png
---
name: Consonnes.bmp
alt: XXXXX
width: 100%
align: center
---
*Spectrogrammes de 12 consonnes du français, précédées et suivies d'un "a" : "aba", "ada", "aga", "apa", "ata", "aka", "afa", "asa", "aʃa", "ama", "ana" et "ala".*
```

Contrairement aux voyelles, dont les caractéristiques acoustiques sont principalement déterminées par les formants, les consonnes présentent une diversité de motifs sonores bien plus complexes. Dans chaque spectrogramme, les deux "a" sont clairement reconnaissables par la présence de formants horizontaux à des valeurs relativement stables. L'intervalle entre les deux, correspondant *a priori* à la consonne, révèle des motifs très différents d'un son à l'autre. Ces dissimilarités acoustiques entre les consonnes tiennent en réalité à la diversité des mouvements articulatoires nécessaires pour les prononcer :
- les **consonnes plosives**, que nous explorerons plus en détail dans la suite de ce chapitre, sont produites en interrompant momentanément le flux d'air, par exemple en joignant les lèvres pour /p/ ou /b/. Cette occlusion engendre un bref silence dans le son de parole, visible sous la forme d’un intervalle vide entre les deux voyelles /a/ sur les spectrogrammes de /aba/, /ada/, /aga/, /apa/, /ata/ et /aka/.
- les **consonnes fricatives** nécessitent de laisser passer seulement un filet d'air turbulent, par exemple en rapprochant la langue du palais pour /s/ ou /ʃ/. Ce phénomène produit un bruit de friction, visible comme une zone d’énergie couvrant une large bande de fréquences sur les spectrogrammes de /afa/, /asa/, et /aʃa/.
- enfin, les autres consonnes, **liquides** (comme /l/) ou **nasales** (comme /m/, /n/), fonctionnent essentiellement sur le même principe de résonances dans la cavité buccale (et nasale) que les voyelles. C'est pourquoi leur spectrogramme présente également des formants à des fréquences précises, mais d'intensité plus faible.

On retrouve pour les consonnes les mêmes problèmes de la discrétisation et du manque d'invariance rencontrés précédemment avec les voyelles. Ainsi, il semble difficile d'associer un son à une consonne plosive de façon univoque. Considérons de plus près les spectrogrammes des deux consonnes plosives /d/ et /t/, précédées et suivies soit de "i", de "a", ou de "ou". On s'aperçoit rapidement que la forme acoustique des consonnes dépend considérablement du contexte, à tel point que le /d/ prononcé en contexte "idi" ressemble plus à un /t/ en contexte "iti" qu'à un autre /d/ en contexte "ada" ou "oudou". Autrement dit, de façon contre-intuitive, des sons extrêmement proches peuvent être perçus comme des phonèmes distincts, une démonstration frappante du problème du manque d’invariance.

```{figure} VdV2.png
---
name: VdV2.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Le phénomène inverse est également observé : deux sons très différents peuvent être perçus comme un seul et même phonème. La figure suivante présente à nouveau les spectrogrammes de "idi", "ada" et "oudou", en mettant en avant en bleu les trajectoires des premier et deuxième formants. Dans chaque cas, les deux formants convergent vers les valeurs stables correspondant aux voyelles "a", "i" et "ou", respectivement. La partie initiale, transitoire du formant traduit quant à elle la consonne "d". On observe que l'attaque du second formant est fortement ascendante dans le cas de "idi", légèrement ascendante dans le cas de "ada", et descendante dans le cas de "oudou". Cet exemple illustre la dépendance contextuelle de la forme acoustique du /d/. La raison de cette dépendance est la **coarticulation**, sur laquelle nous reviendrons en détail plus loin : le mouvement de la langue nécessaire à la production du /d/ se superpose aux commandes articulatoires préparant le phonème qui suit. Ainsi, le son obtenu pour le /d/ est indissociable de celui de la voyelle suivante. Concrètement, la coarticulation pose à nouveau le premier problème de la discrétisation, déjà évoqué dans le cas des voyelles : pour comprendre la parole, il est nécessaire de catégoriser des sons distincts sous une même étiquette -- ici deux sons correspondant à un second formant soit montant soit descendant se traduisent néanmoins par une perception identique du phonème /d/.

```{figure} VdV.png
---
name: VdV.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

## Conclusions temporaires

Nous avons entamé cette section avec pour objectif d'explorer les spectrogrammes de différents phonèmes afin de dévoiler la table de conversion acoustico-phonetique qui permettrait de décoder un son en phonème. En effet, si les phonèmes avaient des formes acoustiques relativement stables, reproduites par les locutrices et locuteurs d'une production à l'autre, il serait alors relativement aisé d'expliquer la capacité de notre cerveau à identifier ces sons. 

Malheureusement notre exploration des voyelles et des consonnes a soulevé deux problèmes théoriques majeurs. D'une part des sons parfois très différents sont perçus comme le même phonème (problème de la discrétisation). D'autre part, deux sons présentant des caractéristiques similaires peuvent être perçus comme un phonème ou un autre, notamment en fonction du contexte (problème du manque d'invariance). Ces deux problèmes remettent sérieusement en question le projet initial d'établir une table de conversion acoustico-phonétique.

: la phonétique est une illusion perceptuelle. Des sons très différents sont perçus de la même manière, tandis que d'autres, identiques, sont compris différemment. Le fait qu'il s'agisse d'une illusion, c'est à dire d'un phénomène dans l'esprit de l'auditeur ou l'auditrice plutôt que dans le son lui même, devient relativement évident lorsqu l'on considère notre capacité à identifier et différencier les phonèmes dans un langage que nous ne connaissons pas.


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

La phonétique acoustique cherche à identifier des similarités entre différentes productions 
d’un même phonème. 
Les formants et transitions de formants sont un élément important du son de parole.
Mais impossible de tracer une correspondance bijective entre phonèmes et formants.
 Seule l’expérimentation psychoacoustique peut permettre de résoudre ce problème 
(i.e. la phonétique expérimentale)




