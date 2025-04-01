# Paradigme expérimental

## Qu'est-ce que le paradigme expérimental ?

Le **paradigme expérimental** est un paramètre de l'expérience moins intuitif que la tâche et la méthode, décrites précédemment. Il s'agit ici essentiellement de définir l'organisation des stimuli au sein d'un essai et le type de réponse attendu. Comme nous le verrons, ce choix a une influence sur la gamme de performances atteignables, et sur les potentiels biais de réponse des participants et participantes. Dans ce chapitre nous décrirons les deux paradigmes les plus courants: le yes/no et le choix forcé.

Nous nous limiterons ici au cas des réponses binaires, donc aux tâches de détection, catégorisation et discrimination.

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

Cette expérience constitue un bon exemple de **paradigme yes/no** : il s'agit pour le sujet de classer l'essai de façon binaire selon les deux catégories correspondant à la tâche ("présent/absent" pour une détection, "catégorie A"/"catégorie B" pour une catégorisation, "identique/différent" pour une discrimination). Le yes/no repose sur un seul stimulus par essai, sauf dans le cas de la tâche de discrimination qui nécessite deux stimuli.

Un problème se pose néanmoins : la mesure obtenue par paradigme yes/no est **dépendante du critère** (*criterion-dependent*), c’est-à-dire que le résultat peut être influencé par les biais de réponse de l'individu. Ainsi, une personne peu sûre d'elle (qui répond très facilement « non » lorsqu'elle n'est pas absolument certaine d'avoir perçu le ton) obtiendra des seuils d’audibilité globalement plus faible que la moyenne, indépendamment de ses capacités perceptives. Ceci signifie que notre mesure psychophysique est polluée par des caractéristiques psychologiques "haut-niveau" du sujet, telles que la confiance en soi, qui ne devraient pas entrer en compte pour un test perceptif. De même, dans une tâche de catégorisation entre les sons "bateau" et "bapeau", la première réponse pourrait être sélectionnée plus fréquemment simplement du fait qu'il s'agit d'un mot courant.

Un moyen d'obtenir une mesure **indépendante du critère** (*criterion-free*) est d'opter pour un paradigme du choix forcé.

## Le paradigme du choix forcé

Voici une seconde expérience permettant elle aussi de mesurer les seuils d'audibilité tonale : à chaque essai, deux stimuli successifs sont présentés dans un ordre aléatoire, l’un étant un ton cible l’autre un silence. Le sujet entend donc deux **intervalles** successifs, soit ton puis silence, soit silence puis ton. Le début de chaque intervalle peut être indiqué par une lumière ou un léger signal sonore. Après ces deux stimuli, la consigne donnée au sujet est de sélectionner l’intervalle contenant le ton : deux boutons de réponse sont disponibles pour indiquer si le ton de trouvait en première position ou en deuxième position. Puis, comme précédemment, on réduit l'intensité du ton et on entame un nouvel essai.

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

La démo suivante permet d'écouter cette expérience. Chacun des deux intervalles est indiqué par un bip aigu, suivi soit du ton cible soit du silence. 

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_2AFC.mp3" type="audio/wav">
</audio>

Cette expérience repose sur la même tâche et la même méthode que la précédente, en revanche le paradigme est différent : il s'agit d'un **choix forcé à deux intervalles** (ou, plus précisément, un "choix forcé à 2 intervalles et à deux alternatives", 2I2AFC).

Une propriété intéressante de ce paradigme, comparé au yes/no, est son insensibilité aux biais potentiels des participants et participantes. Ceci peut être démontré par la Théorie de la Détection du Signal. Intuitivement, chaque essai de l'expérience décrite ci-dessus consiste non pas en une tâche de détection, comme c'est le cas du yes/no, mais en deux détections successives (une pour chaque stimulus présenté) qui sont ensuite comparées l'une avec l'autre. De ce fait, les biais de réponse éventuels s’appliquent de la même façon aux deux stimuli, et ainsi se compensent dans le choix de l’intervalle. Considérons à nouveau l'exemple de la personne réticente à répondre "j'ai entendu le ton" à moins d'être absolument certaine de sa réponse. Comme on l'a vu ses résultats dans un paradigme yes/no seront affectés par cette stratégie de réponse particulière. Dans un paradigme de choix forcé, en revanche, cette personne n'aura pas d'autre choix que de sélectionner le stimulus qui lui semble le plus vraisemblable, contrecarrant ainsi son aversion à donner des réponses incertaines.

En réalité, le choix forcé ne supprime pas tout risque de biais, mais déplace le problème sur une dimension secondaire. Il est en effet possible que le sujet soit biaisé en faveur d'un intervalle particulier, répondant par exemple plus souvent "premier intervalle" que "deuxième intervalle". Néanmoins ce phénomène est moins critique pour l'interprétation des résultats que le biais du yes/no, car il affecte autant la détection des stimuli cibles que des stimuli non-cible.

Les termes "yes/no" et "choix forcé" se sont imposés suite à l'ouvrage fondateur de Green et Swets. Cette terminologie est néanmoins malheureuse car elle induit souvent les débutant·es (et parfois les scientifiques plus aguerri·es) en confusion. Ainsi un paradigme yes/no ne correspond **pas** à une tâche à laquelle on répond par oui ou par non, mais à un **type d'expérience où une seule des alternatives possibles est présentée à chaque essai**. De la même manière, le choix forcé ne correspond **pas** à une tâche avec un ensemble restreint de réponses possibles, mais à un **type d'expérience où toutes les alternatives possibles sont présentées à chaque essai**, la consigne consistant à sélectionner l'un des sons (réponses du type : "premier intervalle", "deuxième intervalle").

Voici un second exemple de choix forcé à deux intervalles, correspondant cette fois à la tâche de détection des modulations (voir [Méthode expérimentale](https://leovarnet.github.io/psychoac-manuel-fr/methodo/Methode.html)). Les deux stimuli étant clairement audibles, il n'est pas nécessaire ici de marquer le début des intervalles par un bip aigu. Les sujets doivent indiquer *lequel des deux sons était fluctuant*.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/demo_2AFC_AM.mp3" type="audio/wav">
</audio>

## Yes/no vs. choix forcé

La principale raison qui peut nous pousser à préférer le paradigme de choix forcé au yes/no lors de la conception d'une expérience est le risque d'effets de critères. Si la tâche envisagée invite particulièrement à donner une réponse plus souvent qu'une autre, ou s'il est important pour notre étude de contrôler précisément les biais des sujets, il est préférable d'opter pour le choix forcé.

Cette insensibilité au critère a cependant un prix : comparé au yes/no, le choix forcé nécessite de présenter un stimulus supplémentaire par essai, et donc de rallonger la durée de l'expérience. Il n'est donc pas conseillé pour des protocoles déjà longs ou pour des participants ou participantes fatiguables.

Un autre aspect diffère entre les deux paradigmes : le niveau de difficulté est plus élevé pour le yes/no que le choix forcé. En effet, il serait théoriquement possible de réaliser la tâche en choix forcé en écoutant uniquement le premier intervalle et en omettant le second, ce qui correspondrait en réalité à la même expérience en paradigme yes/no. Lorsque l'on prête attention aux deux intervalles du choix forcé, on accumule donc plus d'information que dans le paradigme yes/no. En conséquence, la tâche apparaît comme relativement plus facile.

## Une mesure de performance commune : d'

Dans le paragraphe précédent, nous avons souligné que l'utilisation d'un paradigme ou d'un autre affecte la difficulté de l'expérience, toutes choses égales par ailleurs. Ceci peut être un atout, par exemple pour rendre plus accessible une tâche difficile. Mais cette différence de difficulté est également une contrainte car elle complique la comparaison de résultats obtenus au moyen de paradigmes différents.

Fort heureusement, la théorie de la détection du signal permet ici de remettre tous les paradigmes sur une base commune. En effet, elle fournit une nouvelle mesure de performance appelée *d'*, qui, contrairement au pourcentage de réponses correctes, est indépendante du paradigme. Ce d' correspond en réalité à l'écart entre les deux gaussiennes que nous avions définies au chapitre [https://leovarnet.github.io/psychoac-manuel-fr/methodo/Stimuli.html](Stimuli et dimensions). 


```{figure} SDT1.png
---
name: SDT1.png
alt: Schéma de la Théorie de la détection du signal
height: 300px
align: center
---
*Schéma de de la Théorie de la détection du signal. Les courbes rouge et bleue représentent respectivement les probabilités de mesurer une valeur particulière d'énergie E pour le bruit seul ou pour le bruit+signal*
```

Dans cette figure, d' caractérise la superposition entre les deux courbes, c'est à dire la similarité entre les deux types d'essais, <span style="color:rgb(14,0,192)">**B**</span> ou <span style="color:rgb(255,0,0)">**B+T**</span>. Cette valeur caractérise donc les stimuli eux-même, indépendamment du type d'expérience dans lequel ces stimuli sont employés. Les formules permettant de calculer le d' mettent en jeu un certain nombre de paramètres qui dépassent le cadre de ce cours. Néanmoins, les lecteurs et lectrices intéressées pourront les trouver dans tous les manuels de théorie de la détection du signal.

## Différentes variantes du choix forcé 

L'expérience en choix forcé décrite plus haut comporte deux stimuli différents présentés dans deux intervalles successifs, la consigne consistant à en sélectionner un. On appelle donc ce paradigme **choix forcé à 2 intervalles et 2 alternatives** (2I-2AFC), souvent abrégé en 2AFC. Il est possible de réaliser la même tâche de détection en 3I-2AFC, auquel cas il s'agira de sélectionner le signal cible parmi trois intervalles successifs en ordre aléatoire. 

Comme tout choix forcé, le 3I-2AFC est insensible aux effets de critere. Son intérêt principal par rapport au 2I-2AFC réside en sa difficulté plus élevée. Ainsi une expérience qui paraît trop évidente aux participantes et participants avec deux intervalles peut devenir plus engageante avec trois intervalles ou plus. 

Une autre variante utile du choix forcé est sa combinaison avec la tâche de discrimination (souvent appelé **paradigme *oddball***). Dans ce cas, trois intervalles sont présentés successivement dans un ordre aléatoire, l'un contenant un son différent des deux autres. La tâche consiste à les discriminer en indiquant quel intervalle contenait le son différent  (par exemple, un essai A-A-B a pour réponse correcte "troisième intervalle", un essai B-A-B "deuxième intervalle"). Notez la différence avec la détection en 3I-2AFC où le sujet sait par avance quelle est la cible recherchée, tandis qu'il s'agit dans le *oddball* d'identifier un stimulus qui diffère des autres. Cet experience combine les avantages du choix forcé et de la discrimination : elle est indépendante du critère et implicite. Cependant elle est également plus longue puisqu'elle nécessite de diffuser 3 stimuli par essai.

A titre d'exemple, considérons à nouveau le cas de la reconnaissance de paysages sonores naturels. Au chapitre précédent nous avons vu qu'il était préférable de fonder notre approche sur une tâche de discrimination plutôt que de catégorisation, pour ne pas imposer de catégories d'environnement arbitraires. Cependant, comme on peut s'en rendre compte en écoutant la démo, un écueil possible est alors que **tous** les stimuli semblent provenir de lieux différents, ce qui remettrait en cause notre expérience :

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/Soundscape_2AFC.mp3" type="audio/wav">
</audio>

```{figure} Soundscape_discrimination.png
---
name: Soundscape_discrimination.png
alt: Soundscape_discrimination
width: 500px
align: center
---
*Expérience de reconnaissance de paysages sonores naturels avec une tâche de discrimination et un paradigme yes/no.*
```

En d'autres termes, la mesure est dépendante du critère et les sujets peuvent être biaisés en faveur de la réponse "différents lieux". Il est possible pour palier ce problème de changer de paradigme expérimental, en passant d'un yes/no à un choix forcé. L'expérience devient alors un paradigme *oddball* : à chaque essai 3 enregistrements sont présentés dans un ordre aléatoire, deux d'entre eux provenant d'un même lieu, et le troisième d'un lieu different. L'objectif des participants et participantes est d'indiquer lequel des trois sons provient d'un environnement différent des deux autres.

Voici une illustration des deux premiers essais de cette expérience, chacun composé de trois stimuli.

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/methodo/Soundscape_oddball.mp3" type="audio/wav">
</audio>

```{figure} Soundscape_oddball.png
---
name: Soundscape_oddball.png
alt: Soundscape_oddball
width: 500px
align: center
---
*Expérience de reconnaissance de paysages sonores naturels avec une tâche de discrimination et un paradigme de choix forcé (c'est à dire, paradigme *oddball*).*
```

Ce protocole expérimental a, comme le précédent, l'avantage d'être implicite (expliquer la tâche aux sujets ne nécessite pas de leur indiquer quels types de paysages sonores ont été enregistrés) mais il est de plus indépendant du critère. En effet, les sujets ne peuvent pas être biaisés et répondre plus ou moins fréquemment que les sons sont différents, puisqu'ils doivent nécessairement choisir à chaque essai un stimulus différent et deux stimuli identiques.

## Exemples d’expériences pour la mesure du seuil de détection des modulation

Récapitulons à présent les différentes combinaisons de paradigmes et de tâches que nous avons envisagées dans ce chapitre. Pour cela, nous nous appuierons sur un exemple abstrait comparant des sons "bleus" et des sons "orange". Ces deux couleurs peuvent correspondre par exemple à "bip" vs. "silence" dans le cas de l'audiogramme, à "ton modulé" vs. "ton non-modulé" dans le cas de la mesure des seuils de détection des modulations, ou encore à "savane" vs. "prairie" dans le cas de la perception des paysages sonores naturels.

| Exemple de déroulement d'un essai  | Instructions | Paradigme + tâche | Propriétés |
| :--------------- |:---------------|:-----|:-----|
| ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png) | bleu ou orange ? | Yes/no + détect. | |
| ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png)   ![bleu](https://upload.wikimedia.org/wikipedia/commons/6/62/Fairytale_kmix.png) | Sélectionnez le stimulus bleu | 2I2AFC + détect. | indépendant du critère |
| ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png)   ![bleu](https://upload.wikimedia.org/wikipedia/commons/6/62/Fairytale_kmix.png) | identiques ou différents ? |    Yes/no + discrim. | implicite  |
| ![bleu](https://upload.wikimedia.org/wikipedia/commons/6/62/Fairytale_kmix.png)   ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png)   ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png) | Sélectionnez le stimulus bleu | 3I2AFC + détect. | indép. du critère |
| ![bleu](https://upload.wikimedia.org/wikipedia/commons/6/62/Fairytale_kmix.png)   ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png)   ![orange](https://upload.wikimedia.org/wikipedia/commons/e/ea/Fairytale_arts.png) | Sélectionnez le stimulus différent | 3I2AFC + discrim. | implicite et indép. du critère |
