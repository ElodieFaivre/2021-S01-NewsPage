# Formulaire

Un formulaire permet à un internaute de saisir une ou plusieurs infos sur une page WEB.

## HTML

3 Balises importantes : 

### form

La balise '<form>' est obligatoire pour créer un formulaire. Tout le contenu de celui-ci doit être situé à l'intérieur. 

### input
La balise qui permet de saisir du contenu.
Elle est très souvent associée à une balise '<label>' pour expliquer le contenu du champs.

On relie un '<input>' à un label grâce aux attributs `for` et `id`.

```html
<label for="firstname">
    Prénom
</label>
<input type="text" id="firstname">
```

Il existe plein (plein !) de types de champs '<input>' différents. Par défaut, c'est le type `text`. La liste ici : https://developer.mozilla.org/fr/docs/Web/HTML/Element/Input#les_diff%C3%A9rents_types_de_champs_input


Il est possible de définir un attribut `value`. Il permet de

- Définir la valeur à utiliser pour le champ pour un champ à choix multiple
- Définir une valeur par défaut pour un champ texte.


### button

Permet de valider un formulaire. Le button doit impérativement être situé dans le formulaire.
Alternative : '<input type="submit" value="Valider">'