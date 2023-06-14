# Oh my food !
## _Création d'un site pour une entreprise de commande de repas en ligne_


![Build Status](https://badge.buildkite.com/sample.svg?status=passing)

3ème projet de la formation de développeur web d'OpenClassroom.

![Screenshot du site avec aperçu des pages mobiles](https://github.com/KLdvl/OC_P3_Ohmyfood/blob/master/public/images/Screenshot.png)

## Enjeux
---
- Développer un site proposant le menu de 4 grands restaurants parisiens.
- Permettre la réservation en ligne et la composition de menus.

## Livrables attendus
---
- Un fichier au format TXT contenant le lien vers notre repository GitHub.
- Un fichier au format TXT contenant le lien vers la page web du site web.
### Intégration de contenu d'après maquettes

- Une page d'accueil
- Pages de menu (x4)

### Ajout d'effets graphiques et d'animations

**Boutons**
- Au survol, la couleur de fond des boutons principaux devra légèrement s'éclaircir. L'ombre portée devra également être plus visible.

- À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour ça, un
bouton "J’aime" en forme de cœur est présent sur la maquette. Au clic, il devra se
remplir progressivement. Pour cette première version, l’effet peut être apparaître au
survol sur desktop au lieu du clic.

**Page d’accueil**
- Quand l’application aura plus de menus, un “loading spinner” sera nécessaire. Sur
cette maquette, nous souhaitons en avoir un aperçu. Il devra apparaître pendant 1 à
3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et
utiliser les animations CSS (pas de librairie). Le design de ce loader n’est pas défini,
toute proposition est donc la bienvenue tant qu’elle est cohérente avec la charte
graphique du site.

**Pages de menu**
- À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger
décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe
“Entrée”, “Plat” et “Dessert”. Un exemple de l’effet attendu est fourni.

- Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus.
Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de
la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol
sur desktop au lieu du clic. Si l’intitulé du plat est trop long, il devra être rogné avec
des points de suspension. Un exemple de l’effet attendu est fourni.

## Technologies utilisées
---
- [HTML] - Version 5
- [CSS] - Version 3
- [SCSS]
- [VScode] - Editeur de code
- [FontAwesome] - Bibliothèque d'icônes
- [GoogleFonts] - Bibliothèque de polices

## Identité graphique et contraintes techniques
---
**Polices de caractères**
- Logo et titres: Shrikhand
- Texte: Roboto

**Couleurs utilisées**
- Primaire : #9356DC
- Secondaire : #FF79DA
- Tertiaire : #99E2D0

**Compatibilité**
- Développement en mobile-first à partir des maquettes fournies
- Adapatation tablette et desktop libre (supports non prioritaires)
- Responsive design intégré sur tout supports
- Validation HTML et CSS du W3C
- Dernières versions de Chrome, Firefox, Edge

## Installation
---
Une version en ligne est directement accessible à l'adresse : [Ohmyfood](https://nd-ohmyfood.netlify.app/)

Sinon, vous pouvez cloner le projet
```terminal
git clone https://github.com/No0910/ohmyfood.git
```
