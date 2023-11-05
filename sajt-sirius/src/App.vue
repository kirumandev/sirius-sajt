<script setup>
import Logo from './components/Logo.vue'
import Search from './components/Search.vue'
import More from './components/More.vue'
</script>

<template>


    <div class="wrapper">
      <Logo/>
      <Search/>
      <More/>
    </div>

</template>

<style scoped>

.wrapper{
display: flex;
flex-direction: column;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
