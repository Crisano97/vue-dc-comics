<template>
  <main>
    <div class="content">
        <span>-->Content goes here</span>
    </div>
    <div class="main-nav">
        <div class="link-wrapper d-flex justify-content-between p-4">
            <div class="link"></div>
            <div class="link"></div>
            <div class="link"></div>
            <div class="link"></div>
            <div class="link"></div>
        </div>
    </div>
  </main>
</template>

<script>
export default {

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
        padding: 3rem 17.3rem;

        span{
            font-size: 1.7rem;
            font-weight: bold;
        }
    }
    div.main-nav{
        background-color: $mainBgColor;
        padding: 1rem 17rem;

        div.link{
            height: 4rem;
            width: 10rem;
            background-color: gray;
        }
    }
</style>