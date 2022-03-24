<template>
    
    <div class=" text-center">


<li v-for="item in items" :key="item.message">
    {{item.message}}


</li>





</div>
</template>
<script setup>

const items = ([{ message: 'Apple'}, { message: 'shampoo'}, {message: 'frozen pizza'}, {message: 'deoderant'}])




</script>


