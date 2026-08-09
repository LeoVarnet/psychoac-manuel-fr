
```{warning}
Page en cours de construction
```

# Perception catégorielle des phonèmes

Le chapitre précédent nous a conduit à la conclusion que l'observation approfondie d'enregistrements de sons de parole n'était pas suffisante pour déterminer les mécanismes perceptifs impliqués dans la compréhension des phonèmes. Il est donc nécessaire de mettre en œuvre des expériences psychoacoustiques afin de tester directement la perception humaine. 

Dans ce qui suit, nous allons employer diverses variantes de la méthode des stimuli constants pour identifier les caractéristiques acoustiques (ou indices acoustiques) qui permettent au système auditif humain de distinguer les consonnes /b/ et /d/. Bien entendu, ce contraste particulier a été choisi à titre d'illustration, et les mêmes approches peuvent être déployées pour explorer la perception de n'importe quel phonème. 

Comme nous l'avons vu au chapitre 1, la plupart des méthodes psychophysiques nécessitent au préalable de choisir une "dimension d'intérêt", c'est à dire un paramètre physique dont nous souhaitons connaître l'influence sur la perception. Dans un premier temps, nous commençerons par nous interroger sur la contribution des différentes fréquences dans l'intelligibilité des sons de parole avant d'investiguer des détails acoustiques plus fins. L'**approche par filtrage** va nous permettre d'identifier les fréquences du son essentielles à sa compréhension.

## Approche par filtrage

La toute première expérience de psychoacoustique visant à étudier la perception des phonèmes fut mise au point par Harvey Fletcher dans les années 1920, alors qu'il travaillait aux Bell Laboratories. Ce centre de recherche, pionnier dans le domaine des télécommunications, disposait alors de systèmes électroniques innovants pour l'époque qui permettaient de filtrer les sons selon des paramètres de fréquence ajustables. Fletcher comprit rapidement le potentiel de ces outils pour explorer la manière dont les humains perçoivent la parole, marquant ainsi le début d’une approche expérimentale rigoureuse en phonétique expérimentale. 

Son approche reposait sur une méthode de filtrage progressif : en supprimant progressivement des bandes de fréquences, il cherchait à identifier les composantes fréquentielles critiques pour la compréhension des sons de la parole. Pour ce faire, il rassembla un grand nombre d'enregistrements de syllabes consonne-voyelle différant par la consonne initiale (/ba/, /da/, /ga/, /pa/, /ta/, /ka/, /fa/, /sa/, etc.). Chaque enregistrement fut ensuite soumis à différents filtrages passe-haut ou passe-bas, c'est à dire en ne conservant que les informations au-dessus ou en-dessous d'une certaine fréquence de coupure donnée. Les volontaires devaient écouter ces stimuli filtrés, dans un ordre aléatoire, et identifier à chaque fois le phonème perçu. 

```{dropdown} Méthodologie (Fletcher, 1922; Li & Allen, 2009)
**Stimuli** : multiples enregistrements de syllabes formées par une consonne suivie de la voyelle "a" : "pa", "ta", "ka", "fa", "sa", "cha", "ba", "da", "ga", "va", "za", "ja", "ma", "na", et deux autres comportant des consonnes n'existant qu'en anglais -- soit un total de 16 syllabes possibles. Ces enregistrements sont filtrés passe-bas ou passe-haut avec différentes fréquences de coupure.

**Dimension d'intérêt** : fréquence de coupure du filtrage

**Tâche** : intelligibilité ("quelle syllabe avez-vous entendu ?"). Le participant ou la participante répond en appuyant sur un des 16 boutons correspondant aux 16 syllabes possibles.

**Méthode** : méthode des stimuli constants

**Paradigme** : -
```

L'exemple suivant illustre le résultat principal de cette expérience historique. Pour les besoins de cette démo, un unique enregistrement de parole est considéré : un "ba" clairement intelligible. En appliquant un filtrage passe-bas avec des fréquences de coupure de plus en plus basses, nous supprimons progressivement les fréquences aigües du signal, créant ainsi un continuum acoustique le long de notre dimension d'intérêt. Écoutez ces sons de plus en plus altérés en essayant de déterminer à partir de quel point du continuum vous ne parvenez plus à identifier le "ba" initial.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/ba_continuum_LP.wav" type="audio/wav">
</audio>

