<template lang="pug">
  .welcome
    p {{ message }}
    router-link.link(to="/top")
      v-btn go to top
</template>

<script>
export default {
  name: 'welcome',
  data () {
    return {
      message: 'Hello, Joe!'
    }
  }
};
</script>

<style scoped>
.welcome {
  text-align: center;
  margin: 24px;
}
.link {
  text-decoration: none;
}
</style>
