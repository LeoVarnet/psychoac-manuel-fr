# Paradigme expérimental

## Qu'est-ce que le paradigme expérimental ?

Le **paradigme expérimental** est un paramètre de l'expérience moins intuitif que la tâche et la méthode, décrites précédemment. Il s'agit ici essentiellement de définir l'organisation des stimuli au sein d'un essai et le type de réponse attendu. Comme nous le verrons, ce choix a une influence sur la gamme de performances atteignables, et sur les potentiels biais de réponse des participants et participantes. Dans ce chapitre nous décrirons les deux paradigmes les plus courants: le yes/no et le choix forcé.

## Le paradigme yes/no 

Considérons à nouveau l'expérience de mesure des seuils d'audibilité tonale qui constitue le fil rouge de ce chapitre. À chaque essai, un stimulus unique est joué (ton pur à la fréquence cible ou silence) et le sujet doit indiquer si il a ou non perçu un son.

<br /> 

```{figure} ExpeYN.png
---
name: ExpeYN.png
alt: Schéma de l'expérience yes/no
height: 400px
align: center
---
*Rappel : structure de l'expérience de mesure des seuils d'audibilité tonale (méthode des limites, tâche de détection, paradigme yes/no)*
```

<br /> 

Cette expérience constitue un bon exemple de **paradigme yes/no** : il s'agit pour le sujet de répondre simplement à la tâche en classant l'essai de façon binaire selon la tâche demandée  ("présent/absent", "catégorie A"/"catégorie B", "identique/différent"). Le yes/no repose sur un seul stimulus par essai, sauf dans le cas de la tâche de discrimination qui nécessite deux stimuli.

