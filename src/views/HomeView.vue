<template>
  <div class="home">
    <div class="contenedor">
  <img src="../assets/dog.png" />
  <div class="centrado">Alimento para tus mascotas y algo más.
    porque ellos merecen lo mejor
  </div>
</div>
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

@Options({
  components: {
    HelloWorld,
  },
})
export default class HomeView extends Vue {}
</script>

<style>
.contenedor{
    position: relative;
    display: inline-block;
    text-align: center;
}
 

.centrado{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
</style>
