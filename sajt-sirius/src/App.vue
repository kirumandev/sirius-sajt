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
height: 100%;
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;


}

@media (min-width: 1024px) {
 
}
</style>
