<template>
  <footer>
    <!-- {{ title }} -->
    <div class="container footer-top">
      <div class="col-1">
        <div class="top">
          <h1>Dc Comics</h1>
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
                    <a href="">Video</a>
                </li>
                <li>
                    <a href="">News</a>
                </li>
            </ul>
        </div>
        <div class="bottom">
          <h1>shop</h1>
          <ul>
            <li>
              <a href="">shop dc</a>
            </li>
            <li>
              <a href="">shop dc collectibles</a>
            </li>
          </ul>
        </div>
      </div>
      <div class="col-2">
        <h1>Dc</h1>
        <ul>
            <li>
                <a href="">Therms of use</a>
            </li>
            <li>
                <a href="">Privacy Policy</a>
            </li>
            <li>
                <a href="">Ad choises</a>
            </li>
            <li>
                <a href="">Advertising</a>
            </li>
            <li>
                <a href="">Jobs</a>
            </li>
            <li>
                <a href="">Subscriptions</a>
            </li>
            <li>
                <a href="">Talent Workshops</a>
            </li>
        </ul>
      </div>
      <div class="col-3">
        <h1>Sites</h1>
        <ul>
            <li>
                <a href="">DC</a>
            </li>
            <li>
                <a href="">MAD Magazine</a>
            </li>
            <li>
                 <a href="">DC kids</a>
            </li>
            <li>
                <a href="">DC universe</a>
            </li>
             <li>
                 <a href="">DC Power Visa</a>
            </li>
         </ul>
      </div>
      <div class="col-4">
        <img src="..\assets\img\dc-logo-bg.png" alt="">
      </div>
    </div>


     <!-- SECONDA PARTE FOOTER -->
    <div class="container contatti">
      <div class="sign">
        <a href="">sign-up now!</a>
      </div>
      <div class="social">
        <span>follow us</span>
        <a href=""><img src="..\assets\img\footer-facebook.png" alt="social logo"></a>
        <a href=""><img src="..\assets\img\footer-periscope.png" alt="social logo"></a>
        <a href=""><img src="..\assets\img\footer-pinterest.png" alt="social logo"></a>
        <a href=""><img src="..\assets\img\footer-twitter.png" alt="social logo"></a>
        <a href=""><img src="..\assets\img\footer-youtube.png" alt="social logo"></a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: 'Main',
    data() {
      return {
        title: 'Lorem'
      }
    }
}
</script>

<style lang="scss" scoped>
  .footer-top {
    height: 55vh;
    display: flex;
    background-image: url("../assets/img/footer-bg.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: 100%;
  }

  h1 {
    color: white;
    font-size: 120%;
    padding-top: 1em;
    padding-bottom: 1em;

  }

  ul {
    li {
      list-style: none;
      a {
        color: gray;
        text-decoration: none;
        text-transform: capitalize;
      }
    }
  }


  .col-1, .col-2, .col-3 {
    padding-left: 4em;
    padding-top: 2em;
  }

  .col-1 .bottom {
    padding-top: 2em;
  }

  // dA RIVEDERE 
    .col-4 {
      padding-right: 4em;
      margin-left: 12em;
      position: relative;
      img {
        position: absolute;
        top: -25px;
        bottom: 25px;

      }
    }
  
  .contatti {
    background-color: rgb(59, 59, 59);
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 10vh;
  }

  .sign, .social {
    span {
      color: #0072cf;
      font-weight: bold;
      align-self: center;
    }
  }

  .sign {
    padding-left: 4em;
    a {
      color: white;
      border: 3px solid #0072cf;
      padding: 0.5em;
      text-decoration: none;
    }
  }

  .social {
    padding-right: 4em;
    a, span {
      margin: 0.3em;
    }
  }




</style>