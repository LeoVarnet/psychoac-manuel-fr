# Méthode expérimentale

## Qu'est-ce que la méthode expérimentale ?

Fixer la **méthode** de l'expérience revient à déterminer comment les stimuli évoluent d'un essai au suivant : sont-ils toujours identiques, varient-ils en fonction des réponses précédentes, ou indépendamment des réponses ? Ce choix est guidé par des contraintes pratiques, mais également par le type de mesure que l'on souhaite obtenir : mesure de seuil, de performance, ou de sensibilité ? Cette section présente les quatre méthodes les plus courantes, en les reliant à la fonction psychométrique décrite précédemment.

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

Les méthodes sont classées en deux groupes : **méthodes adaptatives** (les stimuli présentés dépendent des réponses précédentes) et **methodes non-adaptatives** (les réponses n'affectent pas le déroulement de l'experience). Parmi les méthodes adaptatives on trouve notamment la methode des limites et la méthode de l'escalier psychophysique. Dans les méthodes non-adaptatives on peut mentionner la mesure de performance et la méthode des stimuli constants. Nous nous concentrerons sur ces 4 méthodes dans les paragraphes qui suivent.

## Méthode des limites

Supposons que nous voulions mesurer le **seuil d’audibilité tonale** (*pure-tone threshold*) d'un individu, c'est à dire le niveau sonore minimal auquel il est capable de détecter la présence d'un ton pur à une fréquence donnée, quelle serait la façon la plus simple et rapide de procéder ?

La réponse à cette question est **l'audiogramme**, un protocole classique et extrêmement courant, pratiqué notamment par les ORL pour détecter et mesurer les pertes auditives éventuelles de leurs patient·es. Pour réaliser un audiogramme, on installe le sujet, muni d'un casque audio, dans une cabine insonorisée en lui demandant de lever la main à chaque fois qu'elle perçoit un son. Au moyen d'un audiomètre, l'expérimentateur·ice contrôle la diffusion de bips à une certaine fréquence et une certaine intensité dans une oreille du sujet (p.ex., ton pur à 1000 Hz et 20 dB SPL presenté dans l'oreille droite). Le premier son est diffusé à une intensité sonore confortable. Si le sujet indique comme attendu qu'il a détecté le bip, on réduit l'intensité d'un nombre de décibels fixé puis on recommence. À chaque bonne réponse le volume sonore est progressivement réduit jusqu'à ce que l'individu ne soit plus en mesure de détecter le bip. On considère alors qu'on a atteint le seuil de détection (en dB SPL) pour la fréquence et l'oreille testée. Cette procédure est alors reproduite pour un large panel de fréquences, pour une oreille puis pour l'autre, de manière à caractériser de la façon la plus complète l'audition de l'individu sur tout le spectre sonore.

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

Voici un exemple de mesure d'audiogramme. Sept fréquences sont testées successivement : 125 Hz, 250 Hz, 500 Hz, 1000 Hz, 2000 Hz, 4000 Hz, et 8000 Hz. Pour chacune, deux mesures sont réalisées correspondant à 11 tons purs d'intensité décroissante. La mesure exacte du seuil d'audibilité tonale nécessite de maîtriser exactement le volume sonore auquel sont diffusés les sons, ce qui n'est pas le cas ici. Néanmoins, vous pouvez obtenir un aperçu de votre sensibilité relative aux différentes fréquences en comptant le nombre de bips que vous percevez dans chaque série. Plus votre oreille est sensible à une fréquence donnée plus vous devriez être capable de dénombrer de tons successifs dans les séries correspondante.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_audiogram.mp3" type="audio/wav">
</audio>

La figure suivante représente les résultats obtenus en moyenne lors de cette petite expérience. Pour plus de simplicité, le seuil de détection n'est pas exprimé en dB mais directement en nombre de tons successifs perçus. On constate que la sensibilité de l'oreille humaine n'est pas équivalente sur tout le spectre sonore : certaines fréquence sont aisément détectées (autour de 2000 Hz) tandis que d'autres nécessitent des intensités sonores plus importantes pour être perçues (p.ex. 125 Hz et 8000 Hz). Cette courbe trace une estimation grossière de l'audiogramme humain.

<br /> 

```{figure} Audiogramme2.png
---
name: Audiogramme2.png
alt: Résultats moyens
width: 400px
align: center
---
*Résultats moyens obtenus sur la démo précédente. Pour chacune des sept fréquences testées, le seuil est représenté en termes de nombre de bips successifs perçus dans la série de 11 : un nombre plus élevé (plus bas sur l'axe) indique un meilleur seuil d'audibilité tonale.*
```

