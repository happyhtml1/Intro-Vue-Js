<template>
  <div class="hello">
<hr>
    <h1>{{ InfoPersonal }}</h1>
    <h3>{{ Nombre }}</h3>
    <h3>{{ Rut }}</h3>
   <hr>
  </div>
</template>

<script>
export default {
  name: 'Estudiante',
  props: {
    msg: String
  },
  data(){
      return{
          InfoPersonal: "Información Personal",
          Nombre: "Ignacia Valenzuela",
          Rut: "18.023.473-K"
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
