<template>
    <div class="head">
        <div class="head_logo">
            <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021141606_260535479.jpg" alt="">
        </div>
        <div class="head_resource">
            <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021143327_897266432.jpg" alt="">
        </div>
        <div class="head_separate">
            <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021141640_1247073894.jpg" alt="">
        </div>
        <div class="head_slogan">
            <span  
            style="color: #2a9e21; font-size: 14px; line-height: 38px;">
            从事废旧金属，塑胶，机械设备等一体化的综合型回收公司 
            </span>
            <img src="http://www.junchuang888.com/uploadfile/image/20161105/20161105093041_1171210955.jpg" alt="">
        </div>
        <div class="head_tel">
            <img src="http://www.junchuang888.com/uploadfile/image/20180917/20180917155241_24811498.jpg" alt="">
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
    .head{
        width: 1200px;
        margin: 0 auto;
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        transform: translateX(-30px);
        div{
            margin:30px 5px;
        }
        &_slogan{
            margin:30px 20px !important;
            span{
                display: block;
            }
        }
    }
</style>