<template>
  <header>
    <div class="container center">
      <div class="left-header">
        <img src="..\assets\img\dc-logo.png" alt="">
      </div>
      <div class="right-header">
        <ul>
      <li>
        <a href="">Characters</a>
      </li>
      <li>
        <a href="">Comics</a>
      </li>
      <li>
        <a href="">Movies</a>
      </li>
      <li>
        <a href="">Tv</a>
      </li>
      <li>
        <a href="">Games</a>
      </li>
      <li>
        <a href="">Collectibles</a>
      </li>
      <li>
        <a href="">Videos</a>
      </li>
      <li>
        <a href="">Fans</a>
      </li>
      <li>
        <a href="">News</a>
      </li>
      <li>
        <a href="">Shop</a>
      </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  
  .container {
    display: flex;
    background-color: aqua;
  }  

  .left-header {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 20%;
  }
  
  .right-header {
    width: 80%;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  ul {
    text-transform: uppercase;
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    li a {
      display: block;
      text-decoration: none;
      margin: 0.3em;
      padding-bottom: 3em;
      padding-top: 3em;
      color: gray;
      font-weight: bold;
      &:hover,
      &:active {
        border-bottom: 4px solid blue;
        color: blue;
      }
    }
  }
</style>