<template>
  <div>
    <h1>About App</h1>
    <p>This is an app that displays api dad jokes</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About us",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "best place for dad jokes"
        }
      ]
    };
  }
};
</script>

<style>
</style>