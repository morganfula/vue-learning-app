<template>
  <the-header title="RememberMe"></the-header>
  <the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
  components: {
    TheHeader,
    TheResources,
  },
};
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
$font-family: 'Roboto', sans-serif;

* {
  box-sizing: border-box;
}

html {
  font-family: $font-family;
}

body {
  margin: 0;
  padding: 0;
}
</style>
