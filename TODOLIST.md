********************* TO DO LIST *********************

BONUS 1 - Connexion USER
        php bin/console make:auth

BONUS 2 - Inscription USER
        php bin/console make:registration-form

5 - CRUD sur USER
        php bin/console make:crud



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

    


