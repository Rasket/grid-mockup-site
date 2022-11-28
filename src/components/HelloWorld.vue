<template lang="pug">
.root
  NavBar
  div.main
    SideBar
    MainContent
</template>

<script>
import NavBar from './NavBar.vue'
import SideBar from './SideBar.vue'
import MainContent from './MainContent.vue'




export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    NavBar,
    SideBar,
    MainContent
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.main {
  display: flex;
}

@import "./color.scss";
.root {
  width: 100vw;
  height: 100vh;
  background: $celeste;
}

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
