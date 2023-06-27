<template>
    <div class="footer">
        <h6>Footer</h6>
        <p class="footer-text">
            <router-link class="menu" to="/"> Home </router-link>
            <router-link class="menu" to="/tutorials"> Tutorials </router-link>
            <router-link class="menu" to="/about"> About </router-link>
        </p>
    </div>
</template>

<script>

export default{

}
</script>

<style scoped>

.footer{
    /* position: fixed;*/
    left: 0; 
    bottom: 0;
    margin: 0 ;
    /* height: 70px; */
    width: 100%;
    background-color:#6495ed ;
}
h6{
    text-align: center;
    font-size: 20px ;
}

.menu{
    font-size: 25px;
    padding-left: 40px;
    /* float: left; */
    /* padding-bottom: 10px; */
    word-spacing: 20px;
}

.menu:hover{
    background-color: yellowgreen;
    font-size: 20px;
}
</style>
