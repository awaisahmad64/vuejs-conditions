<template>
<div>
    <h2 v-if="show">This if statement rendering ture.</h2>
    <h2 v-else >This else statement rendering false.</h2>
    <button v-on:click="display">ToggleFuntion</button>
</div>
</template>
<script>
export default {
   name: 'ifelse',data(){
       return {show:true}
   },methods:{
       display(){
           this.show=!this.show
       }
   }
}
</script>
