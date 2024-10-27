# Site-ACF2L

## Sommaire 
1. Maquette
2. Répartition des tâches
3. Analyse et rectifications
4. Refonte du site
5. Précision sur le site

## 1. Maquette 

https://www.figma.com/design/cUEUVRBnDue1bkfqVTvFF8/ACF2L?node-id=0-1&node-type=canvas&t=eemMrKVpFJ3z4mhp-0

## 2. Répartition des tâches

Nicolas BUISSET : Création des maquettes (Figma) + Analyse critiques + rectifications à réaliser sur le site web actuel + Logo

Léonardo HENRIQUES-MATEUS : Réalisation du site WEB (HTML, CSS, JavaScript)

## 3. Analyse et rectifications
## Analyse Critique
 Header : 

Un très grand espace blanc est présent dès le début de la page avec aucun contenu et uniquement la 2e bannière “Venez pilotez votre ULM !!!” Est bien responsive et prend tout l’espace qui lui est dédié.

La première barre avec le contact est mal placée, ce n’est pas intuitif de mettre les réseaux sociaux, l’adresse e-mail et le numéro de téléphone en haut de page. Le but étant de regarder le site internet et de contacter par la suite l’entreprise si on est intéressé. Cependant là c’est l’inverse, l’utilisateur va oublier le contact en haut de page quand celui-ci sera en bas de page.

Couleurs : la couleur des titres sur les images les bannières sont très mal choisis, les lettres ne se reflètent pas et nous devons fournir un effort pour lire correctement ce qu’il est écrit. Cela montre également un manque d’accessibilité pour les malvoyants.

 Catégorie d’ULM : 

Les numérotations 1, 2, 3 … Sont très espacés des 6 classes ULM, nos yeux doivent donc aller chercher l’information par eux-mêmes ce qui nuie à l'ergonomie et la fluidité de la page. La première carte de la catégorie comporte une petite erreur, une image non adaptée à l’espace qui lui est dédié. En revanche, les deux dernières cartes des tarifs sont très bien réalisées avec les informations colorées pour le titre,  l’achat et le prix avec un ajout d’une description pour donner envie au client.


Nos moyens pédagogiques : 
	
Aucun CSS sur l’image de cette même catégorie, posé brut. Le texte de “nous disposons de :” n’est pas facile à lire, il s’agit d’un bloc de texte sans inter-lignes, saut de lignes etc.

Les deux catégories “Nos moyennes pédagogiques” et “Photo Gallery” sont mal séparées, les deux background sont identiques.

 Photo Gallery :

Lorsque l’utilisateur clique sur une image, il est difficile de savoir que l’on peut switch d’images avec la flèche droite et gauche. De plus, l’image sur laquelle on clique n'apparaît pas forcément en premier (Images concernées : 3, 5, 6, 7) et l’image numéro 4 ne s’affiche pas “The image could not be loaded.”


 Footer : 

Les images à link ne fonctionnent pas (Facebook, Twitter, LinkedIn, Instagram). De plus, ils auraient pu le link les images pour la localisation (lien Google map) et pour le mail (ouvre directement la boîte mail du lecteur et prépare un futur message à envoyer.).


## Pour améliorer le site :

1. En-tête (Header)
Contact : Déplacer les infos de contact vers le footer ou un panneau latéral pour une meilleure accessibilité.
Bannière : Réduire l’espace blanc et optimiser l’appel à l’action pour attirer l'attention.

2. Couleurs et Typographie
Contraste : Améliorer la lisibilité avec des couleurs plus contrastées et vérifier l’accessibilité.
Uniformité : Utiliser une police uniforme et hiérarchisée sur tout le site.

3. Catégorie d’ULM
Espacement : Rapprocher les numérotations et classes ULM pour une navigation plus fluide.
Images adaptatives : Uniformiser les dimensions d’image pour éviter les distorsions.

4. Sections “Moyens pédagogiques” et “Photo Gallery”
Style visuel : Appliquer un CSS uniforme aux images, espacer les textes pour faciliter la lecture.
Séparation des sections : Utiliser des fonds contrastés pour bien distinguer les sections.

5. Galerie photo
Navigation : Ajouter des flèches et un guide pour naviguer dans les images, et résoudre les erreurs de chargement.

6. Footer
Liens fonctionnels : Corriger les liens sociaux, ajouter Google Maps et un lien e-mail interactif.
Interactivité : Ajouter des animations sur les icônes pour indiquer leur fonction.

## 4. Refonte du site

- Une page dédié au Profil avec les informations utilisateurs et la possibilité d'aller regarder les webcams NORD, EST, OUEST des pistes

- Une page dédié à l'entreprise avec toutes les informations (Services, à propos, moyens pédagogiques, Platformes ULM, Hébergement, Vidéo surveillance et sécurité

- Une page dédié à la présentation des Locaux (Hébergement avec Appartement et chambre + Les pistes, hangars et les surfaces de l'entreprise)

- Une page de connexion pour effectuer les achats et/ou obtenir certaines informations supplémentaires avec une possibilité d'accessibilité aux Webcams si l'utilisateur en a l'autorisation

- Une page dédié aux Tarifs des différents Baptême (AutoGire, Multi-axes et Pendulaire avec informations et prix)

## 5. Précisions sur le site

- La page Tarifs est interactive avec la facture dynamique.
- Pour ce qui est du footer les liens fonctionnels sont le "A propos" et les 3 véhicules en dessous de nos formations, les ancres renvoient directement au niveau de la description du véhicule du même nom.
- J'ai essayé de mettre le maximum de commentaires dans le code Html et Javascript pour que ce soit un peu plus lisible.