```{figure} Continua_1.png
---
name: Continua_1.png
alt: XXXXX
width: 100%
align: center
---
*Continuum de parole filtrée passe-bas. Le premier spectrogramme correspond à la syllabe "ba" clairement intelligible. Les fréquences hautes sont ensuite progressivement filtrées par pas successifs (une nouvelle bande de 450 Hz est retirée à chaque stimulus), de sorte que le dernier stimulus ne conserve que les fréquences de 0 Hz à 500 Hz.*
```

La plupart des auditeurs et auditrices rapportent que la qualité du son se dégrade progressivement le long du continuum, mais que le "ba" devient véritablement inintelligible à partir du 9ème stimulus -- c'est à dire quand la fréquence de coupure atteint 1400 Hz. Pour comprendre la raison de cette transition abrupte, la figure suivante représente les positions des formants F1, F2, F3 et F4 pour l’ensemble des stimuli du continuum. 

```{figure} Continua_2.png
---
name: Continua_2.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_1.png`, avec les trajectoires des formants F1, F2, F3 et F4 représentés en bleu.*
```

Les stimuli étant progressivement privés de leurs composantes haute fréquence, les formants disparaissent eux aussi progressivement en commençant par les derniers. Ainsi le F4 est supprimé à partir du simulus numéro 4 et le F3 à partir du stimulus numéro 7. De façon intéressante, le moment où le son "ba" devient subitement inintelligible correspond à la disparition du F2, à partir du 10ème stimulus.

Il est également possible de réaliser la même expérience en supprimant progressivement les basses fréquences pour ne conserver que les fréquences élevées -- ce qui correspond à un filtrage passe-haut -- comme dans la démo suivante :

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/ba_continuum_HP.wav" type="audio/wav">
</audio>

```{figure} Continua_3.png
---
name: Continua_3.png
alt: XXXXX
width: 100%
align: center
---
*Continuum de parole filtrée passe-haut. Le premier spectrogramme correspond à un son "ba" clairement intelligible. Les fréquences basses sont ensuite progressivement filtrées par pas successifs (une nouvelle bande de 450 Hz est retirée à chaque stimulus), de sorte que le dernier stimulus ne conserve que les fréquences de 4550 Hz à 5000 Hz.*
```

Dans ce second exemple, le son "ba" devient inintelligible à partir du stimulus numéro 4. La figure suivante qui représente les trajectoires des formants confirme que, là encore, cette transition brutale d'une syllabe claire à un son incompréhensible correspond au moment de la disparition du F2.

```{figure} Continua_4.png
---
name: Continua_4.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_3.png`, avec les trajectoires des formants F1, F2, F3 et F4 représentés en bleu.*
```

Ces deux exemples sonores semblent donc pointer vers la même conclusion : en l'absence de F2, la consonne "b" n’est pas intelligible. Autrement dit, le cerveau s'appuie sur le F2 pour reconnaître ce phonème.

L'expérience menée par Fletcher était bien sûr plus rigoureuse et mieux contrôlée que la démo ci-dessus (voir encart Méthodologie) ; en particulier les sons correspondant à différentes syllabes et différents filtrages étaient présentés dans un ordre aléatoire. La figure suivante correspond à une réplication récente de cette expérience par l'équipe de Jont Allen à l'Université d'Illinois. Le pourcentage de réponses correctes est ici représenté en fonction de la fréquence de coupure, pour une syllabe "ba" filtrée soit passe-bas (trait rouge), soit passe-haut (trait bleu pointillé). On constate que, dans les deux cas, l’intelligibilité diminue brutalement en dessus ou au dessous de 1500 Hz environ, c'est à dire dans la région du F2, en accord avec notre démo.

```{figure} LiMenonAllen1.png
---
name: LiMenonAllen1.png
alt: XXXXX
width: 60%
align: center
---
*Evolution de l'intelligibilité de la syllabe "ba" filtrée passe-haut (trait bleu pointillé) ou passe-bas (trait rouge), en fonction de la fréquence de coupure. Seules les réponses aux essais où la syllabe "ba" sont présentées ; néanmoins, l'expérience comprenant 16 réponses possibles, le taux de réussite dû à la chance est de 100% / 16 = 6.25% (ligne pointillée noire). Figure adaptée de Li, Menon & Allen (2010).*
```

