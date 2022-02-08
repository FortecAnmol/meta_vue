<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
export default {
  name: 'Home',
  props: {
    msg: String
  },
  metaInfo() {
        return { 
            title: "Home title",
            meta: [
                { name: 'description', content:  'Home description'},
            ]
      }
    }
}
</script>
