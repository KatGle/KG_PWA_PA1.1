<template>
    <div>
        <TopNav/>
        <h1>O nas</h1>
        <h2>Strona o nas</h2>
        <button @click="showInfo">Kliknij mnie</button>
    </div>
</template>

<script>
import TopNav from '/components/nav/TopNav.vue'
export default {
  name: 'Button',
  components: { TopNav },

  methods: {
    showInfo: () => {
        console.log('Witaj w konsoli')
        alert('Witaj')
    }
  }
}
</script>
<style scoped>
h1, h2 {
  color:rgb(46, 2, 106);
  padding: 10px 10px;
}
</style>