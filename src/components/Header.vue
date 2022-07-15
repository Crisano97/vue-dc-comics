<template>
  <header class="d-flex justify-content-around align-items-center">
    <img class="logo" src="../assets/images/dc-logo.png" alt="Dc logo">
    <nav>
        <ul class="d-flex justify-content-between">
            <li>CHARACTERS</li>
            <li>COMICS</li>
            <li>MOVIES</li>
            <li>TV</li>
            <li>GAMES</li>
            <li>COLLECTIBLES</li>
            <li>VIDEOS</li>
            <li>FANS</li>
            <li>NEWS</li>
            <li>SHOP</li>
        </ul>
    </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss"> 
                
        nav{
            width: 50rem;

            ul{
                list-style: none;
                margin: 0;

                li{
                    padding: 3rem 0;
                    border-bottom: 3px solid transparent;
                    &:hover {
                        border-bottom: 3px solid blue;
                    }
                }
            }
        }
    
</style>