# Oreille interne, partie 2 : cellules ciliées et nerf auditif

```{warning}
Page en cours de construction
```

Dans la précédente section de ce chapitre, nous avons vu comment les vibrations transmises à l'oreille interne excitent localement la membrane basilaire, permettant la décomposition du son en différentes fréquences. Nous allons à présent nous intéresser à la seconde fonction essentielle de l'oreille interne : la conversion des vibrations mécaniques en impulsions électriques. Cette étape, appelée **transduction**, est fondamentale puisque le cerveau est en mesure de recevoir et traiter une information électrique, mais non une vibration mécanique. Dans un second temps, nous envisagerons la troisième fonction de la cochlée : l'amplification/compression des signaux.

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

La conversion de l'onde en courant électrique est assurée par environ 3500 **cellules ciliées internes**, réparties sur toute la longueur de la membrane basilaire (voir {numref}`Organ_of_Corti.png` et {numref}`Hair_cell.png`). Comme leur nom l'indique, ces cellules sont dotées, à leur extrémité supérieure, de fins prolongements appelés **stéréocils**, organisés en rangées de hauteurs croissantes. Les stéréocils sont extrêmement sensibles aux mouvements : un déplacement latéral des stéréocils provoque une cascade de réactions électrochimiques qui conduit à une variation du potentiel électrique de la cellule puis à la libération d'un neurotransmetteur, le glutamate. Ce dernier va ensuite se fixer aux récepteurs des fibres du nerf auditif, connectées à la base de la cellule, déclenchant la génération d'un **potentiel d'action**, une impulsion électrique envoyée aux étages supérieurs du système auditif. 

```{figure} Organ_of_Corti.png
---
name: Organ_of_Corti.png
alt: Schéma en coupe de la cochlée
width: 100%
align: center
---
*Schéma de la cochlée en coupe avec un zoom sur l'organe de Corti. (Source : [Openstax](https://openstax.org/books/anatomy-and-physiology/pages/14-1-sensory-perception))*
```

```{figure} Hair_cell.png
---
name: Hair_cell.png
alt: Schéma des cellules cilliées
width: 100%
align: center
---
*Schéma de la cochlée en coupe avec un zoom sur les cellules cilliées. (Source : [Openstax](https://openstax.org/books/anatomy-and-physiology/pages/14-1-sensory-perception))*
```

Ainsi, la cellule ciliée est capable de convertir un mouvement latéral de ses stéréocils en une impulsion électrique, ensuite transmise au cerveau. Mais comment cette propriété est-elle exploitée pour coder les vibrations de la membrane basilaire ? La réponse réside dans une structure spécialisée : **l'organe de Corti** (voir {numref}`Organ_of_Corti.png` et {numref}`I_H_Hair_cell.png`). Les cellules ciliées internes décrites plus haut sont attachées à la membrane basilaire, mais leurs stéréocils sont reliés à une seconde membrane, la membrane tectoriale, disposée parallèlement à la première. Lorsqu'une onde sonore progresse le long de la cochlée, elle induit un déplacement vertical de la membrane basilaire. Ce mouvement provoque un glissement des deux membranes l'une par rapport à l'autre, entraînant un déplacement latéral des stéréocils ce qui génère un potentiel d'action dans les fibres du nerf auditif reliées à la cellule.

```{figure} I_H_Hair_cell.png
---
name: I_H_Hair_cell.png
alt: Schéma de l'ogane de Corti
width: 70%
align: center
---
*Schéma de l'ogane de Corti. (Source : [Gray's Anatomy](https://www.bartleby.com/lit-hub/anatomy-of-the-human-body/fig-931/))*
```

Chaque cellule ciliée interne est ainsi activée par les vibrations de la membrane basilaire à l’endroit précis où elle est fixée. Ceci permet de transmettre au nerf auditif l'information tonotopique évoquée précédemment, sous forme de signaux électriques : chaque fréquence sonore excite un groupe particulier de cellules ciliées, situé à une position spécifique le long de la cochlée -- les fréquences élevées près de la base, les basses fréquences vers l’apex.

