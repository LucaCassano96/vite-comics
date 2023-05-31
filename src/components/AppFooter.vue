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

        <section id="dc">
            <div class="links">
                <div>
                    <h3>DC COMICS</h3>
                    <ul>
                        <li><a href="#">Character</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Comics</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Movies</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">TV</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Games</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">News</a></li>
                    </ul>

                    <h3>SHOP</h3>

                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC COllectibles</a></li>

                    </ul>

                </div>

                <div>

                    <h3>DC </h3>
                    <ul>
                        <li><a href="#">Character</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Comics</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Movies</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">TV</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Games</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">News</a></li>
                    </ul>
                </div>


                <div>

                    <h3> SITES </h3>
                    <ul>
                        <li><a href="#">Character</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Comics</a></li>
                    </ul>
                    <ul>
                        <li><a href="#">Movies</a></li>
                    </ul>

                </div>
            </div>

            <div class="logo">
                <img src="src/assets/img/dc-logo-bg.png" alt="">
            </div>

        </section>

        <section id="contacts">

            <div class="Sign">Sign Up Now!</div>

            <div class="follow"><a href="#">FOLLOW US</a></div>

            <div class="socials">

                
                <div> <img src="src/assets/img/footer-facebook.png" alt=""></div>
                <div> <img src="src/assets/img/footer-periscope.png" alt=""></div>
                <div> <img src="src/assets/img/footer-pinterest.png" alt=""></div>
                <div> <img src="src/assets/img/footer-twitter.png" alt=""></div>
                <div> <img src="src/assets/img/footer-youtube.png" alt=""></div>

            </div>


        </section>


    </footer>
</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;

.info {
    width: 100%;
    height: 100px;
    background-color: $bluecolor;
    color: $whitecolor;
    display: flex;
    justify-content: center;
    align-content: center;

    .card {

        display: flex;
        align-items: center;
        justify-content: center;
        padding: 0 20px;
        font-size: 14px;

        img {
            width: 50px;
            padding: 7px;
        }
    }

}

#dc {
    width: 100%;
    background-image: url("src/assets/img/footer-bg.jpg");
    display: flex;
    justify-content: space-between;


    .links {
        width: 40%;
        display: flex;
        position: relative;
        color: $whitecolor;
        justify-content: space-evenly;
        padding: 20px;

        h3 {
            padding: 7px 0;
        }

        li {
            padding: 5px 0px;
        }

        a {
            color: $greycolor;
            font-size: $fontsize;

        }
    }

    .logo {
        width: 40%;

        img {
            width: 400px;
        }
    }
}

#contacts {
    width: 100%;
    height: 100px;
    background-color: $darkgrey;
    display: flex;
    justify-content: space-evenly;
    align-items: center;

    .Sign {
        color: $whitecolor;
        padding: 10px;
        border: 3px solid $bluecolor;
    }

    .follow{
        a {
            color: $bluecolor;
            font-size: 18px;
        }
    }

    .socials {
        display: flex;

        img {
            padding: 0 10px;
        }

       
    }

}
</style>
