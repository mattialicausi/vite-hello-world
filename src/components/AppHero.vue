<template>
    <div class="hero">
        <div class="wrapper-content">
            <div class="header-hero">
                <h1>Jumbotron</h1> 
            </div>
            <div class="main-hero">
                <div class="nav-bar">
                    <ul>
                        <li>Topics</li>
                        <li>Galleries</li>
                        <li>Downloads</li>
                        <li>About</li>
                        <li>Follow Us</li>
                    </ul>
                </div>
                <div class="container-img">
                    <img class="img-hero" src="../../public/images/space-nasa.jpeg" alt="img space">
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {

            }
        }
        
    }
</script>

<style lang="css">
    .hero{
        height: 90vh;
        background-color: aqua;
        width: 100%;
    }

    .wrapper-content{
        width: 1200px;
        margin: 0 auto;
    }

    .header-hero{
        height: 80px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .main-hero{
        display: flex;
    }

    .nav-bar{
        width: 40%;
    }

    .container-img{
        width: 60%;
        display: flex;
        justify-content: center;
    }

    /* MODIFICO NAV BAR */
    ul{
        display: flex;
        justify-content: space-between;
        list-style: none;
    }

    li{
        padding: 5px;
        border-radius: 10%;
    }

    /* MODIFICO CONTAINER IMG */
    .img-hero{
        height: 80vh;
        width: auto;
        border-radius: 8%;
    }

    /* HOVER LI */
    li:hover{
        background-color: white;
        cursor: pointer;
    }

</style>