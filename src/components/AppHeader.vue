<script>

export default {
    name: "AppHeader"
}
</script>

<template>
    <header>

        <div>
            <img src="src/assets/img/dc-logo.png" alt="">
        </div>

        <ul>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>
            <li>ciao</li>

        </ul>
    </header>
</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;

header {
    width: 100%;
    height: 120px;
    border: 1px solid #000;
    display: flex;
    justify-content: space-around;
    align-items: center;

    img{
        width: 80px;
    }

    ul{
        display: flex;

        li{
            padding: 0 10px;
        }
    }

}
</style>
