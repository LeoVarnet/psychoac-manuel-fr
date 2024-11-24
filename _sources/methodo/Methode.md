# Méthode expérimentale

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

Les méthodes sont classées en deux groupes : méthodes **adaptatives et non-adaptatives.** Parmi les méthodes adaptatives on trouve notamment la methode des limites et la méthode de l'escalier psychophysique. Dans les méthodes non-adaptatives on peut mentionner la mesure de performance et la méthode des stimuli constants.

## Méthode des limites

Supposons que nous voulions mesurer les **seuils d’audibilité tonale** (*pure-tone thresholds*) d'un individu, c'est à dire le niveau sonore minimal auquel il est capable de détecter la présence d'un ton à une fréquence donnée, quelle serait la façon la plus simple et rapide de procéder ?

La solution à cette question est **l'audiogramme**, un protocole classique et extrêmement courant pratiqué notamment par les ORL pour mesurer les pertes auditives éventuelles de leurs patient·es. Pour réaliser un audiogramme, on installe la personne dans une cabine insonorisée et on lui diffuse des bips à une certaine fréquence en lui demandant de lever la main à chaque fois qu'elle en perçoit un. Le premier bip est diffusé à un volume sonore facile, puis à chaque bonne réponse le volume sonore est réduit jusqu'à ce que l'individu ne soit plus en mesure de détecter le bip. On considère alors qu'on a atteint le seuil de détection pour la fréquence testée. Cette procédure est alors reproduite pour un large panel de fréquences, pour une oreille puis pour l'autre, de manière à caractériser de la façon la plus complète l'audition de chaque oreille sur tout le spectre sonore.

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

L'intérêt évident de la méthode des limites est qu'elle permet de \_mesurer un seuil en un temps très court\_ : une descente ou une montée représente une dizaine d'essais, selon le choix du niveau de départ et de la taille du pas, et on répète habituellement trois fois la mesure pour s'assurer de la stabilité du seuil, parfois en alternant méthodes ascendante et descendante.

En revanche cette méthode présente également un important désavantage : le caractère subjectif de la définition du seuil pour cette raison la méthode des limites est classée parmi les **méthodes subjectives**)
