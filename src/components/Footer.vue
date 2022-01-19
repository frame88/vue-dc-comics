<template>
  <footer>
    <!-- {{ title }} -->
    <div class="container">
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
  .container {
    display: flex;
    background-image: url("../assets/img/footer-bg.jpg");
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
</style>