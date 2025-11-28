
```{warning}
Page en cours de construction
```

# Phonétique acoustique

Nous sommes constamment exposé·es à des sons de parole, que notre cerveau comprend quasi instantanément et sans effort apparent. Le processus semble aller de soi, à tel point qu'il est difficile a priori d'imaginer quelles complexités pourraient justifier que ce mécanisme de décodage fasse l'objet de recherches approfondies depuis maintenant plus d'un siècle. Après tout, il nous suffit de disposer d'une copie de l'alphabet morse pour être en mesure de déchiffrer un message codé en morse. De la même manière, ne suffit-il pas à notre cerveau de mémoriser la "table de conversion" des sons en phonèmes pour décoder les sons de parole ? Cette section présente les problèmes théoriques auquel se trouve confrontée cette explication intuitive.

## Qu’est-ce qu’un phonème ?

Les linguistes définissent le **phonème"* comme le **plus petit élément porteur de sens dans le son de parole**, c'est à dire en quelque sorte comme l'atome, ou la brique de base, du langage parlé.

> Quels sont exactement les rapports entre les sons et le sens à l’intérieur du mot et de la langue en général ? Finalement, il s'agit de dégager le plus petit élément phonique chargé d'une valeur significative, ou -- en termes métaphoriques -- il s'agit de trouver les quanta de la langue. *(Jakobson, Six leçons sur le son et le sens, 1942)*

Une approche pour identifier les phonèmes d’une langue donnée :
« bagage » vs. « bagarre »  en français l’opposition g/r est porteuse de sens

On peut ainsi construire des tables des phonèmes et de leurs relations

```{figure} IPA.png
---
name: IPA.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

…mais qu’est-ce qui caractérise acoustiquement un phonème ? Comment le cerveau procède-t-il pour distinguer un phonème d’un autre ?

## Les voyelles

Phonétique acoustique
Etude systématique d’enregistrements de parole pour identifier les similarités entre différentes productions d’un même phonème.

Le spectre des voyelles présente des formants à des fréquences relativement stables… 


```{figure} Formants.png
---
name: Formants.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Les formants correspondent aux résonances de la cavité orale pour une configuration particulière des articulateurs (langue, lèvres, palais…)

```{figure} Boeetal2019.jpg
---
name: Boeetal2019.jpg
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

<video controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/Reson.mp4" type="video/mp4">
</video>

Triangle vocalique : Mesure des valeurs de F1 et F2 pour un grand nombre de productions de voyelles. 

```{figure} Hillen1.png
---
name: Hillen1.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Répartition des voyelles dans l’espace F1-F2

```{figure} Hillen2.png
---
name: Hillen2.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

1er problème : subdivision
Nécessité d’un mécanisme pour découper l’espace acoustique en régions correspondant aux différents phonèmes

```{figure} Hillen3.png
---
name: Hillen3.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

2nd problème : « problème du manque d’invariance »
Recouvrement des régions correspondant aux différents phonèmes. F1 et F2 ne suffisent pas à identifier les voyelles de façon univoque.

```{figure} Hillen4.png
---
name: Hillen4.png
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

## Les consonnes

```{figure} Consonnes.bmp
---
name: Consonnes.bmp
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Les consonnes présentent des caractéristiques acoustiques plus complexes et plus diversifiées que les voyelles. 
Les plosives /p/, /t/, /k/, /b/, /d/, /g/ correspondent à des caractéristiques transitoires.
À nouveau, difficile d’associer transition et plosive de façon univoque


```{figure} Consonne2.bmp
---
name: Consonnes2.bmp
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

```{figure} Consonne3.bmp
---
name: Consonnes3.bmp
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

## Conclusions temporaires

La phonétique acoustique cherche à identifier des similarités entre différentes productions d’un même phonème. 
Les formants et transitions de formants sont un élément important du son de parole.
Mais impossible de tracer une correspondance bijective entre phonèmes et formants.
 Seule l’expérimentation psychoacoustique peut permettre de résoudre ce problème (i.e. la phonétique expérimentale)