Cette approche peut être également appliquée à l'analyse des autres consonnes ({numref}`LiAllen2009.png`). Les courbes obtenues diffèrent selon les phonèmes, confirmant que les indices acoustiques impliqués dans leur identification varient d’un phonème à l’autre.

```{figure} LiAllen2009.png
---
name: LiAllen2009.png
alt: XXXXX
width: 70%
align: center
---
*Même représentation que {numref}`LiMenonAllen1.png` pour toutes les consonnes utilisées dans l'expérience. Attention, l'axe des ordonnées correspond ici au taux d'erreurs, et donc inversé par rapport à la figure précédente. En revanche l'axe des abscisses est identique malgré le changement d'unité. Figure adaptée de Li & Allen (2009).*
```

Ce premier type d'expérience nous enseigne ainsi que le second formant est essentiel à la bonne compréhension de la syllabe "ba". Nous allons à présent examiner quelles caractéristiques de ce formant sont déterminantes.

## Approche par synthèse vocale

Dans les années 50, l'équipe d'Alvin Liberman aux Haskins Laboratories développa une approche complémentaire pour identifier les indices acoustiques utilisés dans la compréhnesion des phonèmes, et en particulier pour explorer le rôle de la transition du formant F2 dans dans l’identification du phonème "b". Ce groupe de scientifiques s'appuya pour cela sur un système appelé *Pattern Playback*, l'un des tout premiers synthétiseurs vocaux, mis au point quelques années auparavant. Celui-ci permet de jouer des spectrogrammes de parole peints manuellement sur une bande transparente. Sans entrer dans les détails, il est composé d'une "tête de lecture" devant laquelle défile la bande peinte, et d'un système de conversion des motifs en sons de différentes fréquences. La figure suivante illustre le principe de l'appareil. La vidéo plus bas est extraite d'un [documentaire d'époque](https://www.youtube.com/watch?si=Y0HcXWyeL367lM-v&t=204&v=rCKp7OfoT9Y&feature=youtu.be) qui permet de voir le Pattern Playback en fonctionnement.

```{figure} PatternPlayback.jpg
---
name: PatternPlayback.jpg
alt: XXXXX
width: 70%
align: center
---
*Schéma de fonctionnement du Pattern Playback. Le tapis roulant correspond à la bande transparente sur laquelle sont dessinés des motifs spectrographiques. Ceux-ci passent entre un faisceau lumineux et une série de photorécepteurs, ce qui permet de "lire" la composition spectrale dessinée à chaque instant, alors que la bande progresse. Ce système de tête de lecture est ensuite connecté à un amplificateur qui convertit chaque fréquence lue en le son correspondant. Figure issue de Cooper, Liberman, Borst (1951)*
```

<video controls width="500">
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/PatternPlayback.mp4" type="video/mp4">
</video>

Munie de ce nouvel outil, l'équipe de Liberman s'employa à explorer la perception des phonèmes. En effet, la synthèse vocale permettait désormais de manipuler de façon fine et contrôlée n'importe quel paramètre du son, afin d’en observer l’impact sur la perception auditive. Une expérience marquante, publiée en 1954, illustre cette approche : elle porte sur la perception des consonnes plosives, en particulier les syllabes "ba", "da" et "ga". À partir d’une représentation spectrographique du son "ba", les chercheurs en produisirent une version synthétique à l’aide du *Pattern Playback*. Ensuite, ils générèrent des variantes de ce son en modifiant uniquement la fréquence d’attaque du deuxième formant (F2). Les sons synthétiques étaient présentés dans un ordre aléatoire à des participants et participantes, qui devaient les catégoriser comme "ba", "da", ou "ga".

```{dropdown} Méthodologie (Liberman, Delattre, Cooper, 1954)
**Stimuli** : multiples syllabes synthétiques reproduisant les trajectoires des formants de "ba", mais avec une modification de la fréquence d'attaque du deuxième formant.

**Dimension d'intérêt** : fréquence d’attaque du 2ème formant.

**Tâche** : catégorisation "ba"/"da"/"ga"

**Méthode** : méthode des stimuli constants

**Paradigme** : yes/no
```

La {numref}`Continua_5.png` représente un continuum similaire à celui utilisé par Liberman, créé ici au moyen d'un autre outil de synthèse vocale rudimentaire, le synthétiseur de Klatt. Tous les sons de parole qui le composent sont exactement identiques, à l'exception de l'attaque du F2 (voir {numref}`Continua_6.png`) qui évolue par pas égaux depuis 900 Hz dans le premier son jusqu'à 2400 Hz dans le dernier. Vous pouvez écouter ce continuum ci-dessous. Par souci de simplicité, les stimuli sont ici joués dans l'ordre en commençant par la syllabe "ba" originale. 

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/badaga_continuum.wav" type="audio/wav">
</audio>

```{figure} Continua_5.png
---
name: Continua_5.png
alt: XXXXX
width: 100%
align: center
---
*Continuum de parole synthétique. Le premier son correspond à un "ba" généré avec un algorithme de synthèse rudimentaire (synthétiseur de Klatt). Un seul des paramètres acoustiques de ce stimulus est ensuite varié : la fréquence d'attaque du F2. Celle-ci est fixée à 900 Hz dans le premier stimulus, puis évolue par pas de 150 Hz jusqu'à atteindre 2400 Hz dans le dernier stimulus. En conséquence, la pente d'attaque du F2 est montante au début du continuum, mais descendante à la fin.*
```

Liberman et ses collègues observèrent que les participants et participantes percevaient les stimuli du continuum comme des "ba" pour les fréquences d'attaque basses, puis des "da" pour les fréqunces d'attaque intermédiaires, et enfin des "ga" pour les fréquences d'attaque hautes. Puisque seul le F2 diffère entre les stimuli du continuum ({numref}`Continua_6.png`), ce résultat confirme que le F2 joue un rôle clé dans la compréhension de la consonne "b" -- comme nous l'avions noté dans l'expérience précédente. Mais il permet également de préciser cette conclusion : c'est plus spécifiquement l'attaque de ce formant qui permet de distinguer le "b" du "d" et du "g".

```{figure} Continua_6.png
---
name: Continua_6.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_5.png`, avec les trajectoires des formants F1, F2 et F3 représentés en bleu.*
```

Cette approche par continuum de parole synthétique s’avère donc particulièrement utile pour identifier les indices acoustiques impliqués dans la perception des phonèmes. En effet, elle permet de tester le rôle d’une caractéristique acoustique spécifique dans la compréhension des sons. Pour cela, il suffit aux scientifiques de construire un continuum de stimuli où seule cette caractéristique varie, puis d'observer si la perception évolue le long de ce continuum. Si c'est le cas, l'expérience valide l’implication de cette caractéristique dans la reconnaissance des phonèmes. Il n'est donc pas surprenant que cette méthode ait été utilisée abondamment, tout d'abord par l'équipe de Liberman pour explorer tous les types de consonnes (voir {numref}`Delattre1968.png`), puis plus récemment par d'autres scientifiques qui ont mis au point des stimuli synthétiques de plus en plus réalistes.

<!-- ```{figure} Winn2020.png -->
<!-- --- -->
<!-- name: Winn2020.png -->
<!-- alt: XXXXX -->
<!-- width: 70% -->
<!-- align: center -->
<!-- --- -->
<!-- *.* -->
<!-- ``` -->

```{figure} Delattre1968.png
---
name: Delattre1968.png
alt: XXXXX
width: 70%
align: center
---
*Synthèse des résultats obtenus par l'équipe de Liberman en appliquant l'approche par continuum de parole synthétique à l'étude de différentes consonnes. Le spectrogramme de chaque consonne du français est ici représenté de façon schématique pour souligner les principaux indices acoustiques impliqués dans la compréhension. Figure issue de Delattre (1968).*
```

## La perception catégorielle

Les conclusions de l'expérience de Liberman et collègues ne se limitent pas à l'identification des indices acoustiques, mais portent également sur le mécanisme de compréhension des phonèmes. Observons de plus près les résultats de l'expérience du continuum synthétique, {numref}`Liberman3.png` (partie supérieure). Le pourcentage de réponses "ba", "da", ou "ga" est représenté en fonction du numéro du stimulus, c'est à dire le long du continuum. On peut noter que la compréhension "bascule" brutalement d'une syllabe à une autre. Autrement dit, la plupart des sons sont perçus sans ambiguïté comme un "ba", un "da", ou un "ga" (à l'exception des stimuli numéros 4, 9 et 10, seuls à produire des pourcentages de réponse intermédiaires entre 0% et 100%). Pourtant le continuum de parole synthétique a été conçu par pas égaux et progressifs. On voit donc que **le long d'un continuum physique linéaire, la perception peut être hautement discontinue**. En d'autres termes, un son à mi-chemin entre "ba" et "da" n'est pas perçu comme une syllabe à mi-chemin entre ces deux 

Speech sounds are treated discontinuously;  a sound that is acoustically halfway between bat and pat does not mean something halfway between batting and patting. (Pinker, Language instinct)

discrimination entre deux stimuli adjacents

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/badaga_disc.wav" type="audio/wav">
</audio>

Les différences de F2 ne sont pas perçues (performance de discrimination ≈ 50%), sauf entre deux catégories.

```{figure} Liberman3.png
---
name: Liberman3.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

Perception catégorielle : définition
1. La fonction psychométrique de catégorisation de phonème a une très forte pente ( peu de stimuli ambigus). Le seuil à 50% s’appelle frontière phonémique. 
2. La discrimination au niveau d’une frontière phonémique est facilitée. Au contraire, les exemplaires d’une même catégorie phonémique sont difficiles à différencier.


```{figure} Chang2010.png
---
name: Chang2010.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

Perception catégorielle de la parole : 
La perception des phonèmes (catégorisation et discrimination) présente des discontinuités marquées au niveau des frontières phonémiques.
Permet de subdiviser l’espace acoustique ! (comme figure 91)




Perception catégorielle : un mécanisme perceptuel très général

```{figure} Todorova2020.png
---
name: Todorova2020.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

Certaines catégories (mais pas toutes) dépendent de la culture :
P.ex., les différentes langues n’ont pas le même répertoire 
de phonèmes
debt-death-deaf (/t/-/θ/-/f/) 
dough-thought-fought (/d/-/θ/-/f/)
bit-beat (/ɪ/-/iː/)
… donc pas les mêmes frontières phonémiques.
 
Les frontières sont apprises au cours du développement de 
l’enfant (dans les 6 premiers mois de la vie, capacités de 
discrimination des phonèmes non-spécifiques à la langue). 

```{figure} Miyawaki1975.png
---
name: Miyawaki1975.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

Les catégorisations spontanées surviennent en permanence dans notre cerveau et dépendent non seulement de notre langue, mais aussi de notre culture.
Une catégorie réunit utilement un ensemble d’éléments. Elle rend disponibles des propriétés qui ne sont pas immédiatement perceptibles. 
Sans perception catégorielle, pas de langage ni de pensée organisée.


Les catégorisations spontanées effectuées par et dans nos cerveaux surviennent en permanence et dépendent non seulement de notre langue, mais aussi de notre époque, de notre culture et de notre état d’âme. Elles s’écartent considérablement du stéréotype de ce qu’est la catégorisation. En effet, la vision intuitive de ce mécanisme psychologique est qu’il consiste à ranger des entités de l’environnement dans des catégories mentales […]  
Une catégorie réunit un ensemble d’éléments avec profit pour l’être qui la possède. Elle rend disponibles des propriétés qui ne sont pas immédiatement perceptibles. […]  
Cela les a conduits à des théories de la catégorisation qui récusent le rôle des définitions précises et font plutôt appel à la proximité soit avec des prototypes, entités mentales génériques stockées en mémoire et qui résument de façon concise toutes les expériences antérieures qu’une personne a eues avec la catégorie en question, soit avec l’ensemble de tous les exemplaires de la catégorie qui ont déjà été rencontrés […]  
l’origine de ces efforts se trouve l’idée novatrice de catégories non homogènes, dotées de degrés forts ou faibles d’appartenance, ce qui revient à distinguer entre membres plus centraux et moins centraux d’une catégorie. […]  
La diversité des niveaux d’abstraction auxquels il peut être approprié de catégoriser est due à la fois à l’importance que prennent le fait de distinguer et celui de regrouper. Durant le repas, on distingue son assiette et celle du voisin, puis elles sont confondues dans le buffet. Un réfrigérateur et un piano ont des usages bien différents, mais pour des déménageurs, il s’agira avant tout de meubles encombrants.[…]  
priorité lorsque l’on aborde n’importe quel domaine inconnu est de se familiariser avec les entités qui font partie du domaine et de savoir les différencier, parce que pour connaître il faut reconnaître. En ce sens, catégoriser, c’est distinguer. […]  
une personne demande à une autre quelque chose d’aussi anodin que : « Tes frites sont bonnes ? », son interlocuteur devrait en toute rigueur lui répondre : « Les six que j’ai mangées jusqu’à présent étaient vraiment excellentes, mais du fait que je n’ai pas goûté les autres dans mon assiette, je ne suis pas en mesure de dire quoi que ce soit avec certitude.  
Les catégories sont des boîtes ; catégoriser, c’est mettre dans une boîte. C’est à cette analogie naïve qu’est due la croyance quasiment irrépressible évoquée au chapitre 4 selon laquelle les objets (et les situations) qui nous entourent auraient tous une catégorie privilégiée d’appartenance qui constituerait leur identité intrinsèque. […] En effet, il se trouve que l’approche de la catégorisation qui était partagée par la quasi-totalité des psychologues expérimentalistes jusque dans le milieu des années 1970, lorsque la psychologue Eleanor Rosch a publié des travaux rendant intenable cette position, était très similaire à cette analogie naïve. Transposition « logico-mathématique » de la vision naïve, elle considérait l’appartenance catégorielle comme déterminée par un ensemble de propriétés précises, nécessaires et suffisantes : on fait partie de la catégorie (on est dans la boîte) si et seulement si on a les propriétés requises ; sinon on est en dehors de la boîte.  
(Hofstadter, l'Analogie)

Sans cette capacité d’abstraction nos vies ressembleraient à celle d’**Irénée Funes, personnage d’une nouvelle de Jorge Luis Borges**, pour qui une chute de cheval eut la conséquence funeste qu’il « se rappelait chaque feuille de chaque arbre de chaque bois, mais […] était presque incapable d’idées générales platoniciennes. Non seulement il lui était difficile de comprendre que le symbole générique chien embrassât tant d’individus dissemblables et de formes diverses ; cela le gênait que le chien de trois heures quatorze (vu de profil) eût le même nom que le chien de trois heures un quart (vu de face) ». À l’inverse de Funes, l’être humain a naturellement la faculté d’abstraire pour faire face à la diversité du monde (Hofstadter, l'Analogie)

Nos catégories sont de grandes simplifications des structures de l’univers mais, bien choisies, elles sont extraordinairement efficaces pour nous permettre de sonder et prévoir ce qui se passe autour de nous. (boucle étrange)

"Our sensory experience is informationally rich and profuse in a way that our cognitive utilization of it is not." (Dretske, 1981b, p.146).  

```{figure} 1000chairs.png
---
name: 1000chairs.png
alt: XXXXX
width: 70%
align: center
---
*.*
```


```{figure} Hofstadter1985.png
---
name: Hofstadter1985.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

Conclusions: 
La perception catégorielle distord l’espace perceptuel. 
Elle revient à ignorer les variations non pertinentes (au sein d’une catégorie)…
…tout en améliorant la sensibilité aux variations pertinentes (entre catégories).
Elle réalise ainsi une forme de conversion analogique-numérique (espace physique continu → espace perceptuel discret)
Les formants et transition des formants jouent un rôle fondamental dans la reconnaissance des phonèmes (p.ex. attaque du F2 pour /b/-/d/-/g/)
Le problème du manque d’invariance subsiste.

## Références


[Fletcher, 1922; Li, Menon & Allen, 2010; Li allen 2009]
Cooper, Liberman, Borst (1951)
(Liberman, Delattre, Cooper, 1954)
Delattre (1968)
