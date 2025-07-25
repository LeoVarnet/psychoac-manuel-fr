# Oreille interne

```{warning}
Page en cours de construction
```

L'**oreille interne** constitue l'élément central du système auditif périphérique. Tandis que l'oreille externe et moyenne peut se réduire, en première approximation, à un simple filtre linéaire, l'oreille interne réalise plusieurs transformations essentielles des vibrations qui lui parviennent par la fenêtre ovale. Sa fonction est d'**analyser les sons en fréquence**, mais également d'**amplifier les sons faibles et de compresser les sons forts**. Enfin, elle réalise une **transduction, en convertissant les vibrations physiques en signaux électriques**.

L'oreille interne se décompose en trois parties : 
- la **cochlée**, petit bijou de l'évolution qui comme nous le verrons est lui-même constitué de plusieurs éléments en interaction
- le **nerf auditif**, qui assure la jonction entre la cochlée et le système auditif central
- le **système vestibulaire**. Ce dernier ne sera pas traité ici puisqu'il ne contribue pas à l'audition. 

```{figure} SysAudExt_IE.JPG
---
name: SysAudExt_IE.JPG
alt: Systeme auditif externe - oreille interne 
height: 400px
align: center
---
*Schéma du système auditif périphérique mettant en évidence l’oreille interne. (Source : [Ivy Livingstone, Biodidac](https://omeka.uottawa.ca/biodidac/items/show/4603))*
```

## La cochlée et la membrane basilaire 

La **cochlée** est l'organe qui réalise notamment la décomposition du son en fréquence, c'est-à-dire son analyse spectrale.

La cochlée possède une forme de coquille d'escargot -- d'où son ancien nom de "limaçon", et sa racine latine *cochlea*. À l'intérieur, le conduit en spirale est divisé en deux sur presque toute sa longueur par une structure relativement rigide, la **lame spirale**, pour former deux canaux qui se rejoignent seulement au sommet (**apex**) et sont emplis d'un liquide appelé **périlymphe** [[1](note1OI)]. Par ailleurs, la cochlée possède à sa **base** deux ouvertures couvertes d'une membrane : une entrée (la fenêtre ovale, attachée à l'étrier et donc reliée à  l'oreille moyenne) et une sortie (la fenêtre ronde). L'onde communiquée par les mouvements de l'étrier au liquide contenu dans la cochlée peut donc suivre un chemin en double hélice, en remontant depuis la base de la cochlée jusqu'à son apex puis en redescendant pour ressortir par la fenêtre ronde. Ce cheminement du son est illustré sur la figure ci_dessous. 
Les canaux montants et descendants sont, rappelons-le, séparés par la lame spirale. Celle-ci possède une structure assez complexe à laquelle nous nous intéresserons plus loin. Dans l'immédiat, retenez que l'élément semi-rigide qui sépare le conduit montant du conduit descendant se nomme la **membrane basilaire**.

```{figure} Cochlea.png
---
name: Cochlea.png
alt: Cochlée
height: 400px
align: center
---
*Schéma de la cochlée et du chemin parcouru par l'onde sonore. Cette figure présente une vue en coupe transversale (Source : Neuroscience, Purves et al.)*
```

Dans son *Traité de l'organe de l'ouïe*, publié en 1683 et considéré comme le premier ouvrage d'otologie, Joseph-Guichard Du Verney décrit précisément la structure de la cochlée et propose sa première théorie fonctionnelle. Il remarqua que la membrane basilaire n'est pas uniforme, mais varie en épaisseur et en résistance sur toute sa longueur : elle est étroite et rigide à la base, mais large et souple au niveau de l'apex. Du Verney émet donc l'hypothèse que ce gradient de propriétés physiques permet à la membrane basilaire d'être sensible à différentes fréquences en différents points. 

>[La membrane basilaire] n'est pas seulement capable de recevoir les tremblements de l'air, mais sa structure doit faire penser qu'elle peut répondre à tous leurs caractères différents. *(Du Verney, Traité de l'organe de l'ouïe, 1683)*

Hermann Von Helmholtz complètera cette théorie en 1863 en introduisant la notion de résonnance -- et en corrigeant quelques erreurs commises par Du Verney. L'idée est donc assez intuitive : lors de son trajet le long de la double hélice, l'onde sonore entraîne la membrane basilaire. Celle-ci ne vibre pas de façon uniforme ; au contraire du fait de son gradient de propriétés physiques, elle entre particulièrement en résonnance en certains points correspondant aux fréquences contenues dans le son. La base est particulièrement sensible aux hautes fréquences (20 kHz) et l'apex aux basses fréquences (20 Hz). Ainsi, la cochlée réalise l'analyse spectrale des vibrations puisqu'**une fréquence particulière excite une région particulière le long de la membrane basilaire**. On appelle cette correspondance le **codage de place** ou **codage tonotopique** (c'et à dire "une note = une position").

