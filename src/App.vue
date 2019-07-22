<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <Graphics msg="Gráfico de controle de clientes"/>
  </div>
</template>

<script>
import Graphics from './components/Graphics.vue'
import Dados from './services/dados'

export default {
  name: 'app',
  components: {
    Graphics
  },
  data() {},
  mounted() {
    // Dados.getAll().then(answer => {
    //   console.log(answer)
    // })
  }
}
</script>

<style>
#app {
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
