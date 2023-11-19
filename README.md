# Réalisation d'une salle immersive

## Introduction : 

Dans le cadre de ma formation à l’ENSG Géomatique, j’ai eu la chance de réaliser un stage à la HEIG-VD car cette école et plus spécifiquement son groupe Géomatique, aimerait avoir à sa disposition une salle immersive comme outil de visualisation 3D et m'a alors chargé de la réalisation de ce fabuleux projet. 

Une salle immersive, c’est une pièce où les participants sont immergés dans des environnements virtuels grâce à des écrans ou des projections. Utilisant la réalité virtuelle ou augmentée, ces salles offrent une expérience potentiellement interactive, qui ouvrent des possibilités diverses dans le divertissement, la formation et la simulation. Dans le cas de cette école, cette salle pourrait être montrée au grand public à l’occasion de portes-ouvertes et servirait plus généralement pour visualiser des données 3D appartenant aux projets d’enseignants, d’associés ou d’étudiants. 

Concernant ce stage, son but premier est la création d’un prototype fonctionnel d’une salle immersive en utilisant plusieurs vidéoprojecteurs (ensuite appelés projecteurs) et un moteur de jeu vidéo, dans une salle borgne dédiée pour l’occasion. Ce but donne alors lieu à différents critères, comme par exemple que les projections soient d’abord correctes, c’est-à-dire qui ne présentent pas de déformations ou au mieux, qui ne bloquent pas l’immersion. Un autre critère intuitif est que ces projections doivent se joindre et enfin, le dernier est que les utilisateurs pourront se déplacer en temps réel à l’intérieur de l'environnement virtuel projeté. 

Cependant, avec cette salle, nous allons utiliser nos projecteurs dans des configurations originales qui créent des déformations nuisant justement à l’immersion. Ainsi, un de nos grands objectifs va être de trouver un protocole qui pourrait corriger n’importe quelle projection. Cela nous aidera à nous affranchir du contexte spatial et augmentera nos possibilités dans les dispositions. De cette manière, la compréhension des fondamentaux de la projection devient obligatoire et représentera alors notre première grande partie.

Dans notre sillage, il a aussi été de mise d’étudier les différents outils disponibles parmi les moteurs de jeu vidéo existants pour déterminer celui qui sied le plus à notre besoin. Ce qui nous donne la deuxième partie de ce rapport qui présente ainsi notre choix : Unreal Engine et en même temps, qui nous fait voir ce que permet un moteur de jeu vidéo sur les projections, notamment concernant les deux objectifs de correction ou de recouvrement des projections.

Finalement, avec toutes ces connaissances, nous pourrons alors passer à la troisième et dernière partie où nous essayerons de créer une configuration qui remplit ces objectifs et nous verrons si nous avons réussi à accomplir notre but.  

Lors de ce rapport, nous allons suivre ce genre de configuration qui servira d’exemple de configuration originale, un exemple qui s’inscrit comme cela dans un repère terrain que nous allons garder tout au long de ce rapport : 
<img width="650" alt="image" src="https://github.com/Matheoia/Salle-immersive/assets/121936719/ba721a59-e57e-42aa-a553-115e5ec9492c">

## Quelques photos et captures d'écran : 

<img width="650" alt="image" src="https://github.com/Matheoia/Salle-immersive/assets/121936719/f9154a12-c747-4430-b823-a8a5733f2e77">

<img width="650" alt="image" src="https://github.com/Matheoia/Salle-immersive/assets/121936719/d11e6852-e27c-427f-a522-c55db109b8a5">

<img width="650" alt="image" src="https://github.com/Matheoia/Salle-immersive/assets/121936719/54ca791d-7bfe-4836-b6a0-09dfa23bb049">




