# Exercice pratique avec jQuery

Comme première expérience avec jQuery, je vous propose de faire quelque chose de simple : un carrousel.

Il y a 3 fichiers pour cet exercice : 
1. `index.html` qui contient tout le markup (code)
2. `style.css` où vous pouvez ajouter des styles nécessaires au bon fonctionnement du carrousel
3. `script.js` où le gros du travail et de la logique doit se faire

Dans les deux derniers fichiers, j'ai ajouté les instructions en français. À vous de les traduire en code

## En CSS
```css
/*

Il faut cacher les images sauf celle qui est .active.
Même chose pour les <article>

*/
```

## En Javascript (jQuery)
```js
// cette ligne permet d'être sûr que le document est prêt à utiliser jQuery
$(function() {
    /*  
    Quand je clique sur un élément de la navigation, 
    le composant : 
    1. met en avant le lien sur lequel je viens de cliquer
    2. affiche l'image adéquate
    3. affiche le paragraphe adéquat
    */
    
});
```

## En HTML
Comme dit plus haut, le fichier HTML a déjà tout pour pouvoir réaliser le carrousel. À vous de décoder, de regarder les attributs et d'identifier les éléments utiles qui permettront de réaliser les instructions ci-dessus.