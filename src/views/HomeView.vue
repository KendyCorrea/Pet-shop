<template>
  <div class="home">
    <div class="contenedor">
  <img src="../assets/dog.png" />
  <div class="centrado"><p> Alimento para tus mascotas y algo más.</p>
   <p>porque ellos merecen lo mejor</p>
   <button>contactar</button>
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
    color: white;
    font-size: 300%;
    font-family: roboto;
}
 

.centrado{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
        p {
            color: #65E73C;
            text-shadow: -2px 2px 4px rgba(0, 0, 0, 0.5),
                2px -2px 0 rgba(255, 255, 255, 0.9);
        }
</style>
