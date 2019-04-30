
<template>
  <div class="hello">  
  <h1>{{ msg }}</h1> 
  <p>      tu jest Wiesi Component.    </p> 
  </div>
  </template>
  <script>
  export default 
  {  name: 'HelloWorld', 
  props: 
  {    msg: String  }






}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
p {
  font-size: 20px;
  font-weight: 600;
  text-align: center;
}
</style>