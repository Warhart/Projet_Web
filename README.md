# Projet_Web
Github du projet Web PHP BDD : STRI

# Présentation du projet

Ce projet porte sur le sujet "Plateforme de covoiturage" de la matière Gestion de projet de STRI.
Le site sera réalisé en PHP et la base de données utilisée sera PostgresSQL.

# Résumé

Ce projet a pour objectif de créer une plateforme de covoiturage permettant de gérer un accès à plusieurs utilisateurs proposant des trajets entre les différentes villes de France. 
Ce service rendu ne sera pas payant, il sera basé sur la solidarité, notamment pour les étudiants qui font des trajets réguliers.
La plateforme permettra de gérer plusieurs connexions simultanément et il sera possible de distinguer plusieurs types de comptes.
Un soutien budgétaire pourrait être apporté par des sponsors.

# Cahier des charges

## Problématique des utilisateurs 
  Se déplacer sans coût
  Rentabilité pour le conducteur et le passager
  
## Objectifs
  Concevoir et gérer une application web qui gère le covoiturage pour les étudiants, basé sur la solidarité.

  On distinguera les utilisateurs possibles : 
    -> les passagers
    -> les conducteurs
    -> Les sponsors
    -> Les administrateurs du site
    
Le site approtera aux utilisateurs plusieurs avantages : 
    Une diminution des frais liés à l'utilisation de la voiture.
    Une réduction du temps passé dans les transports.
    Une meilleure accessibilité vers leur point d'arrivée.
    Des liens pourront se tisser et créer des amitiés.
    Les trajets seront sécurisés avec des personnes de confiance.

## Expression des besoins

  1.Environnement
  
  Ce site de covoiturage sera utlisé par les étudiants d'UPSSITECH.
  
  2.Description des fonctions
  
  F1 : Inscription
  F2 : Authentification
  F3 : Gestion des profils (utilisateurs, sponsors, visiteurs, administrateurs)
  F4 : Gestion des trajets
  F5 : Gestion des réservations
  F6 : Gestion des voitures
  
## Fonctions

F1 : Inscription
 Permet à un visiteur de s'inscrire dans la base de données pour devenir membre du site et qu'il puisse utiliser le servicce de covoiturage si il fait partie de l'UPSSITECH.
 
F2 : Authentification
  Pour accéder aux fonctionnalités de covoiturage, il est nécéssaire de s'enregistrer si on n'a pas de compte ou bien de se connecter si on est membre. On utilisera un login et un mot de passe.

F3 : Gérer les profils
  L'administrateur a le droit de supprimer un compte ou bien de la placer dans une liste noire. Il permet à chacun des membres de faire sa propre gestion de compte. Il sera possible de modifier les informations personnelles ou les préférences.

F4 : Gestion des trajets
  Ajouter un trajet :
l'utilisateur de type "conducteur" publie un trajet en saisissant les informations sur son trajet et il faut qu’il ai une voiture renseignée sur le site.

  Consulter trajet :
l’utilisateur inscrit peut rechercher et consulter les trajets de la semaine courante.

  Modifier/Supprimer trajet :
l'utilisateur (conducteur) peut modifier ou supprimer ses propres trajets.

L’utilisateur passager effectue une recherche du trajet (ville de départ, celle d'arrivée, date), il choisit son trajet et réserve sa place en cliquant sur un bouton "Réserver". Un message de demande est envoyé au conducteur pour qu'il accepte. Un message de confirmation est envoyé au passager après acceptation du conducteur.

Le conducteur peut consulter les réservations de ses trajets ainsi que les passagers. Il peut consulter l'historique de ces réservations.

Le passager peut supprimer la demande de réservation. Le conducteur peut supprimer de manière implicite les demandes en supprimant le trajet.

F5 : Gestion des réservations
  Ajout réservation :
L'utilisateur de type conducteur accepte les demandes de réservations sur ses trajets en ajoutant les passagers sur son trajets. Si la capacité de la voiture est pleine, alors il ne peut plus ajouter de passagers et les demandes de réservation sur ce trajets sont désactivées.

  Modifier/Supprimer réservation :
Un utilisateur de type passager peut modifier sa réservation en modifiant les conditions, ou bien supprimer sa réservation.

F6 : Gestion des voitures
  l'utilisateur de type conducteur gère l'ajout de ses voitures, la modification ainsi la suppression.
  
## Contraintes  
  
Les visiteurs désirant réserver doivent se connecter ou bien s'inscire.

Le site doit être facile à gérer et à manipuler par tout les types d'utilisateurs.
Les interfaces seront ergonomiques, conviviales et faciles à utiliser avec un minimum de saisie de données avec affichage automatiques des informations.

La sécurité des informations sera gérée par l'authentification des utilisateurs.


Projet réalisé dans le cadre de la L3 STRI en liant les matière Web, Base de données et Gestion de projets..
