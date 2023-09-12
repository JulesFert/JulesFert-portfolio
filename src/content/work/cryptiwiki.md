---
title: CryptiWiki
publishDate: 2023-08-04
img: /assets/cryptiwiki-1.png
img_alt: Site cryptiwiki
description: |
  Site de type “wiki” recueillant des informations sur les cryptides, des espèces vivantes dont on suppose l’existence. Par exemple des créatures comme le populaire Monstre du Loch Ness, ou le non moins fameux Yéti.

tags:
  - Back-end
  - Symfony
  - React
---

### Présentation générale du site

> *La cryptozoologie étudie les traces des monstres de légende : les cryptides.*

Il s’agit d’un site de type “wiki” recueillant des informations sur les **cryptides**, des espèces vivantes dont on suppose l’existence, celles-ci étant étayées par des preuves de nature diverse, mais néanmoins insuffisantes pour être reconnues par la communauté scientifique. On parlera de créatures comme le populaire **Monstre du Loch Ness**, ou le non moins fameux **Yéti**.

Il s’articule sur une page d'accueil qui redirige vers des articles, ceux-ci étant l'œuvre participative de la communauté. Le site propose tous les outils nécessaires à l’écriture et à l’édition d’articles par ses membres.

Il fonctionne avec une partie **publique**, accessible à tous, et une partie **privée**, réservée à l’équipe administrative, dans laquelle peuvent être utilisées des fonctionnalités plus critiques pour la mise en marche du site.


### Public cible

Toute personne intriguée par l’inconnu, les mythes et légendes urbaines.
Public à partir de l’adolescence jusqu’à un âge avancé. Avec la possibilité de fédérer un groupe de gens particulièrement passionnés par la découverte et le rêve.

Le public est **francophone**, et susceptible d’utiliser tout type d’appareil pour parcourir le site. Le site pourra être traduit pour le public anglophone dans le futur. 

### Objectifs

La création d’un projet de type “wiki” répond à ces deux problématiques.
	
D’abord, d’une **architecture et navigation simples**, il permet d’accéder à des **articles détaillés** grâce à une barre de recherche et un listing complet et modulable. Les articles eux-mêmes sont des condensés de toutes les informations et illustrations relatifs à chacunes des créatures. 

Ensuite, la sur-couche de **travail participatif** inhérente à ce type de site permet sa constante évolution et mise à jour. Les utilisateurs inscrits pouvant proposer des mises à jour de contenu et même de nouveaux sujets, la plateforme peut ainsi s’adapter à toute nouveauté.

### Equipe Projet

- **FAUCHEUX Benjamin** :  *Lead Developer*

- **FERT Jules** : *Back Developer*, Tech. Specialist in Symfony

- **GIRARD Morgane** : *Front Developer*, Scrum Master

- **KEDADOUCHE Mehdi** : *Back Developer*, Git Master

- **LEROY Silvin** : *Front Developer*, Product Owner


### Technologies utilisées

- Partie Front : **React** v18.0.28, **Redux** v8.1.1, **sass** v1.62.0
- Partie Back : **Symfony** v5.4, **Twig**
- Base de données : **MariaDB** v10.3.25
- Suppléments : **API** Rest

### Mon Rôle au sein de ce projet 

J'ai été, durant ce projet, **référent technique PHP Symfony**. Je m'occupais de la partie back-end du projet avec **Mehdi KEDADOUCHE**. Nous avons mis en place des routes API afin d'alimenter le front en données. Les échanges front-back se faisaient en JSON. 

Nous avons notamment mis en place des routes pour afficher la liste des créatures, une créature par son slug, une créature affcihées au hasard, ainsi que la dernière créature créee. Des routes *edit* et *create* ont étés mises en place pour gérer l'envoi et la réception des data lors de la création ou modification d'un article sur le site. 
