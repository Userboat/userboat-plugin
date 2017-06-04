# Configuration

Il est possible de configurer plusieurs options lors de la génération du formulaire. 

## Paramètres

| Paramètre | Description |
| :--- | :--- |
| _groupId_ | Ce paramètre permet d'aller chercher les champs du formulaire. Il désigne l'identifiant d'un groupe. La valeur par défaut est `undefined`. |
| _locale_ | Ce paramètre est utilisé pour définir la langue à utiliser. La valeur par défaut est `en_US`.  Voir la liste des langues disponibles. |
| _submit_button_text_ | Ce paramètre est utilisé pour définir le texte du boutton d'envoi. |
| _onPostRender_ | Ce paramètre doit être une fonction. Elle est appelée lorsque le formulaire a été généré. Utilisation: `onPostRender = function() { ... }` |
| _onSuccess_ | Ce paramètre doit être une fonction, reçevant comme données les informations du membre lorsque l'envoi du formulaire est un succès. Aucune fonction n'est appelée par défaut. Utilisation: `onSuccess = function(member) { ... }` |
| _onError_ | Ce paramètre doit être une fonction qui est appelée lorsqu'une erreur s'est produite lors de l'envoi du formulaire. Aucune fonction n'est appelée par défaut. Utilisation: `onError = function() { ... }` |
| _onCompleted_ | Ce paramètre doit être une fonction qui est appelée, que le retour soit un succès ou une erreur lors de l'envoi du formulaire. Aucune fonction n'est appelée par défaut. Utilisation: `onCompleted = function() { ... }` |


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
