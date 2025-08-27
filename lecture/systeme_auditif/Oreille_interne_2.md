# Oreille interne, partie 2 : cellules ciliées et nerf auditif

```{warning}
Page en cours de construction
```

Dans la précédente section de ce chapitre, nous avons vu comment les vibrations transmises à l'oreille interne excitent localement la membrane basilaire, permettant la décomposition du son en différentes fréquences. Nous allons à présent nous intéresser à la seconde fonction essentielle de l'oreille interne : la conversion des vibrations mécaniques en impulsions électriques. Cette étape, appelée **transduction**, est fondamentale puisque le cerveau est en mesure de recevoir et traiter une information électrique, mais non une vibration mécanique. Dans un second temps, nous envisagerons la troisième fonction de la cochlée : l'amplification/compression.

```{figure} SysAudExt_IE.JPG
---
name: SysAudExt_IE.JPG
alt: Systeme auditif externe - oreille interne 
width: 100%
align: center
---
*Schéma du système auditif périphérique mettant en évidence l'oreille interne. (Source : [Ivy Livingstone, Biodidac](https://omeka.uottawa.ca/biodidac/items/show/4603))*
```

## Cellules ciliées internes et codage temporel

La conversion de l'onde en courant électrique est assurée par environ 3500 **cellules ciliées internes**, réparties sur toute la longueur de la membrane basilaire (voir {numref}`Organ_of_Corti.png` et {numref}`Hair_cell.png`). Comme leur nom l'indique, ces cellules sont dotées, à leur extrémité supérieure, de fins prolongements appelés **stéréocils**, organisés en rangées de hauteurs croissantes. Les stéréocils sont extrêmement sensibles aux mouvements : un déplacement latéral des stéréocils provoque une cascade de réactions électrochimiques qui conduit à la génération d'un **potentiel d'action** -- c'est-à-dire une impulsion électrique. La partie inférieure de la cellule ciliée est connectée aux fibres du nerf auditif, permettant ainsi de transmettre l'information électrique aux étages supérieurs du système auditif et jusqu'au cerveau.

```{figure} Organ_of_Corti.png
---
name: Organ_of_Corti.png
alt: Schéma en coupe de la cochlée
width: 100%
align: center
---
*Schéma en coupe de la cochlée. (Source : [Openstax](https://openstax.org/books/anatomy-and-physiology/pages/14-1-sensory-perception))*
```

```{figure} Hair_cell.png
---
name: Hair_cell.png
alt: Schéma des cellules cilliées
width: 100%
align: center
---
*Schéma des cellules cilliées. (Source : [Openstax](https://openstax.org/books/anatomy-and-physiology/pages/14-1-sensory-perception))*
```

Ainsi, la cellule ciliée est capable de convertir un mouvement latéral de ses stéréocils en une impulsion électrique. Mais comment cette propriété est-elle exploitée pour coder les vibrations de la membrane basilaire ? La clé réside dans une structure spécialisée : **l'organe de Corti** (voir {numref}`Organ_of_Corti.png` et {numref}`I_H_Hair_cell.png`). Les cellules ciliées internes décrites plus haut sont attachées à la membrane basilaire, mais leurs stéréocils sont reliés à une seconde membrane, la membrane tectoriale, disposée parallèlement à la première. Lorsqu'une onde sonore progresse le long de la cochlée, elle induit un déplacement vertical de la membrane basilaire. Ce mouvement provoque un glissement des deux membranes l'une par rapport à l'autre, entraînant un déplacement latéral des stéréocils ce qui déclenche un potentiel d'action. Le cisaillement mécanique est ainsi converti en signal électrique par la cellule ciliée.

```{figure} I_H_Hair_cell.png
---
name: I_H_Hair_cell.png
alt: Schéma de l'ogane de Corti
width: 70%
align: center
---
*Schéma de l'ogane de Corti. (Source : [Gray's Anatomy](https://www.bartleby.com/lit-hub/anatomy-of-the-human-body/fig-931/))*
```

Les cellules ciliées internes sont entraînées par les mouvements de la membrane basilaire au point précis où elles sont attachées. Elles transmettent ainsi au nerf auditif l'information tonotopique évoquée précédemment, sous forme de signaux électriques : chaque fréquence sonore stimule un groupe spécifique de cellules ciliées, plus ou moins proche de la base de la cochlée.

