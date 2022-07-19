<template>
<div class="abc">
 <h1>This Count Form Add Component</h1> 
 <button @click="addition++">add count is={{addition}}</button>  
</div>
</template>
<script>
export default {
    name:'AddCount',
    data() {
        return {
            addition:0,
        }
    },
}
</script> 
<style>
h1{
    color: rgb(9, 18, 0);
}
button{
    color: brown;
    background-color: aqua;
    border-radius: 20px;
    font-size: larger;
    font-weight: bold;
}
div .abc{
    border: 1px solid black;
    background-image:radial-gradient(rgb(230, 101, 101), rgb(244, 244, 127), rgb(228, 96, 118));
    margin-bottom: 100px;
}
</style>