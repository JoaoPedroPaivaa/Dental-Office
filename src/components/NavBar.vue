<template>
  <v-app-bar app color="#4a4e69" dark flat class="px-8">
    <v-btn icon>
      <v-icon color="#fff">fa-solid fa-tooth</v-icon>
    </v-btn>

    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Inicio</v-btn>
    <v-btn text @click="scroll('project')">Especialidades</v-btn>
    <v-btn text @click="scroll('about')">Sobre</v-btn>
    <v-btn text @click="scroll('contact')"> contato</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
</style>