<script>

export default {
    name: "AppHeader",
    data() {
        return {
            links: [
                {
                    text: "CHARACTERS",
                    url: "#",
                    current: false,
                },
                {
                    text: "COMICS",
                    url: "#",
                    current: true,
                },
                {
                    text: "MOVIES",
                    url: "#",
                    current: false,
                },
                {
                    text: "TV",
                    url: "#",
                    current: false,
                },
                {
                    text: "GAMES",
                    url: "#",
                    current: false,
                },
                {
                    text: "COLLECTIBLES",
                    url: "#",
                    current: false,
                },
                {
                    text: "VIDEOS",
                    url: "#",
                    current: false,
                },
                {
                    text: "NEWS",
                    url: "#",
                    current: false,
                },
                {
                    text: "SHOP",
                    url: "#",
                    current: false,
                },

            ]
        }
    }
}
</script>

<template>
    <header>

        <div>
            <img src="src/assets/img/dc-logo.png" alt="">
        </div>

        <ul>
            <li v-for="link in links">
                <a :href="link.url" :class="link.current ? 'active' : ''"> {{ link.text }}</a>
            </li>


        </ul>
    </header>
</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;

header {
    width: 100%;
    height: 100px;
    display: flex;
    justify-content: space-around;
    align-items: center;

    img {
        width: 70px;
    }

    ul {
        display: flex;

        li {
            padding: 0 10px;
            font-size: $fontsize;

            a {
                padding: 5px;

                &.active,
                &:hover {
                    color: $bluecolor;
                    padding: 40px 5px;
                    border-bottom: 2px solid $bluecolor;
                }
            }
        }
    }

}
</style>
