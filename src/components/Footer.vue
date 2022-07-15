<template>
  <footer>
    <div class="footer-top">
        <nav>
            
        </nav>
    </div>
    <div class="footer-bottom d-flex justify-content-around">
        <div class="sign-up"></div>
        <div class="follow"></div>
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style  lang="scss">

    div.footer-top{
        width: 100%;
        background-color: gray;

        nav{
            background-color: cadetblue;
            height: 24.3rem;
            width: 25rem;
            margin-left: 17.3rem;
        }
    }

    div.footer-bottom{
        padding: 1.3rem 2rem;
        width: 100%;
        background-color: lightgrey;

        div.sign-up{
            height: 4rem;
            width: 10rem;
            background-color: aqua;
        }

        div.follow{
            height: 4rem;
            width: 45rem;
            background-color: beige;
        }
    }

</style>