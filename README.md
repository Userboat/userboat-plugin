# Installation

Intégrer le plugin de Userboat à votre site web est très simple.

1- Ajouter le tag script à votre page pour inclure le javascript à votre page.

```
<script src="https://cdn.userboat.com/userboat.min.js"></script>
```

2- Créer un élément dans la page, celui-ci sera utilisé pour la génération du formulaire.

```
<div class="userboat-demo"></div>
```

3- Initier le plugin à l'aide de l'identifiant de votre groupe,

```
$('.userboat-demo').userboatForm({
    groupId: 'd6d02766-5659-4aa7-893c-3bd02f06bf63'
}).trigger('init');
```



