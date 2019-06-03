<template>
  <div class="hello">
   <div v-bind:key="todo.id" v-for="todo in todos">
      <h3>{{todo.title}}</h3>
   </div>
  </div>
</template>

<script>
export default {
  name: 'Todos',
  props: ['todos']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
