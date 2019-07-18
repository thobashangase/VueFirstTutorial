<!-- Development version with useful console warnings -->
<script src = "https://cdn.jsdelivr.net/npm/vue/dist/vue.js" ></script>

<template>
  <div id="app">
    {{ message }}
  </div>
</template>

<script>
    var app = new Vue({
        el: '#app',
        data: {
          message: 'Hello Vue!'
        }
    })
</script>