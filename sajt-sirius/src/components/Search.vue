<script setup>

</script>

<template>
  <form action="">
    <div class="searchIcon-searchbar">
      <img src="../assets/search-icon.svg" alt="">
      <input type="text" placeholder="Введите название секции или кружка" name="search">
    </div>
    <button type="submit">Найти</button>
  </form>

  
</template>

<style lang="scss">
form{
  margin-top: 50px;
  margin-bottom: 20px;
  width: 1060px;
  background-color: #f8f8f8;

  border-radius: 10px;
  
  display: flex;
  justify-content: space-between;

  overflow: hidden;

  button{
    color: white;
    border: none;
    background-color: #ffa404;
    padding: 10px 40px;
  }

  .searchIcon-searchbar{
    display: flex;
    gap: 10px;
    width: 100%;
    margin-left: 15px;

    input{
      border: none;
      color: #c7c7c7;
      width: 100%;
      background-color: #f8f8f8;
    }

    img{
      width: 20px;
    }
  }


}
</style>
