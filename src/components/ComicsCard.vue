<script>

export default {
    name: "ComicsCard",
    props:{
        details: Object
    }
}
</script>

<template>
    
   

    <div class="card">
        <img :src="details.thumb" alt="img-card">
        <div class="description">{{ details.series }}</div>
    </div>

     
</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;


    .card{
        width: 120px;
        height: 120px;
        margin: 20px;

        img{
            width: 120px;
            height: 120px;
            object-fit: cover;
        }

        .description{
            font-size: $fontsize;
        }
        }


</style>
