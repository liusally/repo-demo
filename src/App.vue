<template>
  <h1>{{ message }}</h1>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      message: 'Hello, Vue!'
    };
  }
};
</script>

<style lang="scss" scoped>
h1 {
  background: yellow;
}
</style>
