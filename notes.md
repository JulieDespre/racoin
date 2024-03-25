Langages Utilisés:

    PHP
    jQuery
    JavaScript
    SCSS
    SQL

Frameworks Utilisés:

    Slim (pour le backend)
    jQuery (pour la manipulation du DOM)
    Twig (pour les templates)

But Général de l'Application:
L'objectif principal de l'application est de permettre aux utilisateurs de poster des annonces à la manière de Leboncoin. Cela implique la possibilité de créer et de publier des annonces en ligne, ainsi que de trouver des revendeurs. Les utilisateurs peuvent soumettre des petites annonces dans diverses catégories et départements. De plus, ils ont la possibilité de consulter, modifier et supprimer leurs propres annonces. La recherche d'annonces est également prise en charge, permettant aux utilisateurs de filtrer les résultats par mots-clés, catégories, départements, et plages de prix.

Estimation des Tâches:

    Mettre à jour les dépendances de Twig et Slim vers leurs versions 2.0 et 1.0 respectivement à l'aide de Composer.

    Refaire le fichier de configuration.

    Corriger les erreurs de namespace dans les contrôleurs.

    Revoir l'architecture de l'application pour adopter une approche de micro-services et éviter le mélange de PHP et de JavaScript.

    Mettre en place un environnement Docker pour le développement et le déploiement.

    Assurer la conformité avec les PSR.

    Supprimer le framework jQuery, jugé lourd et lent.

    Ajouter un fichier .env pour gérer les variables d'environnement.

    Nommer correctement les variables (5).

    Supprimer les variables inutilisées (5).

Mode d'Emploi:
Fournir un Dockerfile et un fichier docker-compose correspondant pour faciliter l'installation et le déploiement de l'application.

Dépendances Non Maintenues:
Migrer de la version 1 à la version 2 de la dépendance "Carbon".
