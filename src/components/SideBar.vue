<template lang="pug">
.sidenav
    .main-conter
        div Главная
        div Цены
        div Контакты
        div История
        div Постирония
        div Вау
</template>

<script>
export default {
    name: 'SideBar',
    props: {
    msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.main-conter {
    margin-left:  10px;
}

.main-conter div{
    color: white;
    padding:  20px;
}



@import "./color.scss";
.sidenav {
    width: 20vw;
    height: 90vh;
    background: $rich-black
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
