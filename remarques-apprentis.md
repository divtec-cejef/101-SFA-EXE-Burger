- Nom des fichiers et dossiers en minuscules `CSS/Main.css` > `css/main.css`
- Nom du fichier de départ `index.html`
- Organiser son site en créant un dossier pour les images `img/`
- Supprimer les fichiers inutiles au bon fonctionnement du site (word, readme, maquette .. )
- Langue en FR
- Ajouter `normalize.css` avant `main.css`
- Titre doit être composé des mêmes mots-clé que le titre principal du site `h1`, SUIVI DU NOM DU SITE.
```html
 <title>Burger de viande hachée | Fifty Burgers</title>
```` 
- Manque viewport
```html
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
```
- Icône du site.
```html
    <link rel="icon" href="favicon.ico"/>
```
- manque texte alternatif, attribut `alt=""`
```html
    <img src="img/fifty-burgers.png" alt="Logo Fifty Burgers"/>
```` 
- Ajout d'un id pour revenir en haut de la page : `<body id="top">`
- Ajouter texte alternatif présentant le contenu de l'image.
- Toujours terminer son code avec une ligne vide
- Attention aux lignes vides inutiles.
- Placer un ancre, un id, sur le body
  `<body id="haut">`
- lien vers id : `<a href="#top">`
- nom des classes en minuscules
- Créer plusieurs paragraphes, voir document Word
- Ajouter les éléments importants, en gras dans le Word `<strong>`
- Utiliser `<div>` à la place du `<p>`
- Pas de `<br>` !!! On utilise les `<br>` uniquement dans les blocs de textes.
# CSS
- Manque déclaration des groupes avec bloc de commentaires
- Marge intérieure : `padding`
- Marge extérieure : `margin`
- Ajouter une ligne vide entre chaque bloc de code.
Manque la mise en page de base
```css
body {
    font-family: Verdana, sans-serif;
    font-weight: normal;
    font-size: 1.2rem;
    line-height: 1.4;
    color: black;
    background-color: white;
}
```