<template>
  <main>
    <div class="content"></div>
    <div class="main-nav"></div>
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
        height: 8rem;
    }

    div.content {
        background-color: #1C1C1C;
    }
    div.main-nav{
        background-color: $mainBgColor;
    }
</style>