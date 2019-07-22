<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <div class="container-fluid">
      <div class="row">
        <div class="col-sm">Grafico</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Graphics",
  props: {
    msg: String
  }
};
</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
