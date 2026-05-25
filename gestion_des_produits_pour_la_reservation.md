Nichetamere.be

# Documentation Commerce et Webform: Ajout de produit dans le formulaire de réservation.

## Gestion des produits (Commerce)

#### Type de produits et variations

Pour bien comprendre il est important de distinguer deux notions:

1. Les types de produits

2. Les variations de produits

##### 1. Types de produits

Un type de produit correspond à une catégorie de produits.

Chaque type permet de définir :

- les informations du produit (description, photo, titre)
- les champs disponibles
- l’organisation du contenu

###### Liste des types de produits utilisés

**Produits Butchcare**

- Butchcare – Baume Nez
- Butchcare – Baume Pattes
- Butchcare – Baume Plis
- Butchcare – Baume Réparateur
- Butchcare – Brume Apaisante Pelage

**Produits Diamex**

- Diamex – Lotion Buccale

**Services**

- Pack Dogwash

À retenir:

**Un type de produit définit la structure du produit : description, photo **

##### 2. Variations de produits

Chaque produit contient une ou plusieurs variations.

Les variations permettent de gérer les prix, la référence (stock), 
les options (si besoin plus tard) et de connecter correctement les produits au panier.
Même si un produit n’a qu’un seul prix, il doit quand même avoir une variation.

Une variation correspond à :

- un prix
- une référence (SKU)
- les informations nécessaires à la commande

Par exemple le produit de type Baume Patte, peux avoir plusieurs variations de produits:

- Baume Patte 20 gr
	- prix: 20 €
	- SKU: BAUME-PATTES-20
  
- Baume Patte 40 gr
	- prix: 40 €
	- SKU: BAUME-PATTES-40

A retenir:

**C’est la variation qui est ajoutée à la commande, pas le produit lui-même**

###### Liste des Types de variation de produit

**Produits Butchcare**

- Butchcare – Baume Nez
- Butchcare – Baume Pattes
- Butchcare – Baume Plis
- Butchcare – Baume Réparateur
- Butchcare – Brume Apaisante Pelage

**Produits Diamex**

- Diamex – Lotion Buccale

**Services**

- Pack Dogwash

##### 3. Création d'un produit et de ses variation.

Lorsque que je crée un produit via commerce > produit > [Ajouter un produit](https://nichetamere.be/fr/product/add).
Je commence par sélectionner un type de produit. Par exemple : Butchcare - Baume Pattes,
je lui défini un titre (le titre du produit peux être le même que le titre du type), 
un corps (une description), un lien vers un autre site web ou il est référencé, et une photo. 
De cette manière, j'ai créé le produit Butchcare - Baume Pattes de type Butchcare - Baume Pattes.

Le nouveau produit: [Butchcare - Baume Patte](https://nichetamere.be/fr/product/4)

Le formulaire de la création de produit dépend de sa configuration : 
Admin > Commerce > Configuration > [Types de produit](https://nichetamere.be/fr/admin/commerce/config/product-types) > Butchcare - Baume Pattes > [Modifier](https://nichetamere.be/fr/admin/commerce/config/product-types/butchcare_baume_pattes/edit?destination=/fr/admin/commerce/config/product-types)

Après la création du produit, je lui défini des variations via Commerce > produit > Butchcare - Baume Patte > Modifier > [Variations](https://nichetamere.be/fr/product/4/variations).
Je définie un titre , c'est ce titre que l'on retrouvera par la suite dans le formulaire de réservation, la référence (Identifiant du stock ou SKU), 
le prix, et la devise. Pour l'instant, il n'y a q'une seule variation main on pourra en ajouter d'autres par la suite. 

Ce formulaire de création de variations dépend de sa configuration : 
Admin >Commerce > Configuration > [type de variation de produit](https://nichetamere.be/fr/admin/commerce/config/product-variation-types) > Butchcare - Baume Pattes > [Modifier](https://nichetamere.be/fr/admin/commerce/config/product-variation-types/butchcare_baume_pattes/edit?destination=/fr/admin/commerce/config/product-variation-types) 

## Intégration des produits dans le formulaire de réservation
