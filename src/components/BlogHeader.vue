<template >
    <nav>
        <ul>
            <li>
                <router-link to="/" exact>博客总览</router-link>
                <router-link to="/add" exact>写博客</router-link>
            </li>
        </ul>
    </nav>
</template>

<script>
export default {
    name:"blog-header"
}
</script>

<style scoped>
 ul{
     list-style-type: none;
     text-align: center;
     margin: 0px;
 }
 li{
     display: inline-block;
     margin: 0 10px;
 }
 a{
     color:#fff;
     padding: 12px;
     border-radius: 5px;
     text-decoration: none;
     font-size: 18px;
 }
 nav{
     background:crimson;
     box-sizing: border-box;
     padding: 30px 0;
     margin-bottom: 30px;
 }
 .router-link-active{
     background: rgba(255, 255,255, 0.7);
     color:#444;
 }
</style>