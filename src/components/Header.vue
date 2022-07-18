<template>
  <header class="py-3 bg-white">
    <div class="wrapper d-flex justify-content-around align-items-center">
        <img class="logo" src="../assets/images/dc-logo.png" alt="Dc logo">
        <nav>
            <ul class="d-flex justify-content-between">
                <li v-for="(link, index) in headerNavLinks" :key="index"><a :href="link.url" class="text-uppercase">
                {{ link.name }}
                </a></li>    
            </ul>
        </nav>
    </div>
  </header>
</template>

<script>
export default {
    data: function(){
       return{
         headerNavLinks: [
            {
                name: 'characters',
                url: '#',
            },
            {
                name: 'comics',
                url: '#',
            },
            {
                name: 'movies',
                url: '#',
            },
            {
                name: 'tv',
                url: '#',
            },
            {
                name: 'games',
                url: '#',
            },
            {
                name: 'collectibles',
                url: '#',
            },
            {
                name: 'videos',
                url: '#',
            },
            {
                name: 'fans',
                url: '#',
            },
            {
                name: 'news',
                url: '#',
            },
            {
                name: 'shop',
                url: '#',
            },
         ]
       }
    }
}
</script>

<style lang="scss" scoped> 

        .wrapper{
            width: 80%;
            margin: 0 auto;
        }

        img{
            width: 5rem;
        }        
        nav{
            width: 50rem;

            ul{
                list-style: none;
                margin: 0;

                a{
                    color: black;
                    text-decoration: none;
                    padding: 2.5rem 0;
                    border-bottom: 5px solid transparent;
                    &:hover {
                        border-bottom: 5px solid blue;
                    }
                }
            }
        }
    
</style>