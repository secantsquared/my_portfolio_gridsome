<template>
  <div class="container">
    <h2>Portfolio</h2>
  </div>
</template>

<script>
export default {
  name: 'Portfolio'
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Geostar&display=swap');
div.container {
  max-width: 80vw;
  margin: 0 auto;
  height: 100vh;
  background: #252a34;
  border-radius: 40px;
  z-index: -1;
  padding: 20px;
}

h2 {
  text-align: center;
  font-size: 7rem;
  letter-spacing: 2px;
  color: #eaeaea;
  font-family: 'Geostar', cursive;
}

div.top {
  width: 100%;
  height: 350px;
  background: #252a34;
}
</style>
