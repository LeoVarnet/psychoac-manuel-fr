
# Conclusion intermédiaire

```{warning}
Page en cours de construction
```

## Structure du modèle du système auditif périphérique

## Codage d'un complexe harmonique 

```{figure} pattern4.png
---
name: pattern4.png
alt: Sortie temporelle des filtres gammatones
width: 75%
align: center
---
*Modélisation des vibrations en différents points de la membrane basilaire, en réponse à un complexe harmonique de fréquence fondamentalementale 300 Hz. Le spectre de ce signal est représenté dans le panneau supérieur. Comme pour la {numref}`pattern.png`, on a tracé en-dessous les fonctions de transfert de six gammatones, de fréquences d'accordage 300 Hz, 600 Hz, 1270 Hz, 3460 Hz, 5060 Hz et 7350 Hz, puis le pattern d'excitation. Les trois derniers gammatones ont des bandes passantes très larges qui englobent un grand nombre d'harmoniques, et effectivement ils correspondent à la région des harmoniques non résolues. La partie inférieure de la figure présente la sortie temporelle de chacun des six gammatones identifiés plus haut. Du fait de phénomènes de battement entre harmoniques, on observe une périodicité à 300 Hz dans la réponse des trois filtres gammatones accordé à 3460 Hz, 5060 Hz et 7350 Hz. (Inspiré de Plack, 2023)*
```

```{figure} AuditorySpectrogram2.png
---
name: AuditorySpectrogram2.png
alt: Spectrogramme auditif
width: 100%
align: center
---
*Deux exemples de spectrogramme auditif, en réponse à un complexe harmonique de fréquence fondamentale 300 Hz (panneau gauche), et à un enregistrement de la voyelle "é" prononcée par une voix avec une fréquence fondamentalementale à 250 Hz (panneau droit). A droite de chaque spectrogramme est représenté le pattern d'excitation correspondant, et au dessus la réponse électrique simulée d'une cellule ciliée particulière (c'est-à-dire une ligne du spectrogramme, identifiée par la flèche rouge) : cellule accordée à 7000 Hz (panneau gauche) ou à 3370 Hz (panneau droit).*
```

En revanche, les filtres gammatones de fréquence d'accordage plus élevée sont, comme on l'a vu précédemment, trop larges pour isoler une composante harmonique et englobent au contraire plusieurs harmoniques proches. Il en découle un phénomène de battement à la fréquence fondamentale dans leur réponse temporelle. Ainsi, pour un complexe harmonique, **les gammatones accordés dans les hautes fréquences (région des harmoniques non-résolues) ont une réponse dont l'envelope est périodique à la fréquence fondamentale du signal**.

Dans le cas du complexe harmonique, déjà évoqué {numref}`pattern3.png` et {numref}`pattern4.png`, la fréquence fondamentalementale est identifiable simultanément par le codage tonotopique (harmoniques résolues dans les basses fréquences marquées par des bandes horizontales), le codage temporel dans les basses fréquences, mais également le codage temporel dans les hautes fréquences grâce au phénomène de battement vu plus haut ({numref}`Phaselock.png`C).

## Systèmes afférent et efférent

Nous avons évoqué précédemment le fait que les cellules ciliées externes permettent, dans certaines situations, l'amplification des oscillations de la membrane basilaire, grâce à un mécanisme convertissant les impulsions électriques en mouvements mécaniques. Ces cellules reçoivent donc des informations provenant d'étages supérieurs du système auditif. Cette information est **descendante** (***top-down***) ou **efférente** tandis que l'information provenant de l'extérieur et transmise au cerveau est dite **montante** (***bottom-up***) ou **afférente**. Ainsi le nerf auditif est constitué de fibres montantes qui 


> Efferent system Brownell, Bader, Bertrand, and Ribaupierre (1985) showed that electrical stimulation of the outer hair cells could lead to their contraction, and Ashmore (1987) reported that this outer contraction occurred with an extremely short latency (120 ls). Therefore, it seems possible that the response of the inner hair cell receptors can be modulated by efferent stimulation of the outer hair cells for frequencies up to the kilohertz range. While it is of interest to study directly the effects produced by efferent stimulation of the outer hair cells, there are experimental difficulties, including the sensitivity of the efferent system to anesthesia. Despite these problems, Winslow and Sachs (1988) have provided neurophysiological evidence that the efferent olivocochlear bundle can improve the sensitivity of afferent auditory nerve fibers to tonal signals in the presence of interfering noise. This is consistent with the earlier behavioral report by Dewson (1968) that discrimination between two vowels in the presence of noise by monkeys was impaired by sectioning of the efferent olivo-cochlear bundle. (Warren)
