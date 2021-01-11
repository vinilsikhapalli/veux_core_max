<template>
    <p>counter is:- {{ count }}</p>
</template>
<script>
export default {
    name: 'Result',
   // props:['count'],

   computed:{
       count (){
         return this.$store.state.count;
       }
   }
}
</script>