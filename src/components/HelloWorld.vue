<template>
    <div>

        <div class="top">

            <div class="img">
                <img src="../assets/1.jpg" width="160">
            </div>

            <div class="menu1">
                <ul>
                    <li><a href="#">课程 </a></li>
                    <li><a href="#">职业路径</a></li>
                    <li><a href="#">实战</a></li>
                    <li><a href="#">猿问</a></li>
                    <li><a href="#">手记</a></li>
                </ul>
            </div>

            <div class="search">
                <a href="#">前端入门</a>
                <a href="#">Java入门</a>
            </div>

            <div class="download"><a>下载APP</a></div>

            <div class="img_1"><img src="../assets/2.png" width="35px"></div>

            <div class="gou">
                <a>购物车</a>
            </div>
        </div>
        <div class="middle">
            <div class="content">
                <img src="../assets/2.jpg" >
                <div class="banner">
                    <a>
                        <p class="tit">Web前端工程师</p>
                        <p class="desc">互联网最火爆的技术</p>
                    </a>
                    <a>
                        <p class="tit">Java工程师</p>
                        <p class="desc">健壮、安全、适用广泛</p>
                    </a>
                    <a>
                        <p class="tit">Android工程师</p>
                        <p class="desc">移动设备市场份额第一</p>
                    </a>
                    <a>
                        <p class="tit">PHP工程师</p>
                        <p class="desc">世界上最好的语言</p>
                    </a>
                    <a>
                        <p class="tit">iOS工程师</p>
                        <p class="desc">可能是全球最好的系统</p>
                    </a>
                </div>

            </div>

            <div class="menu">
                <i-menu></i-menu>
            </div>

        </div>
    </div>
</template>

<script>
    import iMenu from './menu.vue'
    export default {
        components:{iMenu},
        data(){
            return {
            }
        },
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
    * {
        padding: 0;
        margin: 0;;
    }

    .top {
        width: 100%;
        height: 72px;
        background-color: #fff;
    }

    .img {
        padding: 8px 30px;
        float: left;
        display: block;
    }

    .menu1 li {
        float: left;
        list-style-type: none;
        padding-left: 20px;
        padding-right: 10px;
        text-align: center;
        line-height: 72px;
        display: block;
    }

    .menu1 a:link, .menu1 a:visited {
        text-decoration: none;
        color: #333;
        font-size: large;
    }

    .menu1 a:hover, .menu1 a:active {
        color: #000;
    }
    .search{
        padding-left: 100px;
        height: 72px;
        width:200px;
        float: left;
        line-height: 72px;
    }
    .gou{
        padding-right: 50px;
        height: 72px;
        float: right;
        line-height: 72px;
    }
    .search a{
        height: 35px;
        border: 1px solid;
        border-radius: 35px;
        background: #eee;
        text-decoration: none;
        font-size: smaller;
        padding:5px 10px;
        color: #666;
        /*float: left;*/
    }
    .download{
        float: left;
        width: 150px;
        height: 72px;
        line-height: 72px;
    }
    .download a{
        padding-left: 50px;
        color: #333;

    }
    .gou a{
        height: 35px;
        border: 1px solid;
        border-radius: 35px;
        background: #eee;
        text-decoration: none;
        font-size: medium;
        padding:10px 30px;
        color: #666;
    }
    .img_1{
        padding: 20px 50px;
        float: right;
    }
    .menu{
        /*display: block;*/
        float: right;
    }
    .middle{
        width:1152px;
        margin: 30px auto;
    }
    .content{
        width:936px;
        height:456px;
        background: #888;
        float: right;
        position: relative;
    }
    .banner{
        width:936px;
        height:140px;
        background-color: white;
    }
    .banner a{
        width: 180px;
        height: 128px;
        display: block;
        float: left;
    }
    .tit{
        margin-top: 50px;
        font-size: large;
        color: black;
    }
    .desc{
        font-size: smaller;
        color: #888888;
    }
    /*.middle .inner{*/
        /*width: 768px;*/
        /*height: 210px;*/
        /*background-color: #555;*/
        /*position: absolute;*/
        /*left:0;*/
        /*top:0;*/
        /*opacity:1;*/
    /*}*/


</style>
