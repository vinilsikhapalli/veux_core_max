<template>
  <div class="align-center">
    <button class="btn btn-info" @click="increment(1)">Increment</button>
    <button class="btn btn-info" @click="decrement(-1)">Decrement</button>
  </div>
</template>

<script>
export default {
  name: 'Count',

  methods:{
    increment(value){
      this.$store.state.count += value;
  //    this.$emit('updateCounter', value)
  //alert(value)
    },
    decrement(value){
//      this.$emit('updateCounter', value);
      this.$store.state.count += value;
     // alert(value)
    }
  }
}
</script>