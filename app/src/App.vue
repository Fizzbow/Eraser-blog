<template>
  <router-view />
  <div>
    地球
    <q-icon size="large" name="fa-solid fa-earth-americas" />
    <i class="fa-solid fa-earth-americas"></i>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
});
</script>
