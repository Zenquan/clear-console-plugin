<template>
  <div class="hello">
    <Button>点击</Button>
  </div>
</template>

<script>
import Button from 'element-ui/lib/button'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    Button
  },
  mounted() {
    console.log('111>>>', 111);
    console.log('err>>>', 111);
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