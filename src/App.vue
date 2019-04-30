
<template>
  <div id="app"> 
  <HelloWorld msg="Zaczynamy pisać w Vue.js!"/>  
  <HelloAgain /> 
  </div>
  </template>
  <script>
  import HelloWorld from './components/HelloWorld.vue';
  import HelloAgain from './components/HelloAgain.vue'
  export default 
  { 
  name: 'app',  components: {    HelloWorld, HelloAgain  
  }}
  </script>
  <style>
  #app {
  font-family:
  sans-serif;
  text-align: center;
  color: #2c3e50; 
  margin-top: 60px;}
  </style>