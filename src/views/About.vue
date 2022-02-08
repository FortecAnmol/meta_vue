<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
export default {
  name: 'About',
  props: {
    msg: String
  },
  metaInfo() {
        return { 
            title: "About",
            meta: [
                { name: 'description', content:  'About description'},
                {name: 'robots', content: 'index,follow'} 
            ]
      }
    }
}
</script>