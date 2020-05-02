<template>
  <div>
    <center>
      <h1>{{ message }}</h1>
    </center>

    <img src="src/views/images/Corgis.jpg" alt="Corgis">
  </div>
</template>

<script>
export default {
  data() {
    return {
      message: "Corgis are the best!"
    };
  }
};
</script>

<style scoped>
</style>