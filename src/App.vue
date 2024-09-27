<template>
  <Cover />
  <Resume />
  <Content />
</template>

<script>
AOS.init();

import Cover from './components/Cover.vue';
import Resume from './components/Resume.vue';
import Content from './components/Content.vue';

export default {
  name: 'App',
  components: {
    Cover,
    Resume,
    Content
  }
}
</script>

<style>
  body {
    overflow-x: hidden;
  }
</style>
