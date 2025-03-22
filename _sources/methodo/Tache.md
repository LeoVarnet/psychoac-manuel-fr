# Tâche et instructions

## Qu'est-ce que la tâche psychophysique ?

Choisir la **tâche** dans une expérience psychophysique revient à déterminer ce que les participants et participantes doivent faire des sons qu'ils écoutent : faut-il les comparer, les comprendre, chercher à identifier une caractéristique particulière ? Autrement dit il s'agit essentiellement des instructions données aux sujets au début de l'expérience. (Il est cependant à noter que les instructions exactes dependent également du paradigme psychophysique, décrit plus loin).

## Tâche de détection 

Jusqu'à ce point du manuel nous n'avons considéré qu'un seul type de tâche, la **détection**, correspondant à des instructions du type "avez-vous entendu un son ?" (comme dans le cas de l'audiogramme : "avez-vous entendu un bip sonore ?") ou, plus généralement, "le stimulus que vous venez d'écouter possédait-il telle caractéristique particulière" (comme dans le cas de la tâche de détection des modulations : "ce bip est-il modulé ou non ?").

L'expérience prend alors la forme suivante, dans le cas de l'audiogramme :

<br /> 

```{figure} ExpeDetect.png
---
name: ExpeDetect.png
alt: Schéma de l'expérience psychophysique, tâche de détection
width: 400px
align: center
---
*Schéma de la structure d'une expérience psychoacoustique dans le cas d'une tâche de détection (avec un paradigme yes/no).*
```

<br /> 

Combinée à une mesure de seuil, la tâche de détection permet d'estimer des **seuils de détection**, aussi appelés **seuils absolus**. Le seuil de détection correspond donc, pour un stimulus donné, au niveau minimal auquel il est perceptible -- ou auquel il est perceptible avec une précision de X%.

## Tâche de discrimination 

La tâche de **discrimination**, aussi appelée ***same/different***, necessite au minimum deux stimuli par essais. L'objectif du participant ou de la participante est de déterminer si les deux sons étaient les mêmes, ou différents (instructions du type : « Les deux sons que vous venez d'entendre étaient-ils identiques ? »). Comme pour la détection, l'instruction peut également ne porter que sur une caractéristique particulière des stimuli en faisant abstraction des autres aspects (par exemple : « Les deux sons que vous venez d'entendre étaient-ils modulés à la même fréquence ? »), ou sur l'appartenance ou non à une même catégorie (par exemple : « Les deux sons que vous venez d'entendre ont-ils été produits par le même objet  ? »).

Voici un exemple de déroulement d'une expérience de discrimination :

<br /> 

```{figure} ExpeDiscrim.png
---
name: ExpeDiscrim.png
alt: Schéma de l'expérience psychophysique, tâche de discrimination
width: 400px
align: center
---
*Schéma de la structure d'une expérience psychoacoustique dans le cas d'une tâche de discrimination, avec un paradigme yes/no.*
```

<br /> 

Dans le cas d'une mesure de seuil, on obtient ainsi le **seuil de discrimination** aussi appelé **seuil différentiel**, ***differential limens*** (DL) ou ***just noticeable difference*** (JND). Il s'agit de la plus petite variation perceptible d’un stimulus donné.

Au chapitre précédent, nous avons évoqué le seuil d'audibilité tonale, cas particulier de seuils de détection de tons purs. Comme nous l'avons vu, on peut le mesurer en présentant des tons purs d'intensité décroissante jusqu'à ce que le participant ou la participante ne parvienne plus à les détecter (méthode des limites + tâche de détection). La répétion de cette mesure de seuils pour des tons à différentes fréquences permet de tracer l'audiogramme et ainsi de démontrer que, au niveau liminaire, l’intensité perçue dépend de la fréquence. Par exemple, comme on peut le lire sur la figure suivante, un ton pur à 20 dB SPL sera audible ou non selon que sa fréquence est 50 Hz ou 500 Hz.

<br /> 

```{figure} Audiogramme4.png
---
name: Audiogramme4.png
alt: Audiogramme
width: 400px
align: center
---
*Rappel : tracé de l'audiogramme.*
```

<br /> 

En revanche, cette expérience ne permet pas de déterminer si le même phénomène se produit à des niveaux supraliminaires, c'est-à-dire au-dessus du seuil de perception : la perception de l'intensité à des niveaux élevés dépend-elle de la fréquence ? Pour le savoir, il est nécessaire de réaliser une seconde expérience, très similaire à la première mais basée sur une tâche de discrimination. Le protocole expérimental est identique, à une différence près : deux sons sont présentés à chaque essais et la tâche consiste à indiquer s'ils étaient de même intensité ou non. Le premier son est un stimulus de référence, identique pour tous les essais, ici un ton pur à 1 kHz et à une intensité fixe (p.ex. 60 dB SPL). Le second son est le véritable stimulus de test, un ton pur à la fréquence testée (p.ex. 500 Hz), et d'intensité variable. Après avoir écouté les deux sons, le participant ou la participante doit indiquer s'ils étaient à la même intensité ou non. On suit la méthode des limites pour déterminer le seuil de discrimination, le niveau du ton testé pour lequel il est jugé à la même intensité que le son de référence. 

Voici une démo de la mesure de seuil de discrimination décrite ci-dessus.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/isosonique.wav" type="audio/wav">
</audio>

