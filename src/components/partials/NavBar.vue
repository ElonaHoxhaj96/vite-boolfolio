<script>
    export default{
        name: 'NavBar'
    }
</script>

<template>
    <div>
        <ul>
            <li> <router-link :to="{name:'home2'}">Home</router-link></li>
            <li> <router-link :to="{name:'about'}">Chi simo</router-link></li>
            <li> <router-link :to="{name:'blog'}">I miei Post</router-link></li>
            <li> <router-link :to="{name:'contacts'}">Contatti</router-link></li>
        </ul>
    </div>

</template>

<style lang="scss" scoped>
ul{
    list-style: none;
    width: 100%;
    margin: 0 auto;
    li{
        display: inline-block;
        a{
            display: inline-block;
            margin: 0 10px;
            color: white;
            text-decoration: none;
            text-transform: uppercase;
            padding: 5px 10px;
            border: 1px solid white;
            &:hover{
                color: yellow;
            }
        }
    }

}

</style>