<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Engenheira de software graduada na ufms.
    </p>
  <div>Gosto de me movimentar, sempre saindo da zona de conforto. Considero o desenvolvimento uma arte.</div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
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
