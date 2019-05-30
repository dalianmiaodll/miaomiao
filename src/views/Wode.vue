<template>
    <div>
        <Header1 title="我的喵喵"/>
        <form >
            <input type="text" placeholder="账户名/手机号/Email">
            <input type="password" placeholder="请输入您的密码">
            <input type="submit" value="登陆" class="btn">
        </form>
        <ul>
            <li class="left">立即注册</li>
            <li class="right">忘记密码</li>
        </ul>
        
        <Footer1/>
    </div>
</template>
<script>
import Header1 from '@/components/Header.vue'
import Footer1 from '@/components/Footer.vue'
export default {
    name:'dianying',
    data () {
        return {
            
        }
    },
    components: {
        Header1,
        Footer1
    }
}
</script>
<style scoped>
input{
    display: block;
    width: 100%;
    height: 40px;
     border: none;
     border-bottom: 1px solid #666;
     background: none;
     outline:none;     
}
.btn{
    width: 95%;
    background-color:red;
    border: none;
    font-size: 20px;
    margin: 10px auto;
}
ul{
    font-size: 12px;
    color:red;
    
}
.left{
    float:left;
}
.right{
    float:right;
}

</style>
