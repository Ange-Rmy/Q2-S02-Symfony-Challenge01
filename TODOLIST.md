********************* TO DO LIST *********************


5 - CRUD sur USER
        php bin/console make:crud
            User
            UserController
            no
    
    Envoi des documents sur GitHub via le terminal
    
INFO DE GILLES
    1ère difficulté :
        La route /user/new/ envoie un message d'erreur : le champs roles a besoin d'un traitement spécifique et doit proposer de choisir 1 ou plusieurs rôles parmi une liste de choix.

    2ème difficulté :
        L'encodage du password doit être effectué. il faut s'inspirer de l'existant dans RegistrationController et reproduire le code dans la fonction new() de UserController attention d'importer toutes les classes nécessaires dans ce fichier, et de rajouter les paramètres dans new()


************************* DONE *************************

1 - Création projet Symfony
    Dans GitHub:
        Création d'un Référentiel

    Dans le terminal :
        symfony new tenth_june_first_challenge --webapp
        cd tenth_june_first_challenge
    
    Envoi des documents sur GitHub via le terminal

    Lancement du projet
        symfony server:start


2 - Mettre en place class USER + Mettre login et e-mail
        php bin/console make:user
        php bin/console make:migration
        php bin/console doctrine:migrations:migrate
        php bin/console make:entity
            email
        php bin/console make:migration
        php bin/console doctrine:migrations:migrate

    Envoi des documents sur GitHub via le terminal


BONUS 1 - Connexion USER
        php bin/console make:auth
            1
            AppCustomAuthenticator
            SecurityController
            yes

    Envoi des documents sur GitHub via le terminal


BONUS 2 - Inscription USER
        php bin/console make:registration-form
            yes
            ni
            yes

    Envoi des documents sur GitHub via le terminal



