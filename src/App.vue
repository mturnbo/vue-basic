<template>
  <div id="app">
    <h2>{{ appName }}</h2>
  </div>
</template>

<script>
  export default {
    name: 'app',
    el: '#app',
    data: () => ({
      appName: 'Vue Basic'
    }),
  }
</script>
