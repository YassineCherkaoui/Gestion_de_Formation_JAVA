## Gestion de Formation

![gestion des employes](https://peoplespheres.fr/wp-content/uploads/2019/03/formation_0.png)

## Contexte du projet

Le processus de formation est initialisé lorsque le responsable formation reçoit une demande de formation de la part d’un employé. Afin d’envoyer plusieurs demandes de formation, l’employé doit s’authentifier, et il peut consulter un catalogue contenant plusieurs formations (il peut ne pas soumettre la demande). Il sélectionne une formation qui peut donner lieu à plusieurs sessions. Ces formations sont proposées par un organisme de formation. L’employé peut consulter l’état de ses demandes de formation en cours et éventuellement les annuler individuellement. Les demandes sont automatiquement enregistrées par le système et transmises au responsable de formation qui traite les demandes, et répond en les validant (réponse de type accord) ou les annulant (désaccord). En cas d’accord sur une session précise, le responsable recherche dans le catalogue des formations agréées un stage correspondant à la demande. Il informe l’employé du contenu de la formation et lui propose une liste des sessions. Lorsque l’employé retourne son choix, le responsable de formation inscrit le participant à la session auprès de l’organisme de formation concerné. Le responsable formation contrôle par la suite la facture que lui a adressée l’organisme de formation avant de la transmettre au comptable. En cas d’empêchement, l’employé doit informer le responsable de formation au plus tôt pour annuler l’inscription ou la demande. Le responsable de formation met à jour le catalogue de formations. Il peut introduire une nouvelle formation dans le catalogue, modifier une formation existante ou supprimer une formation qu’un organisme a abandonnée. Il peut également modifier les regroupements de formations qui ont été faits par thèmes. Il a aussi la possibilité de mettre à jour les dates et lieux des sessions.

# Gestion de Projet

Présentez un planning de la gestion du projet en spécifiant les tâches à faire, vous pouvez utiliser : Jira, Trello ou BinFire…

**Conception **

1/ Spécifier les exigences fonctionnelles par un diagramme de cas d’utilisation 2/ Proposer un diagramme de classes spécifiant la structure statique du système de gestion des formations 3/ Proposer un diagramme de séquences pour les cas d’utilisation

4/ Déterminer l’objet le plus dynamique dans le système, et proposer un diagramme d’états transition pour cet objet 5/ Proposer un diagramme d’activités globale du processus de formation

# Base de Données :

Créer une base de données MySQL (GestionFormations) qui contient 3 tables Formation, Session et Employé

# Application Desktop :

Réaliser une application desktop Java (Fx ou Swing) qui permet de : Faire une opération (CRUD) création, lecture, modification et suppression d’une formation (code, libellé, description) Faire une opération (CRUD) création, lecture, modification et suppression d’un employé (matricule, nom prénom, login, mot de passe, ville) Faire une opération (CRUD) création, lecture, modification et suppression d’une session (code, libellé, formation) Utiliser l’API Google Map pour afficher la localisation d’un employé selon sa ville lors de son authentification

# Application Web :

Créer 2 pages web dynamique responsive en utilisant la technologie Node.js (Back-End) pour afficher une formation avec la/les sessions correspondantes, simplifier l’affichage en utilisant Html et CSS L’utilisateur clique sur un bouton de l’application desktop pour afficher la formation demandée

## Modalités pédagogiques

Travail en Bnôme

Durée 7 jours à compter du 12/01/20

# Capture d'écran

![Login](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/login.PNG)
![homeUser](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/homeUser.PNG)
![HomeAdmin](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/HomeAdmin.PNG)
![register](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/register.PNG)
![ListeOfRequest](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/ListeOfRequest.PNG)
![NodeJs](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/NodeJs.png)
![Map](https://github.com/YassineCherkaoui/Gestion_de_Formation_JAVA/blob/master/ScreenShot/Map.png)

## COMMENT COURIR !!

```bash
    # how to run
Pour Exécuter ce Projet, vous devez suivre ces étapes :
Étape 1: installé nodejs sur votre PC: https://nodejs.org/en/download/ .
Étape 2: Extraire le fichier.
Étape 3: Ouvrez le dossier avec Nimporte quel IDE (VScode / notepad .....)
Étape 4: installez node-module avec cette commande << npm install --save >>.

```

Maintenant, les étapes suivantes comment connecter la base de données

```
Étape 5: installez Apache (Xampp / wamp).
Étape 6: Ouvrez un navigateur et accédez à l'URL "http://localhost/phpmyadmin/".
Étape 7: Ensuite, cliquez sur l'onglet bases de données.
Étape 8: Créez une base de données nommant "GestionFormations" puis cliquez sur l'onglet d'importation
Étape 9: Cliquez sur parcourir le fichier et sélectionnez le fichier "GestionFormations.sql qui se trouve dans le dossier
Étape 10: Cliquez sur aller.
```

La dernière étape

```

Étape 11: Ouvrez le Terminal et appuyez sur npm start

    ## Enjoy

```

```

```
