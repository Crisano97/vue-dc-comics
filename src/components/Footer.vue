<template>
  <footer>
    <div class="footer-top d-flex justify-content-around">
        <nav>
            
        </nav>
    </div>
    <div class="footer-bottom d-flex justify-content-between">
        <button class="sign-up">SIGN-UP NOW!</button>
        <div class="follow d-flex align-items-center justify-content-center">
            <span>FOLLOW US</span>
            <div class="img-wrapper d-flex justify-content-around w-50 ms-3">
                <img src="../assets/images/footer-facebook.png" alt="">
                <img src="../assets/images/footer-twitter.png" alt="">
                <img src="../assets/images/footer-youtube.png" alt="">
                <img src="../assets/images/footer-pinterest.png" alt="">
                <img src="../assets/images/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style  lang="scss" scoped>

   footer{

        background-image: url('../assets/images/footer-bg.jpg');
        background-size: cover;

     div.footer-top{
        width: 100%;
            height: 25.2rem;

        
        nav{
            width: 75%;
            background-image: url('../assets/images/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: right;
        }
    }

    div.footer-bottom{
        padding: 1.3rem 17rem;
        width: 100%;
        background-color: #303030;

        button.sign-up{
            padding: 10px 10px;
            background-color: transparent;
            border-color: #0282F9;
            color: white;
        }

        div.follow{
            // height: 4rem;
            width: 28rem;

            span{
                color: #0282F9;
                font-weight: bold;
                font-size: 1.3rem;
            }
        }
    }
   }

</style>