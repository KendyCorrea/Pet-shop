<template>
  <div class="Servicios">
<ServiciosComponent/>
<Footercomponent/>
    </div>

</template>

<script>
import { defineComponent } from 'vue';
import ServiciosComponent from '@/components/ServiciosComponent.vue';
import Footercomponent from '@/components/FooterComponent.vue';
export default defineComponent({
  name: 'ServiciosView',
  components: {
  ServiciosComponent,
  Footercomponent,
  },
});
</script>