

# Cahier de suivi du projet de Elise PUJOL

* Séance du 20 Décembre 2017 

Je suis en groupe avec Maugan SCIARRA.
Nous avons choisi de réaliser une sarbacane électronique. On aimerait utiliser l'air comprimé pour le lancement.
Créer un système de recharge automatique. Contrôler ainsi la sarbacane soit grâce à un joystick, soit avec le téléphone ou soit avec le pc.
Pendant cette séance, nous avons cherché sur internet des idées de comment le réaliser en regardant le fonctionnement de tout ce qu'on
avait besoin.
Nous avons décidé de nommer notre projet Arrow-matics.

* Séance du 12 Janvier 2018

On a testé la sarbacane. On a décidé de propulser la fléchette grâce à un compresseur à air.
On a testé le moteur pas à pas. On a essayé de changer le code pour le contrôler via le téléphone par bluetooth et pour qu'il puisse tourner dans un sens puis dans l'autre à notre demande. 

* Séance du 19 Janvier 2018

On a reçu le compresseur à air. On l'a testé et soudé aux fils de tel manière à utiliser une batterie car le PS280 ne délivrait pas assez de courant.
J'ai dessiné les pièces sur inventor pour en créer certaines aux Templiers et pour voir l'ensemble du projet. 
J'ai fais des recherches sur l'électrovannes pour comprendre comment ça fonctionne et comment l'utiliser avec l'arduino.
Nous avons ensuite réussi à faire fonctionner le moteur pas à pas lorsqu'on le demandait via le téléphone. Il tourne dans les deux sens.

* Séance du 23 Janvier 2018

On a fait la présentation du projet. On a fait ensuite le programme pour piloter le moteur responsable du rechargement. C'est à dire, faire en sorte qu'il tourne du bon angle, lorsqu'on le demande.

* Séance du 6 février 2018

On a soudé un module pour controler l'alimention du compresseur à air. On a réussi à coder ce module, de telle sorte à l'allumer et l'éteindre quand on le veut. 

* Séance du 22 février 2018

Nous avons quelques problèmes.. Nous n'avons pas assez de sorties sur l'arduino pour relier les 3 moteurs. Donc il va falloir réussir à faire communiquer mon arduino avec celui de Maugan. De plus, pour le rechargement, il faudra essayer de récupérer la postition initale de notre sarbacanne pour qu'elle puisse se mettre à la verticale droite.
Donc dans cette séance, on va essayer de résoudre ces problèmes.
J'ai essayé en vain de connecter les deux arduinos.

* Séance du 15 mars 2018

On a reçu le solénoïde. Seulement, on a remarqué qu'il n'avait pas assez de puissance pour pincer le tuyau où l'ai arrive. De ce fait, M Masson nous a passé un servo-moteur pour que quand il tourne, à l'aide d'un fil, il pousse le tuyan et arrive à le pincer pour couper l'arrivée d'air. Nous avons donc essayé de le faire fonctionner. Seulement, nous avons un problème de code. Il ne tourne pas en continu dans un seul sens. Mais, il fait des allers-retour aléatoire des deux côtés.

* Séance du 27 mars 2018

Première partie des présentations. 
Maugan et moi avons essayé de trouver un moyen pour fixer le tuyau de telle sorte que quand le servomoteur s'active, le tuyau se plie suffisament pour couper l'arriver d'air et augmenter la pression. Nous avons alors essayé avec un clou, et ceci fonctionne !!!!

* Séance du 4 avril 2018

Nous avons refais des tests pour que la pression soit plus forte car l'expérience avec le clou n'était pas satisfaisant. 

* Séance du 17 avril 2018

Nous avons essayé de relier la sarbacanne et le solénoïde. Les pièces ne collent pas entre elles.

* Séance du 2 mai 2018

Nous avons réussi à fabriquer la pièce qui permet de relier la sarbacanne au solénoïde. On ne comprenait pas pourquoi la pression n'était pas assez forte, pour propulser la fléchette. En effet, la fléchette n'était jetée avec aucune puissance. Nous avons compris après qu'il y avait une mauvaise isolation, donc on a mis du chatertone autour de la pièce. La fléchette est propulsée avec plus de puissance. M Masson nous a passé un autre arduino car on n'avait pas assez d'entrés/sorties pour relier tous nos moteurs.

* Séance du 7 mai 2018

Nous avons connecté nos moteurs et notre module bluetooth à notre nouvel arduino. On s'est rendu compte que lorsque on active le bluetooth, il n'y plus assez de tension pour les moteurs. Il nous faut donc un adapteur 5V pour les moteurs.

* Jusqu'au rendu

On s'est rendu compte que les moteurs n'étaient pas assez puissant pour soulever un poid assez lourd. On a dû s'arranger pour que le moteur faisant le mouvement à la verticale ne porte pas l'électrovanne donc on y a mis un tuyau. On a assemblé toutes les pièces ensemble. Le système de rechargement étant trop complexe, on a laissé tombé.
