<template>
  <main>
    <div class="container dark">
      <span>Contents goes here</span>
    </div>
    <div class="container blue">
      <div class="box prodotto">
        <div class="icona">
          <img src="..\\assets\img\buy-comics-digital-comics.png" alt="Digital comics">
        </div>
        <div class="link">
          <a href="">Digital comics</a>
        </div>
      </div>
      <div class="box prodotto">
        <div class="icona">
          <img src="..\\assets\img\buy-comics-merchandise.png" alt="dc Merchandise">
        </div>
        <div class="link">
          <a href="">dc Merchandise</a>
          
        </div>
      </div>
      <div class="box prodotto">
        <div class="icona">
          <img src="..\\assets\img\buy-comics-shop-locator.png" alt="comic shop locator">
        </div>
        <div class="link">
          <a href="">comic shop locator</a>
        </div>
      </div>
      <div class="box prodotto">
        <div class="icona">
          <img src="..\\assets\img\buy-comics-subscriptions.png" alt="subscription">
        </div>
        <div class="link">
          <a href="">
            subscription
          </a>
        </div>
      </div>
      <div class="box prodotto">
        <div class="icona">
          <img src="..\\assets\img\buy-comics-merchandise.png" alt="dc power visa">
        </div>
        <div class="link">
          <a href="">
            dc power visa
          </a>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  // .container {
  //   background-color: black;
  //   color: white;
  //   margin-left: 4em;
  //   margin-right: 4em;
  //   //height: 10vh;
  // }

  .box {
    display: flex;
    color: white;
    justify-content: space-between;
    margin: 1em;
  }

  .dark {
    background-color: black;
    height: 10vh;
    color: white;
    padding: 1em;
    padding-left: 4em;
    padding-right: 4em;
  }

  .blue {
    background-color: #0072cf;
    padding-left: 4em;
    padding-right: 4em;
    height: 15vh;
    display: flex;
    align-items: center;
    justify-content: center;
    a {
      color: white;
      text-decoration: none;
    }
  }

  .icona {
    img {
      width: 3em;
    }
  }

  .link {
    align-self: center;
  }


</style>