<template>
  <footer>

        <div class="footer-top d-flex justify-content-around">
            <div class="wrapper">
                <nav>
                <div class="list-wrapper d-flex flex-wrap justify-content-between w-50 pt-4">
                    <div class="nav-lists" v-for="(navElement, index) in footerNavLinks" :key="index">
                        <h5 class="text-white fw-bold text-uppercase">
                            {{ navElement.title }}
                        </h5>
                        <ul>
                            <li v-for="(navLink, navLinkIndex) in navElement.content" :key="navLinkIndex">
                                <a :href="navLink.url">
                                    {{ navLink.text }}
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
            </div>
        </div>
        <div class="py-4 footer-bottom">
            <div class="container-bottom  d-flex justify-content-between">
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
    data: function(){
        return{
            footerNavLinks: [
                {
                    title: 'dc comics',
                    content: [
                        {
                            text: 'Characters',
                            url: '#',
                        },
                        {
                            text: 'Comics',
                            url: '#',
                        },
                        {
                            text: 'Movies',
                            url: '#',
                        },
                        {
                            text: 'TV',
                            url: '#',
                        },
                        {
                            text: 'Games',
                            url: '#',
                        },
                        {
                            text: 'Videos',
                            url: '#',
                        },
                        {
                            text: 'News',
                            url: '#',
                        },
                    ]
                },
                {
                    title: 'dc',
                    content: [
                        {
                            text: 'Therms Of Use',
                            url: '#',
                        },
                        {
                            text: 'Primary policy (New)',
                            url: '#',
                        },
                        {
                            text: 'Ad Choic',
                            url: '#',
                        },
                        {
                            text: 'Adversting',
                            url: '#',
                        },
                        {
                            text: 'Jobs',
                            url: '#',
                        },
                        {
                            text: 'Subscriptions',
                            url: '#',
                        },
                        {
                            text: 'Talent Workshops',
                            url: '#',
                        },
                        {
                            text: 'CPSC Certificates',
                            url: '#',
                        },
                        {
                            text: 'Ratings',
                            url: '#',
                        },
                        {
                            text: 'Shop Help',
                            url: '#',
                        },
                        {
                            text: 'Contact Us',
                            url: '#',
                        },
                        {
                            text: 'News',
                            url: '#',
                        },
                    ]
                },
                {
                    title: 'sites',
                    content: [
                        {
                            text: 'DC',
                            url: '#',
                        },
                        {
                            text: 'MAD Magazine',
                            url: '#',
                        },
                        {
                            text: 'DC Kids',
                            url: '#',
                        },
                        {
                            text: 'DC Universe',
                            url: '#',
                        },
                        {
                            text: 'DC Power Visa',
                            url: '#',
                        },
                    ]
                },
                {
                    title: 'shop',
                    content: [
                        {
                            text: 'Shop DC',
                            url: '#',
                        },
                        {
                            text: 'Shop DC Collectibles',
                            url: '#',
                        },
                    ]
                },
            ]
        }
    }
}
</script>

<style  lang="scss" scoped>

   footer{

        background-image: url('../assets/images/footer-bg.jpg');
        background-size: cover;

        .wrapper{
            width: 80%;
            margin: 0 auto;
        }

        nav{
            padding: 0.7rem;
            width: 90%;
            margin: 0 auto;
            background-image: url('../assets/images/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-position: right;

            ul{
                list-style: none;
                padding: 0 0.2rem;
                margin-right: 2rem;
                
                a{
                    text-decoration: none;
                    color: gray;
                    font-size: 0.8rem;
                }            
            }
        }

    div.footer-bottom{
        background-color: #303030;

        .container-bottom{
            width: 70%;
            margin: 0 auto;
        }

        button.sign-up{
            padding: 0 10px;
            background-color: transparent;
            border-color: #0282F9;
            color: white;
            font-weight: bold;
        }

        div.follow{
            width: 30rem;

            span{
                color: #0282F9;
                font-weight: bold;
                font-size: 1.3rem;
            }

            img{
                width: 1.7rem;
            }
        }
    }
   }

</style>