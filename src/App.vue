<template>
<div>
  <ComponentBasics title="hello this a prop"/>
</div>
</template>

<script>
import ComponentBasics from './components/ComponentBasics.vue'

export default{
  name: 'App',

  components: {
    ComponentBasics,
  },
}
</script>

<style>
.cbasics{
  top: 50%;
  left: 25%;
  display: flex;
  justify-content: center;
  background-color: chocolate;
}
</style>