<br /> 

Voici un tracé stylisé des courbes d'audiogramme typiques de 3 tranches d'âge. On retrouve le profil général observé dans notre petite expérience : les seuils d'audibilité tonale chez l'humain sont meilleurs autour de 1 à 2 kHz. Au contraire, notre acuité auditive est mauvaise lorsque l'on s'approche des limites de l'audition humaine (20 Hz et 20 kHz). Le vieillissement résulte très souvent en une perte de sensibilité auditive dans les hautes fréquences nommée presbyacousie. Nous reviendrons sur ces résultats dans le chapitre 3. Dans l'immédiat, intéressons-nous au protocole expérimental suivi pour mesurer les seuils auditifs.

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

L'expérience de l'audiogramme que nous venons de décrire suit la **méthode des limites descendante**, une méthode adaptative très simple qui consiste à choisir un niveau de départ facile sur la dimension d'intérêt (ici l'intensité des bips) puis à augmenter progressivement la difficulté d'un essai à l'autre par pas constant jusqu'à ce que le participant ou la participante ne soit plus en mesure de réaliser la tâche demandée. À l'inverse, la **méthode des limites ascendante** part d'un niveau difficile pour s'arrêter dès que le sujet  parvient à effectuer la tâche.

L'intérêt évident de la méthode des limites est qu'elle permet de mesurer un seuil en un temps très court : une descente ou une montée représentent une dizaine d'essais, selon le choix du niveau de départ et de la taille du pas, et on répète habituellement trois fois la mesure pour s'assurer de la stabilité du seuil, parfois en alternant méthodes ascendante et descendante. La figure et l'exemple sonore suivants illustrent une mesure composée de 6 répétitions, ascendantes et descendantes, en réduisant progressivement la taille du pas pour obtenir une meilleure précision.

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

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_limits.mp3" type="audio/wav">
</audio>

Notons d'ores et déjà qu'il est facile d'appliquer la même méthode à d'autres tâches psychoacoustiques. Voici par exemple le même enchaînement de méthodes de limites ascendantes et descendantes que précédemment, cette fois dans le cas d'une tâche de détection des modulations (instruction données au sujet : "indiquez si vous avez perçu une vibration dans le son"). La dimension d'intérêt variée d'un essai à l'autre est dans ce cas l'ampleur des fluctuations, des modulations plus fines étant plus difficiles à détecter.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_limitsAM.mp3" type="audio/wav">
</audio>

Nous reviendrons dans les sections suivantes sur la notion de tâche psychophysique, et comment la combiner avec différentes méthodes.

On pourrait reprocher à cette expérience -- comme à toutes celles que nous verrons par la suite dans ce chapitre -- de ne pas tenir compte des biais d'attente du participant ou de la participante : lors d'une série descendante, par exemple, le fait de s'attendre à entendre le bip suivant facilite très certainement sa détection. Dans le pire de cas, un sujet "tricheur" pourrait décider de répondre toujours "j'ai entendu le bip" pour obtenir des résultats arbitrairement elevés. Il est néanmoins aisé de contrecarrer ces stratégies en insérant des essais sans bips, répartis aléatoirement, et pour lesquels la réponse correcte serait donc "je n'ai pas entendu de son". Si ces essais sont aussi nombreux que les essais présentant un bip, nous sommes assuré·es que la mesure obtenue ne sera pas affectée par les biais d'attente.

Néanmoins, la méthode des limites présente un désavantage majeur : le caractère subjectif de la définition du seuil. Pour s'en rendre compte, représentons la situation du point de vue de la fonction psychométrique. Considérons dans un premier temps un cas de forte sensibilité, c'est à dire de pente abrupte. Le seuil de détection correspond à la région très étroite où la fonction prend des valeurs intermédiaires entre 0 et 1. La fonction psychométrique peut être parcourue par la méthode des limites ascendante ou descendante afin de découvrir le seuil de détection -- qui se traduit par un changement dans les réponses du participant ou de la participante.

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

Il est donc conseillé d'user de la méthode des limites de préférence pour des tâches où la sensibilité est forte ou, à défaut, de vérifier que la mesure de seuil est relativement stable. Alternativement, il est possible de se tourner vers la méthode de l'escalier psychophysique pour obtenir une meilleure définition du seuil, indépendante de la sensibilité.

## Escalier psychophysique 

