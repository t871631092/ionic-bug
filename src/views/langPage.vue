<template>
  <ion-page>
    <ion-router-outlet />
  </ion-page>
</template>

<script lang="ts">
import { IonPage, IonRouterOutlet } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'langPage',
  components: {
    IonPage,
    IonRouterOutlet
  }
});
</script>