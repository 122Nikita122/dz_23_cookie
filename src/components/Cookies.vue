<template>
  <div >
    <h1>Столько то раз нажал на печеньку {{count}}</h1>
    <img class="cookie"  src="../assets/cookie.jpg"  v-on:click="counter">    
  </div>
</template>

<script>

export default {
  name: 'Cookies',
    data(){
      return {
        count: 0,         
      };
    },  
  methods:{
    counter(){
      return this.count++
    }
  }

}
</script>

<style>
.cookie {
  height: 200px;  
}
</style>