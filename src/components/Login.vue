<template>
<div class="d1">
<form>
<label for="user">userName:<input type="text" name="userName" id="user"></label><br>
<label for="pass">Password:<input type="password" name="pass" id="pass"></label>
<button type="submit">login</button>
</form>
</div>
</template>
<script>
export default {
    name:'LoginPage',
}
</script>
<style>
.d1{
    background-color: aqua;
    margin:auto;
    width: 50%;
border: 1px solid black;
}
.d1 form label{
    padding: 10px;
    display: grid;
    grid-template-columns: 6fr 6fr;
    font-weight: bold;
}
.d1 form button{
    width: 20%;
    position: relative;
left: 10px;
}
.d1 form button:hover{
    background-color: rgb(6, 45, 45);
}
</style>