<template>
  <h1>{{ message }}</h1>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Привет, мир',
    };
  },
};
</script>

<style>
#app {
    width: 80vw;
    margin: 0 auto;

}
h1 {
  font-size: 40px;
  font-family: 'Roboto', sans-serif;
  color: blue;
}


</style>