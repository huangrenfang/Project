<template>
  <div class="home">
    <div class="banner">
      <el-carousel>
        <el-carousel-item v-for="item in this.imgList" :key="item" style="display: inline;">
          <img :src="item" alt="">
        </el-carousel-item>
      </el-carousel>
    </div>
    <div class="search">
      <div class="search_content">
        <strong style="color: #2a9e21;">热门关键词:</strong>
        <a href="">深圳废料回收公司，</a>
        <a href="">深圳废品回收，</a>
        <a href="">深圳废金属回收，</a>
        <a href="">深圳物资回收公司，</a>
        <a href="">深圳废料回收 </a>
      </div>
      <div class="search_input">
        <ul>
          <li style="width: 26px;  height: 21px;" class="search_icon">
            <input type="image"  
            style="border:none;" 
            src="http://www.junchuang888.com/uploadfile/image/20161021/20161021144954_26744096.jpg" 
            name="imageField"
            width="26">
          </li>
          <li style="width: 176px; background: url(uploadfile/image/20161021/20161021145117_1650715692.jpg) no-repeat; height: 21px; margin-right:5px;">
            <input 
            type="text" 
            name="infoname" 
            id="" 
            size="10" 
            onfocus="if(this.value=='请输入关键词'){this.value='';this.style.color='#fff'}"
            onblur="if(this.value==''){this.value='请输入关键词';this.style.color='#cccccc'}"
            value="请输入关键词"
            style="margin: 2px 0px 0px 15px; 
            background: rgb(255, 255, 255); 
            padding: 0px; 
            border: 0px solid rgb(204, 0, 0); 
            width: 130px; 
            height: 15px; 
            color: rgb(204, 204, 204);">
          </li>
        </ul>
      </div>
    </div>
    <div class="content">
      <div class="content_title">
        您还在为以下问题而烦恼吗？
      </div>
      <div class="content_img">
      </div>
      <div class="content_title2">
        君创再生资源回收为您解决一切烦恼
      </div>
      <div class="content_title3">
        统一指导价格，统一装车，统一计量，做到公平买卖，保持清洁卫生
      </div>
    </div>
    <div class="trouble">
      <ul>
        <li class="trouble_1"><a>废料堆积如山<br>怎么办？</a></li>
        <li class="trouble_2"><a>废料产生危害<br>怎么解决？</a></li>
        <li class="trouble_3"><a>资质齐全回收公司<br>哪里找？</a></li>
        <li class="trouble_4"><a>收购价格现金支付<br>谁好？</a></li>
        <li class="trouble_5"><a>客户来访废料急处理<br>谁快？</a></li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Home',
  components: {
  },
  data(){
    return{
      imgList:[
        "http://www.junchuang888.com/uploadfile/image/20161103/20161103104905_359239913.jpg",
        "http://www.junchuang888.com/uploadfile/image/20161103/20161103100426_1984990439.jpg",
        "http://www.junchuang888.com/uploadfile/image/20161114/20161114085908_401739348.jpg"
      ]
    }
  },
  methods: {
    
  },
}
</script>

<style lang="scss">
  .el-carousel__container{
    width: 100% !important;
    // height: 500px !important;
    img{
      background-size:cover;
      width:100%;
      text-align: center;
    }
  }
  .el-carousel__arrow{
    background: #330000;
  }
  .search{
    width: 100%;
    height: 45px;
    line-height: 45px;
    background: #eeeeee;
    margin: 0 auto;
    color: #484848;
    &_content{
      height: 45px;
      margin: 0 auto;
    }
  }
  .search a:hover{
    color:#2a9e21;
  }
  .search_content{
    margin-left: 20px;
  }
  .search_input{
    float: right;
    padding-top: 13px;
    margin-top: -70px;
    li{
      float:right;
      list-style: none;
    }
    input:first-child{
      
    }
  }
  .search_icon{
    position: relative;
    top:5px;
    right: 25px;
  }
  .content_title{
    width: 1200px;
    font-size: 39px;
    line-height: 60px;
    color: #2a9e21;
    text-align: center;
    font-weight: bold;
    margin: 0 auto;
    padding-top: 30px;
  }
  .content_img{
    height: 22px;
    width: 7px;
    background: url(http://www.junchuang888.com//uploadfile/image/20161021/20161021161902_504773367.jpg) no-repeat;
    margin: 0 auto;
    padding: 5px 0px;
  }
  .content_title2{
    font-size: 21px;
    text-align: center;
    margin-bottom: 14px;
  }
  .content_title3{
    width: 512px;
    height: 58px;
    border: 1px solid #37f129;
    line-height: 58px;
    font-size: 16px;
    color: #32b228;
    text-align: center;
    margin: 0 auto;
  }
  .trouble{
    width: 1200px;
    height: 180px;
    margin: 60px auto;
    position: relative;
    left: -50px;
    li{
      float: left;
      text-align: center;
      width: 180px;
      font-size: 18px;
      list-style: none;
    }
    a{
      width: 180px;
      height: 85px;
      font-size: 18px;
      color: #fff;
      line-height: 80px;
      padding-top: 95px;
      display: block;
      line-height: 30px;
    }
  }
  .trouble_1{
    width: 180px;
    height: 180px;
    text-align: center;
    background: url(http://www.junchuang888.com//uploadfile/image/20161021/20161021163052_2083594947.png);
    margin: 0 auto;
  }
  .trouble_2{
    width: 180px;
    height: 180px;
    text-align: center;
    background: url(http://www.junchuang888.com//uploadfile/image/20161021/20161021180131_543665099.png);
    margin: 0 auto;
    margin-left: 74px;
  }
  .trouble_3{
    width: 180px;
    height: 180px;
    text-align: center;
    background: url(http://www.junchuang888.com//uploadfile/image/20161026/20161026092405_1240094194.png);
    margin: 0 auto;
    margin-left: 74px;
  }
  .trouble_4{
    width: 180px;
    height: 180px;
    text-align: center;
    background: url(http://www.junchuang888.com//uploadfile/image/20161021/20161021180621_2064714894.png);
    margin: 0 auto;
    margin-left: 74px;
  }
  .trouble_5{
    width: 180px;
    height: 180px;
    text-align: center;
    background: url(http://www.junchuang888.com//uploadfile/image/20161021/20161021180731_421687259.png);
    margin: 0 auto;
    margin-left: 74px;
    position: absolute;
    left: 1000px;
  }
</style>