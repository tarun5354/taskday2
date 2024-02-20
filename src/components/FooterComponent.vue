<template>
    <div id="pages">
        <h1 id="deatails-heading"> Details</h1>
    <input type="text" placeholder="employee-id"/><br>
    <input type="password" placeholder="password"/><br>
    <button id=button3>submit</button>

</div>



</template>

<script>
 export default{
    name: 'FooterComponent'
 }
</script>
<style>
#pages{
    background-color: rgb(175, 245, 245);
    width:500px;
    margin:20px auto;
    text-align: center;
    box-shadow: 10px 10px 8px #90bcc7;
    border-radius: 20px;
}
input{
    margin: 20px;
    width:100px;
    height: 25px;
    color: black;
}
#deatails-heading{
    color: aliceblue;
    margin-top: 50px;
    padding-top: 20px;
}
#button3{
    font-size: 20px;
    padding: 17px;
    width: auto;
    margin:20px;
    border-radius:12px;
    box-shadow: 5px;
    color: rgb(227, 239, 247);
    font-weight: bold;
    border-radius:20px;
    border: 1px springgreen none;
    background-color: rgba(0, 189, 126, 0.884);
}


</style>