<template>
  <div class="home">
    <h1>{{ title }}</h1>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';

export default Vue.extend({
  name: 'Home',

  data: () => ({
    title: 'Helloz!'
  })
});
</script>
