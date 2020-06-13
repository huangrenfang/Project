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
    <div class="clear"></div>
    <div id="bg">
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
    <div class="business">
      <div class="business_left">
        <div class="business_left_title">
          君创业务范围
        </div>
        <div class="business_left_content">
          <div class="business_left_content_bg">
            <table width="200" border="0" cellpadding="0" cellspacing="0">
              <tbody>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废铜回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废铝回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废铁回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废锡回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">整厂回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">库存回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废锌合金回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废不锈钢回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废钨钢回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废线缆回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废塑胶回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废线路板回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废电子电池回收</b>
                  </td>
                </tr>
                <tr>
                  <td height="39">
                    <b style="font-size:14px;">废机器设备回收</b>
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
        <div class="business_left_footer">
          <img src="http://www.junchuang888.com/uploadfile/image/20161110/20161110111449_1789148336.jpg" alt="">
        </div>
      </div>
      <div class="business_right">
        <div class="business_right_title">
            <span style="color:#484848">更多>></span>
            <div class="show_business">
              业务范围展示
            </div>
        </div>
        <div class="business_right_content" style="width:932px; padding-top:20px; border-top:none; margin:0 auto;">
          <div id="colee" style="overflow: hidden; height: 655px; width: 932px; line-height: 25px; margin-bottom: 10px;">
            <div id="colee1">
              <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
                <tbody>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        废铁回收
                      </span>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div id="colee2">
              <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
                <tbody>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                  <tr>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                    <td align="center" style="padding-left:5px">
                      <img src="http://www.junchuang888.com/uploadfile/image/20170305/20170305213252_1641644556.jpg" alt="" >
                      <br>
                      <span>
                        colee2
                      </span>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <div class="advantage">
      <img src="http://www.junchuang888.com/uploadfile/image/20161110/20161110115036_795754480.jpg" alt="">
    </div>
    
    <div class="advantage_resource">
      <div class="advantage_resource_1">
        <div class="advantage_resource_1_left" style=" width:420px; margin-left:163px;">
          <div class="advantage_resource_1_left_word1">
            资质齐全，规模宏大，资金雄厚
          </div>
          <div class="advantage_resource_1_left_word2">
            Qualified complete, large-scale, well-funded
          </div>
          <div class="advantage_resource_1_left_word3">
            深圳君创再生资源有限公司是一家证件齐全、规模较大、资金雄厚，有强大的处理加工能力的回收企业
          </div>
        </div>
        <!-- <div class="advantage_resource_1_right" style="margin-top:16px; margin-right:21px;">
          <img src="http://www.junchuang888.com/uploadfile/image/20161102/20161102145033_115705958.png" alt="">
        </div> -->
      </div>
      <div class="advantage_resource_2">
        <div class="advantage_resource_2_right" style="width: 420px; margin-right: 46px;">
          <div class="advantage_resource_2_right_word1">
            打包机，破碎机，各种回收机械
          </div>
          <div class="advantage_resource_2_right_word2" style="font-size: 12px; line-height: 15px;">
            Balers, crushers, all kinds of recycling machinery
          </div>
          <div class="advantage_resource_2_right_word3">
            君创公司自有各类废料回收机械，金属打包机和塑胶破碎机等，提高操作效能，更好地服务客户，突显回收优势
          </div>
        </div>
      </div>
      <div class="advantage_resource_3">
        <div class="advantage_resource_3_left" style="width: 420px; margin-left: 170px;">
          <div class="advantage_resource_3_left_word1">
            地域站点，运输车队，固定工人
          </div>
          <div class="advantage_resource_3_left_word2" style="font-size: 12px; line-height: 15px;">
            Regional sites, transport fleet, fixed workers
          </div>
          <div class="advantage_resource_3_left_word3">
            君创公司在珠三角城市均有回收站点，并有自己的运输车队和固定工人，节省回收成本,为大小客户提供满意服务，提高竞争优势
          </div>
        </div>
      </div>
      <div class="advantage_resource_4">
        <div class="advantage_resource_4_right" style=" width:420px; margin-right:40px; ">
          <div class="advantage_resource_4_right_word1">
            业务团队，解决工厂回收烦恼
          </div>
          <div class="advantage_resource_4_right_word2" style="font-size:12px; line-height:18px;">
            Business team, to solve the plant recycling troubles
          </div>
          <div class="advantage_resource_4_right_word3">
            君创用成熟的业务素养为各公司解决无法长期合作的困扰，为工厂制定长期合作的回收方案。针对废料脏，乱，杂提供解决方案，体现整体竞争优势
          </div>
        </div>
      </div>
    </div>
    </div>
    <div class="introduction_title">
      
    </div>
    <div class="introduction_content">
      <div class="introduction_content_bg">
        <div class="introduction_content_bg_left" style="width:815px;">
          <div class="introduction_content_bg_left_reborn">
            君创再生资源
          </div>
          <div class="introduction_content_bg_left_phone">
            欢迎来电洽谈
          </div>&nbsp;&nbsp;
          <div class="introduction_content_bg_left_slogan" style="text-indent:2em;">
            深圳君创再生资源有限公司是一家规模较大、资金雄厚的。公司本着“公平公正、诚实守信、互惠互利、薄利多销”的经营理念，以及良好的经营信誉，业务遍及深圳各区，与广东等地的多家企业有长期的合作关系，随着业务的发和壮大，合作伙伴已逐步向全国范围扩大。
            <div>
              本公司一贯奉行：守信.保质.快捷.竭诚的服务宗旨,大力提倡"资源再生,绿色环保"的政策,结合本行业的特点及公司的实际,努力开拓, 不断创新,力求满足有色金属市场的发展需要. .
            </div>
            <div>
              公司的服务,统一指导价格,统一装车,统一计量,做到公平买卖,保持清洁卫生.
            </div>
            <span style="color:#2a9e21">
            经营范围：
            </span>
            <div>
              专业从事回收各种有色金属,塑料制品.工业废铁、仓库积压、废铜回收、废铝回收、废锌回收、废铅回收、不锈钢回收等一切废旧物品等.
            </div>
            <div>
              为了节省贵公司的资金、资源,也为了我们的环境更美好,希望贵公司大力提倡物资回收再利用,我们将尽力的努力促进双方共同发展......
            </div>
          </div>
        </div>
        <div class="introduction_content_bg_right" style="margin-top:25px; margin-right:23px;">
          <img src="http://www.junchuang888.com/uploadfile/image/20161117/20161117091426_1183506417.png" alt="">
        </div>
      </div>
      <div class="introduction_content_footer">
        <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021200920_1444184369.png" alt="">
      </div>
      <div class="recycling_site">
      <div style="width: 1002px; font-size:30px; line-height: 30px; font-weight:bold; color:#2a9e21; text-align: center; margin: 0 auto;">
        君创回收现场
        <br>
        <span style="font-size:12px; text-transform:uppercase; color:#666666;">
          junchuang Recycling site
        </span>
      </div>
      <div class="row_carousel">
        <ul>
          <li class="row_carousel_content1">
            <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021202013_709981879.jpg" alt="">
          </li>
          <li class="row_carousel_content2">
            <div id="colee_right" style="overflow: hidden; width: 1078px;">
              <table cellpadding="0" cellspacing="0" border="0">
                <tbody>
                  <tr>
                    <td id="colee_right1" valign="top" align="center">
                      <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
                        <tbody>
                          <tr>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                          </tr>
                        </tbody>
                      </table>
                    </td>
                    <td id="colee_right2" valign="top">
                      <table width="100%" border="0" align="center" cellpadding="0" cellspacing="0">
                        <tbody>
                          <tr>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                            <td align="center" style="padding-left:5px;">
                              <img src="http://www.junchuang888.com/uploadfile/image/20161022/20161022161440_642275415.jpg" alt="">
                            </td>
                          </tr>
                        </tbody>
                      </table>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </li>
          <li class="row_carousel_content3">
            <img src="http://www.junchuang888.com/uploadfile/image/20161021/20161021201954_2063427441.jpg" alt="">
          </li>
        </ul>
      </div>
      <div class="news_question_bg">
        <div class="news_question_bg_left">
          <div class="news_question_bg_left_title">
            <div class="news_question_bg_left_title_content1"></div>
            <div class="news_question_bg_left_title_content2">常见</div>
            <div class="news_question_bg_left_title_content3">问题</div>
            <div class="news_question_bg_left_title_content4">Questions</div>
            <div class="news_question_bg_left_title_content5">+更多>></div>
          </div>
          <div class="news_question_bg_left_introduction" style="margin-top:20px;text-indent:2em;" >
            <ul>
              <li class="n1">
                <img src="http://www.junchuang888.com/uploadfile/image/20161115/20161115200328_870698097.jpg" alt="">
              </li>
              <li class="n2">
              <div>
                一、废金属：【磷铜、红铜、杯士铜、白铜、紫铜、青铜(62#、65#)、黄铜、漆包线铜、铜屑、铝、不锈钢(316.316L.304.301.202)、不锈铁、锌合金(渣)、铅、工业铁、镀金、镀银制品等废五金废有色金属回收】
              </div>
              <div>
                二、废电子：【电子脚、含银锡、无铅锡、含铅锡、锡渣、锡条、锡线、锡灰、锡膏、线路板、IC、电容、二极管、三极管、变压器、充电器、废电缆电线、电阻、等废电子回收】
              </div>
              </li>
            </ul>
          </div>
          <div class="news_question_bg_left_handle">
            <div class="news_question_bg_left_handle_left">
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">01</div>
                <div class="news_question_bg_left_handle_content_h2">君创为您讲述废品回收有哪些分类......</div>
              </div>
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">03</div>
                <div class="news_question_bg_left_handle_content_h2">废旧塑料回收利用的主要途径分有哪.....</div>
              </div>
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">05</div>
                <div class="news_question_bg_left_handle_content_h2">废品回收的益处有哪些?......</div>
              </div>
            </div>
            <div class="news_question_bg_left_handle_right">
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">02</div>
                <div class="news_question_bg_left_handle_content_h2">教您如何将废铝再生加工......</div>
              </div>
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">04</div>
                <div class="news_question_bg_left_handle_content_h2">废铜的分类有哪些？......</div>
              </div>
              <div class="news_question_bg_left_handle_content">
                <div class="news_question_bg_left_handle_content_h1">06</div>
                <div class="news_question_bg_left_handle_content_h2">废不锈钢金属回收该如何处理......</div>
              </div>
            </div>
          </div>
        </div>
        <div class="news_question_bg_right">
          <div class="news_question_bg_right_title">
            <div class="news_question_bg_right_title_content1"></div>
            <div class="news_question_bg_right_title_content2">行业</div>
            <div class="news_question_bg_right_title_content3">咨询</div>
            <div class="news_question_bg_right_title_content4">Industry</div>
            <div class="news_question_bg_right_title_content5">+更多>></div>
          </div>
          <div class="news_question_bg_right_content">
            <div class="news_question_bg_right_content_1">
              <span>我国成为废塑料资源综合利用率的国家之一</span>
              <br>
              <font>作为可再生资源的废塑料已成为我国资源综合利用的重要组成部分，为提高石油资源利用..</font>
            </div>
            <div class="news_question_bg_right_content_1">
              <span>2016中国废塑料行业发展深度剖析</span>
              <br>
              <font>2016年5月25日下午，商务部流通业发展司发布《中国再生资源回收行业发展报告2016》。2015年是...</font>
            </div>
            <div class="news_question_bg_right_content_2">
              <div class="news_question_bg_right_content_2_run">
                <div class="news_question_bg_right_content_2_run_tag">

                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="link">
        <div class="link_left">

        </div>
        <div class="link_right">
          <div class="link_right_content">
            <ul>
              <li>废品回收</li>
              <li>深圳废品回收</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
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
  mounted() {
    var speed=30;
    var colee2=document.getElementById("colee2");
    var colee1=document.getElementById("colee1");
    var colee=document.getElementById("colee");
    // colee2.innerHTML=colee1.innerHTML; //克隆colee1为colee2
    function Marquee1(){
    //当滚动至colee1与colee2交界时
    if(colee2.offsetHeight-colee.scrollTop<=0){
      colee.scrollTop-=colee1.offsetHeight; //colee跳到最顶端
      }else{
      colee.scrollTop++
    }
    }
    var MyMar1=setInterval(Marquee1,speed)//设置定时器
    //鼠标移上时清除定时器达到滚动停止的目的
    colee.onmouseover=function() {clearInterval(MyMar1)}
    //鼠标移开时重设定时器
    colee.onmouseout=function(){MyMar1=setInterval(Marquee1,speed)}




	var colee_right2=document.getElementById("colee_right2");
	var colee_right1=document.getElementById("colee_right1");
	var colee_right=document.getElementById("colee_right");
	colee_right2.innerHTML=colee_right1.innerHTML
	function Marquee4(){
	if(colee_right.scrollLeft<=0)
	colee_right.scrollLeft+=colee_right2.offsetWidth
	else{
	colee_right.scrollLeft--
	}
	}
	var MyMar4=setInterval(Marquee4,speed)
	colee_right.onmouseover=function() {clearInterval(MyMar4)}
	colee_right.onmouseout=function() {MyMar4=setInterval(Marquee4,speed)}
	
  },
  methods: {
    
  },
}
</script>

<style lang="scss">
@import '../assets/css/home.scss';
  
</style>