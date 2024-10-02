<script>
import axios from 'axios';

    export default{
        name: 'Blog',
        methods:{
            getApi(){
                axios.get('http://127.0.0.1:8000/api/posts')
                    .then(result => {
                        console.log(result.data)
                    })
            }
        },
        mounted(){
            this.getApi()
        }
    }
</script>

<template>
    <div>
        <h1>Blog</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Iusto voluptatem vel hic enim, quos officiis, impedit reprehenderit non commodi earum qui molestias corrupti porro voluptas recusandae aliquam maxime nulla dolore. Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum aut dolores dicta id reiciendis excepturi optio, exercitationem vero ab nostrum sequi. Officia itaque laboriosam quod corporis suscipit repellat cum rerum.</p>
    </div>

</template>

<style lang="sass" scoped>

</style>