# Cahier de suivi du projet de Maugan SCIARRA

* Séance du 20 Décembre 2017 

Je me suis mit en collaboration avec Elise PUJOL
Nous avons choisit de faire une sarbacane automatique avec une compression de l'air pour le lancement, et un système de rechargement.
Celle-ci pourat être controller à distance.
Nous avons ensuite fait des recherche sur ce qui existe déjà pour nous donné une première idée de notre projet.
Celui-ci ce nommera normalement Arrow-matics.


* Séance du 12 Janvier 2018

Nous avons essayer de faire fonctionner un moteur pas à pas a et de contrôler le moteur avec notre téléphone par connexion bluethooth. pour l'instant on arrive a le faire démarrer ou s'arreter mais on voudrais arriver a le faire tourner dans un sens tant que on reste appuyer sur un bouton et de même dans l'autre sens

* Séance du 19 Janvier 2018

Nous avons reussit à faire fonctionner le moteur et a integres un programme permettant de contrôler la rotation tant que nous restont appuyer sur un bouton sur notre téléphone. L'information est bien transmise par bluetooth.
Nous avons reçu le compresseur, nous avons changer le cable d'allimentation pour pouvoir le brancher sur une batterie.
Après test cela fonctionne si on bloque l'arriver d'air pour augmenter la pression.

* Séance du 23 Janvier 2018

Présentation du projet version diapo. Par la suite nous avons programmer une rotation de 60° du moteur par pression de bouton sur le teléhone en prévision du système de rechargement

* Séance du 6 Fevrier 2018

Nous avons souder le compresseur a air a un module permettant de controler l'alimentation sur l'arduino puis nous avons programmer le fait de pouvoir allumer ou eteindre le compresseur par bluetooth.
On c'est rendu compte de plusieurs problème : Nous n'avons pas assez de sortie sur un arduino pour tout relier et en ce qui concerne le rechargement il faut pouvoir récuperer l'angle du moteur ce qui peut poser problème avec un moteur PaP.

* Séance du 22 Fevrier 2018

J'ai essayer de faire un programme qui recuper l'angle du moteur PaP pour Pour crée un stade de départ et un stade final et avoir un angle variant entre 0 et 90 degrès. De plus il faudrait reussir a réinitialliser la position pour recharger soit à remettre l'angle à 90 degrès.
Cela fonctionne a peu près mais des améliorations restes a faire.

* Séance du 15 mars 2018

Plusieurs essayer pour essayer de couper la pression puis la relacher. Le solénoide est pas assez puissant peut etre faudrait t'il bloquer le tuyau et pousser des 2 coter ? ou alors nous envisageon l'utilisation d'un moteur pas à pas pour pouvoir tordre le tuyau mais à ce stade nous avons des problème pour faire fonctionner le moteur comme il faut

* Séance du 28 mars 2018

Nous avons mis au point le bon code et cela semble fonctionner, le tuyau ce bloque bien et l'air mais l'air ce relache trop lentement on essaye de trouver une solution pour faire ce relachement plus vire.

* Séance du 4 avril 2018

Nous en sommes toujours au meme point, la pression n'est pas assez forte, nous avons effectuer nos dernières tentative avec ce systeme mais nous devons abandonné cette solution et en trouver une autre

* Séance du 17 avril 2018

Nous avons enfin reçu l'electrovanne, j'essaie de faire le code pour l'alimenter correctement pendant que Elise regarde comment connecter le compresseur à celle-ci mais cela semble complexe et aucun magasin ne propose la pièce adapter

* Séance du 2 mai 2018

Enfin, nous avons la toute les pieces pour connecter la sarbacanne à l'electrovanne et au compresseur. LEs premier test ne sont pas concluant mais après mise en place de chatertonne pour bloquer toutes les potentielles perte d'air cela fonctionne ! La flechette est bien expulsé à une dizaine de mètres.

* Séance du 7 mai 2018

Sur le nouvel arduino nous connectons tous notre systeme mais lorsque les 3 moteur et le bluetooth fonctionnent en même temps on a une chute de tension qui stop le bluetooth. Nous devons alors alimenter les moteur par un autre moyen.

-------------------
* Travail jusqu'au rendu :

Les moteurs ne sont pas assez puissant pour faire bouger l'ensemble du systeme. On a donc mit un tuyau entre l'electrovanne et la sarbacanne. Il n'y a pas de grande pertes de pression donc cela semble fonctionné. Le barillet à était imprimé et on essaye de connecter les différent moteur a toutes les parties de notre sarbacanne
