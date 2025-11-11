
```{warning}
Page en cours de construction
```

# Introduction

Les attributs auditifs forment les fondations de l'édifice perceptif, sur lesquelles reposent de nombreux étages de complexité croissante. Après avoir considéré comment nous percevons des caractéristiques sonores simples, comme la hauteur d'un ton pur, il est temps de nous tourner vers des sons plus naturels et plus communs. Dans ce chapitre, nous nous intéresserons à un type de stimuli sonore extrêmement utile pour les êtres humains : les sons de parole. Nous verrons en particulier comment les phonèmes, unités de base du langage oral, sont décodés par le cerveau.  

## La parole est un code 

**La communication parlée est un moyen de télécommunication comme un autre** : la personne qui parle transmet certaines informations à son interlocuteur ou interlocutrice, située le plus souvent à une distance d'un mètre environ. Il s'agit donc bien de "communication à distance" (télé-communication), même si le chemin parcouru par l'information est beaucoup plus court que dans le cas de la transmission téléphonique ou du système morse.

Quelque soit le système de télécommunication considéré, la situation peut être schématisée de la façon suivante (voir figure xxx) : un émetteur ou une émettrice souhaite transmettre un message à un·e destinataire. Pour couvrir la distance qui les sépare il est nécessaire de prendre appui sur un certain medium, c'est à dire un substrat physique qui porte le message, comme les ondes électromagnétiques dans le cas du code morse. Le message ne pouvant être converti directement en ondes électromagnétiques, il faut au préalable le coder dans un format plus adéquat et plus robuste, ici une série de traits et de points. Ce code est ensuite envoyé par l'émetteur·ice, puis réceptionné par le ou la destinataire qui devra le décoder pour revenir au message original. Cette formalisation est au centre de la **théorie de l'information**, cadre mathématique qui permet d'évaluer l'efficacité d'un code particulier et de déterminer le code le mieux adapté, en particulier dans le cas où la transmission est dégradée par des interférences.

```{figure} Shannon1.jpg
---
name: Shannon1.jpg
alt: XXXXX
width: 70%
align: center
---
*Schéma du principe de la télécommunication, ici pour la transmission morse.*
```

Cette conceptualisation de la télécommunication comme une opération de codage / transmission bruitée / décodage est également tout à fait valide dans le cas de la communication parlée. Les deux interlocuteur·ices qui se font face doivent ici, pour transmettre le message formé dans leur esprit, le convertir sous une forme pouvant être véhiculée dans l'air. **Cette forme est le son de parole, une organisation particulière des vibrations de l'air qui forme un code permettant de transporter une infinité de messages différents**. Comme nous le verrons plus loin, ce code est particulièrement robuste aux interférences, comme la présence d'un bruit de fond si la conversation n'a pas lieu dans un environnement parfaitement silencieux. 

```{figure} Shannon2.jpg
---
name: Shannon2.jpg
alt: XXXXX
width: 70%
align: center
---
*Même schéma que précédemment, dans le cas de la communication parlée. La seule différence est le medium (ici les vibrations de l'air) et le code utilisé.*
```

## Une double articulation : phrases, mots, phonèmes 

Le code de la parole fonctionne sur la base de petites unités sonores combinées pour former d'autres unités plus grandes. En effet, une personne peut connaître 60 000 mots mais elle ne peut pas produire 60 000 sons différents discriminables par l'oreille humaine. Le son de parole se compose donc d'un petit nombre de briques sonores élémentaires, dont l'agencement selon un ordre particulier permet de transmettre un message spécifique. Autrement dit, **le langage est un système combinatoire**. C'est la raison pour laquelle, selon l'aphorisme de Wilhelm von Humboldt, le langage se caractérise par *"l'usage infini de moyens finis"*.

Cette combinatoire s'organise sur plusieurs niveaux. **Les phrases sont composées de mots**, petites unités de sens dont l'agencement spécifique implique un sens particulier de la phrase (ainsi, "le chat a mangé la souris" est clairement différent de "la souris a mangé le chat" même si les deux sont formées à partir des mêmes mots). À leur tour, **les mots sont composés de phonèmes**, comme dans le cas de "souris" la succession des sons élémentaires "s", "ou", "r" et "i" (/s/, /u/, /r/ et /i/ en notation phonétique) dans cet ordre précis.

