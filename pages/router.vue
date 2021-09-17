<template>
  <v-row>
    <v-col class="text-center">
      <blockquote class="blockquote">
        Router <br />
        <NuxtLink to="/howard">HB dans le dossier courant (404)</NuxtLink>
        <br />
        <NuxtLink to="/user/howard">HB dans le dossier user</NuxtLink>
        <br />
        <NuxtLink to="/product/700">Product ID (Facultatif)</NuxtLink>
        <br />
        <NuxtLink to="/playstation/">PlayStation ID (Obligatoire sinon index.vue)</NuxtLink>
        <br />
        <NuxtLink to="/playstation/5">PlayStation ID (Obligatoire)</NuxtLink>
        <footer>
          <small>
            <em>Cliquez sur les liens ci-haut.</em>
          </small>
        </footer>
      </blockquote>
    </v-col>
  </v-row>
</template>
