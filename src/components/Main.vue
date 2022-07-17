<template>
  <main>
    <div class="content">
        <span>-->Content goes here</span>
    </div>
    <div class="main-nav">
        <div class="link-wrapper d-flex justify-content-between p-4 align-items-center">
            <div class="link" v-for="(link, index) in mainLinks" :key="index">
                <img class="link-img" :src="link.src" :alt="link.text">
                <span class="text-uppercase ms-2"> {{ link.text }} </span>
            </div>
            
        </div>
    </div>
  </main>
</template>

<script>
export default {
data: function(){
       return{
         mainLinks: [
            {
                text: 'digital comics',
                src: '/images/buy-comics-digital-comics.png'
            },
            {
                text: 'dc merchandise',
                src: '/images/buy-comics-merchandise.png'
            },
            {
                text: 'subscription',
                src: '/images/buy-comics-subscriptions.png'
            },
            {
                text: 'comic shop locator',
                src: '/images/buy-comics-shop-locator.png'
            },
            {
                text: 'dc power visa',
                src: '/images/buy-dc-power-visa.svg'
            },
         ]
       }
    }
}
</script>

<style  lang="scss">
    @import "../styles/variables.scss";

    div{
        width: 100%;
        // height: 8rem;
    }

    div.content {
        background-color: #1C1C1C;
        color: white;
        padding: 3rem 16rem;

        span{
            font-size: 1.7rem;
            font-weight: bold;
        }
    }
    div.main-nav{
        background-color: $mainBgColor;
        padding: 1rem 17rem;

        div.link{
            height: fit-content;
            width: fit-content;
            color: white;

            .link-img{
                width: 3rem;
            }
        }
    }
</style>