
<template>
  <div class="hello">
    <div class="logo">
      <p>Welcome Use supernovayo</p>
      <br>
    </div>
    <ul>
      <li><a href="#/index">to index page</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
    }
  }
}
</script>
<style scoped lang='less'>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
  text-align: center;
}
a {
  color: #42b983;
}
.logo{
  text-align: center;
  img{
    width: 125px;
  }
}
</style>
