
# Conclusion intermédiaire

```{warning}
Page en cours de construction
```

Parvenu·es au niveau du nerf auditif, qui marque la frontière entre le système auditif périphérique et le système auditif central, il est temps de marquer une pause pour récapituler ce que nous avons vu jusqu'ici, mais également pour développer certaines notions que nous avons seulement esquissées plus tôt.

## Structure du modèle du système auditif périphérique

Dans les sections qui précèdent, nous avons listé les différentes étapes de traitement du signal sonore à travers le système auditif périphérique en en proposant des modélisations simples. Si ces modules peuvent être enrichis, jusqu'à devenir extrêmement complexes pour tenir compte des effets de spatialisation, de feedback, ou des nombreuses non-linéarités, la structure générale du modèle est quant à elle relativement stable. En effet, chaque étape décrite ici est un "passage obligé" pour l'information sonore. En conséquence, les différents modèles auditifs disponibles possèdent tous la même organisation, même si certains modules peuvent être omis en première approximation. La figure suivante illustre la structure de 8 modèles "classiques" du système auditif périphérique, en faisant apparaitre les correspondances entre étapes du traitement. On retrouve les différents modules décrits précédemment : 
- Stage 1 : filtre d'oreille externe
- Stage 2 : filtre d'oreille moyenne
- Stage 3 : décomposition en fréquence par la membrane basilaire, modélisée par un banc de filtres (incluant éventuellement l'amplification/compression par les cellules ciliées externes). P.ex. banc de filtres gammatones.
- Stage 4 : modèle de la transduction par les cellules ciliées. P.ex. rectification demie-onde suivie d'un filtre passe-bas de fréquence de coupure 1 kHz.
- Stage 5 : modèle des synapses du nerf auditif. A minima, ce module réalise une compression supplémentaire du signal. Il peut également prendre en compte les différents types de fibres, et/ou produire une série de potentiels d'action.
- Stage 6 : modèles du noyau cochléaire et du colliculus inférieur. Nous envisagerons ce module dans la section suivante.
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

Cette structure relativement "rectiligne" du système auditif périphérique, formée par une série de modules successifs, contraste avec le système auditif central, constitué quant à lui de nombreuses voies parallèles, comme nous le verrons plus loin.

## Codage d'un complexe harmonique 

Les exemples choisis pour illustrer le principe du spectrogramme auditif ([ref]) se sont concentrés principalement sur des tons purs ou combinaison de ton purs dans les basses fréquences. Il est néanmoins utile pour les chapitres suivants de se pencher sur le cas des complexes harmoniques. Nous avons vu ({numref}`pattern3.png` et {numref}`pattern4.png`) que du point de vue du codage tonotopique les harmoniques dans les basses fréquences étaient résolues (elles correspondent à des pics dans le pattern d'excitation) tandis que les harmoniques plus hautes étaient non-résolues. Qu'en est-il du point de vue du codage temporel ?

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

Nous avons détaillé précédemment le cas des trois gammatones accordés aux fréquences les plus basses. Ceux-ci sont suffisamment étroits pour n'englober qu'une harmonique (ils sont situés dans la région des harmoniques résolues) et leur sortie fluctue donc à la fréquence de cette harmonique. En revanche, les filtres gammatones de fréquence d'accordage plus élevée sont, comme on l'a vu précédemment, trop larges pour isoler une composante harmonique et englobent au contraire plusieurs harmoniques proches (qui sont donc non-résolues). Il en découle un phénomène de battement à la fréquence fondamentale dans leur réponse temporelle : la superposition de plusieurs tons purs espacés de ∆f engendre un signal modulé à la fréquence ∆f. Ainsi, pour un complexe harmonique, **les gammatones accordés dans les hautes fréquences (région des harmoniques non-résolues) ont une réponse dont l'envelope est périodique à la fréquence fondamentale du signal**.

Les cellules ciliées internes accordées dans les hautes fréquences agissant, on l'a vu, comme des extracteurs d'enveloppe, elles extraient les modulations à la fréquence fondamentalementale et les transmettent aux fibres du nerf auditif. Ce phénomène est clairement visible dans le spectrogramme auditif comme illustré par la figure suivante. Pour le complexe harmonique comme pour le son de la voyelle "è", les cellules ciliées accordées sur les fréquences aiguës présentent des fluctuations très claires à 300 Hz et 250 Hz, respectivement. Ainsi, Pour des sons harmoniques, la fréquence fondamentalementale est codée de trois façons différentes au niveau du nerf auditif : un code tonotopique (pic dans le pattern d'excitation), un code temporel dans les basses fréquences, et un code temporel dans les hautes fréquences dû au phénomène de battement.

```{figure} AuditorySpectrograms2.png
---
name: AuditorySpectrograms2.png
alt: Spectrogramme auditif
width: 80%
align: center
---
*Deux exemples de spectrogramme auditif, en réponse à un complexe harmonique de fréquence fondamentale 300 Hz (panneau gauche), et à un enregistrement de la voyelle "é" prononcée par une voix avec une fréquence fondamentalementale à 250 Hz (panneau droit). A droite de chaque spectrogramme est représenté le pattern d'excitation correspondant, et au dessus la réponse électrique simulée d'une cellule ciliée particulière (c'est-à-dire une ligne du spectrogramme, identifiée par la flèche rouge) : cellule accordée à 7000 Hz (panneau gauche) ou à 3370 Hz (panneau droit).*
```

## Systèmes afférent et efférent

Le rôle du système auditif périphérique est de capter le monde sonore qui nous entoure pour transmettre cette information au cerveau. L'information suit donc globalement un chemin ascendant (***bottom-up***) depuis les récepteurs sensoriels jusqu'au cortex auditif : elle est dite **afférente**.

Il faut noter néanmoins que notre oreille est loin d'être un simple capteur qui se contenterait de réceptionner les sons et de les transcrire en signal électrique aussi fidèlement que possible, comme pourrait le faire un microphone idéal. Au contraire, le signal est filtré et transformé à chaque étape du système auditif, dès le pavillon, à tel point que certaines informations sont perdues tandis que d'autres sont codées de façon redondante. La frontière entre sensation et perception est donc relativement floue puisque le système auditif périphérique produit une représentation complexe qui met en évidence certaines informations utiles à l'individu (amplification des sons faibles, décomposition en fréquence).

Autre différence fondamentale avec un simple microphone : en sens opposé de l'information afférente, des informations **efférentes**, ou descendantes (***top-down***) sont transmises depuis les étages supérieurs vers les récepteurs sensoriels. Nous avons évoqué précédemment deux exemples de tels mécanismes de feedback : le réflexe stapédien qui immobilise les osselets lorsque le niveau sonore devient trop important, et les cellules ciliées externes qui amplifient les sons trop faibles. 

La fonction principale du nerf auditif étant de transmettre l'information depuis les récepteurs sensoriels aux étages supérieurs, il est composé majoritairement de fibres afférentes connectées aux cellules ciliées internes. Néanmoins, il contient également une proportion non négligeable de fibres efférentes connectées aux cellules ciliées externes. Là encore, la séparation entre sensation "pure" et perception se trouve brouillée. En réalité, dans le système auditif, les signaux 

L

le fait que les cellules ciliées externes permettent, dans certaines situations, l'amplification des oscillations de la membrane basilaire, grâce à un mécanisme convertissant les impulsions électriques en mouvements mécaniques. Ces cellules reçoivent donc des informations provenant d'étages supérieurs du système auditif. Cette information est **descendante** (***top-down***) ou **efférente** tandis que l'information provenant de l'extérieur et transmise au cerveau est dite **montante** (***bottom-up***) ou **afférente**. Ainsi le nerf auditif est constitué de fibres montantes qui 

La portée Il est intéressant de noter que ce mécanisme de feedback brouille la 

> Efferent system Brownell, Bader, Bertrand, and Ribaupierre (1985) showed that electrical stimulation of the outer hair cells could lead to their contraction, and Ashmore (1987) reported that this outer contraction occurred with an extremely short latency (120 ls). Therefore, it seems possible that the response of the inner hair cell receptors can be modulated by efferent stimulation of the outer hair cells for frequencies up to the kilohertz range. While it is of interest to study directly the effects produced by efferent stimulation of the outer hair cells, there are experimental difficulties, including the sensitivity of the efferent system to anesthesia. Despite these problems, Winslow and Sachs (1988) have provided neurophysiological evidence that the efferent olivocochlear bundle can improve the sensitivity of afferent auditory nerve fibers to tonal signals in the presence of interfering noise. This is consistent with the earlier behavioral report by Dewson (1968) that discrimination between two vowels in the presence of noise by monkeys was impaired by sectioning of the efferent olivo-cochlear bundle. (Warren)
