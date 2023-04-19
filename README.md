# Projet sur les marées
LEGRAND Joachim <br>
BACCAR Skander <br>

## Problématique : 
Comment prédire une marée à un endroit donné ? 

## Introduction :
Pour la projet d'ARE dynamic nous avons choisi de mener notre projet de modélisation sur sujet que nous avons nous-même choisi. Notre projet porte sur les marées plus exactement sur la prédiction des marées. 

## La formation et les types de marées :
Les marées sont formées grâce à l'attraction de la Lune et du Soleil sur la Terre mais la force de cette attraction varie en focntion de la postion de la Lune ainsi que celle du Soleil. Cette attraction est un des facteurs provoquant les marées mais il y'en a également d'autre tel que le cycle lunaire qui agit sur la formation des marées. 
À partir de cela on retrouve différents types de marées telles que les marées de vives-eaux ainsi que les marées de mortes-eaux mais également les marées de type diurne et de type semi-diurne : 
- Vives-eaux : lorsque le Soleil, la Lune et la Terre sont alignés -> période de nouvelle Lune et de pleine Lune.
- Mortes-eaux : lorsque l'alignement entre la Terre, le Soleil et la Lune forme un angle droit -> premier et dernier quartier de la Lune. 
- Une pleine mer (marée haute) et une basse mer (marée basse) par jour -> marée de type diurne.
- Deux pleines mers et deux basses mers par jour -> marée de type semi-diurne.

## Paramètres pris en compte :
Pour notre modélisation nous avons pris en compte 2 paramètres qui vont essayer de nous permettre de prédire une marée à un endroit donné : 
- Le cycle lunaire car en effet la Lune ( si c'est la pleine Lune ou si c'est le premier quartier) est un facteur important à prendre compte si l'on veut prédire une marée.
- Le calendrier des marées car les marées sont de cycles périodiques et donc si l'on possède le calendirer des marées alors cela nous aideras à prédire la marée.
-Schéma de l'idée du graphique après prédiction : 
![Schéma de l'idée du graphique après prédiction](https://github.com/are-dynamic-2023-g004/Projetmarees.github.io/blob/main/IMG_0019.jpg)
- Dans ce schéma representant la prédiction de la marée un jour donnée, on a 2 informations qui sont la hauteur de la marée sur l'axe des y et l'heure correspondant à chaque hauteur sur l'axe des x ce qui nous permet donc de savoir quans est-ce que aura lieu la basse mer ou la haute mer mais également la hauteur de celle-ci.

## Représentation graphique: 
La représentation graphique pour la prédiction de la marée a été faite à partir d'un code python qui à la fin donne un graphique dans lequel nous retrouvons les informations les plus importantes qui sont la hauteur de la marée en fonction de l'heure ce qui nous permet de savoir quel type de marée il s'agit mais également à quel moment elle va avoir lieu.

![Graphique prédiction marée](https://github.com/are-dynamic-2023-g004/Projetmarees.github.io/commit/70318de3ddfd9b95628dc927cbc5069e41305f54)





