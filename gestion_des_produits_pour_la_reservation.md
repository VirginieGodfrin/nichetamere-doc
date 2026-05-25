Nichetamere.be
Documentation Commerce et Webform : Ajout de produit dans le formulaire de réservation.
📘Introduction,  Fonctionnement général
Objectif du site :
Le site permet de gérer :
la réservation de services Dogwash
la vente de produits
la création automatique de commandes
L’objectif est de proposer une expérience simple pour le client final, tout en facilitant la gestion pour l’administrateur.
Les 3 composants principaux
Le fonctionnement du site repose sur trois modules principaux :
    • Commerce
    • Webform
    • Webform Booking
Commerce — Produits et commandes
Le module Commerce permet de gérer :
- les produits (ex : packs, articles)
- les prix
- les commandes
Chaque produit est structuré pour pouvoir être utilisé dans le formulaire de réservation.
Webform — Formulaire de réservation
Le module Webform permet de créer un formulaire utilisé par les clients pour :
- sélectionner un créneau
- choisir un service ou un pack
- ajouter des produits
Ce formulaire est le point d’entrée principal pour l’utilisateur.
Webform Booking — Gestion des créneaux
Le module Webform Booking permet de :
- proposer des créneaux disponibles
- éviter les réservations en double
- organiser le planning
Fonctionnement global
Lorsqu’un client utilise le site :
1. Le client remplit le formulaire
2. Il choisit un créneau
3. Il sélectionne un pack et des produits
4. Une commande est automatiquement créée
Principe important à retenir
🔑Commerce stocke les produits
🔑Webform les affiche
🔑Le client les sélectionne
🔑Une commande est générée automatiquement
🛍️ Gestion des produits (Commerce)
Type de produits et variations

Pour bien comprendre il est important de distinguer deux notions:
1. Les types de produits
2. Les variations de produits


1. Types de produits

Un type de produit correspond à une catégorie de produits.
Chaque type permet de définir :
les informations du produit (description, photo, titre)
les champs disponibles
l’organisation du contenu

Liste des types de produits utilisés
🧴 Produits Butchcare
Butchcare – Baume Nez
Butchcare – Baume Pattes
Butchcare – Baume Plis
Butchcare – Baume Réparateur
Butchcare – Brume Apaisante Pelage
🧴 Produits Diamex
Diamex – Lotion Buccale
🛁 Services
Pack Dogwash


À retenir:
Un type de produit définit la structure du produit (ce que l’on peut remplir)


2. Variations de produits

Chaque produit contient une ou plusieurs variations.
Les variations permettent de gérer les prix, la référence (stock), les options (si besoin plus tard) et de connecter correctement les produits au panier. Même si un produit n’a qu’un seul prix, il doit quand même avoir une variation.

Une variation correspond à :
un prix
une référence (SKU)
les informations nécessaires à la commande

Par exemple le produit de type Baume Patte, peux avoir plusieurs variations de produits:

Baume Patte 20 gr
prix: 20 €
SKU: BAUME-PATTES-20
Baume Patte 40 gr
prix: 40 €
SKU: BAUME-PATTES-40

A retenir:
c’est la variation qui est ajoutée à la commande, pas le produit lui-même

Liste des Type de variation de produit
🧴 Produits Butchcare
Butchcare - Baume Nez 	
Butchcare - Baume Pattes 
Butchcare - Baume Plis 
Butchcare - Baume Réparateur 
Butchcare Brume Apaisante Pelage 
🧴 Produits Diamex
Diamex - Lotion Buccale 
🛁 Services
Pack Dogwash Variation


3. Création d'un produit et de ses variation.

Lorsque que je crée un produit via commerce > produit > Ajouter un produit, je commence par sélectionner un type de produit. Par exemple : Butchcare - Baume Pattes, je lui défini un titre (le titre du produit peux être le même que le titre du type), un corps (une description), un lien vers un autre site web ou il est référencé, et une photo. De cette manière, j'ai créé le produit Butchcare - Baume Pattes de type Butchcare - Baume Pattes.
Le nouveau produit: (Butchcare - Baume Patte)[https://nichetamere.be/fr/product/4]
Le formulaire de la création de produit depend de sa configuration : Admin > Commerce > Configuration > Types de produit > Butchcare - Baume Pattes > Modifier

Après la création du produit, je lui défini des variations via Commerce > produit > Butchcare - Baume Patte > Modifier > Variations. Je définie un titre , c'est ce titre que l'on retrouvera par la suite dans le formulaire de reservation, la référence (Identifiant du stock ou SKU), le prix, et la devise. Pour l'instant, il n'y a q'une seule variation main on pourra en ajouter d'autres par la suite. 
Ce formulaire de création de variation dépend de sa configuration : Admin >Commerce > Configuration > type de variation de produit > Butchcare - Baume Pattes > modifier 
