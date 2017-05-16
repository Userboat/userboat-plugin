# Configuration

Il est possible de configurer plusieurs options lors de la génération du formulaire. 

## Paramètres

| Paramètre | Description |
| :--- | :--- |
| _groupId_ | Ce paramètre permet d'aller chercher les champs du formulaire. Il désigne l'identifiant d'un groupe. La valeur par défaut est `undefined`. |
| _locale_ | Ce paramètre est utilisé pour définir la langue à utiliser. La valeur par défaut est `en_US`.  Voir la liste des langues disponibles. |
| _submit_button_text_ | Ce texte remplace celui par défaut dans le bouton pour soumettre le formulaire. La valeur par défaut est `Submit`. |

## Méthodes

Pour utiliser les méthodes, il faut avoir l'objet de type `userboatForm`. Par exemple:

```javascript
$('#form').userboatForm().trigger('init');
```

Les méthodes disponibles sont les suivantes:

| Paramètre | Description |
| :--- | :--- |
| _.trigger('init')_ | Cette méthode permet de lancer la construction du formulaire.  |
| _.trigger('destroy')_ | Cette méthode permet de supprimer un formulaire. Les ressources sont libérées convenablement. |