Cette conception simple de la cochlée est suffisante pour la plupart des applications, et notamment pour les besoins de ce cours. Cependant, elle est partiellement erronée. C'est Georg von Békésy qui, sur la base d'une série d'expériences commencées en 1928, proposera l'approche moderne du fonctionnement de la cochlée, un travail qui lui valut le prix Nobel. En effectuant des mesures précises de la membrane basilaire en mouvement, il démontre notamment que les vibrations de la membrane basilaire ne sont pas stationnaires comme on le supposait précédemment ; autrement dit celle-ci ne vibre pas comme une corde d'un instrument de musique. Les ondes sont au contraire transitoires, elles remontent le long de la membrane basilaire. De plus l'onde dans le liquide ne suit en réalité pas le trajet complet de la double hélice. Le point de résonnance de la membrane basilaire, d'impédance presque nulle, lui fournit un raccourci pour traverser la lame spirale et redescendre immédiatement sans passer par l'apex. Pour cette raison les vibrations de la membrane basilaire décroissent de façon très abrupte au delà du point de résonnance. [...]

Pour être complet, un modèle mécanique de la cochlée doit inclure un grand nombre de paramètres et d'équations de façon à simuler la mise en mouvement du liquide et la propagation de l'onde dans ce milieu, l'entraînement de la membrane basilaire vue comme chaîne de resonnateurs couplés d'inertie mécanique variable, ainsi que les effets de rétroaction dont il sera question plus loin. Ce domaine fait donc actuellement l'objet d'importants travaux.

Outre les simulations de la cochlée, il est également possible de mesurer ses mouvements en réaction à des sons. On peut par exemple enregistrer, au moyen d'une electrode, l'activité des cellules cilliées qui -- comme nous le verrons par la suite -- envoient des impulsions lorsque le point de la membrane basilaire auquel elles sont attachées est mis en mouvement. En plaçant l'électrode à un certain niveau de la membrane basilaire et en jouant un son on peut ainsi voir si le point testé est sensible à ce son. En répétant cette mesure pour chaque fréquence on peut ainsi représenter la fonction de transfert du point considéré sur la membrane basilaire.




Mesurer la tonotopie et la sélectivité fréquentielle de la cochlée :
Tuning curves : chaque courbe correspondant à une position sur la membrane basilaire. On mesure l’excitation de la cochlée en réponse à une intensité acoustique donnée.

Une position sur la cochlée correspond à une fréquence d’accordage (tuning frequency) particulière. Chaque fréquence excite aussi les régions adjacentes : la sélectivité fréquentielle est limitée. 

Mapping quasi-logarithmique entre fréquence d’accordage et position sur la membrane basilaire.

## Modéliser la cochlée (part 1)

Le banc de filtres gammatones : 
Banc de filtres passe-bande espacés quasi-logarithmiquement entre 20 Hz et 20.000 Hz.
Largeur des filtres proportionnelle à la fréquence centrale (i.e. facteur de qualité constant)

Le pattern d’excitation

Représentation de l’amplitude en sortie d’un banc de filtres gammatone : Pour un stimulus donné, niveau de sortie de chaque gammatone en fonction de sa fréquence d’accordage

Une modélisation de l’excitation de la cochlée par le stim

Calcul du pattern d’excitation en réponse à un ton pur à 1 kHz

Quelques propriétés : 
Le pattern d’excitation d’un ton pur a une certaine largeur (= résolution en fréquence du système auditif humain)
Il est asymétrique (= upward spread of excitation) car la largeur des filtres gammatone est proportionnelle à leur fréquence.
Cette asymétrie est plus marquée pour les sons plus forts.
La largeur (= résolution) croît avec la fréquence.
Par conséquent, dans un complexe harmonique, seules les premières harmoniques sont clairement séparées sur le pattern d’excitation (= « harmoniques résolues »)
Au contraire, dans les hautes fréquences, les harmoniques sont non-résolues : on ne les distingue plus sur le pattern d’excitation.

## Cellules cilliées

> The two main roles of the cochlea are to separate the input acoustic signal into overlapping frequency bands, and to compress the large acoustic intensity range into the much smaller mechanical and electrical dynamic range of the inner hair cell. (Allen 2001)

The hair cells in the organ of Corti are tuned to certain sound frequencies by way of their location in the cochlea, due to the degree of stiffness in the basilar membrane.[8] This stiffness is due to, among other things, the thickness and width of the basilar membrane,[9] which along the length of the cochlea is stiffest nearest its beginning at the oval window, where the stapes introduces the vibrations coming from the eardrum. Since its stiffness is high there, it allows only high-frequency vibrations to move the basilar membrane, and thus the hair cells. The farther a wave travels towards the cochlea's apex (the helicotrema), the less stiff the basilar membrane is; thus lower frequencies travel down the tube, and the less-stiff membrane is moved most easily by them where the reduced stiffness allows: that is, as the basilar membrane gets less and less stiff, waves slow down and it responds better to lower frequencies. In addition, in mammals, the cochlea is coiled, which has been shown to enhance low-frequency vibrations as they travel through the fluid-filled coil.[10] This spatial arrangement of sound reception is referred to as tonotopy. 

> The assumption of a ‘passive’ cochlea, where elements are brought into mechanical oscillation solely by means of the incident sound, is not tenable. The degree of resonance of the elements of the cochlea can be measured, and the results are not compatible with the very heavy damping which must arise from the viscosity of the liquid. For this reason the 'regeneration hypothesis' is put forward, and it is suggested that an electromechanical action takes place whereby a supply of electrical energy is employed to counteract the damping. (*The physical basis of the action of the cochlea, Thomas Gold, 1948*)

## Notes

(note1OI)=

[1] Notez qu'en réalité la cochlée est divisée non en deux mais en trois conduits, le troisième étant hermétiquement séparé des deux autres et empli d'un liquide différent, l'endolymphe. Ce détail n'est cependant pas important pour pour la présente description.
