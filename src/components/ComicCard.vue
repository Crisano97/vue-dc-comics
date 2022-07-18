<template>
    <div class="comic-card">
        <div class="image-container">
            <img :src="imageUrl" :alt="comicType">
        </div>
        <h6 class="text-uppercase mt-4">
            {{ comicSerie }}
        </h6>
    </div>
</template>

<script>
export default {
    props:{
        'imageUrl': String,
        'comicPrice': String,
        'comicSerie': String,
        'comicType': String,

    }
}
</script>

<style lang="scss">
     div.comic-card{
            width: calc(100% / 6 - 1.5rem);
            height: 15rem;
            div.image-container{
                height: 10rem;
                img{
                    object-fit: cover;
                    object-position: top;
                    width: 100%;
                    height: 100%;
                }
            }
            h6{
                font-size: .8rem;
            }
        }
</style>