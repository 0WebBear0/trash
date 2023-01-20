<template>
  <v-app>
    <v-navigation-drawer
        app
        left
        absolute
        temporary
        v-model="drawer"
    >

    </v-navigation-drawer>
    <v-app-bar color="grey">

    </v-app-bar>
    <v-main>
      <v-container class="">
        <v-row>
          <v-col class="w-25 h-25 text-red">1</v-col>
          <v-col class="w-25 h-25 text-red">2</v-col>
          <v-col class="w-25 h-25 text-red">3</v-col>
          <v-col class="w-25 h-25 text-red">4</v-col>
          <v-col class="w-25 h-25 text-red">5</v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>
<script setup lang="js">

const drawer = false

</script>
<style>

</style>
