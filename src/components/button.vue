<template>
    <div id="button">
     <b-button v-on:click = "result" variant="danger">Button</b-button>
     <input v-model="input" placeholder="type a location">
    <h1>{{input}}</h1>
    </div>
</template>

<script>
export default {
      methods: {
    result: function() {
        console.log('test')
    }
      }
    
}
</script>