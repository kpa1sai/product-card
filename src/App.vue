<template>
  <body>
    <ProductCard/>
  </body>
</template>

<script>
  import ProductCard from './components/ProductCard.vue';
  export default{
    data(){
    return{
      
    }
  },
  components:{
    ProductCard
  }
  }
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Fuzzy+Bubbles&display=swap');
  * {
    font-family: 'Fuzzy Bubbles';
    box-sizing: border-box;
    padding: 0;
    margin: 0%;
  }
  body{
    background-color: hsl(30, 38%, 92%);
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
</style>
