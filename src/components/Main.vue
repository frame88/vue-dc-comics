<template>
  <main>
      <div class="top">
          <div class="jumbotron">
              <div class="container relative">
                  <div class="title">
                    <h2>Current Series</h2>
                  </div>
              </div>
          </div>
          
          <div class="top-b">
              <div class="container">
              <div class="products">
                  <Product
                  v-for="(product, index) in products" :key="index"
                  :src="product.thumb"
                  :alt="product.series"
                  :series="product.series"
                  />
              </div>
          </div>
          </div>
      </div>
      <div class="bottom">
          <div class="container">
              <ul>
                  <li>
                      <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
                      <span>Digital comics</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-merchandise.png" alt="Digital comics">
                      <span>dc merchandise</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-subscriptions.png" alt="Digital comics">
                      <span>subscription</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-comics-shop-locator.png" alt="Digital comics">
                      <span>comic shop locator</span>
                  </li>
                  <li>
                      <img src="../assets/img/buy-dc-power-visa.svg" alt="Digital comics">
                      <span>dc power visa</span>
                  </li>
              </ul>
          </div>
      </div>
  </main>
</template>

<script>
import Product from './Product.vue'
export default {
    name:'Main',
    components: {
        Product,
    },
    data (){
        return{
            products: [
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
                            "price": "$19.99",
                            "series": "Action Comics",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
                            "price": "$3.99",
                            "series": "American Vampire 1976",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
                            "price": "$16.99",
                            "series": "Aquaman",
                            "type": "graphic novel"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
                            "price": "$2.99",
                            "series": "Batgirl",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                            "price": "$3.99",
                            "series": "Batman",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
                            "price": "$2.99",
                            "series": "Batman Beyond",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
                            "price": "$3.99",
                            "series": "Batman/Superman",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
                            "price": "$4.99",
                            "series": "Batman/Superman Annual",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
                            "price": "$5.99",
                            "series": "Batman: The Joker War Zone",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
                            "price": "$6.99",
                            "series": "Batman: Three Jokers",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
                            "price": "$4.99",
                            "series": "Batman: White Knight Presents: Harley Quinn",
                            "type": "comic book"
                        },
                        {
                            "thumb": "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
                            "price": "$16.99",
                            "series": "Catwoman",
                            "type": "graphic novel"
                        }
                ]
            }
    }
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/partials/_variables.scss";

    .jumbotron{
        width: 100%;
        height: 400px;
        background-image: url(../assets/img/jumbotron.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        .container{
            height: 100%;
        }
        .title{
            position: absolute;
            bottom: -25px;
            left: 0;
            background-color: $bluemain;
            padding: 10px;
            width: 250px;
            text-align: center;
            h2{
                color: white;
                text-transform: uppercase;
            }
        }
    }
    .top-b{
        background-color: #303030;
        .products{
        display: flex;
        justify-content: space-between;
        flex-wrap: wrap;
        padding: 30px;
    }
    }
    
    .bottom{
        background-color: $bluemain;
        height: 170px;
        display: flex;
        align-items: center;
        ul{
            list-style: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
            li{
                display: flex;
                align-items: center;
                gap: 8px;
                height: 40px;
            }
            li span{
                color: white;
                text-transform: uppercase;
            }
            li img{
                height: 100%;
            }
        }
    }
</style>