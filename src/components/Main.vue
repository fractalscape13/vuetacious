<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Stuff & Things</h3>
    <ul>
      <li><a href="https://www.linkedin.com/in/josephwangemann/" target="_blank" rel="noopener">LinkedIn</a></li>
      <li><a href="https://github.com/fractalscape13" target="_blank" rel="noopener">Github</a></li>
      <li><a href="https://soundcloud.com/j-w-32" target="_blank" rel="noopener">Soundcloud</a></li>
      <li><a href="https://twitter.com/fractalscape13" target="_blank" rel="noopener">Twitter</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Main',
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
  color: #4285dd;
}
</style>
