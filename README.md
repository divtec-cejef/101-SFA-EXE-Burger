# Exercice Fifty Burgers

  * **Exemple de solution :** http://kode.ch/fifty-burgers/
  * **Code de la solution :** https://github.com/divtec-cejef/101-SFA-EXE-Burger/tree/solution
  * **Remaques faites aux apprentis :** https://github.com/divtec-cejef/101-SFA-EXE-Burger/blob/solution/remarques-apprentis.md


## Objectif
Votre objectif est de créer le site **Fifty Burgers** 
en vous basant sur :

* Les textes du document Word `Recette du fifty burger.docx`
* Les images `burger-viande-hachee.jpg` et `fifty-burgers.png`
* La maquette graphique `maquette-fifty-burgers.png`
* Les consignes du designer, du prochain chapitre

## Consignes du designer
Pour commencer, voici la palette de couleurs :

* Beige _pain_ : `#E8A062`
* Brun _viande_ : `#823922`
* Vert _salade_ : `#00A24B`
* Jaune _fromage_ : `#FDC032`
* Blanc : `#ffffff`
* Noir : `#000000`

**Palette en ligne :** https://coolors.co/e8a062-823922-00a24b-fdc032-ffffff-000000

### Règles générales à appliquer à tous le site :
* Police des textes `Verdana`
* Épaisseur, poids, de la police normal `400`
* Taille des textes `120%`
* Hauteur de ligne `1.4`
* Couleur du texte noir
* Couleur de l'arrière-plan blanc
* Les liens ne sont **PAS soulignés**,
  ils sont verts et deviennent beige lorsqu'on les survole
* Les titres de niveau 1 et 2 utilisent la police `Georgia`
* Les titres 1 sont jaunes, font `4x` la taille du texte de base
  et on une hauteur de ligne de `0.9`
* Les titres 2 font `2.5x` la taille du texte de base
  et ont une marge extérieure de
  `60px` haut,
  `20px` bas et
  `0` gauche/droite. 
* Tous les paragraphes ont un interligne de `1.5`

---
### Entête du site
* Arrière-plan noir
* Texte centré horizontalement
* Marge intérieure de `10px`
* Le logo, image d'entête, a une hauteur max de `160px`

### Contenu principal du site
* marges intérieures de `20px`
* marges extérieures de `0` haut/bas
  et automatique gauche/droite
* largeur maximum de `600px`

#### Paragraphe d'introduction
* taille du texte `1.3x` la taille du texte de base
* texte est _stylé_ en italic
* texte est _transformé_ en majuscule

#### Listes à puces des ingrédients
Les ingrédients sont séparés en deux listes à puces,
voir document `Recette du fifty burger.docx`.

##### Liste à puces
* suppression des puces de la liste
* marges intérieures à `0`
* largeur max de `95%`
* marges extérieures de `40px` haut/bas et
  automatique gauche/droite

##### Éléments de la liste à puces
* arrière-plan beige
* couleur du texte blanc
* marges intérieures `10px` haut/bas et `40px` gauche/droite

###### Au 1er élément de la liste
* bordure arrondie de `30px` au coins supérieurs gauches/droites

###### Au dernier élément de la liste
* bordure arrondie de `30px` au coins inférieurs gauches/droites

---
### Pied de page du site
* arrière-plan brun
* couleur du texte blanc
* texte centré horizontalement
* marges intérieures de `10px`
* marges extérieures de
  `20px`haut,
  automatique gauche/droite et
  `40px` bas
* largeur max de `400px`
* hauteur minimum de `50px`
* bordure haut et bas beige de `30px`
* bordure arrondie de `30px`

**Note :** Ne pas oublier d'ajouter un **paragraphe** avec le lien **"Retourner en haut de la page"**
au tout début du pied de page. Pour qu'il fonctionne ajoute une ancre `#top` au `<body>`.

## Bonus Burger... _si tu vises le 6 !_

Donner un look de **Big Mac** aux listes à puces des ingrédients
en leur ajoutant de la viande, de la salade et du frooooommmaaaage :

* Sélectionner les éléments de la liste
  en position paire, _even_ en anglais : le 2e, 4e, 6e, ... 
  Donner à ces éléments les styles suivants :
  * couleur de fond brune (viande)
  * bordure supérieure jaune de `5px` (fromage)
  * bordure inférieure verte de `10px` (salade)
  
* Pour s'assurer que le dernier élément est un pain
  ( c'est nettement plus facile pour manger),
  sélectionner le dernier élément de la liste
  et lui appliquer les styles suivants :
  * couleur de fond beige
  * supprimer les bordures (sauf si tu veux terminer par de la salade)
  
