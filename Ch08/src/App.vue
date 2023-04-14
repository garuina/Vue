<template>
 <h3>Ch08.Vuetify 실습</h3>
 <p>
    <router-link to="/components">Components</router-link> /
    <router-link to="/grids">Grids</router-link> /
    <router-link to="/layout">Layout</router-link> /
 </p>

 <Components></Components>
 <Grids></Grids>
</template>

<script setup>
import Components from './components/sub1/Components.vue';
import Grids from './components/sub2/Grids.vue';

</script>

<style scoped>
#app{
  padding: 10px;
}
</style>
