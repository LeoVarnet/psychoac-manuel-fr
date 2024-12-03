# Méthode expérimentale

## Qu'est-ce que la méthode expérimentale ?

Fixer la **méthode** de l'expérience revient à déterminer comment les stimuli évoluent d'un essai au suivant : sont-ils toujours identiques, varient-ils en fonction des réponses précédentes, ou indépendamment des réponses ? Ce choix est guidé par des contraintes pratiques, mais également par le type de mesure que l'on souhaite obtenir : mesure de seuil, de performance, ou de sensibilité ? Cette section présente les quatre méthodes les plus courantes, en les reliant au moyen de la fonction psychométrique.

<br /> 

```{figure} expérience.png
---
name: expérience.png
alt: Schéma de l'expérience psychophysique
width: 400px
align: center
---
*Rappel : schéma de la structure d'une expérience psychoacoustique.*
```

<br /> 

Les méthodes sont classées en deux groupes : **méthodes adaptatives** (les stimuli présentés dépendent des réponses précédentes) et **methodes non-adaptatives** (les réponses n'affectent pas le déroulement de l'experience). Parmi les méthodes adaptatives on trouve notamment la methode des limites et la méthode de l'escalier psychophysique. Dans les méthodes non-adaptatives on peut mentionner la mesure de performance et la méthode des stimuli constants.

## Méthode des limites

Supposons que nous voulions mesurer les **seuils d’audibilité tonale** (*pure-tone thresholds*) d'un individu, c'est à dire le niveau sonore minimal auquel il est capable de détecter la présence d'un ton pur à une fréquence donnée, quelle serait la façon la plus simple et rapide de procéder ?

La réponse à cette question est **l'audiogramme**, un protocole classique et extrêmement courant pratiqué notamment par les ORL pour mesurer les pertes auditives éventuelles de leurs patient·es. Pour réaliser un audiogramme, on installe la personne dans une cabine insonorisée et on lui diffuse des bips à une certaine fréquence en lui demandant de lever la main à chaque fois qu'elle en perçoit un. Le premier bip est diffusé à un volume sonore facile, puis à chaque bonne réponse le volume sonore est réduit jusqu'à ce que l'individu ne soit plus en mesure de détecter le bip. On considère alors qu'on a atteint le seuil de détection pour la fréquence testée. Cette procédure est alors reproduite pour un large panel de fréquences, pour une oreille puis pour l'autre, de manière à caractériser de la façon la plus complète l'audition de chaque oreille sur tout le spectre sonore.

<br /> 

```{figure} Audiogramme.png
---
name: Audiogramme.png
alt: Réalisation d'un audiogramme
width: 400px
align: center
---
*Réalisation d'un examen audiométrique par une ORL.*
```

<br /> 

Voici une démo de mesure d'audiogramme. La figure suivante représente les résultats moyens obtenus sur cette démo. Pour plus de simplicité, le seuil de détection n'est pas exprimé en dB mais directement en nombre de tons successifs perçus.

```
<iframe src="https://github.com/LeoVarnet/psychoac-manuel-fr/blob/main/lecture/methodo/audiogramme.mp3" height="100" width="400" name="iframename">Démo audiogramme</iframe>
```

<br /> 

```{figure} Audiogramme2.png
---
name: Audiogramme2.png
alt: Résultats moyens
width: 400px
align: center
---
*Résultats moyens obtenus sur la démo précédente.*
```

<br /> 

Voici un tracé stylisé des courbes d'audiogramme typiques de 3 tranches d'âge. Globalement, comme vous avez pu vous en rendre compte dans la démo, les seuils d'audibilité tonale chez l'humain sont meilleurs autour de 1 à 2 kHz. Au contraire, notre acuité auditive est mauvaise lorsque l'on s'approche des limites de l'audition humaine (20 Hz et 20 kHz).

<br /> 

```{figure} Audiogramme3.png
---
name: Audiogramme3.png
alt: Audiogrammes typiques
width: 400px
align: center
---
*Exemple d'audiogrammes typiques pour 3 tranches d'âge.*
```

<br /> 

Cette expérience extrêmement simple suit la **méthode des limites descendante**, qui consiste à choisir un niveau de départ facile sur la dimension d'intérêt puis à augmenter progressivement la difficulté d'un essai à l'autre par pas constant jusqu'à ce que le participant ou la participante ne soit plus en mesure de réaliser la tâche demandée. À l'inverse, la **méthode des limites ascendante** part d'un niveau bas pour s'arrêter dès que le participant parvient à effectuer la tâche.

