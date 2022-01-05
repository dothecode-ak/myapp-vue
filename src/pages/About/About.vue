<template>
  <fragment>
    <h1>Anil Yadav</h1>
    <p>{{msg}}</p>
    <button v-on:click="data(100)" v-if="show">Click me</button>
      </fragment>
</template>
<script>
export default {
    name:'App',
    props:{
        msg:String
    },
    methods: {
      data(d)
      {
        alert(d)
      }
    },
    data()
    {
return {show:true}
    }
  
}
</script>