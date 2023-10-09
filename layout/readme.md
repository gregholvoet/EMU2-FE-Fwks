# FLEX vs GRID
Le but de l'exercice : réaliser la structure suivante selon les différentes techniques évoquées. N'hésitez pas à enregistrer les images pour pouvoir travailler hors ligne. Travaillez en pixel. Le résultat ne doit pas forcément être responsive mais par la suite vous verrez les avantages de certaines techniques par rapport à d'autres.

## Serious game
<a href="http://flexboxfroggy.com/#fr">Flexbox Froggy</a>
<a href="http://cssgridgarden.com/#fr">Grid Garden</a>

## Astuces
- Vous pouvez générer des images via <a href="https://placekitten.com/">Placekitten.com</a> ou utiliser les vôtres
- Pour la partie Flex, vous pouvez utiliser <a href="https://getbootstrap.com/docs/5.2/layout/grid/">la grille de Bootstrap</a>
- Vous pouvez générer une grille (CSS Grid) avec <a href="https://grid.layoutit.com/">Layoutit!</a>

### Propriétés CSS utiles pour l'exercice
```css
.we-need-this-properties {
  border-radius             : 25%;
  font-family               : monospace;
  font-size                 : 16px;
  font-weight               : bold;
  text-align                : right;

  display                   : block;
  padding                   : 10px 15px;
  margin                    : 10px 15px 10px;
  width                     : 300px;
  height                    : 300px;
  max-width                 : 300px;

  align-items               : flex-start;
  align-self                : flex-end;
  flex-basis                : 30%;
  flex-wrap                 : wrap;
  justify-content           : space-between;

  grid-gap                  : 15px;
  grid-template-columns     : 30% 30% 10%;
  grid-template-rows        : 1fr 1fr 1fr;
  grid-column               : 1 / 4;
  grid-row                  : 2;
}
```
