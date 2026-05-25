# Documentation Commerce et Webform : Commerce - Webform - Webform Booking

## Introduction – Fonctionnement général

### Objectif du site :

Le site permet de gérer :

- la réservation de services Dogwash
- la vente de produits
- la création automatique de commandes

L’objectif est de proposer une expérience simple pour le client final, tout en facilitant la gestion pour l’administrateur.

#### Les 3 composants principaux

Le fonctionnement du site repose sur trois modules principaux :

- Commerce
- Webform
- Webform Booking

#### Commerce — Produits et commandes

Le module Commerce permet de gérer :

- Les produits (ex. : packs, articles)
- Les prix
- Les commandes

Chaque produit est structuré pour pouvoir être utilisé dans le formulaire de réservation.

#### Webform — Formulaire de réservation

Le module Webform permet de créer un formulaire utilisé par les clients pour :

- Sélectionner un créneau
- Choisir un pack
- Ajouter des produits

Ce formulaire est le point d’entrée principal pour l’utilisateur.

#### Webform Booking — Gestion des créneaux

Le module Webform Booking permet de :

- Proposer des créneaux disponibles
- Eviter les réservations en double
- Organiser le planning

#### Fonctionnement global

Lorsqu’un client utilise le site :

1. Il remplit le formulaire
2. Il choisit un créneau
3. Il sélectionne un pack et des produits
4. Une commande est automatiquement créée

#### Principes importants à retenir

- Commerce stocke les produits
- Webform les affiche
- Le client les sélectionne
- Une commande est générée automatiquement
