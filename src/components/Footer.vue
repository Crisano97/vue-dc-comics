<template>
  <footer>
    <div class="footer-top"></div>
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
        height: 25rem;
        background-color: gray;
    }
    div.footer-bottom{
        padding: 1.3rem;
        width: 100%;
        height: 7.5rem;
        background-color: lightgrey;

        div.sign-up{
            height: 5rem;
            width: 5rem;
            background-color: aqua;
        }

        div.follow{
            height: 5rem;
            width: 50rem;
            background-color: beige;
        }
    }

</style>