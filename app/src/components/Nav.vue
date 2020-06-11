<template>
    <!-- <div id="nav_bg">
        <ul>
            
            
        </ul>   
    </div> -->
    <div id="nav_bg">
        <div id="nav_c">
            <div id="nav">
                <div id="mainmenu" class="downmainmenu">
                    <ul>
                        <li>公司首页</li>
                        <li>关于君创</li>
                        <li>业务范围</li>
                        <li>荣誉资质</li>
                        <li>供求商机</li>
                        <li>新闻中心</li>
                        <li>在线沟通</li>
                        <li>联系君创</li>
                    </ul>
                </div>
            </div>
            <div id="nav_r"></div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{

        }
    }
}
</script>

<style lang="scss">
    #nav_bg{
            width: 100%;
            height: 55px;
            background: #2a9e21;
            margin: 0 auto;
        li{
            line-height: 55px;
            text-decoration: none;
            font-size: 14px;
            font-weight: bold;
            width: 150px;
            text-align: center;
            display: block;
            color: #fff;
            float: left;
            text-align: center;
            background: url(http://login.114my.cn/memberpic/junchuang/uploadfile/image/20161021/20161021143746_1647170228.jpg) left no-repeat;
        }
    }
    #nav_c{
        width: 1202px;
        height: 55px;
        margin: 0 auto;
    }
    #nav{
        width: 1200px;
        height: 55px;
        float: left;
        div{
            margin: 0px;
            padding: 0px;
        }
    }
    .downmainmenu{
        position: absolute;
        font: bold 14px;
        height: 55px;
        overflow: visible
    }
    .downmainmenu UL {
        Z-INDEX: 100;
        PADDING-BOTTOM: 0px;
        LIST-STYLE-TYPE: none;
        MARGIN: 0px;
        PADDING-LEFT: 0px;
        PADDING-RIGHT: 0px;
        PADDING-TOP: 0px;
    }
    #nav ul li {
        background: url(http://login.114my.cn/memberpic/junchuang/uploadfile/image/20161021/20161021143746_1647170228.jpg) left no-repeat;
    }
    #nav ul li::after {
        background: url(http://login.114my.cn/memberpic/junchuang/uploadfile/image/20161021/20161021143746_1647170228.jpg) left no-repeat;
    }
    #nav li {
        float: left;
        text-align: center;
        width: 150px;
        font-size: 14px;
        line-height: 55px;
    }
    .downmainmenu UL LI UL {
        WIDTH: 150px !important;
        POSITION: absolute;
        DISPLAY: none;
        BACKGROUND: #fff;
        VISIBILITY: hidden;
        PADDING-TOP: 0px;
        LEFT: 1px;
        border: 1px #747474 solid;
        border-top: 0px none;
    }
    .downmainmenu UL {
        Z-INDEX: 100;
        PADDING-BOTTOM: 0px;
        LIST-STYLE-TYPE: none;
        MARGIN: 0px;
        PADDING-LEFT: 0px;
        PADDING-RIGHT: 0px;
        PADDING-TOP: 0px;
    }
    #mainmenu li:hover{
        color:#FFFF00;
    }
    #nav_r {
        width: 2px;
        float: right;
        height: 55px;
        text-align: center;
        background: url(http://login.114my.cn/memberpic/junchuang/uploadfile/image/20161021/20161021143746_1647170228.jpg) no-repeat;
        margin: 0 auto;
    }
</style>