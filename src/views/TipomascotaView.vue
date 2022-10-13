<template>
  <div class="Tipos">
<TipoMascotaComponent/>
<Footercomponent/>
    </div>

</template>

<script>
import { defineComponent } from 'vue';
import TipoMascotaComponent from '@/components/TipoMascotaComponent.vue';
import Footercomponent from '@/components/FooterComponent.vue';
export default defineComponent({
  name: 'TipoMascotaView',
  components: {
  TipoMascotaComponent,
  Footercomponent,
  },
});
</script>