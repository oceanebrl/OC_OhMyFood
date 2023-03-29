# Oh My  Food !

[Lien vers la page web](https://ohmyfood-oceanebrl.vercel.app/)

> Oh My Food est un projet fictif. Il s'agit du 3ème projet de la formation développeur web d'OpenClassrooms. Les maquettes et  les idées leur appartiennent.

## Scénario

![logo de OhMyFood](./assets_description/ohmyfood.png)

OhMyFood! est une startup qui tente de s'imposer dans le marché de la restauration, d'où son nom. Le but est de créer un site 100% mobile répertoriant les menus de restaurants gastronomiques. La particularité forte d'OhMyFood! est, qu'en plus de proposer un système de réservation, on peut choisir et composer son  menu directement sur le site afin  d'être servi une fois arrivé sur place.

## Maquettes

Vous pouvez retrouver toutes les maquettes utilisées pour ce projet dans le dossier `assets_description > maquettes`.

### Maquette de la page d'accueil

![maquette OhMyFood!, page d'accueil](./assets_description/maquettes/Accueil.png)

## Notes de synthèse

### Cible

Classe moyennes et supérieures, connectées et souvent pressées, souhaitant déguster des produits de qualités.

### Identité graphique :

**Polices**
* Shrikhand
* Roboto

**Couleurs**
* `#9356CD`
* `#FF79DA`
* `#99E2D0`

## Contraintes techniques

* Header et Footer présents sur toutes les pages.
* Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir, et l'ombre porté être plus visible.
* Un bouton "j'aime" doit être présent, même si non fonctionnel. Lorsqu'on le survole, il doit s'animer pour remplir le cœur vide en dessous (choix du remplissage et de l'animation libre)
* Loading spinner nécessaire, qui doit duré entre 1 à 3 secondes.
* Aucune librairie n'est permise pour le projet, seul le préprocesseurs Sass ou Scss et permis
* Lors de l'arrivée dans les menus, les plats doivent avoir une animation d'apparition une à une.
* Toujours sur ses plats, au survol de la souris, une petite coche doit apparaître sur le côté droit.

## Organisation du repos

```
scss
```

Vous pouvez retrouver le CSS ici. Cependant, il n'a pas été formaté par mes soins, et a été  mappé grâce à Sass. Je vous conseillerai plus de regarder les fichiers Scss pour une meilleur lisibilité du code.

```
images
```

Ici, vous retrouverez toutes les images utilisées pour le site, que ce soit les logos ou les images des restaurants.

```
pages
```

Puisque nous n'avons pas un affichage dynamique, vous avez ici les pages une à une des restaurants. Elles sont toutes similaires dans la forme, seul le contenu change.


```
scss
```

Ici, vous avez tout le code Scss. Le code est fragmenté dans plusieurs fichiers pour tenter de rendre le tout beaucoup plus maintenable dans le futur.

## Une envie de tester ce code par vous-même ?

C'est toujours rigolo de modifier un code de soit-même pour tenter de nouvelles choses. Vous pouvez cloner ce repos facilement et le manipuler.

Tout d'abord, il vous faut [node](https://nodejs.org/fr/download) d'installé sur votre ordinateur.

Vous pouvez cloner le repos avec VSCode grâce à la commande (`ctrl + ù` pour ouvrir le temrinal) :

```
> git https://github.com/oceanebrl/OC_Booki.git
```

Et vous devrez ensuite installer les dépenses nécessaires grâce à :

```
> npm install
```

Sass a été installé avec node. Donc il vous suffit d'utiliser :

```
> sass --watch ./scss/main.scss ./css/style.css
``` 

comme commande si vous voulez modifier les fichier scss. 
