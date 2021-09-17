<template>
  <v-row>
    <v-col class="text-center">
      <blockquote class="blockquote">
        {{ this.$route.params.id }}
        <br />
        <NuxtLink to="../">Retour à l'index</NuxtLink>
        <footer>
          <small>
            <em></em>
          </small>
        </footer>
      </blockquote>
    </v-col>
  </v-row>
</template>
