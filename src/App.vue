<template>
  <the-header title="RememberMe"></the-header>
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';

export default {
  components: {
    TheHeader,
  },
  data() {
    return {
      storedResources: [
        {
          id: 'official-guide',
          title: 'Official Guide',
          description: 'The official Vue-js documentation.',
          link: 'https://vuejs.org',
        },
        {
          id: 'google',
          title: 'Google',
          description: 'Learn to search anything',
          link: 'https://google.org',
        },
      ],
    };
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
