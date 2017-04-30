<template>
  <div class="signin">
    <input type="text" placeholder="Project Name" v-model="title">{{title}}</input><button v-on:click="titleProject(title)">Title Project</button>
  </div>
</template>

<script>
export default {
  name: 'signin',
  data() {
    return {
      sups: 'Welcome to Your Vue.js App',
    };
  },
  methods: {
    titleProject(title) {
      console.log(title);
      return '';
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
