# Stimuli et dimension

Le premier aspect à considérer lors de la mise en place d'une expérience de psychoacoustique est le **choix des stimuli**. Parmi les quatre caractéristiques décrites dans ce chapitre, le stimulus est sans nul doute la plus simple à déterminer puisqu'elle découle directement de la question scientifique considérée. Néanmoins, il est important de s'arrêter sur les principes qui doivent guider le choix des stimuli. Ceci nous donnera également l'occasion de présenter très brièvement le cadre de la Théorie de la détection du signal.

## Choix des stimuli et de la dimension d'intérêt

En psychophysique, le choix des stimuli (et dans une certaine mesure de la tâche) doit être guidé par le principe de **réductionnisme** : les sons présentés aux sujets doivent être les plus simples possible de façon à **solliciter uniquement le mécanisme cognitif étudié**. Ainsi, par exemple, si je m'intéresse à la perception des sons du langage, mais non à l'intelligibilité des mots, je devrais utiliser des pseudo-mots sans signification, comme "balure", "capoune", ou "aga", plutôt que des mots véritables, de façon à ne pas activer les mécanismes de l'accès au sens des mots -- qui ne nous intéressent pas et risqueraient de perturber notre mesure. De même l'étude de la perception des fréquences doit se fonder en priorité sur des stimuli simples comme les tons purs ou les complexes harmoniques, plutôt que sûr des mélodies composées de multiples notes ayant chacune des durées particulières.

Cependant, le choix d'un type particulier de stimulus, comme le ton pur, n'est pas encore assez spécifique. En effet, les tons purs peuvent varier en fréquence, mais également en durée ou en intensité. Dans le cadre d'une expérience psychophysique, on se limitera donc à une (ou un petit nombre de) **dimensions d’intérêt**, c'est à dire de paramètres acoustiques dont on cherche à étudier l’effet sur la perception. On pourra ainsi utiliser des tons purs de différentes fréquence, mais de même durée et de même intensité. Ou encore des bruits de brouhaha formés par une superposition d'un nombre N de voix simultanées, mais dans une seule et même langue, avec des locuteur·ices parlant dans un même registre de voix, et sans présenter de vidéo de la situation en simultané.

De façon plus générale la construction des questions psychophysiques elles-mêmes est sous-tendue par une approche réductionniste. Il s'agit, comme on le verra dans les chapitres suivants, de réduire une question extrêment large ("comment perçoit-on les sons ?") à des questions de plus en plus précises portant sur des mécanismes perceptifs de plus en plus spécifiques ("comment perçoit-on la hauteur tonale d'un son ?", puis "comment perçoit-on la hauteur tonale d'une série harmonique ?", puis "quel est le rôle de fréquence de la fondamentale dans la perception de la hauteur tonale d'une série harmonique ?", etc.). En cela, la psychophysique ne se distingue pas de l'ensemble des sciences modernes, toutes construites en suivant un raisonnement réductionniste.

## Un bref aperçu de la Théorie de la détection du signal

Une question qui se pose alors est de relier théoriquement la dimension d’intérêt des stimuli et la capacité d'un système à percevoir ces stimuli. Il s'agit d'une question centrale pour la **théorie de la détection du signal**, cadre mathématique dérivé de la théorie de l'information, et permettant de modéliser la capacité d’un système à séparer l’information du bruit. Cette théorie fut initialement développée pour les systèmes radar, mais rapidement appliqué à la perception humaine. [Green & Swets, 1966].

Pour illustrer les objectifs et méthodes de la TDS, considérons la situation suivante :

Nous sommes en possession d'un appareil permettant de mesurer l'énergie **E** d'un son. Au moyen de ce système nous analysons des stimuli de durée fixe composés soit d'un bruit seul (<span style="color:rgb(14,0,192)">**B**</span>) soit d'un bruit et d'un signal sonore cible (<span style="color:rgb(255,0,0)">**B+T**</span>). Nous souhaitons déterminer, sur la base de cette mesure d'énergie, si le signal sonore était présent ou non.

Pour simplifier le problème, nous supposons que le signal à détecter a une énergie mesurée de 1 (dans une unité arbitraire), notée *d'*, et que l'énergie du bruit suit une distribution gaussienne avec un écart-type de 1. On peut alors représenter la situation par la figure suivante:

<br /> 

```{figure} SDT1.png
---
name: SDT1.png
alt: Schéma de la Théorie de la détection du signal
height: 300px
align: center
---
*Schéma de de la Théorie de la détection du signal. Les courbes rouge et bleue représentent respectivement les probabilités de mesurer une valeur particulière d'énergie E pour le bruit seul ou pour le bruit+signal*
```

<br /> 

Dans la situation décrite ci-dessus, il est possible, dans une certaine mesure, de détecter la présence ou l'absence du signal cible à partir de la valeur d'énergie **E** totale. Ainsi, pour une valeur de E = 7 on peut répondre de façon assez certaine que le signal cible était présent, tandis qu'une valeur E = 4 nous indique plutôt que le signal cible était absent. Pour des valeurs intermédiaires il est plus difficile de donner une réponse tranchée, mais une règle optimale dans ce cas serait de répondre "ton présent" pour toute valeur de E supérieure à 5.5, et ton absent sinon. Un calcul de probabilité permet de démontrer que l'application de cette règle dans la situation décrite précédemment produit 64% de réponses correctes en moyenne.

On peut à présent se demander comment ce pourcentage évolue en fonction de la difficulté de la tâche. Ici, le niveau de difficulté dépend directement de *d'*, la différence entre le son avec ou sans le signal. Cette distance entre les deux gaussienne jouera ici le rôle de **variable d'intérêt**. À nouveau, il est possible de montrer par le calcul que la probabilité de détection en fonction de *d'* suit une loi cumulative gaussienne :

$$ p_{détect}(d') = 1/{1=e^{-(\alpha + \beta \cdot d'}} $$

<br /> 

```{figure} SDT2.png
---
name: SDT2.png
alt: Lien entre fonction psychométrique et difficulté de la tâche
height: 400px
align: center
---
*Calcul de la fonction psychométrique pour la situation décrite précédemment*
```

<br /> 

Lorsque la distance entre les deux gaussiennes augmente la tâche devient de plus en plus simple à réaliser -- et effectivement le pourcentage de détections tend alors vers 100%. Au contraire lorsqu'on diminue l'énergie du ton jusqu'à *d' = 0* (un signal cible d'énergie nulle, autrement dit une tâche de détection impossible à réaliser) la probabilité chute à 50%, ce qui correspond au pourcentage de bonnes réponses obtenu en répondant au hasard.

Notez que dans l'exemple choisi, *d'* est toujours positif car il n'aurait pas de sens que l'énergie du signal+bruit soit moindre que celle du bruit seul. Néanmoins dans d'autres situations, il peut être pertinent de continuer la courbe auquel cas on obtient la loi cumulative gaussienne complète, couvrant des probabilités de 0% à 100%.
