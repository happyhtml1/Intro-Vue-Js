<template>
  <div class="hello">
      <h1>{{ infoCurso }}</h1>
    <h3>{{ msg }}</h3>
    <h3>{{ msg2 }}</h3>
    <h3>{{ msg3 }}</h3>
   <hr>
  </div>
</template>

<script>
export default {
  name: 'Curso',
  props: {
    infoCurso: String,
    msg: String,
    msg2: String,
    msg3: Date
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
