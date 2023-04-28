<template>
  <ion-app>
    <ion-router-outlet />
  </ion-app>
</template>

<script setup lang="ts">
import { IonApp, IonRouterOutlet } from '@ionic/vue';
import { ref } from 'vue';


const data = ref([
  {text: ' hola', value: 1},
  {text: ' mundo', value: 1},
]);





</script>
