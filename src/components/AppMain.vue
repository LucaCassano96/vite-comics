<script>

export default {
    name: "AppMain"
}
</script>

<template>
    
    <main>
        Content goes here
    </main>


</template>

<style lang="scss" scoped>
@use "../styles/variables.scss" as *;

main{
    width: 100%;
    height: 150px;
    background-color: $greycolor;
    color: $whitecolor;
    font-size: 30px;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>
