## Afficher une image

Pour afficher une image dans un fichier `.html`, tu dois utiliser la balise `img` en remplissant le nom de l'image :

```html
<img src="dossier/mon-image.jpg" />
```

## Changer la taille d'une image

Il est possible de changer la taille de toutes les images en même temps à l'aide du fichier `styles.css`

Tu peux modifier la largeur avec `width` et la hauteur avec `height`. Tu n'es pas obliger de mettre les 2. L'image se redimensionnera automatiquement.

```css
img {
    width: 100px;
    height: 300px;
}
```

## Changer la police de caractères

Dans le fichier `styles.css`, pour changer la police de caractère de toute la page, tu dois ajouter une `font-family` à la base `body` :

```css
body {
    font-family: 'Arial';
}
```

## Lien hypertexte

Dans un fichier `.html`, tu peux aller sur une autre page ou sur un autre site web à l'aide d'un lien hypertexte :

```html
<a href="http://www.google.com">Google</a>
```