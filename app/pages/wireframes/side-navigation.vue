<template>
  <v-app id="inspire">
    <v-navigation-drawer
      class="pt-4"
      color="grey-lighten-3"
      model-value
      rail
    >
      <v-avatar
        v-for="n in 6"
        :key="n"
        :color="`grey-${n === 1 ? 'darken' : 'lighten'}-1`"
        :size="n === 1 ? 36 : 20"
        class="d-block text-center mx-auto mb-9"
      />
    </v-navigation-drawer>

    <v-main>
      <!--  -->
    </v-main>
  </v-app>
</template>
