<template>
  <div class="section-wrapper">
    <div class="text-button">
      <p>Узнай какое занятие подойдет вашему ребенку</p>
      <button>Узнать</button>
    </div>
    <div class="girls-wrapper">
      <img id="first" src="../assets/girl-with-background.svg" alt="">
      <img id="second" src="../assets/girl.svg" alt="">
      <img id="third" src="../assets/girl.svg" alt="">
    </div>
  </div>
</template>

<style lang="scss">
.section-wrapper{
  width: 1060px;
  height: 180px;
  padding: 0 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  border-radius: 20px;
  box-shadow: 5px 5px 25px #79797926;
  
  .text-button{
    width: 200px;

    p{
      font-weight: 800;
    }

    button{
      color: white;
      border: none;
      background-color: #ffa404;
      border-radius: 10px;
      padding: 10px 40px;
    }
  }

  .girls-wrapper{

    display: flex;
    align-items: center;
    gap: 10px;

   #first{
    height: 157px;
   }

   #second{
    height: 55px;
    
   }

   #third{
    height: 93px;
    transform: scaleX(-1);
    margin-left: 50px;
   }
  }
}
</style>
