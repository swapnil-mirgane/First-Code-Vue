<template>
<div>
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