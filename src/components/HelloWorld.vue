<template>
  <div>
    <h1>{{ msg }}</h1>
    <h2> Hello Tarun</h2>
  
  <p>Hey we are starting our application vue3 in <span id=Big>visual studio </span></p> 
  </div>
  </template>
   
  
  <script>
  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  
  }
  #Big{
    font-size:2rem;
    color: black;
  }
  p{
    color: rgb(189, 140, 235);
  }
  </style>
  