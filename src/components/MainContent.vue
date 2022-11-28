<template lang="pug">
.maincontent
    .main-container
        span 
            h1 1213
            p 123213131
        span.specious 231
        span 
            testingSlots
                template(v-slot:iconfirst)
                    div 12
</template>

<script>



import testingSlots from './testingSlots.vue'


export default {
    name: 'MainContent',
    props: {
    msg: String
    },
    components: {
        testingSlots
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.main-container {
    margin-top: 30px;
    display: flex;
    justify-content: space-around;
  }
  
@import "./color.scss";
.maincontent {
    width: 80vw;
    height: 90vh;
    background: #bdfffdff;
}

.maincontent span {    
    background: rgb(195, 207, 206); 
    width: 20%;
    border-radius: 5px;
    border: 1px solid #0f799c;
    padding: 25px 15px;
    margin: 15px 15px;
    box-shadow: 0px 5px 10px 9px #011d26;
}

.specious {
    width: 30% !important;
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