Mais ce n'est pas tout : l'onde sonore étant composée de fluctuations périodiques, les déplacements de la membrane basilaire et des stéréocils le sont également. La figure xxx représente la charge électrique d'une cellule en réponse à des tons purs de différentes fréquence. Pour des fréquences lentes (en dessous de 1 kHz), on observe effectivement que l'activité électrique de la cellule reproduit assez fidèlement la périodicité de l'onde sonore. Ceci constitue le principe du **codage temporel** : les cellules ciliées déchargent de façon globalement synchrone avec les vibrations de la membrane basilaire. Il est donc possible de déduire la fréquence du son en observant la fréquence du signal électrique transmis.

Cependant, ce mécanisme a ses limites. En réalité, la cellule ciliée ne peut pas réagir instantanément à chaque mouvement des stéréocils : elle a besoin d'un temps très court pour se recharger avant de pouvoir produire à nouveau un potentiel d'action. Pour des sons de fréquence basse, comme on l'a vu, ce délai est suffisamment court pour permettre à la cellule de suivre chaque cycle sonore. En revanche, lorsque la fréquence augmente au delà de 1 kHz, les vibrations deviennent trop rapides pour que la cellule puisse réagir à chaque période de l'onde. Dans ce cas, la réponse électrique devient plus stable et plus constante. Au lieu de refléter les détails temporels fins du son, elle reflète surtout l'intensité moyenne de la fréquence considérée (figure xxx).

```{figure} Phaselock.png
---
name: Phaselock.png
alt: Phase-locking
width: 60%
align: center
---
* (Palmer & Russel, 1986)*
```

**Le codage des fréquences par l'oreille interne est donc double**. D'une part, chaque fréquence active une région spécifique de la membrane basilaire, mobilisant un sous-ensemble distinct de cellules ciliées (codage tonotopique). D'autre part, les potentiels d'action suivent approximativement le rythme des vibrations, rendant le signal électrique lui-même périodique (codage temporel). Par ailleurs, ces deux codes présentent chacun des limitations spécifiques dans les hautes fréquences : le codage tonotopique devient de moins en moins précis pour les fréquences élevées, tandis que le codage temporel ne peut pas suivre fidèlement la périodicité du son au delà de 1 kHz environ.
## Modéliser l'oreille interne (partie 2) : spectrogramme auditif

Nous avons vu précédemment comment le pattern d'excitation permet de rendre compte du codage tonotopique au sein de la cochlée. En revanche, ce modèle purement fréquentiel ne rend pas compte du codage temporel, qui repose sur l'organisation dans le temps des impulsions électriques. Il est toutefois possible d’en obtenir une approximation en considérant le décours temporel de la sortie de chaque filtre gammatone -- qui correspond aux oscillations de la membrane basilaire en un point spécifique. La figure suivante illustre ces vibrations en réponse à un complexe harmonique pour six gammatones spécifiques. Sans surprise, le gammatone accordé à la fréquence fondamentale (ici 500 Hz) produit un signal périodique à la méme fréquence, tandis qu'un gammatone accordé à 1200 Hz est relativement peu excité. Les filtres gammatones de fréquence d'accordage élevée sont, comme on l'a vu précédemment, trop larges pour isoler une composante harmonique. Au contraire, ils englobent plusieurs composantes proches, produisant un phénomène de battement à la fréquence fondamentale. Ainsi, **dans les basses fréquences, région des harmoniques résolues, les sorties des gammatones sont périodiques, mais dans les hautes fréquences, où les harmoniques sont non-résolues, l'envelope des fluctuations est périodique à la fréquence fondamentale**.

```{figure} pattern4.png
---
name: pattern4.png
alt: Sortie temporelle des filtres gammatones
width: 60%
align: center
---
*Sortie temporelle des filtres gammatone.*
```

