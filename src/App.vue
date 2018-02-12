<template>
    <div>
        <headerBlog></headerBlog>
        <router-view></router-view>
    </div>
</template>

<script>
    import addBlog from './components/addBlog';
    import showBlog from './components/showBlogs';
    import headerBlog from './components/headerBlog';
    export default {
        components: {
            'add-blog': addBlog,
            'show-blog': showBlog,
            'headerBlog': headerBlog
        },
        data(){
            return {

            }
        },
        methods: {

        }
    }
</script>

<style lang="scss" scoped>
body{
    margin: 0;
    font-family: 'Nunito Semibold';
}
</style>
