<template>
    <nav>
        <h2>{{title}}</h2>
    </nav>
</template>
<script>
export default {
    name:'header1',
    props:{
        title:{
            type:String,
            default:'喵喵电影'
        
        }
    }
}
</script>
<style scoped>
nav{
    width: 100%;
    height: 50px;
    background-color:red;
    text-align: center;
    line-height: 50px
}

</style>

