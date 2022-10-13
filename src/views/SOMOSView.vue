<template>
  <div class="Somos">
<QuienesSomosComponent/>
<Footercomponent/>
    </div>

</template>

<script>
import { defineComponent } from 'vue';
import QuienesSomosComponent from '@/components/QuienesSomosComponent.vue';
import Footercomponent from '@/components/FooterComponent.vue';
export default defineComponent({
  name: 'SomosView',
  components: {
  QuienesSomosComponent,
  Footercomponent,
  },
});
</script>