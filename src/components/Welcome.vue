<template lang="pug">
  .container
    p {{ message }}
    router-link.link(to="/top")
      v-btn go to top
</template>

<script>
export default {
  name: 'Welcome',
  data () {
    return {
      message: 'Hello, Joe!'
    }
  }
};
</script>

<style scoped>
.container {
  text-align: center;
  margin: 24px;
}
.link {
  text-decoration: none;
}
</style>
