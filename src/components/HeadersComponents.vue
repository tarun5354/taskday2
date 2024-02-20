<template>
    <div class="headers">
  <ul>
    <li><img alt="Vue logo" src="../assets/logo.png"></li>
      <li>Home</li>
      
      <li>Products</li>
      
      <li>marketing</li>
      <li>services</li>
      <li> connect</li>
      <li> settings</li>
      <li> about us</li>
  </ul>
  <div><input text="search" placeholder="search here"/></div>
</div>

</template>

<script>
export default{
    name:'HeadersComponents'
}


</script>
<style>
ul {

display: flex;

align-items: center;

}

li {

margin: 0px 20px;
padding: 5px;
color: green;
list-style-type: none;

}
li img{
width:50px;
}
.headers{
display: flex;
justify-content: space-between;

}



</style>