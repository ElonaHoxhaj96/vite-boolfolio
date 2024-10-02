<script>
    export default{
        name: 'NavBar'
    }
</script>

<template>
    <div>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Chi siamo</a></li>
            <li><a href="#">I miei Post</a></li>
            <li><a href="#">Contatti</a></li>
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