Un problème se pose néanmoins : la mesure obtenue par paradigme yes/no est **dépendante du critère** (*criterion-dependent*), c’est-à-dire que le résultat peut être influencé par les biais de réponse de l'individu. Ainsi, une personne peu sûre d'elle (qui répond très facilement « non » lorsqu'elle n'est pas absolument certaine d'avoir perçu le ton) obtiendra des seuils d’audibilité globalement plus faible que la moyenne, indépendamment de ses capacités perceptives. Ceci signifie que notre mesure psychophysique est polluée par des caractéristiques psychologiques "haut-niveau" du sujet, telles que la confiance en soi, qui ne devraient pas entrer ici en compte.

Un moyen d'obtenir une mesure **indépendante du critère** (*criterion-free*) est d'opter pour un paradigme du choix forcé.

## Le paradigme du choix forcé

Voici une seconde expérience permettant elle aussi de mesurer les seuils d'audibilité tonale :
À chaque essai, deux stimuli successifs sont présentés dans un ordre aléatoire, l’un étant un ton cible l’autre un silence. Le début de chaque intervalle peut être indiqué par une lumière ou un léger signal sonore. Après ces deux stimuli, la consigne donnée au sujet est de sélectionner l’intervalle contenant le ton. Deux boutons de réponse sont disponibles pour indiquer si le ton de trouvait en première position ou en deuxième position.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/2AFC.wav" type="audio/wav">
</audio>

<br /> 

```{figure} ExpeFC.png
---
name: ExpeFC.png
alt: Schéma de l'expérience forced choice
height: 400px
align: center
---
*Structure de l'expérience de mesure des seuils d'audibilité tonale en paradigme de choix forcé (méthode des limites, tâche de détection, paradigme 2AFC)**
```

<br /> 

Cette seconde expérience repose sur la même tâche et la même méthode que la précédente, en revanche le paradigme est différent : il s'agit d'un **choix forcé à deux alternatives**.

Une propriété intéressante de ce paradigme, comparé au yes/no, est son insensibilité aux biais potentiels des participants et participantes. Ceci peut être démontré par la Théorie de la Détection du Signal. Intuitivement, chaque essai de l'expérience décrite ci-dessus consiste non pas en une tâche de détection, mais en deux détections successives (une pour chaque stimulus présentés) qui sont ensuite comparées l'une avec l'autre. De ce fait, le biais de réponse éventuel s’applique de la même façon aux deux stimuli, et ainsi se compense dans le choix de l’intervalle. Considérons à nouveau l'exemple de la personne réticente à répondre "j'ai entendu le ton" à moins d'être absolument certaine de sa réponse. Comme on l'a vu ses résultats dans un paradigme yes/no seront affectés par cette stratégie de réponse particulière. Dans un paradigme de choix forcé, en revanche, cette personne n'aura pas d'autre choix que de sélectionner le stimulus qui lui semble le plus vraisemblable, contrecarrant ainsi son aversion à donner des réponses incertaines.

En réalité, le choix forcé ne supprime pas tout risque de biais, mais déplace le problème sur une dimension moins critique. Il est en effet possible d'être biaisé en faveur d'un intervalle particulier, par exemple de répondre plus souvent "premier intervalle" que "deuxième intervalle". Néanmoins ce phénomène est moins critique pour l'interprétation des résultats que le biais du yes/no, car il affecte autant la détection des stimuli cibles que des stimuli non-cible.

Les termes "yes/no" et "choix forcé" se sont imposés suite à l'ouvrage fondateur de Green et Swets. Cette terminologie est néanmoins malheureuse car elle induit souvent les débutant·es (et parfois les scientifiques plus aguerri·es) en confusion. Ainsi un paradigme yes/no ne correspond **pas** à une tâche à laquelle on répond par oui ou par non, mais à un **type d'expérience où une seule des alternatives possibles est présentée à chaque essai**. De la même manière, le choix forcé ne correspond **pas** à une tâche avec un ensemble restreint de réponses possibles, mais à un **type d'expérience où toutes les alternatives possibles sont présentées à chaque essai**, la consigne consistant à sélectionner l'un des sons (réponses du type : "premier intervalle", "deuxième intervalle").

## Yes/no vs. choix forcé

La principale raison qui peut nous faire préférer le paradigme de choix forcé au yes/no durant la conception d'une expérience est donc l'importance pour nos conclusions des possibles effets de critères. Si la tâche envisagée invite particulièrement à donner une réponse plus souvent qu'une autre, ou s'il est important pour notre étude de contrôler précisément les biais des sujets, il est préférable d'opter pour le choix forcé.

Cette insensibilité au critère a cependant un prix : comparé au yes/no le choix forcé nécessite de présenter un stimulus supplémentaire par essai, et donc de rallonger la durée de l'expérience. Il n'est donc pas conseillé pour des protocoles déjà longs ou pour des participants ou participantes fatiguables.

Un autre aspect diffère entre les deux paradigmes : le niveau de difficulté est plus élevé pour le yes/no que le choix forcé. En effet, il serait théoriquement possible de réaliser la tâche en choix forcé en écoutant uniquement le premier intervalle et en omettant le second, ce qui correspondrait en réalité à l'expérience correspondante en yes/no. Lorsque l'on prête attention aux deux intervalles du choix forcé, on accumule donc plus d'information que dans le paradigme yes/no.

Pour l’audiométrie, le paradigme yes-no conduit à une sous-estimation des seuils d’audibilité tonale de ~2 dB par rapport au paradigme choix forcé.
(= dans l’audiogramme classique les individus sont biaisés, ils ont globalement tendance à sous-évaluer leur capacité à détecter les tons)

<br /> 

```{figure} YNvsFC.png
---
name: YNvsFC.png
alt: Comparaison yes/no vs Forced Choice
height: 400px
align: center
---
*.......*
```

<br /> 

<br /> 

```{figure} YNvsFC_2.png
---
name: YNvsFC_2.png
alt: Comparaison yes/no vs Forced Choice
height: 400px
align: center
---
*.......*
```

<br /> 

## Une mesure de performance commune : d'

Dans le paragraphe précédent, nous avons souligné que l'utilisation d'un paradigme ou d'un autre conduit à changer la difficulté de l'expérience, toutes choses égales par ailleurs. Ceci peut être un atout, par exemple pour rendre plus praticable une tâche difficile. Mais cette difficulté variable est également une contrainte du point de vue des scientifiques car elle complexifie la comparaison de résultats obtenus au moyen de paradigmes différents.

Heureusement, la théorie de la détection du signal permet ici de remettre tous les paradigmes sur une base commune.

## Différentes variantes du choix forcé 

L'expérience en choix forcé décrite plus haut comporte deux stimuli différents présentés dans deux intervalles successifs, la consigne consistant à en sélectionner un. On appelle donc ce paradigme **choix forcé à 2 intervalles et 2 alternatives** (2I-2AFC), souvent abrégé en 2AFC. Il est possible de réaliser la même tâche de détection en 3I-2AFC, auquel cas il s'agira de sélectionner le signal cible parmi trois intervalles successifs en ordre aléatoire. 

Comme tout choix forcé, le 3I-2AFC est insensible aux effets de critere. Son intérêt principal par rapport au 2I-2AFC réside en sa difficulté plus élevée. Ainsi une expérience qui paraît trop évidente aux participantes et participants avec deux intervalles peut devenir plus engageante avec trois intervalles ou plus. 

Une autre variante utile du choix forcé est sa combinaison avec la tâche de discrimination (souvent appelé**paradigme oddball**). Dans ce cas, trois intervalles sont présentés successivement dans un ordre aléatoire, l'un contenant un son différent des deux autres. La tâche consiste à les discriminer en indiquant quel intervalle contenait le son différent  (par exemple, un essai A-A-B a pour réponse correcte "troisième intervalle", un essai B-A-B "deuxième intervalle") [[notez la différence avec la détection en 3I-2AFC où le sujet sait par avance quel]]. Cet experience combine les avantages du choix forcé et de la discrimination : elle est indépendante du critère et implicite. Cependant elle est également plus longue.

## Exemples d’expériences pour la mesure du seuil de détection des modulation

