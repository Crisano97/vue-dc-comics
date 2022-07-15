<template>
  <header class="d-flex justify-content-around align-items-center">
    <img class="logo" src="../assets/images/dc-logo.png" alt="Dc logo">
    <nav>
        <ul class="d-flex justify-content-between">
            <li class="text-uppercase" v-for="(link, index) in headerNavLinks" :key="index">
                {{ link }}
            </li>
            
        </ul>
    </nav>
  </header>
</template>

<script>
export default {
    data: function(){
       return{
         headerNavLinks: ['characters', 'comics', 'movies', 'tv', 'games', 'collectibles', 'videos', 'fans', 'news', 'shop']
       }
    }
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