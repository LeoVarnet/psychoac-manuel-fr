
```{warning}
Page en cours de construction
```

# Introduction

Les attributs auditifs forment les fondations de l'édifice perceptif, sur lesquelles reposent de nombreux étages de complexité croissante. Après avoir considéré comment nous percevons des caractéristiques sonores simples, comme la hauteur d'un ton pur, il est temps de nous tourner vers des sons plus naturels et plus communs. Dans ce chapitre, nous nous intéresserons à un type de stimuli extrêmement utiles pour les êtres humains : les sons de parole. Nous verrons en particulier comment les phonèmes, unités de base du langage oral, sont décodés par le cerveau.  

## La parole est un code 

**La communication parlée est un moyen de télécommunication comme un autre** : la personne qui parle transmet certaines informations à son interlocuteur ou interlocutrice, située le plus souvent à une distance d'un mètre environ. Il s'agit donc bien de "communication à distance" (télé-communication), même si le chemin parcouru par l'information est beaucoup plus court que dans le cas de la transmission téléphonique ou de la communication morse par exemple.

Quelque soit le système de télécommunication considéré, la situation peut être schématisée de la façon suivante (voir {numref}`Shannon1.jpg`) : un émetteur ou une émettrice souhaite transmettre un message à un·e destinataire. Pour couvrir la distance qui les sépare il est nécessaire de prendre appui sur un certain medium, c'est à dire un substrat physique qui porte le message, comme les ondes électromagnétiques dans le cas du code morse. Le message ne pouvant être exprimé directement en ondes électromagnétiques, il est nécessaire au préalable le coder dans un format plus adéquat, ici une série de traits et de points. Ce code est ensuite envoyé par l'émetteur·ice, puis réceptionné par le ou la destinataire qui devra le décoder pour revenir au message original. Cette formalisation est au centre de la **théorie de l'information**, cadre mathématique qui permet d'évaluer l'efficacité d'un code particulier et de déterminer le code le mieux adapté, en particulier dans le cas où la transmission est dégradée par des interférences.

```{figure} Shannon1.jpg
---
name: Shannon1.jpg
alt: XXXXX
width: 90%
align: center
---
*Schéma du principe de la télécommunication, ici pour la transmission morse.*
```

Cette conceptualisation de la télécommunication comme une opération de codage / transmission bruitée / décodage est également tout à fait valide dans le cas de la communication parlée ({numref}`Shannon1.jpg`). Les deux interlocuteur·ices qui se font face doivent ici, pour transmettre le message formé dans leur esprit, le convertir sous une forme pouvant être véhiculée dans l'air. **Cette forme est le son de parole, une organisation particulière des vibrations de l'air qui forme un code permettant de transporter une infinité de messages différents**. Comme nous le verrons plus loin, ce code est particulièrement robuste aux interférences, comme la présence d'un bruit de fond si la conversation n'a pas lieu dans un environnement parfaitement silencieux. 

```{figure} Shannon2.jpg
---
name: Shannon2.jpg
alt: XXXXX
width: 90%
align: center
---
*Même schéma que précédemment, dans le cas de la communication parlée. La seule différence est le medium (ici les vibrations de l'air) et le code utilisé.*
```

## Une double articulation : phrases, mots, phonèmes 

Le code de la parole fonctionne sur la base de petites unités sonores combinées pour former d'autres unités plus grandes. En effet, une personne peut connaître 60 000 mots mais elle ne peut pas produire 60 000 sons différents discriminables par l'oreille humaine. Le son de parole se compose donc d'un petit nombre de briques sonores élémentaires, dont l'agencement selon un ordre particulier permet de transmettre un message spécifique. Autrement dit, **le langage est un système combinatoire**. C'est la raison pour laquelle, selon l'aphorisme de Wilhelm von Humboldt, le langage se caractérise par *"l'usage infini de moyens finis"*.

