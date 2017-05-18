<template>
  <section id="app">
    <h1>parent component</h1>
    <h2>text inside parent</h2>
    <p>parent sets color to crimson</p>
    <child-component>
      <p slot="foobar"> text from inside parent trough slot</p>
    </child-component>
   </section>
  </section>
</template>

<script>
import childComponent from './components/childComponent.vue';

export default {
  components: {childComponent}
}
</script>

<style scoped>
  p {color: crimson;}
</style>
