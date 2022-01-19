<template>
  <header>
    <h1>bell e buon</h1>
    <div class="container center">
      <div class="left">
        <img src="..\assets\img\dc-logo.png" alt="">
      </div>
      <div class="right">
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
  }

  .right {
    display: flex;
    align-items: center;
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
    }
  }
</style>