L'intérêt évident de la méthode des limites est qu'elle permet de mesurer un seuil en un temps très court : une descente ou une montée représentent une dizaine d'essais, selon le choix du niveau de départ et de la taille du pas, et on répète habituellement trois fois la mesure pour s'assurer de la stabilité du seuil, parfois en alternant méthodes ascendante et descendante. La figure suivante illustre une mesure composée de 6 répétitions, ascendantes et descendantes, en réduisant progressivement la taille du pas pour obtenir une meilleure précision.

<br /> 

```{figure} MethodeLimite.png
---
name: MethodeLimite.png
alt: Méthode des limites
width: 400px
align: center
---
*Enchaînement de méthodes de limites ascendantes et descendantes alternées autour d'un même seuil de détection. Dans cet exemple, la taille du pas est réduite après chaque série descendante puis ascendante.*
```

<br /> 

En revanche cette méthode présente également un désavantage majeur : le caractère subjectif de la définition du seuil. Pour s'en rendre compte, représentons la situation du point de vue de la fonction psychométrique. Considérons dans un premier temps un cas de forte sensibilité, c'est à dire de pente abrupte. Le seuil de détection correspond à la zone très étroite de la pente.

<br /> 

```{figure} MethodeLimite2.png
---
name: MethodeLimite2.png
alt: Fonction psychométrique abrupte
width: 500px
align: center
---
*Fonction psychométrique dans un cas de forte sensibilité.*
```

<br /> 

Cette fonction psychométrique est parcourue par la méthode des limites ascendante ou descendante jusqu'à découvrir le seuil de détection qui se traduit par un changement dans les réponses du participant ou de la participante.

<br /> 

```{figure} MethodeLimiteMontante.png
---
name: MethodeLimiteMontante.png
alt: Fonction psychométrique, méthode des limites ascendante
width: 500px
align: center
---
*Fonction psychométrique dans un cas de forte sensibilité, parcourue selon la méthode des limites ascendante.*
```

```{figure} MethodeLimiteDescendante.png
---
name: MethodeLimiteDescendante.png
alt: Fonction psychométrique, méthode des limites descendante
width: 500px
align: center
---
*Fonction psychométrique dans un cas de forte sensibilité, parcourue selon la méthode des limites descendante.*
```

<br /> 

Imaginons à présent que la sensibilité soit plus faible, c'est à dire que la pente de la fonction psychométrique soit plus douce. Il est alors difficile de définir -- et donc de mesurer -- précisément le seuil, celui-ci pouvant être placé arbitrairement à n'importe quel endroit dans la région de la pente. En pratique, l'expérience peut donner des résultats très variables d'un sujet à l'autre, voire pour un même sujet.

<br /> 

```{figure} MethodeLimiteMontante2.png
---
name: MethodeLimiteMontante2.png
alt: Fonction psychométrique de faible pente, méthode des limites ascendante
width: 500px
align: center
---
*Fonction psychométrique dans un cas de faible sensibilité, parcourue selon la méthode des limites ascendante.*
```

<br /> 

Il est donc conseillé d'user de la méthode des limites de préférence pour des tâches ou la sensibilité est forte, ou à défaut, de vérifier que la mesure de seuil est relativement stable. Alternativement, il est possible de se tourner vers la méthode de l'escalier psychophysique pour obtenir une meilleure définition du seuil, indépendante de la sensibilité.

## Escalier psychophysique 

L'escalier psychophysique est une amélioration de la méthode des limites visant à estimer un seuil perceptif défini sur une base objective, c'est à dire statistiquement. Plutôt que de considérer le seuil comme une valeur frontière au delà de laquelle le stimulus devient subitement inaudible, comme c'est le cas pour la methode des limites, l'escalier psychophysique définit le seuil comme une valeur correspondant à un certain pourcentage de réponses (on parle alors de **seuil à X%**).

L'escalier psychophysique **1-up-1-down** suit une règle adaptative très simple. Comme pour la méthode des limites descendante, une valeur de départ "facile" est choisie. Après chaque bonne réponse, le niveau de difficulté est augmenté d'un pas le long de la dimension d'intérêt. Au contraire, après chaque mauvaise réponse, le niveau de difficulté est diminué d'un pas.


<br /> 

```{figure} staircase.jpg
---
name: staircase.jpg
alt: Déroulement d'une expérience avec la méthode staircase
width: 500px
align: center
---
*Exemples d'évolution de la dimension d'intérêt (ici le niveau sonore, "stimulus level") dans le cas d'un escalier psychophysique. Les carrés noirs correspondent aux réponses "j'ai entendu le son", les ronds blancs aux réponses "je n'ai pas entendu le son". L'escalier A correspond à une règle 1-up-1-down, le B à une règle 1-up-3-down. Notez que dans ces deux exemples, la taille de pas change au cours de l'escalier.*
```

<br /> 


