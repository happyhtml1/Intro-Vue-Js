<template>
  <div id="app">

    <img alt="Vue logo" src="./assets/logo.png">
    <Estudiante/>
    <Profesional/>
    <Curso infoCurso="Información del Curso" msg="FrontEnd" msg2="Gen 3" msg3="13-01-2020"/>
    <link href="https://fonts.googleapis.com/css?family=Bellota|Francois+One&display=swap" rel="stylesheet">

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
  background-image: url('./assets/imagen2.jpg');
  background-size: cover;
  font-family: 'Bellota', cursive;

  
}
hr{
  border-color: red ;
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
