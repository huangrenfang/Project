<template>
    <div class="header">
        <div class="header_title">
            <div class="header_title_left"> 
            您好！欢迎访问深圳君创再生资源有限公司官网！
            </div>
            <div class="header_title_right">
            <router-link to="/about" icon="el-icon-arrow-up">返回首页</router-link>
            <router-link to="/about" icon="el-icon-arrow-up">在线留言</router-link>
            <router-link to="/about" icon="el-icon-arrow-up">联系君创</router-link>
            </div>
        </div>
        <div class="clear"></div>
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
  a{
    text-decoration-line: none;
  }
  a:visited{
    color: #8e8d8d;
  }
  div{
      margin: 0px;
      padding: 0px;
  }
  body{
    width: 100%;
    font-size: 12px;
    background: #FFF;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-family: "Microsoft Yahei";
    color: #484848;
  }
  .header{
    width: 100%;
    height: 37px;
    border-bottom: 1px #eaeaea solid;
    // margin: 0 auto;
    transform: translateX(-10px);
    &_title{
      width: 1200px;
      color: #8e8d8d;
      height: 33px;
      line-height: 33px;
      margin: 0 auto;
      &_left{
        width: 380px;
        float: left;
      }
      &_right{
        width: 190px;
        float: right;
        a{
          margin:0 5px;
        }
      }
    } 
  }
</style>