<template>
    <ul>
       
        <li v-for="books in book">
             {{ books.title }}: {{books.author}}
             </li>

    </ul>
</template>


<script>
export default {
    name: 'BookItem',
    props: ['book']
    
}
</script>



<style  scoped>
li {
   display: block;
   margin: 0 10px;
}
</style>