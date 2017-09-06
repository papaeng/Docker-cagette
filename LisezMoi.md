# Docker-cagette
Image Docker du logiciel Cagette ( http://www.cagette.net ) le logiciel libre du circuit court

### Présentation du logiciel
Bénévoles et coordinateurs, oubliez les feuilles Excel à envoyer par mail, les listes d'adhérents jamais à jour ! Cagette.net simplifie la vie des coordinateurs et des adhérents en fournissant des outils adaptés, spécialement conçus pour les AMAP et les groupements d'achat.

Testé sur le terrain depuis 2013, ce logiciel propose des outils concrets et utiles : gérer les adhésions et les commandes, planifier les livraisons, administrer la liste des produits et des producteurs... 
Ne perdez plus de temps avec de mauvais outils, et concentrez vous sur ce qui est vraiment important : Animer votre groupe et développer les circuits courts !

### Installation
* Télécharger le fichier zip
* Dézipper le fichier zip
* Aller dans le répertoire dézippé
* taper la commande "docker-compose up" 
* Attendez que les 2 containers docker se créent ( la base de données MariaDB et Cagette )
* Ouvrir votre navigateur préféré et saisir : http://adresseIPdelaMachineDocker
* Une page doit s'afficher la première fois avec la création de tables de cagette, aprés un rafraichissement de la page vous êtes sur la page d'accueil.
* Créer l'utilisateur admin par défaut en allant sur http://adresseIPdelaMachineDocker/install

Et voilà !

### A faire :
* Améliorer la documentation sur cette version Docker
* Export des volumes pour une sauvegarde de Cagette
* Utilisation de Swarm et mise en mode service ( mode cluster )
* Utilisation d'un certificat Letsencrypt (  avec 2 containers supplémentaire reverse-proxy et letsencrypt companion )

vos contributions......

### Comment contribuer ?
* En allant sur le forum de cagette : https://groups.google.com/forum/#!forum/cagette et en participant aux échanges ( tout seul on va plus vite mais ensemble on va plus loin )
* En participant à ce dépot pour améliorer/optimiser cette version de Cagette en Docker

### Remerciements
Nous remercions tyjak car nous nous basons sur sa création d'une version Docker de Cagette ( https://github.com/tyjak/docker_cagette )

Nous remercions l'équipe de cagette et sa documentation d'installation qui nous a permis de construire cette version Docker

Nous vous remercions pour l'utilisation de cette version en Docker et de vos retours
