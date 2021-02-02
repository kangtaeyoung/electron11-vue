<template>
  <div id="app">
   
    <router-view></router-view>
  </div>
</template>

<script>
 

  export default {
    name: 'my-project',
     components: {
       
   },
   data() {
      return {
        items :  [
          {
            name: "File",
            menu: [{ name: "Open"}, {name: "New Window"}, {name: "Exit"}]
          },
          {
            name: "Edit",
            menu: [{ name: "Cut"}, {name: "Copy"}, {name: "Paste"}]
          }
        ]
      }
   
   }
  }
</script>

<style>
  /* CSS */
</style>
