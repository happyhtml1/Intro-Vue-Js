<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Estudiante/>
    <Profesional/>
    <Curso infoCurso="Información del Curso" msg="FrontEnd" msg2="Gen 3" msg3="13-01-2020"/>
  </div>
</template>

<script>
import Curso from './components/Curso.vue'
import Profesional from './components/Profesional.vue'
import Estudiante from './components/Estudiante.vue'

export default {
  name: 'App',
  components: {
    Curso,
    Profesional,
    Estudiante
  }
}
</script>

<style>
body{
  background-image: url(../public/imagen1.jpg);
  background-size: cover;
  
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