Cette combinatoire s'organise sur plusieurs niveaux. **Les phrases sont composées de mots**, petites unités de sens dont l'agencement spécifique implique un sens particulier de la phrase (ainsi, "le chat a mangé la souris" est clairement différent de "la souris a mangé le chat" même si les deux sont formées à partir des mêmes mots). À leur tour, **les mots sont composés de phonèmes**, comme dans le cas de "souris" la succession des sons élémentaires "s", "ou", "r" et "i" (/s/, /u/, /r/ et /i/ en notation phonétique) dans cet ordre précis.

La combinatoire du langage parlé se déploie donc sur deux niveaux (phrase-mots, mots-phonèmes), c'est-à-dire qu'elle fonctionne selon une **double articulation**, ce qui lui permet de former un code robuste basé sur un dictionnaire de sons relativement réduit [[1](note1introPhon)]. Imaginez par exemple un langage où les phrases "le chat a mangé la souris" et "la souris a mangé le chat" se traduiraient par des séries de sons complètement différentes : ce code ne serait pas efficace et demanderait de garder en mémoire un nombre disproportionné d'associations entre son et sens. Au contraire, le langage parlé s'appuie sur un nombre très restreint de phonèmes différents pour exprimer une infinité d'idées.

> Cette invention merveilleuse de composer de vingt-cinq ou trente sons cette infinie variété de mots [et de phrases], qui, n'ayant rien de semblable en eux-mêmes à ce qui se passe dans notre esprit, ne laissent pas d'en découvrir aux autres tout le secret, et de faire entendre à ceux qui n'y peuvent pénétrer, tout ce que nous concevons, et tous les divers mouvemens de notre âme. *(Arnauld et Lancelot, Grammaire de Port-Royal, 1660)*  

## Craquer le code de la parole 

Le son de parole est donc un code formé par combinaison de petits sons élémentaires, les phonèmes, qui composent des unités linguistiques plus grandes. Pour être compris, le son doit tout d'abord être décodé en une série de phonèmes, qui seront ensuite assemblés en mots, pour former des phrases et reconstituer le sens du discours. Par exemple, pour comprendre l'extrait ci-dessous (dont le spectrogramme est représenté en {numref}`VoixHumaineSpectro.bmp`), il est nécessaire d'en extraire la succession de phonèmes "ménɔ̃sépaldoktœrʃmidt" [[2](note2introPhon)] avant de pouvoir identifier les mots "mais", "non", "c'", "est", "pas", "l'", "docteur" et "Schmidt" pour ensuite reconstruire le sens de la phrase. 

<audio controls>
  <source src="https://github.com/LeoVarnet/psychoac-manuel-fr/raw/refs/heads/main/lecture/phonetique_experimentale/LaVoixHumaine_ex2.wav" type="audio/wav">
</audio>

```{figure} VoixHumaineSpectro.bmp
---
name: VoixHumaineSpectro.bmp
alt: XXXXX
width: 100%
align: center
---
*Spectrogramme d'un son de parole extrait de *La Voix Humaine* de Cocteau, dans lequel Simone Signoret prononce la phrase "Mais non, c'est pas l'docteur Schmidt". Lorsque nous écoutons cet enregistrement, notre cerveau le décode en une succession de phonèmes comme indiqué au-dessus. Chacun de ces phonèmes correspond visuellement à un segment relativement bien délimité du son. *
```

Le système auditif humain est ainsi capable de réaliser une "conversion acoustique-phonétique", et c'est à cette première étape de décodage de la parole que nous nous intéresserons dans ce chapitre 4. Il s'agit en quelque sorte de "craquer" le code de la parole, c'est-à-dire **d'identifier les indices acoustiques qui permettent au système auditif de différencier un phonème d'un autre**. 

Comme dans le cas de la psychoacoustique (chapitre 3), et plus généralement de la psychophysique (chapitre 1), l'objectif est donc de mettre en évidence la relation entre le stimulus (le son de parole) et les représentations mentales que celui-ci évoque dans notre esprit (ici des représentations linguistiques, les phonèmes). Par exemple, pourquoi tel son est-il perçu comme un "b" et tel autre comme un "d" ? Soulignons que le phonème est bien un objet cognitif, et non physique. Il n'est pas contenu dans le son même mais seulement dans l'esprit des locuteurs et locutrices de la langue.

