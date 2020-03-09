<template>
  <div class="hello">
    <h1>{{ InfoProf }}</h1>
    <h3>{{ trabajoActual }}</h3>
    <h3>{{ profesion }}</h3>
    <h3>{{ fechaInicio }}</h3>
   
  </div>
</template>

<script>
export default {
  name: 'Profesional',
  props: {
    msg: String
  },
  data(){
      return{
          InfoProf: "Información Profesional",
          trabajoActual: "Cesante",
          profesion: "Administrador de empresas",
          fechaInicio: "13-01-2020"
      }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
