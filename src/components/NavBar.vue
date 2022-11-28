<template lang="pug">
.navbar
    .main-cont
        span Главная
        span Цены
        span Контакты
        span История
        span Постирония
        span Вау
</template>

<script>
export default {
    name: 'NavBar',
    props: {
    msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.main-cont {
    line-height: 10vh;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}

@import "./color.scss";
.navbar {
    width: 100vw;
    height: 10vh;
    background: $slimy-green;
}

h3 {
    margin: 40px 0 0;
}
ul {
    list-style-type: none;
    padding: 0;
}
li {
    display: inline-block;
    margin: 0 10px;
}
a {
    color: #42b983;
}
</style>
