<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="40"
        />

      </div>

      <v-spacer></v-spacer>

      <v-btn text> LOGIN </v-btn>
      <v-icon> mdi-account-tie </v-icon>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>
<!--<template> 
<v-app> 
 <navbar> </navbar>
 <v-main>
  <router></router>

  </v-main>
</v-app>
</template>-->
<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
<style lan="sscs">
@import url('@/assets/styles.css');
</style>