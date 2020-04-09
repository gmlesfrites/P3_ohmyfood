Projet 3 de la formation Developpeur Web d'Openclassrooms

Il s'agit de réaliser le site internet de la startup ohmyfood.
Le produit final doit être responsive et correspondre à la maquette fournie.

Ce projet a été construit en plusieurs phases :
-création de la banche master avec le fichier initial index.html

-création de la branche develop pour créer toute la base du site
	page d'accueil : index.html
	page générique de menu: menu-0.html
	pages de menus: menu-1 à menu-4.html
	pages de mentions légales: mentions-legales.html

- utilisation du préprocesseur Sass pour la création du fichier final style.css
	Base (base et typographie)
	Components (liens, boutons, icônes fontawesome, images)
	Layout (container, footer, formulaire, header, navigation)
	Pages (index, mentions légales, menu-0 à menu-4)
	Utils (fonctions, variables, mixins, extensions)

-création d'une branche animations
	Points de suspension (dans la feuille _i.scss)
	Titres des entrées/plats/desserts soulignés au passage (dans la feuille _menus.scss)
	Liens contact et mentions légales du footer qui se secouent au passage (dans la feuille _link.scss)
	Zoom sur les visuels de menus dans la pages d'accueil (dans la feuille _index.scss)

-création d'une branche mediaqueries 
	Travail dès le début en mobile first
	Breaktpoints : 768px, 1024px, 1440px et 1900px

-création d'une branche gh-pages
	compile tous les commit de toutes les branches au fur et à mesure
	visualisation du produit finalisé avec gitpages


Après travail sur les animations et les mediqueries, ces branches n'ont pas été actualisées.
Les seules présentant le travail 'à jour' sont develop et gh-pages.
	
Travail régulièrement vérifié par le biais des sites :
	https://validator.w3.org/
	https://jigsaw.w3.org/
	https://wave.webaim.org/
	https://www.webpagetest.org/