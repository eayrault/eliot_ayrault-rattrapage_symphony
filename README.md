# Supermarché 89 (Symfony)

Cette application Symfony est le site web du Supermarché 89. Il regroupe tout les produits disponibles ainsi que la catégorie à laquelle ils appartiennent.

## Base de donnée

Vous trouverez dans le projet une base de donnée de test nommée : ``rattrapage_symfony_db.sql``.

### Utilisateurs de test :

User 1:
- email : eliot1@fake.com
- mot de passe : motdepasse

User 2:
- email  : guest.fake1@gmail.com
- mot de passe : motdepasse

User 3:
- email : guest.fake2@gmail.com
- mot de passe : motdepasse

User 4:
- email : guest.fake3@gmail.com
- mot de passe : motdepasse

User 5:
- email : guest4@fake.com
- mot de passe : motdepasse

## Pages :

User :
- ``/register`` : Page d'inscription au site web.
- ``/login`` : Page de connexion au site web.
- ``/logout`` : Deconnexion

Produits :
- ``/`` : Page d'acceuil. Contient la liste des produits.
- ``/product/new`` : Page de création de produit.
- ``/product/{id}`` : Page de détails de chaque produit.
- ``/product/{id}/edit`` : Page de modification du produit.
- ``/product/{id}/delete`` : Suppression du produit.

Catégories :
- ``/category`` : Page contenant la liste des catégories.
- ``/category/new`` : Page de création de catégorie.
- ``/category/{id}`` : Page de détails de chaque catégorie.
- ``/category/{id}/edit`` : Page de modification de la catégorie.
- ``/category/{id}/delete`` : Suppression de la catégorie.