Mais ce n'est pas tout : l'onde sonore étant composée de fluctuations périodiques, les déplacements de la membrane basilaire et des stéréocils le sont également. La {numref}`Phaselock.png` représente la charge électrique d'une cellule en réponse à des tons purs de différentes fréquence. Pour des fréquences lentes (en dessous de 1 kHz), on observe effectivement que le potentiel électrique de la cellule suit assez fidèlement la périodicité de l'onde sonore. Ceci constitue le principe du **codage temporel** : les cellules ciliées s'activent de façon globalement synchrone avec les vibrations de la membrane basilaire. Il est donc possible de déduire la fréquence du son en observant la fréquence du signal électrique transmis.

Cependant, ce mécanisme de codage a ses limites. En effet, la cellule ciliée ne peut pas réagir instantanément à chaque mouvement des stéréocils : elle a besoin d'un temps très court pour se décharger avant de pouvoir être à nouveau activée. Pour des sons de fréquence basse, comme on l'a vu, ce délai est suffisamment court pour permettre à la cellule de suivre chaque cycle sonore. En revanche, lorsque la fréquence augmente au delà de 1 kHz, les fluctuations deviennent trop rapides pour que la cellule puisse réagir à chaque période de l'onde. Dans ce cas, la réponse électrique devient plus stable et plus constante. Au lieu de suivre les détails temporels fins du son, elle reflète alors surtout l'intensité moyenne de la fréquence considérée ({numref}`Phaselock.png`).

```{figure} Phaselock.png
---
name: Phaselock.png
alt: Phaselock.png
width: 60%
align: center
---
*Fluctuations du potentiel électrique de cellules cilliées en réponse à des tons purs à différentes fréquences. Pour des fréquences inférieures à 1 kHz, l'activité électrique présente une périodicité à la même fréquence que le son : c'est le codage temporel. Au dessus de 1 kHz, la cellule n'est plus en mesure de suivre les fluctuations rapides du son. (Palmer and Russel, 1986)*
```

**Le codage des fréquences par l'oreille interne est donc double**. D'une part, chaque fréquence active une région spécifique de la membrane basilaire, mobilisant un sous-ensemble distinct de cellules ciliées (codage tonotopique). D'autre part, les fluctuations de la membrane basilaire suivent approximativement le rythme de l'onde, rendant le signal électrique lui-même périodique (codage temporel). Par ailleurs, ces deux codes présentent chacun des limitations spécifiques dans les hautes fréquences : le codage tonotopique devient de moins en moins précis pour les fréquences élevées, tandis que le codage temporel ne peut pas suivre fidèlement la périodicité du son au delà de 1 kHz environ.

## Modéliser l'oreille interne (partie 2) : spectrogramme auditif

Nous avons vu précédemment comment le pattern d'excitation rend compte du codage tonotopique au sein de la cochlée. En revanche, cette représentation purement fréquentielle ne permet pas de visualiser le codage temporel, qui repose sur l'organisation dans le temps du signal. Pour explorer cette dimension temporelle, on peut toutefois examiner le décours temporel de la sortie de chaque filtre gammatone -- qui modélise les oscillations de la membrane basilaire en un point spécifique. La figure suivante illustre ces vibrations en réponse à un complexe harmonique pour six gammatones de différentes fréquences d'accordage. Sans surprise, le gammatone centré sur la fréquence fondamentale (ici 500 Hz) produit un signal périodique à la méme fréquence, tandis qu'un gammatone accordé à 1200 Hz est relativement peu excité car il est situé entre deux harmoniques. Ceci correspond au double code évoqué précédemment : non seulement la membrane basilaire est particulièrement excitée au point correspondant à la fréquence du son, mais ses oscillations suivent elles-mêmes cette fréquence.

