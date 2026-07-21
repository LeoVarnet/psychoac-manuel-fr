
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

L'exemple suivant illustre le principe de cette expérience historique. Pour les besoins de cette démo, je n'ai utilisé qu'un unique enregistrement de parole : un "ba" clairement intelligible. En appliquant un filtrage passe-bas avec des fréquences de coupure de plus en plus basses, nous supprimons progressivement les fréquences aigües du signal, créant ainsi un continuum acoustique le long de notre dimension d'intérêt. Écoutez ces sons de plus en plus altérés en essayant de déterminer à partir de quel point du continuum vous ne parvenez plus à identifier le "ba" initial.

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



[Fletcher, 1922; Li, Menon & Allen, 2010]



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

```{figure} Continua_4.png
---
name: Continua_4.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_3.png`, avec les trajectoires des formants F1, F2, F3 et F4 représentés en bleu.*
```

Stimuli : syllabes consonne+/a/, filtrées passe-bas ou passe-haut. 
Dimension : fréquence de coupure du filtrage
Tâche : intelligibilité
Méthode : méthode des stimuli constants
Paradigme : -



```{figure} LiMenonAllen1.png
---
name: LiMenonAllen1.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Quand le F2 disparait, /b/ n’est plus intelligible.

```{figure} Fletcher22.png
---
name: Fletcher22.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

```{figure} LiAllen2009.png
---
name: LiAllen2009.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```


## Approche par synthèse vocale

[Liberman, Delattre, Cooper, 1954]

Evaluer le rôle de la transition du formant F2 dans dans l’identification du phonème /b/…
…En utilisant un Pattern Playback
Pattern Playback : l’un des premiers synthétiseurs de parole [Cooper, Liberman, Borst, 1951]


```{figure} PatternPlayback.jpg
---
name: PatternPlayback.jpg
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Stimuli : syllabes synthétiques consonne+/a/
Dimension : fréquence d’attaque du 2ème formant.
Tâche : catégorisation /b/-/d/
Méthode : méthode des stimuli constants
Paradigme : yes/no



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

```{figure} Continua_6.png
---
name: Continua_6.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_5.png`, avec les trajectoires des formants F1, F2 et F3 représentés en bleu.*
```

Quand on modifie la transition de F2, le /b/ devient /d/ puis /g/.

L’approche par continuum de parole synthétique a été généralisée à de nombreuses questions, avec des stimuli synthétiques de plus en plus réalistes.


```{figure} Winn2020.png
---
name: Winn2020.png
alt: XXXXX
width: 70%
align: center
---
*.*
```


```{figure} Delattre1968.png
---
name: Delattre1968.png
alt: XXXXX
width: 70%
align: center
---
*.*
```

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
