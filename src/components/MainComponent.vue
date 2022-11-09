<template>
    <header>
        <h2>{{titolo}}</h2>
    </header>
    <main>

    </main>
</template>

<script>
    export default {
        name: 'MainComponent',
        data() {
            return {
                titolo: 'See all our photos', 
                listaImg: [],
            }
        },
            methods: {
                callApi(){
                    axios.get('https://api.nasa.gov/planetary/apod?api_key=DEMO_KEY&start_date=2017-07-08&end_date=2017-07-10').then((res)=>{
                    this.listaImg = res.data
                    console.log(res.data)
                    })
                }
                
            },

            mounted(){
                this.callApi();
            },
        
    }
</script>

<style lang="css">
    header {
        margin: 0 auto;
        height: auto;
        width: 100%;
    }

    h2{
        text-align: center;
        margin-top: 30px;
    }
</style>