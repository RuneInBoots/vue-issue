<template>
  <transition>
    <section>
      <h1>Child component</h1>
      <h2>text inside child</h2>
      <p>child sets background to gold</p>
      <h2>text from parent with slot</h2>
      <slot name="foobar"></slot>
    </section>
  </transition>
</template>

<style lang="css" scoped>
  p {background-color: gold;}
</style>