En revanche, les filtres gammatones de fréquence d'accordage plus élevée sont, comme on l'a vu précédemment, trop larges pour isoler une composante harmonique et englobent au contraire plusieurs harmoniques proches. Il en découle un phénomène de battement à la fréquence fondamentale dans leur réponse temporelle. Ainsi, pour un complexe harmonique, **les gammatones accordés dans les hautes fréquences (région des harmoniques non-résolues) ont une réponse dont l'envelope est périodique à la fréquence fondamentale du signal**.

```{figure} pattern4.png
---
name: pattern4.png
alt: Sortie temporelle des filtres gammatones
width: 60%
align: center
---
*Modélisation des vibrations en différents points de la membrane basilaire, en réponse à un complexe harmonique de fréquence fondamentalementale 500 Hz. Le spectre de ce signal est représenté dans le panneau supérieur. En dessous sont tracées les réponses en fréquence de six gammatones, de fréquences d'accordage 500 Hz, 1268 Hz, 2631 Hz, 4176 Hz, 6083 Hz et 8817 Hz. La partie inférieure de la figure présente la sortie temporelle de chacun de ces gammatones. On observe une périodicité à 500 Hz dans la réponse du filtre gammatone accordé à 500 Hz, et dans l'enveloppe de la réponse des filtres de fréquence d'accordage élevées. (Inspiré de Plack, 2023)*
```