Pour modéliser le taux de décharges des cellules cilliées, c'est-à-dire le nombre de potentiels d'action transmis au nerf auditif à un instant donné, une approximation simple consiste à prendre la valeur absolue de la sortie du gammatone, puis de le filtrer passe-bas en dessous de 1 kHz [en effet, les cellules ciliées ne déchargent que lors des pics positif de l'onde, et elles sont incapables de suivre des fréquences au delà de 1 kHz environ]. Ceci revient en pratique à extraire l'enveloppe du signal. En affichant cette enveloppe en fonction de la fréquence centrale du gammatone et du temps, on obtient une représentation spectro-temporelle appelée **spectrogramme auditif**. Chaque ligne de cette représentation correspond à une position le long de la cochlée et les nuances de couleurs indiquent le taux de décharges des cellules cilliées correspondantes, au cours du temps.

```{figure} AuditorySpectrogram.png
---
name: AuditorySpectrogram.png
alt: Spectrogramme auditif
width: 100%
align: center
---
*Spectrogramme auditif.*
```

Trois spectrogrammes auditifs sont représentés figure xxx. Le premier correspond à l'écoute d'un simple ton pur à 300 Hz. On identifie aisément le codage tonotopique (présence d'une bande horizontale, c'est à dire d'une région de la cochlée particulièrement excitée par le ton pur), mais également le codage temporel (périodicité à 300 Hz de l'excitation). On retrouve ce double code dans le spectrogramme auditif de deux tons purs. Dans le cas du complexe harmonique, la fréquence fondamentalementale est identifiable simultanément par le codage tonotopique (harmoniques résolues dans les basses fréquences marquées par des bandes horizontales), le codage temporel dans les basses fréquences, mais également le codage temporel dans les hautes fréquences grâce au phénomène de battement vu plus haut.

## Cellules cilliées externes et amplification-compression

La troisième et dernière fonction de la cochlée est d'effectuer une compression de dynamique. En effet, l'oreille humaine est capable de percevoir des sons très faibles (de l'ordre de quelques dB SPL) mais également des sons très forts (le seuil de douleur se situant approximativement à 120 dB SPL). L'écart entre les deux représente une gamme de 120 dB, c'est à dire un facteur xxx. Ceci est rendu possible grâce à une étape de compression du signal lors de la transduction.

La compression est notamment assurée par les ~25000 **cellules ciliées externes**. Celles-ci sont disposées tout le long de la cochlée, comme les cellules ciliées internes, mais organisées en trois rangées (voir xxx). Les deux types de cellules possèdent une structure similaire mais fonctionnent sur un principe opposé : tandis que les cellules ciliées internes convertissent un mouvement mécanique en impulsion électrique envoyée dans les fibres du nerf auditif, les cellules ciliées externes convertissent une impulsion électrique venue du nerf auditif en mouvement mécanique. Ainsi, la cellule ciliée externe se contracte sous l'effet d'une commande électrique. Étant fixée à la membrane basilaire et reliée par ses stéréocils à la membrane tectoriale, elle peut ainsi amplifier ou atténuer les oscillations au sein de la cochlée. Ce mécanisme actif de rétroaction peut être mis en évidence en comparant les tuning curves mesurées sur un organisme vivant et sur un organisme mort (voir figure suivante). Dans ce dernier cas le fonctionnement mécanique passif de la cochlée est toujours en œuvre, mais les mécanismes actifs -- notamment liés aux cellules ciliées externes -- sont éteints.

```{figure} Postmortem.jpeg
---
name: Postmortem.jpeg
alt: Isoresponse tuning curve pre-/post mortem
width: 70%
align: center
---
*Isoresponse tuning curve pre-/post mortem.*
```

Comme on le constate sur la figure, les *tuning curves* mesurées post-mortem -- et correspondant donc au fonctionnement purement mécanique de la cochlée -- sont très atténuées (xxx dB au maximum) et relativement larges. La viscosité de la périlymphe et la résistance de la membrane basilaire entraînent une grande déperdition d'énergie et on voit donc que l'idée d'une cochlée fonctionnant sur la seule base de l'action mecanique de l'onde entrante n'est pas tenable. Seule l'existence de mécanismes actifs compensant le damping et améliorant la sélectivité fréquentielle permet d'expliquer la grande efficacité de la cochlée dans la transmission de l'information. 

Néanmoins, ce système de feedback actif est plus ou moins sollicité en fonction du niveau sonore : il renforce la perception des sons faibles mais laisse les sons forts être naturellement atténués. Ceci peut être observé en comparant les *tuning curves* mesurées en une même position pour des stimuli de différentes intensité (figure xxx). 

```{figure} TuningGain.png
---
name: TuningGain.png
alt: tuning curve effect of level
width: 70%
align: center
---
*tuning curve effect of level.*
```

Lorsque le niveau sonore est faible, les tuning curves possédent une excellente résolution et [check] n'atténuent pas les sons au niveau de leur fréquence d'accordage. En revanche, à des niveaux sonores élevés, la tuning curve devient très peu sélective et atténuent fortement les sons (xxx dB et plus). De façon prévisible, le même phénomène peut également être observé au niveau des patterns d'excitation (voir figure xxx)

> Efferent system Brownell, Bader, Bertrand, and Ribaupierre (1985) showed that electrical stimulation of the outer hair cells could lead to their contraction, and Ashmore (1987) reported that this outer contraction occurred with an extremely short latency (120 ls). Therefore, it seems possible that the response of the inner hair cell receptors can be modulated by efferent stimulation of the outer hair cells for frequencies up to the kilohertz range. While it is of interest to study directly the effects produced by efferent stimulation of the outer hair cells, there are experimental difficulties, including the sensitivity of the efferent system to anesthesia. Despite these problems, Winslow and Sachs (1988) have provided neurophysiological evidence that the efferent olivocochlear bundle can improve the sensitivity of afferent auditory nerve fibers to tonal signals in the presence of interfering noise. This is consistent with the earlier behavioral report by Dewson (1968) that discrimination between two vowels in the presence of noise by monkeys was impaired by sectioning of the efferent olivo-cochlear bundle. (Warren)

## Modéliser l'oreille interne (partie 3) : DRNL

Il est possible de mettre à jour le modèle de la cochlée comme un banc de filtres gammatones, vu précédemment, pour prendre en compte l'effet des cellules ciliées externes. Une première option très simple consiste à appliquer une fonction compressive (par exemple une loi puissance avec un exposant négatif) sur la sortie des gammatones. Ceci n'est cependant pas entièrement satisfaisant car la cochlée ainsi simulée, si elle réalise bien une compression de dynamique, conserve cependant la même résolution fréquencielle quel que soit le niveau sonore d'entrée. Une seconde option, légèrement plus sophistiquée, s'appuie sur des *dual-resonance nonlinear filters* (**filtres DRNL**). Ces filtres non-linéaires reproduisent l'évolution des *tuning curves* avec le niveau sonore, illustré figure xxx. Pour cela, ils combinent en réalité deux branches : la première, linéaire et semblable aux gammatones mais avec une résolution plus faible, correspond à l'action mécanique du système, tandis que la deuxième, non-linéaire et plus sélective en fréquence, rend compte des mécanismes actifs (voirfig xxx).


```{figure} DRNL.png
---
name: DRNL.png
alt: DRNL
width: 70%
align: center
---
*DRNL.*
```

## Nerf auditif


```{figure} ANtonotopy.png
---
name: ANtonotopy.png
alt: tonotopy in the auditory nerve
width: 50%
align: center
---
*tonotopy in the auditory nerve (red: 20 Hz; green: 1 kHz; blue 20 kHz).*
```



Par conséquent, les impulsions électriques envoyées au nerf auditif par les cellules ciliées présentent, elles aussi, une périodicité à la même fréquence ({numref}`PhaseLocking.png`). 


```{figure} PhaseLocking.png
---
name: PhaseLocking.png
alt: Phase-locking
width: 60%
align: center
---
*Illustration du principe du codage temporel. La partie supérieure de la figure représente l'onde sonore. En dessous sont schématisés les potentiels évoqués générés par trois cellules ciliées internes accordées à la fréquence de cette onde, et transmis au nerf auditif. Les décharges surviennennt globalement à proximité des maxima de la vibration, même si tous les maxima ne donnent pas nécessairement lieu à une décharge synchrone de toutes les cellules, certaines impulsions pouvant être absentes ou décalées. Néanmoins, chaque cellule émet des impulsions électriques avec une périodicité globalement alignée sur celle de l'onde. Dans la partie inférieure de la figure, la sommation des décharges provenant de l'ensemble des cellules ciliées montre que, malgré une certaine variabilité, le signal global transmis au nerf auditif reproduit la périodicité du stimulus sonore. (Source: Plack 2005)*
```