## La parole est elle vraiment un code ?

Avant d'explorer plus avant le fonctionnement du code acoustico-phonetique à la base de la communication parlée, prenons le temps de balayer plusieurs confusions pouvant être induites par la métaphore du code.

Tout d'abord, les termes de "code", "message", "information" ou encore "communication" pourraient laisser penser que la finalité première du langage est de permettre la transmission d'informations entre deux individus. C'est parfois le cas, si par exemple je vous indique mon numéro de téléphone. Mais nombre d'interactions langagières n'ont pas véritablement de contenu informationnel, comme la question "Salut, ça va ?" qui n'attend le plus souvent pas de réponse. 

> Il est faux de penser que l'usage du langage humain se caractérise par la volonté ou le fait d'apporter de l'information. Le langage humain peut être utilisé pour informer ou pour tromper, pour clarifier ses propres pensées, pour prouver son habileté ou tout simplement pour jouer. *(Noam Chomsky, Le langage et la pensée, 1967)*

Du point de vue du "code" de la communication parlée, les termes de "message" et d' "information" désignent donc toute pensée que le locuteur ou la locutrice désire transmettre, sans prendre en compte sa pertinence. De ce point de vue, même "bla bla bla" est un message linguistique valable.

Une seconde confusion possible serait de penser que l'opération de décodage consiste uniquement à identifier les symboles sonores prononcés et à leur faire correspondre leur sens, stocké dans un grand dictionnaire mental. C'est effectivement le principe de nombreux codes, comme le code morse qui nécessite uniquement une table de correspondance alphabétique pour être compris par des néophytes, en revanche le compréhension de la parole est plus complexe. Comme nous le verrons par la suite, elle repose également sur des **inférences**. Imaginez par exemple que, lors d'une soirée si bruyante qu'il est difficile de s'entendre, votre partenaire vous regarde et vous fait un signe en pointant sa montre imaginaire. Dans cette interaction minimale le code se limite au signe signifiant "montre" ou "heure". Mais un certain nombre d'inférences vous permettent de déduire que le message sous-jacent n'est pas "est-ce que tu aurais l'heure ?" ou "j'ai perdu ma montre, est-ce que tu l'as vue quelque part ?" mais "on avait dit qu'on ne rentrerait pas plus tard que minuit, il est l'heure d'y aller". Le même genre de processus est à l'œuvre en continu dans la compréhension de la parole.

> Il est est vrai que le langage est un code qui associe des représentations phonétiques et des représentations sémantiques des phrases. Cependant, un fossé sépare la représentation sémantique d'une phrase et la pensée veritablement communiquée. Ce fossé est franchi non au moyen d'un code supplémentaire mais grâce à des inférences. *(Sperber & Wilson, Relevance, 1986)*

Comme nous le verrons, des inférences sont même à l'œuvre dès le niveau des phonèmes. Mais pour bien le comprendre il faut d'abord définir plus précisément la notion de "phonèmes".

## Notes

(note1introPhon)=

[1] Il existe en réalité une troisième articulation, qui est souvent omise par soucis de simplicité. En effet, les mots sont parfois composés de morphèmes, des portions de mots qui leurs donnent leur sens exact, comme "incassable" formé à partir du morphème "cass", précédé du préfixe "in-" et suivi du suffixe "able", ce qui indique qu'il s'agit d'un adjectif relatif à l'impossibilité de l'action de casser.

(note2introPhon)=

[2] En notation phonétique "simplifiée" pour faciliter la compréhension.

## Références

- Arnauld, A., & Lancelot, C. (1660). Grammaire générale et raisonnée de Port-Royal. P. Le Petit. http://archive.org/details/grammairegnr00arnauoft
- Chomsky, N. (1967). Language and Mind. Harcourt Brace. https://doi.org/10.1017/CBO9780511791222
- Sperber, D., & Wilson, D. (1986). Relevance : Communication and Cognition. Harvard University Press.

