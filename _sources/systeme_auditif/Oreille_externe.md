
# Oreille externe

Nous entamons notre périple le long du système auditif par l'élément qui constitue l'interface avec le monde extérieur : l'**oreille externe**. Celle-ci est composée de deux parties : le **pavillon** et le **conduit auditif**. Bien que très sommaire -- elle se résume à un simple "entonnoir" passif par lequel le son peut s'engouffrer -- l'oreille externe réalise en réalité certains traitements importants pour l'audition. 

```{figure} SysAudExt_OE.JPG
---
name: SysAudExt_OE.JPG
alt: Systeme auditif externe - oreille externe
height: 400px
align: center
---
*Schéma du système auditif périphérique mettant en évidence l'oreille externe.*
```

## Pavillon 

Avec sa forme de cornet acoustique, le pavillon auriculaire permet en premier lieu de **canaliser l'onde sonore** et de la diriger vers l'intérieur du canal auditif. Darwin considérait que le pavillon n'avait pas de fonction specifique chez l'humain et qu'il s'agissait simplement d'un vestige de structures plus élaborées chez nos ancêtres -- notant en particulier la présence chez certains individus d'un renflement particulier du bord supérieur de l'helix qui correspond à la pointe de l'oreille des primates. C'est Lord Rayleigh qui, le premier, suggère en 1876 un rôle possible de la forme de l'oreille externe pour la localisation des sons, puisqu'il est possible dans une certaine mesure d'identifier l'origine d'un son sans indices visuels et avec une seule oreille. 

En effet, le pavillon auriculaire étant globalement orienté vers l'avant, il capte mieux les sons provenant de cette direction -- fournissant ainsi une indication pour déterminer si la source est située devant ou derrière nous. Mais ce n'est pas tout : les circonvolutions engendrent elles aussi des réflexions des sons provenant de directions particulières, permettant là aussi de les localiser. Ainsi, des expériences ayant employé un moule pour modifier la structure des circonvolutions en remplissant certaines cavités ont montré que la capacité à localiser les sons dans l'espace est alors perturbée. Notez que les sons ne sont pas modifiés par le seul pavillon, mais également par l'ensemble de la tête de l'individu, qui projette une ombre acoustique dans certaines directions [[1](note1orext)]. Ces différents aspects modifient le timbre des sons selon leur direction d'origine -- c'est à dire que la fonction de transfert de l'oreille externe dépend de l'orientation. Pour faire une analogie visuelle, il faudrait imaginer que la couleur des objets que nous regardons change selon qu'ils sont au centre ou en périphérie du champ de vision, en haut ou en bas. Nous reviendrons au chapitre 5 sur cette propriété du système auditif.

La configuration exacte des circonvolutions est spécifique à chaque individu, et il en va donc de même de la fonction de transfert. Il est possible de mesurer cette fonction de transfert en plaçant un microphone à l'intérieur du conduit auditif, et en mesurant la réponse à des tons purs de toutes les directions possibles. On obtient ainsi la ***Head-Related Transfer Function*** (HRTF) de l'individu, qu'on peut ensuite utiliser pour génerer des son spatialisés impressionnants de réalisme. 

## Conduit auditif 

Comme nous venons de le voir, l'oreille externe réalise un filtrage directionnel. La figure suivante présente les HRTF correspondant à trois directions, mesurées chez 40 individus.


```{figure} HRTF.jpg
---
name: HRTF.jpg
alt: HRTF
height: 300px
align: center
---
*HRTF mesurées sur 40 individus, pour 3 directions. Le trait blanc correspond à la moyenne sur le groupe. (Møller et al, 1995)*
```

Dans l'ensemble les résonnances au sein de l'oreille externe conduisent à une amplification d'environ 10 dB des fréquences autour de 2 kHz. En effet, la forme tubulaire du conduit auditif et sa taille induisent mécaniquement des résonnances dans cette gamme de fréquence. Au bout du conduit auditif, l'onde fait ensuite vibrer le tympan, une membrane qui assure le lien avec l'oreille moyenne.

## Modéliser l'oreille externe 

Dans le cadre de ce chapitre nous ne nous intéresserons pas au traitement de l'information de localisation des sons. Pour modéliser l'effet de l'oreille externe, nous choisirons donc de partir de l'hypothèse de sons pénétrant dans l'oreille avec un angle d'incidence de 90°,  comme c'est le cas lors d’une écoute au casque. Dans ce cas, il suffit de considérer la HRTF centrale présentée dans la figure précédente, et de l’utiliser comme un filtre linéaire, ainsi qu'illustré dans la figure suivante :

```{figure} outer_ear_filter.jpg
---
name: outer_ear_filter.jpg
alt: Filtre d'oreille externe
height: 200px
align: center
---
*Approximation du filtre d'oreille externe pour une onde pénértrant l'oreille latéralement, à 90° par rapport à l'axe de la tête (Lopez-Poveda and Meddis, 2001; Pralong and Carlile, 1996).*
```

Lorsqu'on applique ce filtre à un signal sonore, par exemple ici un brouhaha composé de 5 voix superposées, on constate une légère amplification des fréquences entre 2000 et 3000 Hz.

```{figure} outer_ear_demo.jpg
---
name: outer_ear_demo.jpg
alt: Démo du filtre d'oreille externe
height: 300px
align: center
---
*Spectrogramme d'un brouhaha composé de 5 voix superposées, avant (gauche) et après (droite) passage par l'oreille externe. Cette figure a été obtenue par simulation grâce au filtre décrit ci-dessus.*
```

Bien qu'extrêmement simple cette simulation de l'oreille externe comme un simple filtre linéaire est assez courante dans les modèles ne s'intéressant pas à la localisation (Osses et al., 2022).

## Notes

(note1orext)=

[1] Du point de vue de la fonction de localisation, on pourrait donc considérer que la tête est une extension de l'oreille.

## Références

Lopez-Poveda, E. A., Johannesen, P. T., Pérez-González, P., Blanco, J. L., Kalluri, S., & Edwards, B. (2017). Predictors of Hearing-Aid Outcomes. Trends in Hearing, 21, 2331216517730526. https://doi.org/10.1177/2331216517730526

Møller, H., Sørensen, M. F., Hammershøi, D., & Jensen, C. B. (1995). Head-Related Transfer Functions of Human Subjects. Journal of The Audio Engineering Society. 

Osses, A., Varnet, L., Carney, L. H., Dau, T., Bruce, I. C., Verhulst, S., & Majdak, P. (2022). A comparative study of eight human auditory models of monaural processing. Acta Acustica, 6, 17. https://doi.org/10.1051/aacus/2022008

Pralong, D., & Carlile, S. (1996). The role of individualized headphone calibration for the generation of high fidelity virtual auditory space. The Journal of the Acoustical Society of America, 100(6), 3785–3793. https://doi.org/10.1121/1.417337
