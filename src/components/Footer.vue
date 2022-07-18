<template>
  <footer>
    <div class="wrapper">
        <div class="footer-top d-flex justify-content-around">
            <nav>
                <div class="list-wrapper d-flex flex-wrap">
                    <ul>
                    <li><a class="text-white fs-4 fw-bold" href="#">DC COMICS</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <ul>
                    <li><a class="text-white fs-4 fw-bold" href="#">DC</a></li>
                    <li><a href="#">Therms Of Use</a></li>
                    <li><a href="#">Primary policy (New)</a></li>
                    <li><a href="#">Ad Choice</a></li>
                    <li><a href="#">Adversting</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscriptions</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                    <li><a href="#">Talent Workshops</a></li>
                </ul>
                <ul>
                    <li><a class="text-white fs-4 fw-bold" href="#">DC COMICS</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <ul>
                    <li><a class="text-white fs-4 fw-bold" href="#">DC COMICS</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
                </div>
            </nav>
        </div>
        <div class="py-4 footer-bottom d-flex justify-content-between">
            <button class="sign-up">SIGN-UP NOW!</button>
            <div class="follow d-flex align-items-center justify-content-end">
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
            // height: 27.5rem;

        
        nav{
            padding: 0.7rem;
            width: 80%;
            background-image: url('../assets/images/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: right;

            div.list-wrapper {
                width: 33rem;

                ul{
                list-style: none;
                padding: 0 0.2rem;
                
                a{
                    text-decoration: none;
                    color: gray;
                    font-size: 0.8rem;
                }
                
            }
            }
        }
    }

    div.footer-bottom{
        padding: 1rem 10rem;
        width: 100%;
        background-color: #303030;

        button.sign-up{
            padding: 0 10px;
            background-color: transparent;
            border-color: #0282F9;
            color: white;
            font-weight: bold;
        }

        div.follow{
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