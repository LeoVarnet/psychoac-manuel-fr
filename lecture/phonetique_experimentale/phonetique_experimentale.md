
```{warning}
Page en cours de construction
```

# Phonétique expérimentale

Le chapitre précédent nous a conduit à la conclusion que l'observation approfondie d'enregistrements de sons de parole n'était pas suffisante pour déterminer les mécanismes perceptifs impliqués dans la compréhension des phonèmes. Il est donc nécessaire de mettre en œuvre des expériences psychoacoustiques afin de tester directement la perception humaine. 

Dans ce qui suit, nous allons mettre au point diverses variantes de la méthode des stimuli constants pour identifier les caractéristiques acoustiques (ou indices acoustiques) qui permettent au système auditif de distinguer les consonnes /b/ et /d/. Bien entendu, ce choix particulier est à titre d'illustration, ces approches pouvant également être déployées pour explorer la perception de n'importe quel phonème. 

Comme nous l'avons vu au chapitre 1, les principales approches psychophysiques nécessitent au préalable de choisir une "dimension d'intérêt", c'est à dire un paramètre physique dont nous souhaitons connaître l'influence sur la perception. Dans un premier temps, nous commençons par nous interroger sur la contribution des différentes fréquences dans l'intelligibilité des sons de parole avant d'investiguer des détails acoustiques plus fins.

## Approche par filtrage

La toute première expérience de psychoacoustique visant à étudier la perception des phonèmes date des années 1920. Elle fut mise au point par Harvey Fletcher, au sein des Bell labs. Ce centre de recherche et développement spécialisé dans les télécommunications dispose alors de systèmes électroniques permettant de filtrer les sons selon des paramètres variables -- une nouveauté pour l'époque. Harvey Fletcher réalise qu'il peut se servir de cet équipement pour étudier la façon dont les humains perçoivent les sons de parole. Son approche est la suivante : il rassemble un grand nombre d'enregistrements de syllabes différant par la consonne initiale (/ba/, /da/, /ga/, /pa/, /ta/, /ka/, /fa/, /sa/, etc.), et filtre chacun de ces sons passe-haut ou passe-bas avec diverses fréquences de coupure, c'est à dire en ne conservant que les informations au-dessus ou en-dessous d'une certaine fréquence.

[Fletcher, 1922; Li, Menon & Allen, 2010]



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
*Continuum de parole filtrée passe-bas. Le premier spectrogramme correspond à un son "ba" clairement intelligible. Les fréquences hautes sont ensuite progressivement filtrées par pas successifs (une nouvelle bande de 450 Hz est retirée à chaque stimulus), de sorte que le dernier stimulus ne conserve que les fréquences de 0 Hz à 500 Hz.*
```

```{figure} Continua_2.png
---
name: Continua_2.png
alt: XXXXX
width: 100%
align: center
---
*Même continuum que {numref}`Continua_1.png`, avec les trajectoires des formants F1, F2, F3 et F4 représentés en bleu.*
```


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
*XXX.*
```

```{figure} Continua_6.png
---
name: Continua_6.png
alt: XXXXX
width: 100%
align: center
---
*XXX.*
```

Quand on modifie la transition de F2, le /b/ devient /d/ puis /g/.

L’approche par continuum de parole synthétique a été généralisée à de nombreuses questions, avec des stimuli synthétiques de plus en plus réalistes.





