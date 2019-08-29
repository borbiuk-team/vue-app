<template>
  <div class="main">
    <h1>{{ msg }}</h1>
    <h3>References</h3>
    <ul>
      <li>
        <a href="https://github.com/borbiuk-team/vue-app" rel="noopener"
          >repository</a
        >
      </li>
    </ul>
    <ul>
      <li>
        <a href="https://github.com/borbiuk-team" target="_blank" rel="noopener"
          >organization</a
        >
      </li>
      <li>
        <a href="https://github.com/borbiuk" target="_blank" rel="noopener"
          >creator</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "main",
  props: {
    msg: String
  }
};
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