Ce deuxième protocole expérimental, lorsqu'il est répété pour un certain nombre de fréquences test, permet de tracer la **courbe isosonique** pour l'intensité de référence. En répliquant la procédure pour différentes intensités de référence, on obtient ainsi un faisceau de courbes isosoniques qui offrent un aperçu de la perception de l'intensité selon les fréquences à différents niveaux sonores. Nous reviendrons sur l'interprétation de ces courbes au chapitre 3.

<br /> 

```{figure} Isosonique.png
---
name: Isosonique.png
alt: Courbes isosoniques
width: 500px
align: center
---
*Courbes isosoniques typiques. Chaque courbe bleue est mesurée relativement à un ton de référence à 1 kHz et dont l'intensité est indiquée en orange. La courbe la plus basse (en vert) correspond aux seuils auditifs mesurés précédemment par l'audiogramme. Chaque courbe indique donc un ensemble de tons purs perçus comme ayant la même intensité.*
```

<br /> 

## Choix de la tâche psychophysique

On distingue quatre grands types de tâches psychophysiques :

- **Détection** : Pouvez-vous l’entendre ? Pouvez-vous entendre telle caractéristique ?
- **Discrimination** ou ***same/different*** : Pouvez-vous entendre la différence avec cet autre stimulus ? (Attention, le terme *discrimination* est parfois également utilisé dans la littérature scientifique pour désigner des tâches de catégorisation.)
- **Catégorisation** ou **identification** : À quelle catégorie appartient le son que vous venez d'entendre ? Est-ce plutôt un X, un Y, ou un Z ?
- **Reconnaissance** ou **intelligibilité** : Quel est le son que vous venez d'entendre ? Pouvez vous répéter ce que vous avez compris ?

Comme illustré par la comparaison entre l'audiogramme (méthode des limites + détection) et les courbes isosonique (méthode des limites + discrimination), les quatre tâches psychophysiques ci-dessus sont combinables avec les 4 méthodes psychophysiques vues précédemment. Par exemple, on peut mesurer seuil d'intelligibilité à 50% avec un escalier psychophysique 1-up-1-down couplé à une tâche d'intelligibilité. La valeur obtenue est appelée *speech reception threshold* (SRT) et est très couramment utilisée en psycholinguistique.

Comme pour les stimuli au chapitre précédent, le choix d'un type particulier de tâche est avant tout guidé par la question de recherche : les scientifiques travaillant sur la compréhension des sons de parole privilégient par exemple les tâches d'intelligibilité, plus proches de la situation quotidienne de communication, mais peuvent être amené·es à utiliser des tâches de catégorisation, discrimination, voire de détection, pour explorer certains aspects spécifiques des mécanismes de décodage des sons. Cependant d'autres facteurs peuvent entrer en jeu comme détaillé dans les sections suivantes.

## Tâches et stratégies 

Il convient de souligner à ce stade qu'il existe un recouvrement partiel entre ces différentes tâches. Ainsi, une tâche de détection d'un signal particulier peut être considérée comme une catégorisation du stimulus entre les deux catégories "signal présent" et "signal absent". De même, si l'on ne considère qu'un ensemble restreint de son possibles, la reconnaissance est assimilable à une forme de catégorisation. Cette redondance reste toutefois sans grande conséquence, à condition que la tâche soit clairement définie.

En revanche, un point plus problématique réside dans le fait que la tâche ne décrit pas seulement le protocole expérimental en lui-même, mais également la manière dont le participant ou la participante exécute les instructions qui lui sont données. Considérons par exemple une tâche de discrimination nécessitant de comparer un stimulus et un signal cible de référence présenté à chaque essai. Il est possible de réaliser effectivement cette tâche comme une discrimination, mais une alternative possible consisterait à ignorer le signal de référence -- puisque celui-ci est identique d'un essai à l'autre -- et à écouter uniquement sur le stimulus. Cela reviendrait alors à effectuer une tâche de détection. Cette distinction est importante car elle implique des processus cognitifs potentiellement distincts, et se traduit par des performances différentes. En pratique, il est donc important pour l'expérimentateur ou l'expérimentatrice d'envisager toutes les stratégies possibles pour réaliser la tâche, et éventuellement de mettre en place des contrôles pour éliminer certaines stratégies jugées indésirables (par exemple, dans la tâche décrite ci-dessus, changer régulièrement le signal cible pour contraindre le participant ou la participante à prêter attention à la référence). 

## Instructions implicites

Les tâches de détection et de catégorisation nécessitent de décrire précisément le ou les stimuli-cible au sujet pour qu'il soit en mesure de réaliser l'expérience. Dans certains cas, on ne souhaite pas donner trop de détails dans les instructions, notamment lorsque les stimuli sont trop complexes pour être décrits de façon succincte et compréhensible par des personnes extérieures au domaine, ou s'il y a un risque de rendre ainsi le comportement du sujet moins naturel ou d’imposer une « grille de lecture » particulière. On peut alors utiliser la tâche de discrimination pour donner des **instructions implicites**. En effet, il suffit pour cette tâche de demander à identifier le son différent -- sans nécessairement préciser en quoi consiste la différence.
En contrepartie, la tâche de discrimination nécessite de présenter un stimulus de plus à chaque essai ce qui peut rallonger considérablement l'expérience.



Exemple : perception des paysages sonores