La combinatoire du langage parlé se déploie donc sur deux niveaux (phrase-mots, mots-phonèmes), c'est-à-dire qu'elle fonctionne selon une **double articulation**, ce qui lui permet de former un code robuste basé sur un dictionnaire relativement réduit [Il existe en réalité une troisième articulation qui est souvent omise par soucis de simplicité. En effet, les mots sont parfois composés de morphèmes, des portions de mots qui leurs donnent leur sens exact, comme "mangé" formé à partir du morphème "mang" suivi du suffixe "é", ce qui indique qu'il s'agit du passé simple du verbe manger]. Imaginez par exemple un langage où les phrases "le chat a mangé la souris" et "la souris a mangé le chat" se traduiraient par des séries de sons complètement différentes : ce code ne serait pas efficace et demanderait de garder en mémoire un nombre disproportionné d'associations entre son et sens. Au contraire, le langage parlé s'appuie sur un nombre très réduit de phonèmes différents pour exprimer une infinité d'idées.

> _the marvellous invention of composing out of 25 or 30 sounds that_  
_infinite variety of words, which tho' they have no natural_  
_resemblance to the operations of the mind, are yet the means of unfolding all its secrets, and of disclosing unto those, who cannot see into our hearts, the variety of our thoughts, and our sentiments upon all_  
_manner of subjects. Words therefore may be defined, distinct and articulate sounds, made use of by men as signs, to express their thoughts. (Arnauld and Lancelot, Grammaire de Port-Royal: 22)_  

Dans ce qui suit nous nous concentrerons sur l'étage le plus bas de cette hiérarchie, le phonème. Notons d'ores et déjà que, contrairement aux mots qui pris isolement ont une signification, les phonèmes ne contribuent pas à la compréhension de l'ensemble en apportant des "portions de sens". La signification du mot "souris" ne peut être déduite du sens de "s", "ou", "r" et "i" pris individuellement et de leur ordre.

xxx représentation d'un son de parole ?

## Craquer le code de la parole 

Le son de parole est donc un code complexe formé de plusieurs unités linguistiques emboîtées : pour être compris, le son doit être décodé en une série de phonèmes, qui seront ensuite assemblés en mots, pour former des phrases et reconstituer au sens du discours. Les psycholinguistes qui s'intéressent à la transformation du son en sens doivent donc en premier lieu se pencher sur la première étape du décodage : l'identification des phonèmes. Il s'agit ainsi de « craquer » le code de la parole, c'est-à-dire **d'identifier les indices acoustiques qui permettent au système auditif de différencier un phonème d'un autre**.

Comme au chapitre précédent, l'objectif est donc de mettre en évidence la relation entre le son (de parole) et les représentations mentales que celui-ci évoque dans notre esprit (ici des représentations linguistiques, les phonèmes). Par exemple, pourquoi tel son est-il perçu comme un "b" et tel autre comme un "d" ? Soulignons que le phonème est bien un objet cognitif, et non physique. Il n'est pas contenu dans le son même mais seulement dans l'esprit des locuteurs et locutrices de la langue.

```{figure} PhysiqueVSCognitif.jpg
---
name: PhysiqueVSCognitif.jpg
alt: XXXXX
width: 70%
align: center
---
*XXX.*
```

Objectifs
Présenter les problématiques de la phonétique expérimentale
Mettre en application les méthodes expérimentales vues au cours 1
Notions plus générales :
	- Indices acoustiques
	- Perception catégorielle
	- Combinaison d’indices

## La parole est elle vraiment un code ?

Avant d'explorer plus avant le fonctionnement du code acoustico-phonetique à la base de la communication parlée, prenons le temps de balayer plusieurs confusions pouvant être induites par la métaphore du code.

Tout d'abord, les termes de "code", "message", "information" ou encore "communication" pourraient laisser penser que la finalité première du langage est de permettre la transmission d'informations entre deux individus. C'est parfois le cas, si par exemple vous me demandez mon numéro de téléphone et que je vous réponds. Mais nombre d'interactions n'ont pas véritablement de contenu informationnel, comme la question "Salut, ça va ?" qui n'attend le plus souvent pas de réponse.

> l’idée voulant que le langage ait pour fonction la communication est effectivement acceptée comme un dogme. […]  
En résumé, ce dogme ne repose sur aucun fondement, et des données assez probantes permettent désormais de penser qu’il est carrément faux. Le langage est certes parfois employé pour la communication, tout comme le sont les styles de vêtements, l’expression du visage, la posture et bien d’autres choses." ([[Chomsky, quelle sorte de créature sommes-nous?]])  
