<template>
  <iPhone msg="Welcome to Your Vue.js App"/>
</template>

<script>
import iPhone from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    iPhone
  }
}
</script>

<style>
#app {
  h2 {
    color: orange;
    padding: 20px;
    ;
}

p { color: black;

}


h1 {
    color: pink;
    font-size: 2em;
    font-family: Georgia, 'Times New Roman', Times, serif;
    border-bottom: 20px dotted orange;
    text-wrap: nowrap;
    
}

h3 {
    color:blueviolet
}
}
</style>