Pour modéliser les fluctuations du potentiel électrique des cellules cilliées en réponse à un son, une approximation peut être obtenues en deux étapes simples : rectifier la sortie du gammatone en mettant à zéro les valeurs négatives (car les cellules ciliées se chargent lorsque les stéréocils sont pliés dans un sens, mais non dans l'autre), puis appliquer un filtrage passe-bas en dessous de 1 kHz (en effet, comme évoqué plus haut, les cellules ciliées sont incapables de suivre des fréquences au delà de 1 kHz environ). En affichant le résultat en fonction de la fréquence centrale du gammatone et du temps, on obtient une représentation spectro-temporelle appelée **spectrogramme auditif** (voir {numref}`AuditorySpectrogram.png`). Chaque ligne de cette représentation correspond à une position le long de la cochlée et les nuances de couleurs indiquent le taux de décharges des cellules cilliées correspondantes au cours du temps.

```{figure} AuditorySpectrogram.png
---
name: AuditorySpectrogram.png
alt: Spectrogramme auditif
width: 100%
align: center
---
*Trois exemples de spectrogramme auditif, en réponse à un ton pur à 300 Hz (panneau A), à deux tons purs à 300 et 600 Hz (panneau B), et à un complexe harmonique de fréquence fondamentalementale 300 Hz (panneau C). A droite de chaque spectrogramme est représenté le pattern d'excitation, et au dessus la réponse électrique simulée d'une cellule ciliée particulière (c'est-à-direune ligne du spectrogramme) : cellule accordée à 300 Hz (panneau A), à 600 Hz (panneau B) ou à 3000 Hz (panneau C).*
```

Trois spectrogrammes auditifs sont représentés {numref}`AuditorySpectrogram.png`. Le premier correspond à l'écoute d'un simple ton pur à 300 Hz. On identifie aisément le codage tonotopique par la présence d'une bande horizontale, c'est à dire d'une région de la cochlée particulièrement excitée par le ton pur. Le spectrogramme auditif rend également compte du codage temporel, sous la forme d'une périodicité à 300 Hz de l'excitation [traveling wave]. Cette dernière est particulièrement bien visible lorsqu'on isole le taux de décharges simulé des cellules accordées à 300 Hz, qui reproduit assez fidèlement les observations de la {numref}`Phaselock.png`. On retrouve ce double code tonotopique/temporel lorsqu'on considère le spectrogramme auditif de deux tons purs ({numref}`Phaselock.png`B). 

Dans le cas du complexe harmonique, déjà évoqué {numref}`pattern3.png` et {numref}`pattern4.png`, la fréquence fondamentalementale est identifiable simultanément par le codage tonotopique (harmoniques résolues dans les basses fréquences marquées par des bandes horizontales), le codage temporel dans les basses fréquences, mais également le codage temporel dans les hautes fréquences grâce au phénomène de battement vu plus haut ({numref}`Phaselock.png`C).

## Cellules cilliées externes et amplification-compression

La troisième et dernière fonction de la cochlée est d'effectuer une compression de dynamique. En effet, l'oreille humaine est capable de percevoir des sons très faibles (de l'ordre de quelques dB SPL) mais également des sons très forts (le seuil de douleur se situant approximativement à 120 dB SPL). L'écart entre les deux représente une gamme d'environ 120 dB, c'est à dire un facteur 1000000000000 ! Ceci est rendu possible grâce à une étape d'amplification des signaux faibles lors de la transduction.

L'amplification est notamment assurée par les ~25000 **cellules ciliées externes**. Celles-ci sont disposées tout le long de la cochlée, comme les cellules ciliées internes, mais organisées en trois rangées (voir {numref}`I_H_Hair_cell.png`). Les deux types de cellules possèdent une structure similaire mais fonctionnent sur un principe opposé : tandis que les cellules ciliées internes convertissent un mouvement mécanique en impulsion électrique envoyée dans les fibres du nerf auditif, les cellules ciliées externes convertissent une impulsion électrique venue du nerf auditif en mouvement mécanique. Ainsi, la cellule ciliée externe se contracte sous l'effet d'une commande électrique. Étant fixée à la membrane basilaire et reliée par ses stéréocils à la membrane tectoriale, elle peut ainsi amplifier ou atténuer les oscillations au sein de la cochlée. Ce mécanisme actif de rétroaction peut être mis en évidence en comparant les tuning curves mesurées sur un organisme vivant et sur un organisme mort (voir figure suivante). Dans ce dernier cas le fonctionnement mécanique passif de la cochlée est toujours en œuvre, mais les mécanismes actifs -- notamment liés aux cellules ciliées externes -- sont éteints.

```{figure} Postmortem.jpeg
---
name: Postmortem.jpeg
alt: Isoresponse tuning curve pre-/post mortem
width: 70%
align: center
---
*Isoresponse tuning curves mesurée ante-mortem (courbe verte, similaire à la {numref}`Isoresponse2.png`) ou post-mortem (courbe rouge, même mesure, mais sans action des mécanismes actifs).*
```

Comme on le constate sur la figure, la *tuning curve* mesurée post-mortem -- et correspondant donc au fonctionnement purement mécanique de la cochlée -- sont très atténuées (facteur 100 par rapport à la tuning curve ante-mortem) et relativement larges. La viscosité de la périlymphe et la résistance de la membrane basilaire entraînent une grande déperdition d'énergie et on voit donc que l'idée d'une cochlée fonctionnant sur la seule base de l'action mecanique de l'onde entrante n'est pas tenable. Seule l'existence de mécanismes actifs compensant le damping et améliorant la sélectivité fréquentielle permet d'expliquer la grande efficacité de la cochlée dans la transmission de l'information. 

Néanmoins, ce système de feedback actif est plus ou moins sollicité en fonction du niveau sonore : il renforce la perception des sons faibles mais laisse les sons forts être naturellement atténués. Ceci peut être observé en comparant les *tuning curves* mesurées en une même position pour des stimuli de différentes intensité ({numref}`TuningGain.png`). 

```{figure} TuningGain.png
---
name: TuningGain.png
alt: tuning curve effect of level
width: 70%
align: center
---
*Tuning curve pour une même cellule ciliée, mesurée avec différents volumes sonores pour la stimulation. Cette mesure met en évidence la non-linéarité du système : les sons faibles sont plus amplifiés que les sons forts, et la sélectivité est meilleure dans le premier cas.*
```

Lorsque le niveau sonore est faible, les tuning curves possédent une excellente résolution et [check] n'atténuent pas les sons au niveau de leur fréquence d'accordage. En revanche, à des niveaux sonores élevés, la tuning curve devient très peu sélective et atténuent fortement les sons (gain maximum divisé par un facteur 100). De façon prévisible, le même phénomène peut également être observé au niveau des patterns d'excitation (voir {numref}`Excitation.jpeg`)

## Modéliser l'oreille interne (partie 3) : DRNL

Il est possible de mettre à jour le modèle de la cochlée comme un banc de filtres gammatones, vu précédemment, pour prendre en compte l'effet des cellules ciliées externes. Une première option très simple consiste à appliquer une fonction compressive (par exemple une loi puissance avec un exposant négatif) sur la sortie des gammatones. Ceci n'est cependant pas entièrement satisfaisant car la cochlée ainsi simulée, si elle réalise bien une compression de dynamique, conserve cependant la même résolution fréquencielle quel que soit le niveau sonore d'entrée. Une seconde option, légèrement plus sophistiquée, s'appuie sur des *dual-resonance nonlinear filters* (**filtres DRNL**). Ces filtres non-linéaires reproduisent l'évolution des *tuning curves* avec le niveau sonore, illustré {numref}`TuningGain.png`. Leur réponse est calculée comme la somme des réponses de deux filtres plus simples : Le premier, linéaire et semblable aux gammatones mais avec une résolution plus faible, correspond à l'action mécanique du système, tandis que le deuxième, non-linéaire et plus sélectif en fréquence, rend compte des mécanismes actifs. La figure illustre le gain d'un filtre DRNL accordé à 1000 Hz Hz, lorsque le niveau sonore entrant est faible (30 dB SPL) ou fort (90 dB SPL). La réponse de la branche linéaire (en vert) est identique dans les deux cas ; en revanche la branche non-linéaire (en rouge) amplifie plus le son faible que le son fort. La somme des deux, en bleu, correspond à la sortie du DRNL et reproduit approximativement les observations de la {numref}`TuningGain.png`.

```{figure} DRNL.png
---
name: DRNL.png
alt: DRNL
width: 70%
align: center
---
*Tuning curve simulée au moyen d'un filtre DRNL, pour un niveau sonore entrant de 30 dB SPL (gauche) ou de 90 dB SPL (droite). La courbe bleue correspond à la réponse en fréquence du DRNL, les courbes vertes et rouges à ses composantes linéaires et non-linéaires, respectivement.*
```

Un aspect qui n'est cependant pas pris en compte dans le modèle DRNL est la dynamique temporelle du contrôle de gain. En effet, les filtres non-linéaire décrits ci-dessus réagissent instantanément 

## Nerf auditif

[parler de la connexion]

**Le double codage des sons réalisé par la cochlée est maintenu au niveau du nerf auditif**. D'une part, chaque fibre du nerf auditif étant connectée à une région particulière de la membrane basilaire, elle est préférentiellement activée par certaines fréquences. Ce codage tonotopique se retrouve dans l'organisation des fibres au sein du nerf auditif : celles codant les fréquences aiguës sont au centre et celles codant les fréquences graves sont en périphérie. 

```{figure} ANtonotopy.png
---
name: ANtonotopy.png
alt: tonotopy in the auditory nerve
width: 50%
align: center
---
*Organisation tonotopique au sein du nerf auditif. Les fibres correspondant à trois gammes de fréquences, connectées à différents points de la cochlée sont identifiées en couleur : basse fréquence en rouge, fréquences médium en vert, hautes fréquences en bleu.*
```

D'autre part, le codage temporel observé dans la charge electrique des cellules ciliées est lui aussi maintenu au niveau du nerf auditif. Comme nous l'avons vu, les cellules ciliées envoient des potentiels d'action, qui correspondent à des pics du déplacement de la membrane basilaire. Les vibrations étant périodiques, les impulsions électriques envoyées au nerf auditif par les cellules ciliées présentent, elles aussi, une périodicité à la même fréquence. Comme illustré dans la ({numref}`PhaseLocking.png`) les décharges surviennennt globalement à proximité des maxima de la vibration, même si tous les maxima ne donnent pas nécessairement lieu à une décharge synchrone de toutes les cellules, certaines impulsions pouvant être absentes ou décalées. Néanmoins, chaque cellule émet des impulsions électriques avec une périodicité globalement alignée sur celle de l'onde. Dans la partie inférieure de la figure, la sommation des décharges transmises par l'ensemble des cellules ciliées au nerf auditif montre que, malgré une certaine variabilité, le signal global reproduit la périodicité du stimulus sonore.

```{figure} PhaseLocking.png
---
name: PhaseLocking.png
alt: Phase-locking
width: 60%
align: center
---
*Illustration du principe du codage temporel. La partie supérieure de la figure représente l'onde sonore. En dessous sont schématisés les potentiels évoqués générés par trois cellules ciliées internes accordées à la fréquence de cette onde, et transmis au nerf auditif.  (Source: Plack 2005)*
```

Il faut ici mentionner que le nerf auditif ne joue pas uniquement un rôle de transmetteur. Même si, considérées dans leur ensemble, les potentiels d'action semblent simplement véhiculer les codes tonotopique et temporel établis par la cochlée, en réalité les différentes fibres du nerf auditif connectées à une même cellule ciliée ne transmettent pas exactement la même information. Certaines fibres dites "à bas seuil" sont activés dès que la cellule ciliée correspondante est excitée, même légèrement, mais saturent ensuite rapidement (c'est à dire qu'elles ne distinguent pas une excitation moyenne d'une activation forte). Au contraire, d'autres fibres dites "à haut seuil" ne se déclenchent qu'à partir d'un niveau relativement élevé d'excitation. Pour cette raison, les modèles du nerf auditif incluent généralement une dernière étape simulant les réponses des différents types de fibres ainsi qu'un processus aléatoire décidant du déclenchement ou non du potentiel d'action dans chaque fibre à un moment donné. Ces composantes ne sont pas nécessaires pour les besoins de ce cours et ne seront donc pas considérées par la suite.

## Systèmes afférent et efférent

Nous avons évoqué précédemment le fait que les cellules ciliées externes permettent, dans certaines situations, l'amplification des oscillations de la membrane basilaire, grâce à un mécanisme convertissant les impulsions électriques en mouvements mécaniques. Ces cellules reçoivent donc des informations provenant d'étages supérieurs du système auditif. Cette information est **descendante** (***top-down***) ou **afférente** tandis que l'information provenant de l'extérieur et transmise au cerveau est dite **montante** (***bottom-up***) ou efférente. Ainsi le nerf auditif est constitué de fibres montantes qui 


> Efferent system Brownell, Bader, Bertrand, and Ribaupierre (1985) showed that electrical stimulation of the outer hair cells could lead to their contraction, and Ashmore (1987) reported that this outer contraction occurred with an extremely short latency (120 ls). Therefore, it seems possible that the response of the inner hair cell receptors can be modulated by efferent stimulation of the outer hair cells for frequencies up to the kilohertz range. While it is of interest to study directly the effects produced by efferent stimulation of the outer hair cells, there are experimental difficulties, including the sensitivity of the efferent system to anesthesia. Despite these problems, Winslow and Sachs (1988) have provided neurophysiological evidence that the efferent olivocochlear bundle can improve the sensitivity of afferent auditory nerve fibers to tonal signals in the presence of interfering noise. This is consistent with the earlier behavioral report by Dewson (1968) that discrimination between two vowels in the presence of noise by monkeys was impaired by sectioning of the efferent olivo-cochlear bundle. (Warren)

