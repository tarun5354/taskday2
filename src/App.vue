<template>

  
  <HeadersComponents/>
  
  
  <HelloWorld msg="Welcome to Mantra" />
  <HomeComponent/>
  <FooterComponent/>
  
  
  </template>
  
  <script>
  import HelloWorld from './components/HelloWorld.vue';
  import HomeComponent from './components/HomeComponent.vue';
  import FooterComponent from './components/FooterComponent.vue'
  import HeadersComponents from './components/HeadersComponents.vue';
  export default {
      name: 'App',
      components: {
          HomeComponent,
          HelloWorld,
          FooterComponent,
          HeadersComponents
      }
  }
  </script>
  
  <style>
  #app {
      font-family: Avenir, Helvetica, Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      text-align: center;
      color: #2c3e50;
      margin-top: 60px;
  }
  
  
  
  </style>
  