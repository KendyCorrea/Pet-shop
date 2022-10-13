<template>
  <div class="Contacto">
<ContactosComponent/>
<Footercomponent/>
    </div>

</template>

<script>
import { defineComponent } from 'vue';
import ContactosComponent from '@/components/ContactosComponent.vue';
import Footercomponent from '@/components/FooterComponent.vue';
export default defineComponent({
  name: 'ContactosView',
  components: {
  ContactosComponent,
  Footercomponent,
  },
});
</script>