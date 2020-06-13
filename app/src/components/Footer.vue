<template>
    <div id="footer">
        <div class="footer_nav">
            <div class="footer_nav_contetn" style="height: 50px; font-size: 14px; line-height: 50px;">
                <a href="">网站首页</a>
                | 
                <a href="">关于君创 </a>
                | 
                <a href=""> 业务范围  </a>
                | 
                <a href="">供求商机 </a>
                | 
                <a href="">回收案例 </a>
                | 
                <a href="">回收现场 </a>
                | 
                <a href="">荣誉资质 </a>
                | 
                <a href="">新闻中心 </a>
                | 
                <a href="">行业资讯 </a>
                | 
                <a href="">常见问题</a>
                | 
                <a href="">人才招聘</a>
                | 
                <a href="">联系君创</a>
            </div>
        </div>
        <div class="footer_content" style="padding-top:20px; padding-bottom:30px;">
            <div class="footer_content_all">
                <div class="footer_content_all_left" style="line-height: 35px; margin-top: 20px;">
Copyright © 2016 深圳君创再生资源有限公司 版权所有 【Bmap】【Gmap】
                    <span id="cnzz_stat_icon_1260651022">
                        <a href="https://www.cnzz.com/stat/website.php?web_id=1260651022">
                            <img src="http://icon.cnzz.com/img/pic.gif" alt="" border="0" hspace="0" vspace="0">
                        </a>
                        粤ICP备16102889号
                    </span>
                    <div>
地&nbsp;址：深圳市宝安区松岗街道松岗社区东风工业区风景厂厂房一101&nbsp;手&nbsp;机：13528818338&nbsp;联系人：陈先生
                    </div>
                    <div>
本站是专业的再生资源回收-深圳君创再生资源有限公司的官方网站，提供详细的报价，齐全的产品信息 【后台管理】
                    【百度统计】
                    </div>
                    
                    
                    <div>
 *本站相关网页素材及相关资源均来源互联网，如有侵权请速告知，我们将会在24小时内删除*技术支持【东莞网站建设】访问量： 349570
                    </div>
                </div>
                <div class="footer_content_all_right">
                    <div class="qrcode_wechat" style="margin-left:20px; background:#2a9e21; color:#fff;">
                        <img src="http://www.junchuang888.com/uploadfile/image/20161118/20161118082954_1859089380.jpg" alt="" width="120" height="120">
                        <br>
                        扫一扫加微信
                    </div>
                    <div class="qrcode_qq" style="margin-left:20px; background:#2a9e21; color:#fff;">
                        <img src="http://www.junchuang888.com/uploadfile/image/20161117/20161117090718_1855910848.png" alt="" width="120" height="120">
                        <br>
                        扫一扫加QQ二维码
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{

        }
    },
    mounted() {
        var cnzz_protocol = (("https:" == document.location.protocol) ? " https://" : " http://");
        document.write(unescape("%3Cspan id='cnzz_stat_icon_1260651022'%3E%3C/span%3E%3Cscript src='" + cnzz_protocol + "s95.cnzz.com/z_stat.php%3Fid%3D1260651022%26show%3Dpic' type='text/javascript'%3E%3C/script%3E"));

        var _hmt = _hmt || [];
        (function() {
        var hm = document.createElement("script");
        hm.src = "https://hm.baidu.com/hm.js?5b209f027bc99dc3da2ab98ba6bc8f14";
        var s = document.getElementsByTagName("script")[0]; 
        s.parentNode.insertBefore(hm, s);
        })();
    },
    methods:{

    }
}
</script>

<style lang="scss">
    #footer{
        // background:black;
        width: 100%;
        a:visited{
            color: #fff;
        }
        .footer_nav{
            text-align: center;
            width: 100%;
            height: auto;
            color: #FFF;
            background: #2a9e21;
            margin: 0 auto;
            margin-top: 30px;
            &_content{
                a{
                    font-size: 14px;
                }
                width: 1200px;
                margin: 0 auto;
                text-align: center;
            }
        }
        .footer_content{
            width: 100%;
            margin: 0 auto;
            &_all{
                width: 1200px;
                margin: 0 auto;
                height: auto;
                &_left{
                    width: 800px;
                    float: left;
                    font-size: 12px;
                    margin: auto;
                }
                &_right{
                    width: 150px;
                    float: right;
                    margin: 0 auto;
                    text-align: center;
                    line-height: 30px;
                    margin-top: 0px;
                    div{
                        float: left;
                    }
                    .qrcode_qq{
                        // float: left;
                        margin-left:20px; background:#2a9e21; color:#fff;
                        width: 150px;
                        float: left;
                        margin: 0 auto;
                        text-align: center;
                        line-height: 30px;
                        margin-top: -160px;
                    }
                    .qrcode_wechat{
                            width: 150px;
                            float: right;
                            margin: 0 auto;
                            text-align: center;
                            line-height: 30px;
                            margin-top: 10px;
                            margin-right: 160px;

                    }
                }
            }
        }
    }
</style>