L'escalier psychophysique est une amélioration de la méthode des limites visant à estimer un seuil perceptif défini sur une base objective, c'est à dire statistiquement. Plutôt que de considérer le seuil comme une valeur frontière au delà de laquelle le stimulus devient subitement inaudible, comme c'est le cas pour la methode des limites, l'escalier psychophysique définit le seuil comme une valeur correspondant à un certain pourcentage de réponses (on parle alors de **seuil à X%**).

L'escalier psychophysique **1-up-1-down** suit une règle adaptative très simple. Comme pour la méthode des limites descendante, une valeur de départ "facile" est choisie. Après chaque bonne réponse, le niveau de difficulté est augmenté d'un pas le long de la dimension d'intérêt. Au contraire, après chaque mauvaise réponse, le niveau de difficulté est diminué d'un pas.

La partie A de la figure suivante illustre le déroulement d'une mesure de seuil de détection au moyen de la règle 1-up-1-down. Le début de l'escalier est semblable à la méthode des limites descendantes : le niveau du stimulus est diminué par pas successifs tant que le sujet parvient à  détecter celui-ci correctement (symboles noirs). En revanche, contrairement à la méthode des limites, l'expérience ne s'interrompt pas au moment où le sujet donne la première réponse négative (symbole blanc), mais un nouveau stimulus est présenté avec un niveau rehaussé de la valeur d'un pas. L'expérience continue en suivant cette règle, si bien que le niveau finit par osciller autour d'une certaine valeur. Cette valeur correspond au seuil de détection à 50%, c'est à dire le niveau sonore pour lequel le stimulus est détecté 50% du temps (c'est-à-dire avec une probabilité de 50%).

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

Les deux exemples audio suivants correspondent aux parties A et B de la figure ci-dessus. Comme précédemment, chaque essai est suivi d'un signal sonore indiquant la réponse positive ou négative du sujet.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_staircase1.mp3" type="audio/wav">
</audio>

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_staircase2.mp3" type="audio/wav">
</audio>

Il est très simple de démontrer que l'escalier 1-down-1-up converge vers le seuil à 50%. En effet, à l'équilibre, la probabilité de monter est égale à la probabilité de descendre, soit :

\begin{gather*}
p(descendre) = p(monter)\\
p(détection) = p(non-détection)\\
p(détection) = 1 - p(détection)\\
p(détection) = 0.5\\
\end{gather*}

L'escalier 1-down-1-up offre donc une manière relativement efficace d'évaluer le seuil à 50%. L'estimation d'un seuil nécessite habituellement une trentaine d'essais, une durée qui peut varier selon la valeur de départ de l'escalier et le degré de précision souhaité. Il est également possible, comme illustré sur la figure, de réduire la taille du pas au cours de l'escalier de façon à combiner convergence rapide et estimation précise.

Notez que le seuil à 50% estimé par cette méthode ne possède a priori aucune propriété particulière du point de vue perceptif, comparé par exemple au seuil à 53% ou à 70%. Il s'agit simplement d'un pourcentage arbitraire mais qui permet de définir le seuil de façon univoque. Néanmoins certaines questions de recherche peuvent nécessiter d'estimer un seuil plus élevé. Ainsi, par exemple, pour une expérience où les sujets obtiennent déjà un score de 50% en répondant aléatoirement, viser le seuil de détection à 50% serait absurde -- on préférera alors caractériser la perception au moyen d'un seuil plus élevé, par exemple à 75%.

Fort heureusement, la méthode de l'escalier psychophysique n'est pas restreinte à un unique point de convergence possible. Il est possible d'atteindre n'importe quel seuil en changeant la règle de progression. Ainsi par exemple, appliquer une règle de **3-down-1-up** telle que celle illustrée dans la partie B de la figure précédente permet de viser le seuil à 79.4%. En effet,

\begin{gather*}
p(descendre) = p(monter)\\
p(détection)^{3} = p(non-détection)\\
p(détection)^{3} = 1 - p(détection)^{3}\\
p(détection)^{3} = 0.5\\
p(détection) = 0.794
\end{gather*}

Une autre possibilité consiste à définir des pas asymétriques pour les montées et les descentes.

En résumé, l'escalier psychophysique permet de parcourir la fonction psychométrique jusqu'à converger vers un pourcentage de réponses prédéfini. Le seuil à X% correspond alors à la position en ordonnée une fois l'équilibre atteint. 

<br /> 

```{figure} psychostaircase1.png
---
name: psychostaircase1.png
alt: Fonction psychométrique et méthode de l'escalier psychophysique
width: 500px
align: center
---
*Fonction psychométrique parcourue selon la méthode de l'escalier psychophysique. La règle appliquée dans cet exemple est un two-down-one-up.*
```

<br /> 


<br /> 

```{figure} psychostaircase2.png
---
name: psychostaircase1.png
alt: Fonction psychométrique et méthode de l'escalier psychophysique
width: 500px
align: center
---
*Lecture du seuil une fois la convergence de l'escalier atteinte. La règle du two-down-one-up est à l'équilibre lorsque la probabilité de réponse correcte est de 70.7%. Le seuil à 70.7% correspond alors à la valeur de la dimension d'intérêt au niveau de la convergence.*
```

<br /> 

L'escalier psychophysique est donc un moyen d'obtenir une mesure relativement rapide de seuil qui n'est pas restreinte à la limite de la perception, contrairement à la méthode des limites, mais peut viser n'importe quel pourcentage de réponses correctes. Cette définition statistique du seuil est par ailleurs valable quelle que soit la pente de la fonction psychométrique. 

Outre leur rapidité, les méthodes adaptatives ont l'avantage d'être relativement flexibles, fonctionnant même si la stratégie du sujet n'est pas stable dans le temps. Dans ce cas l'escalier continuera simplement de suivre un point d'équilibre mouvant. De plus, comme nous le détaillerons plus loin, en visant un niveau de difficulté donné la méthode de l'escalier permet d'éviter l'effet plafond.

L'inconvénient des méthodes adaptatives, en revanche, est que tous les sujets ne recevront pas exactement le même ensemble de stimuli: celles et ceux qui ont plus de difficultés à réaliser la tâche auront des stimuli plus faciles que les individus plus performants. Ce déséquilibre peut poser problème, par exemple si l'on souhaite comparer deux groupes dans les mêmes conditions expérimentales. Ceci nous incite donc à considérer des méthodes non-adaptatives, pour lesquelles les stimuli présentés ne dépendent pas des performances.

## La mesure de performance 

Une façon extrêmement simple et intuitive de comparer deux groupes dans les mêmes conditions expérimentales est de réaliser une **mesure de performance**. On choisit alors simplement un niveau fixe de la dimension d'intérêt -- qui n'est donc à proprement parler plus une "variable" de l'expérience -- et on mesure le pourcentage de bonnes réponses de chaque groupe à ce niveau. Comme nous l'avons souligné précédemment, cette expérience peut bien sûr nécessiter d'insérer des essais correspondant à la réponse "non", c'est à dire des stimuli où le signal à détecter est absent, pour éviter que les sujets soient tentés de répondre systématiquement "oui" sans réellement percevoir le stimulus. Par exemple, on peut mesurer rapidement les capacités de détection de ton pur à 5 dB SPL en présentant une dizaine de stimuli à ce niveau sonore, alternés aléatoirement avec autant d'essais où le ton est absent, et en mesurant le pourcentage de réponses correctes total. Ceci revient en réalité à mesurer la valeur de la fonction psychométrique en un point unique :

<br /> 

```{figure} psychoperf1.png
---
name: psychoperf1.png
alt: Fonction psychométrique et mesure de performance
width: 500px
align: center
---
*Lien entre la mesure de performance et la fonction psychométrique. On présente ici des stimuli à un niveau arbitraire représenté par la flèche bleue. La méthode nous permet de mesurer la valeur correspondante de la fonction psychométrique, c'est à dire le pourcentage de réponses correctes pour ce niveau particulier.*
```

<br /> 

De la même manière, il est possible au moyen de la mesure de performance de comparer deux conditions, toutes choses égales par ailleurs (par exemple la détection d'un ton pur à 5 dB SPL ou du même ton pur en présence de bruit). Dans l'exemple suivant, les deux conditions correspondent à deux fonctions psychométriques de couleurs différentes :

<br /> 

```{figure} psychoperf2.png
---
name: psychoperf2.png
alt: Fonction psychométrique et comparaison de performances
width: 500px
align: center
---
*Exemple de comparaison de performances entre deux conditions ou deux groupes (sybolisés par les fonctions psychométriques rouge et noire). Pour un niveau donné, les performances sont différentes ce qui indique que les fonctions psychométriques sous-jacentes le sont également.*
```

<br /> 

La figure suivante illustre les résultats d'une mesure de performance pour la reconnaissance de parole par trois groupes dans quatre conditions expérimentales. Ceci conduit donc à 3 x 4 = 12 mesures de performance, qui peuvent ensuite être comparées deux à deux.

<br /> 

```{figure} perf.png
---
name: perf.png
alt: Exemple de mesure de performances
width: 500px
align: center
---
*Exemple de mesures de performance en compréhension de parole réalisée chez différents groupes de sujets (symbolisés par les différentes couleurs) et dans différentes conditions epérimentales (dans le silence, dans le bruit, etc...)*
```

<br /> 

Il faut néanmoins souligner un écueil potentiel de cette méthode. Si le niveau choisi sur la dimension d'intérêt est trop élevé (tâche trop facile) ou trop bas (tâche trop difficile), les performances mesurées seront proches du plafond ou du plancher respectivement et il ne sera pas possible de différencier les deux conditions. La mesure de performance nécessite donc quelques connaissances préalables pour fixer judicieusement le niveau de difficulté de l'expérience.

<br /> 

```{figure} psychoperf3.png
---
name: psychoperf3.png
alt: Fonction psychométrique et comparaison de performances dans un cas d'effet plafond
width: 500px
align: center
---
*Exemple de comparaison de performances dans un cas d'effet plafond. Le niveau choisi étant trop simple, les deux groupes obtiennent une performance proche de 100% et il est alors impossible de les distinguer, bien que les fonctions psychométriques sous-jacentes soient en réalité différentes.*
```

<br /> 

Notez en revanche que les comparaisons basées sur une méthode adaptative -- c'est-à-dire visant une mesure de seuil -- ne présentent pas cette limitation, car le niveau de performance est déterminé par l'expérimentateur ou l’expérimentatrice. Cependant, de façon générale, les mesures de performance et les mesures de seuil ne fournissent qu'une vision très restreinte de la fonction psychométrique, limitée à un point unique. Pour caractériser la perception de manière plus exhaustive, il peut être préférable d’adopter la méthode des stimuli constants.

## Méthode des stimuli constants 

La **méthode des stimuli constants** consiste simplement à réitérer la mesure de performance en différents points le long de la dimension d'intérêt. Plutôt que de mesurer le taux de bonnes réponses pour un niveau unique, on définit un continuum de 10 à 15 niveaux, régulièrement espacés, et on présente des essais correspondant à ces différents niveaux dans un ordre aléatoire. Ceci permet d'échantillonner la fonction psychométrique en plusieurs points, de façon à visualiser le profil général de la courbe. Il est ensuite possible d'utiliser des méthodes statistiques pour ajuster une fonction logistique aux données collectées et estimer la pente et le seuil à n'importe quel pourcentage de réponses correctes. La méthode des stimuli constants est donc _la seule méthode permettant d'obtenir une estimation de la sensibilité_.

<br /> 

```{figure} StimConst1.png
---
name: StimConst1.png
alt: Fonction psychométrique et méthode des stimuli constants
width: 500px
align: center
---
*Fonction psychométrique parcourue par la méthode des stimuli constants. Les différentes mesures de performances correspondant à 7 niveaux de la dimension d'intérêt permettent d'échantillonner la fonction psychométrique, puis de déterminer sa pente ou son seuil à X%*
```

<br /> 

Voici un exemple de méthode des stimuli constants dans la situation de détection de tons purs à la fréquence de 1000 Hz. Douze niveaux sonores différents sont présentés dans un ordre aléatoire, la tâche du sujet consistant à indiquer après chaque essai s'il a perçu ou non un son. Chaque niveau est présenté un total de trois fois.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_constantstimuli.mp3" type="audio/wav">
</audio>

La figure ci-dessous résume les résultats moyens obtenus dans l'expérience précédente : les points correspondent aux performances mesurées et la courbe à la fonction ajustée sur la base de ces données. Comme attendu, les pourcentages de détection sont proches de 0 lorsque le ton est présenté à un niveau extrêmement faible (< 3 dB SPL). Puis les performances s'améliorent avec le niveau sonore jusqu'à atteindre le maximum de 100%. La courbe totale suit une fonction psychométrique telle que décrite au chapitre précédent.

<br /> 

```{figure} SDT7.png
---
name: SDT7.png
alt: Méthode des stimuli constants appliquée à la détection de ton pur
width: 500px
align: center
---
*Exemple de fonction psychométrique estimée par la méthode des stimuli constants, dans le cas de la tâche de détection de ton pur dans le silence.*
```

<br /> 

La méthode des stimuli constants offre ainsi la caractérisation la plus complète possible de la fonction psychométrique, au contraire des méthodes des limites ou de l'escalier psychophysique qui ne visent qu'à estimer un seuil, et de la mesure de performance qui ne fournit la valeur de la fonction psychométrique qu'en un point unique. Elle est en revanche plus coûteuse en temps : la mesure de performance unique nécessitant une trentaine d'essais, la méthode des stimuli constants requiert 300 à 450 essais au total. Ainsi, il serait par exemple déraisonnable d'espérer mesurer un audiogramme au moyen de la méthode des stimuli constants. En effet, cela nécessiterait de réaliser une caractérisation de la fonction psychométrique pour chaque fréquence pour laquelle on souhaite caractériser le seuil, soit plusieurs milliers d'essais.

## Comparaison des méthodes expérimentales 

En résumé, le choix d'une méthode expérimentale particulière est guidé par plusieurs facteurs. Tout d'abord, le type de mesure visée : souhaite-t-on obtenir un pourcentage moyen de réponse, un seuil, ou une mesure de sensibilité ? La méthode des stimuli constants donne accès à ces trois informations, en revanche les méthodes adaptatives sont restreintes à des estimations de seuil (on peut en théorie  estimer une sensibilité à partir de l'escalier psychophysique mais cette mesure est peu précise et donc déconseillée), et la mesure de performance ne fournit qu'un pourcentage de réponses.

Un autre critère important pour guider le choix d'une méthode particulière est la durée de l'expérience. En effet les études impliquant un nombre élevé de conditions, ou des participants et participantes particulièrement fatiguables, seront limitées sur le nombre d'essais maximum par estimation. Bien que le nombre d'essais dépende également du degré de précision souhaité, on peut estimer grossièrement que la mesure de performance et la méthode des limites nécessitent 20-30 essais, l'escalier psychophysique une cinquantaine d'essais, et la méthode des stimuli constants plusieurs centaines d'essais. Il faut noter que la durée totale de l'expérience dépend également d'autres facteurs, notamment le nombre de stimuli présentés à chaque essais, comme nous le verrons aux chapitres suivants.

Comme nous l'avons vu, chaque méthode correspond à une façon particulière de parcourir la fonction psychométrique :

<br /> 

```{figure} AllMethods2.png
---
name: AllMethods2.png
alt: Résumé des différentes méthodes psychophysiques
width: 900px
align: center
---
*Comparaison des différentes méthodes expérimentales du point de vue de l'exploration de la fonction psychométrique*
```

<br /> 

On peut également représenter le déroulement temporel des quatre méthodes expérimentales.

<br /> 

```{figure} AllMethods.png
---
name: AllMethods.png
alt: Résumé des différentes méthodes psychophysiques
width: 900px
align: center
---
*Comparaison des différentes méthodes expérimentales du point de vue du déroulement de l'experience.*
```

<br /> 
 
Bien que cette figure ne le fasse pas apparaître explicitement, notez que, comme la mesure de performance, les méthodes adaptatives peuvent comporter des essais sans stimuli de façon à ne pas encourager les participants et participantes à répondre "oui" sans avoir réellement perçu le son.

## D'autres méthodes psychophysiques

Dans un souci de concision, je me suis jusqu'ici volontairement limité à ma description de quatre méthodes extrêmement courantes, en faisant l'impasse sur d'autres. En particulier, je n'ai pas jugé utile de mentionner la **méthode des ajustements**, souvent évoquée dans les manuels mais relativement peu utilisée en pratique. Il s'agit d'une mesure adaptative dans laquelle le sujet fait varier lui-même le stimuli le long de la dimension d'intérêt afin de le placer au niveau qu'il juge être la limite de son seuil de détection. Ce type de protocole est très intéractif et donc agréable du point de vue des participants et participantes, en revanche elle est particulièrement subjective et sujette aux différentes formes de biais évoqués plus haut. La **double-passe** est une méthode non adaptative qui vise à estimer le "bruit interne", c'est à dire le degré de variabilité des réponses des sujets. Elle consiste à présenter le même ensemble de stimuli à deux reprises et à comparer si les réponses étaient identiques entre la première passe et la seconde. Finalement, notez qu'il est possible d'utiliser la méthode des stimuli constants sur deux dimensions d'intérêt simultanément, en définissant un continuum de stimuli bidimensionnel. La **corrélation inverse** est une forme de généralisation de cette approche à des continuum de dimensionnalité très élevée (parfois des milliers de dimensions étudiées conjointement), en introduisant un échantillonnage aléatoire le long de chaque dimension.
