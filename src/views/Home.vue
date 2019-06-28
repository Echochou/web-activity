<template>
  <div class="home">
    <DownLoad />
  </div>
</template>

<script>
// @ is an alias to /src
import DownLoad from '@/views/download/index.vue';

export default {
  name: 'home',
  components: {
    DownLoad,
  },
};
</script>
