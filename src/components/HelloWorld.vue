<template lang="pug">
    .hello
        h1 {{ msg }}
        p
            | For guide and recipes on how to configure / customize this project,
            br
            | check out the
            |
            a(href="https://github.com/vuejs/vue-cli/tree/dev/docs", target="_blank") vue-cli documentation
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
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
