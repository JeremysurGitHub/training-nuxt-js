# Router

## Résumé

Nuxt fait le routing pour nous, tous les fichiers .vue dans le dossier page sont des routes. Aucune config est à faire.

Dans une page il faut utiliser la balise < NuxtLink> :

```javascript
<NuxtLink to="/inspire">Lien vers inspire</NuxtLink>
```

On peut utiliser des routes avec des id, il faut un _ devant les fichiers .vue ! 

> On peut utiliser des index.vue si l'ID est pas renseigné.

> C'est bien expliqué dans la doc : https://nuxtjs.org/docs/features/file-system-routing

## Automatic Routes

Most websites will have more than one page (i.e. a home page, about page, contact page etc.). In order to show these pages, we need a Router. That's where vue-router comes in. When working with the Vue application, you have to set up a configuration file (i.e. router.js) and add all your routes manually to it. Nuxt.js automatically generates the vue-router configuration for you, based on your provided Vue files inside the pages directory. That means you never have to write a router config again! Nuxt.js also gives you automatic code-splitting for all your routes.

In other words, all you have to do to have routing in your application is to create .vue files in the pages folder.

Lien : https://nuxtjs.org/docs/get-started/routing