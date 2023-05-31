<script>

export default {
    name: "AppFooter"
}
</script>

<template>
    
    <footer>

        <section class="info">

            <div class="card">
                <img src="src/assets/img/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="card">
                <img src="src/assets/img/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="card">
                <img src="src/assets/img/buy-comics-shop-locator.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="card">
                <img src="src/assets/img/buy-comics-subscriptions.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
    
            <div class="card">
                <img src="src/assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC PWER VISA</span>
            </div>


        </section>

        <section>

        </section>

        <section>
            
        </section>


    </footer>
  


</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;

.info{
    width: 100%;
    height: 120px;
    background-color: $bluecolor;
    color: $whitecolor;
    display: flex;
    justify-content: center;
    align-content: center;

 .card{

    display: flex;
    align-items: center;
    justify-content: center;
    padding: 0 20px;
    font-size: 14px;

    img{
        width: 50px;
        padding: 7px;
    }
 }

   

}

</style>
