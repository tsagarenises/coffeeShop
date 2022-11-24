<template>
    <div class="beinspired">
        <div  class="home_principal hidden-mobile" id="main_cont">
        <div class="content_center">
            <h1>BE INSPIRED BY GOOD FOOD</h1>
            <p><a href="https://www.pumpernickels.ca/catering-catalog-book" target="_self"><img alt="" src="../assets/Pum_pp0_Cover-(1).jpg" style="width: 350px; height: 455px; margin-right: 10px; margin-left: 10px; border-width: 1px; border-style: solid;" /></a></p>

                <h3><strong>OUR LATEST CATERING BROCHURE IS NOW AVAILABLE<br />
                FOR ALL YOUR CATERING INSPIRATION!</strong></h3>

                <hr />
                <p>EXPRESS TAKE-OUT IS AVAILABLE AT SOME LOCATIONS.<br />
                ORDER YOUR PERSONAL TAKE-OUT MEAL ONLINE &amp; PICK UP AT OUR COUNTERS.</p>

                <hr />
                <p>WE CATER THROUGHOUT NTINDA COMPLEX &amp; KAMPALA.<br />
                <strong><span class="phone">+256 784 901590 &nbsp; &nbsp; </span>&nbsp; </strong></p>        </div>
       </div>

       <div class="content_center home_content">
                
                <div class="home_banner_1_1">
                    <a href="https://www.pumpernickels.ca/catering-catalog-book">
                    <img src="../assets/banner-20220929095740-51.jpg"/>
                    </a></div>
                            <div class="home_banner_1_2"><a href="https://www.pumpernickels.ca/catalog/holiday-packages">
                            <img src="../assets/banner-20220929100030-95.jpg"/>
                            </a>
                            </div>
                                    <div class="home_banner_2_1">
                                        <a href="https://www.pumpernickels.ca/product/signature-bowl">
                                        <img src="../assets/banner-20220929095942-102.jpg"/>
                                        </a>
                                        </div>        
                
                <div class="home_banner_2_2">
                    <a href="https://www.pumpernickels.ca/catalog/individual-package-menu">
                    <img src="../assets/banner-20210929095846-53.jpg"/>
                    </a>
                    </div>
        
                <div class="clear"></div>

                
              
      
    </div>
    </div>
 </template>
<script>
   
    export default {
        name:'HomePage'
       
    }
</script>
<style >
.beinspired{
    background:url(https://www.pumpernickels.ca/images/back_body.jpg) repeat;
}
.home_principal {/*background:url(https://www.pumpernickels.ca/images/back_body.jpg) repeat;*/ background-color: rgb(219, 219, 213); text-align:center;}
.home_principal .content_center { position:relative; overflow:hidden; margin-top: 0px; }
.home_principal_logo { /*background:url(images/because_logo.png) no-repeat;*/ width:261px; height:161px; position:absolute; right:0; top:70px; z-index:1;}
.home_principal h1 {  font-family: 'bebas_neueregular'; font-size:38px; padding:21px 0 11px 0; letter-spacing:1px;background:url(https://www.pumpernickels.ca/images/dot_line.png) repeat-x bottom;width:678px; margin:0 auto 10px auto;}
.home_principal p { font-family: 'Roboto', sans-serif; font-weight:300; font-size:18px; line-height:29px; margin:0; padding:0 0 17px 0;}
.home_principal p, .home_principal h1{ z-index:2; position:relative;}
.home_content { padding:45px 15px 90px; width:1170px;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;

}
.content_center {
    margin: 0 auto;
    padding-bottom: 1px;
    width: 1170px;
    position: relative;
}
h1{   font-family: "Roboto Condensed",sans-serif;    font-size: 38px;    font-weight: bold; margin:0px}
h1 span{color:#F6C65B; }
.float_left { float:left;}
.float_right { float:right;}
.hideIphone{ display:inline-block}
a img{ border:none}

.home_banner_1_1 { width: 677px; height: 420px; overflow: hidden; float: left; display: block;  margin:0 0 15px 0;}
.home_banner_1_2 { width: 450px; height: 420px; overflow: hidden; float: right; display: block; margin:0 0 15px 0;}
.home_banner_2_1 {  width: 450px; height: 420px; overflow: hidden; float: left; display: block; margin:0 0 15px 0;}
.home_banner_2_2 { width: 677px; height: 420px; overflow: hidden; float: right; display: block;}


footer {position: absolute; left: 0; bottom: 0; height: 223px; width: 100%; overflow:hidden;}

/*footer*/
footer.footer2 .box-opacity-footer{ height:270px; bottom:-220px; transition:0.4s ease;position:fixed;z-index:2; width:100%; left:0;}
footer.footer2 .box-opacity-footer .content_center{ margin-top: 0px;}
footer.footer2 .box-opacity-footer:hover{ bottom:0;}
/*footer.footer2 .box-opacity-footer{ height:271px;}*/


.back-yellow{ background: #F6C65B; width:100%; text-align:center}
.back-yellow .title{ padding:31px 0 5px; margin:0px auto 0px auto; display:block; font-size:30px; color:#3B3E40;  font-family: 'bebas_neueregular'; width:165px; text-align:center}

.box-test{ margin:14px auto 0;  width:1095px;}
.box-test .arrow-left{ float:left; margin: 15px 55px 0 0; height:32px }
.box-test .arrow-left:hover{ background-position:0px -42px}
.box-test .arrow-right{margin: 15px 0px 0 64px; float:left;width:32px; height:32px }
.box-test .arrow-right:hover{ background-position:-40px -42px}
.box-inter-testi{ width:910px; position:relative; float:left; height:143px; overflow:hidden; margin-bottom:35px}
.box-inter-testi ul{ list-style:none; padding:0px; margin:0px; position:absolute; left:0px; top:0px; width:99999px}
.box-inter-testi ul li { float:left; width:910px}
.box-inter-testi ul li .text{	font-family: 'Georgia-Italic';font-style:italic; font-size:19px; line-height: 32px; }
.box-inter-testi ul li .autor{ margin:17px auto 0px auto ;color:#3B3E40; font-size:13px; width:215px; text-align:center; font-family: 'Open Sans', sans-serif; font-weight:300;}
.back-black{ background:#000; padding:10px 0 5px;}
.box-social{ margin:10px 0px 0px 0px; color:#F6C65B; float:left; width:288px}
.box-social a{ border-radius:30px; width:30px; height:30px; line-height:30px; text-align:center; color:#F6C65B; border:3px solid #F6C65B;
    opacity:0.5; float:left; margin:0px 7px 0px 0px; font-size:19px !important}
.box-social a:hover{ opacity:1; border:3px solid #FFF;}
.box-social span{ float:left; margin:7px 52px 0px 0px; font-family: 'bebas_neueregular'; font-size:22px; }
.box-social-right{  float:right; padding:20px 0px 20px 0px }
.link-footer{ font-weight:400; list-style:none; margin:17px 28px 0 42px; padding:0px; color:#F6C65B}
.link-footer li {
    float: left;
    margin: 0;
    width: 23%;
}
.link-footer li.clear{

}
.link-footer li.last{ margin:0px !important}
.link-footer li .title{ font-size:16px; display:block; margin:0px 0px 17px 0px}
.link-footer li .title a,.link-footer li .title, .link-footer li .title a:visited { font-size:16px;text-transform: uppercase}
.link-footer li .title a:hover { color:white;}
.link-footer li a{  font-weight:400;text-transform:uppercase; font-size:12px; color:#F6C65B; display:table; margin:0px 12px 13px 0px; }
.link-footer li a:hover {color:#FFF;}
.box-opacity-footer{ background:rgba(0,0,0,0.9); display:table; width:100%}
.p-center-footer{height:62px; font-size:12px; color:#F6C65B; font-weight:400;  width:100%; text-align:center;
   clear:both; margin-bottom:10px; font-weight:400
}
.p-center-footer img {
    height: 121px;
    margin: 0;
    position: absolute;
    right: 24px;
    top: -121px;
}
.copyright{ float:left; margin:33px 0 0 43px}
.link-footer1{ float:right; margin: 32px 54px 0 0}
.link-footer1 a{font-weight:400; text-decoration:underline; margin:0px 15px;  color:#F6C65B;  font-weight:400; font-size:12px;}
.link-footer1 a:hover { color: #fff;}
.message.success{ background:#157522; color:#fff; padding:5px;}
.success2{ background:#157522; color:#fff; padding:5px; margin-bottom:5px}
.error2, .error3{ background:#A20002; color:#fff; padding:5px; margin-bottom:5px}
.message.success span{ display:block;}
.divMessage{ margin:0px 0 10px 0; padding:4px 10px; display:none; color:#fff;}
.divMessage.error{ background:#A20002;}
.divMessage.success{ background:#157522;}
.redBorder {    border: 1px solid #CF0000 !important;}
.content-icon-twiter{ float:left;}
.content-icon-face{ float:left; margin:-2px 25px 0px 0px}
.mobileMenu{ display:none}
.productName{ width:55%;}
.progress{ width:166px; height:3px; display:block; background:#000; position:relative; margin:3px 0 0;}
.progress .white{ background:#fff; width:0; height:3px; display:block; position:absolute; left:0; top:0; }


.messages {
    border-radius: 2px;
    font-size: 14px;
    margin: 10px;
    padding: 10px 10px 10px 45px;
    position: relative;
}
.messages span{
    display: block;
}
.messages.error {
    border: 1px solid #e18b7c;
    color: #e10707;
}
.messages.success{
    border: 1px solid #c1d779;
    color: #333;
}
.messages.warning {
    
    border: 1px solid #DBAF51;
    color: #000;
}

.overlay{
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    left: 0;
    background-color: rgba(0,0,0,0.5);
    display: none;

}

.step_top_link {
    padding: 30px 51px 0;
}
.step_top_link a{

    color: #3B3E40;
    display: inline-block;

    font-size: 18px;
    height: 24px;
    line-height: 24px;
    margin: 14px 0 0;
    padding: 0 0 0 32px;
    text-decoration: underline;
}
table.coupon{
    width: 100%;

}
table.coupon tr td:last-child{
    width: 100px;
}

table.tip{
    width: 100%;
    margin-top: 20px;
}
table.tip input[type="text"] {
    width: 70px;
}
.tipTypeCont {
    line-height: 44px;
}
table.tip tr td:last-child{
    width: 100px;
}
.total-padding input[type="text"] {
    border: 1px solid #d7d7d7;
    border-radius: 5px;
    color: #a9a9a9;
    float: left;
    font-size: 15px;
    height: 43px;
    line-height: 43px;
    margin: 0;
    padding: 0 0 0 17px;
    width: 90%;
}
.total-padding button {
    background: none repeat scroll 0 0 #000000;
    border: medium none;
    border-radius: 5px;
    color: #f6c65b;
    display: inline-block;
    float: right;
    font-family: "Open Sans",sans-serif;
    font-size: 15px;
    font-weight: bold;
    height: 43px;
    margin: 0;
    padding: 0;
    text-align: center;
    width: auto;
    width: 130px;
    text-align: center;
}





table.orders {
    border-spacing: 0;
    width: 100%;
}
table.orders tr{}
table.orders thead{background-color: #EBBF5C}
table.orders thead th{font-weight: normal}
table.orders thead th span {
    border-right: 1px solid;
    color: #000000;
    display: block;
    font-size: 14px;
    line-height: 30px;
    margin: 8px 0;
}
table.orders thead th:last-child span{border: none}

table.orders tbody{}
table.orders tbody tr.hidden{display: none}
table.orders tbody td {
    padding: 10px 0 0;
    position: relative;
}
table.orders tbody td span {
    background-color: rgba(0, 0, 0, 0.7);
    color: #ffffff;
    display: block;
    font-family: Roboto;
    font-size: 14px;
    line-height: 46px;
    text-align: center;
    position: relative;

}
table.orders tbody td:last-child b {
    background: none repeat scroll 0 0 #ebbf5c;
    display: block;
    position: absolute;
    right: -47px;
    top: 10px;
    height: 46px;
    width: 46px;
    text-align: center;
    line-height: 40px;
    cursor: pointer;
    font-weight: normal;
}
.orderDetails{
    background-color: #fff;
    color: #353535;
    font-size: 13px;
    position: relative;
}
table.shipInfo{
    border-spacing: 0;
    background-color: #EDEFEF;
    width: 100%;
}
table.shipInfo td {
    color: #353535;
    font-family: Roboto;
    font-size: 13px;
    font-weight: 400;
    line-height: 140%;
    padding: 25px !important;
}
table.shipInfo label {
    display: block;
    font-size: 13px;
    font-weight: bold;
    margin-bottom: 6px;
}
table.shipInfo td:first-child{
    font-size: 14px;
}
table.shipInfo td:first-child label{
    margin-top: 5px;
}
table.shipInfo td:first-child,
table.shipInfo td:last-child{
    background-color: #E4E7E7;
}

.orderItemsWrap{padding: 20px 50px;border-spacing: 2px;color: #000;font-family: Roboto}
.orderItems{}
.orderItems th{background-color: #EDEFEF;font-size: 13px;color: #353535;text-align: center;font-weight: normal}
.orderItems th:last-child {
    width: 108px;
}
.orderItems th:first-child{text-align: left}
.orderItems td {
    border-bottom: 1px solid #edefef;
    color: #000000;
    font-size: 14px;
    font-weight: 400;
    padding: 10px !important;
    text-align: center;
}
.orderItems tr:last-child td{}
.orderItems td:first-child{text-align: left}
.orderItems p {
    line-height: 100%;
    padding: 0;
    margin: 0;
    color: #000;
}
.orderItems{}
.orderItems{}

.ordersTotal {
    float: right;
    width: 100%;
}
.ordersTotal td {
    color: #000000;
    font-size: 14px;
    line-height: 100%;
    padding: 4px 10px !important;
    text-transform: uppercase;
    width: 50%;
    font-weight: 400;
}
.ordersTotal td:last-child {
    width: 84px !important;
}
.ordersTotal tr:last-child td {
    border-top: 1px solid #eeeeee;
    font-size: 18px;
    padding-top: 13px !important;
}
.orderReorder{
    display: inline-block;
    float: right;
}
.orderReorder {
    background-color: #ebbf5c;
    color: #000000;
    display: inline-block;
    float: right;
    font-size: 14px;
    margin: 10px 0;
    padding: 0 20px;
}
.orderReorder:hover {
    background-color: #000000;
    color: #ebbf5c;

}
.orderClose {
    background: none repeat scroll 0 0 #000000;
    cursor: pointer;
    display: block;
    font-weight: normal;
    height: 46px;
    line-height: 49px;
    position: absolute;
    right: -47px;
    text-align: center;
    top: 0;
    width: 46px;
    cursor: pointer;
    display: block;
}
.orderPrint {
    isplay: block;
    cursor: pointer;
    background: none repeat scroll 0 0 #000000;
    cursor: pointer;
    display: block;
    font-weight: normal;
    height: 46px;
    line-height: 47px;
    position: absolute;
    right: -47px;
    text-align: center;
    top: 48px;
    width: 46px;
}

.addFavorite {
    cursor: pointer;
    font-size: 20px;
    position: absolute !important;
    right: 0;
    top: 0;
}
.addFavorite.active{
    color: #C9302C;
}
.mobile{
    display: none !important;
}

.deliveryTime input {
    width: 149px !important;
    float: left;
}

.deliveryTime .select {
    width: 148px;
    margin-left: 10px;
}

.deliveryTime .select .text {
    margin-left: 10px;
    width: auto;
}
.step2 textarea {
    background: none repeat scroll 0 0 #ffffff;
    border: 1px solid #e1e1e1;
    border-radius: 5px;
    color: #3b3e40;
    display: block;
    font-size: 15px;
    height: 50px;
    padding: 10px;
    width: 90%;
    font-family: "Roboto", sans-serif;
}

.deliveryTime{position: relative;width: 390px}

.deliveryTime .wrapInput{float: left}
#locations .select{
    width: 336px;
}
.deliveryTime .over{
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0,0,0,0.5);
    display: none;
    z-index: 100;

}
.buorg div {
    background: rgba(0, 0, 0, 0) none repeat scroll 0 0 !important;
    font-size: 16px;
    margin: 0 auto;
    max-width: 930px;
    padding: 10px 0 !important;
    position: relative;
}
.buorg {
    background: #000 none repeat scroll 0 0 !important;
    border-bottom: 1px solid #000 !important;
    color: #f6c65b !important;
    cursor: pointer;
    font-family: Arial,Helvetica,sans-serif;
    font-size: 12px;
    left: 0;
    position: fixed;
    text-align: left;
    top: 0;
    width: 100%;
    z-index: 111111;
    height: 58px !important;
}
.buorg a, .buorg a:visited {
    color: #f6c65b !important;
    text-decoration: underline;
}
#buorgclose {
    background-color: #f6c65b !important;
    font-family: menu;
    font-size: 28px !important;
    font-weight: bold;
    height: 28px !important;
    line-height: 100%;
    margin-top: 0;
    padding: 0 !important;
    position: absolute;
    right: 0 !important;
    text-align: center;
    top: 3px !important;
    width: 29px !important;
    color: #fff;
}
.content_center_big img{
    max-width: 100%;
}

ul.products_group{
    list-style: none;
    padding: 0;
    margin: 0;
}
ul.products_group li{
    float: left;
    width: 49%;
    margin-right: 2%;
}
ul.products_group li:last-child{
    margin-right: 0;
}
ul.products_group li a{}
ul.products_group li a img{width: 100%}
.main_video {
    padding: 0 15px 10px 11px;
    height: 646px;
}
.main_video iframe{
    width: 100%;
    height: 100%;
}

.type-element {
    height: 100%;
    position: absolute;
    right: 0;
    top: 0;
    width: 100%;
    z-index: 10;
}
.box-video{
    width: 368px;
    margin: 10px;
}
.box-video a {
    display: block;
    height: 215px;
    position: relative;
}
.box-video a img {
    width: 100%;
    height: auto;
    max-width: none;
}
.box-video h3{
    color: #fff;
    text-align: center;
}

/*Account setup---------------------------------------------------*/
.acc-setup-page .step1_title_wait{
    width: 33.333%;
    color: #3b3e40;
}
.acc-setup-page .step1_title_wait span{
    color: #3B3E40;
}
.acc-setup-page .step1_title_wait.step4_title_wait2{
    background: #000;
}
.acc-setup-page .step1_title_wait.act{
    color: #fff;
}
.acc-setup-page .step1_title_wait.act span{
    color: #fff;
}
.acc-setup-page .step1_title_wait.passive_black {
   
}
.acc-setup-page .step1_title_wait.step4_title_wait2.act{
    background: #F6C65B;
}
.step2.acc-setup-page{
    width: 100%;
}
.acc-setup-page .step-cont-acc{
    display: none;
}
.acc-setup-page .step-cont-acc.act{
    display: block;
}
.acc-setup-page .step-cont-acc{
    padding: 45px 40px 40px;
}
.acc-setup-page .step-cont-acc .step-cont-acc-info,
.acc-setup-page .step-cont-billing-info{
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    justify-content: space-between;
}
.acc-setup-page .step-cont-acc .step-cont-acc-info input{
    width: 495px;
}
.acc-setup-page .step-cont-acc button{
    margin-bottom: 0; 
}
.acc-setup-page .step-cont-billing-info input{
    width: 495px;
}
.acc-setup-page .step-cont-billing-info select{
    display: inline-block;
    vertical-align: top;
}
.acc-setup-page .select.error{
    width: auto !important;
    float: none;
} 
.acc-setup-page .select.wrapInput label.error{
    background: transparent;
    top: -30px;
}
/*Account setup---------------------------------------------------*/



.content_center_small {
    margin-top: 170px;
    padding: 40px;
    max-width: 800px;
}
.pickup-content .content_center_small{
    margin-top: 212px;
}
.content_center_small h2 {
    text-align: center;
    font-family: 'Roboto', sans-serif;
    font-weight: 300;
    font-size: 38px;
    padding: 0;
    margin: 0;
}
.content_center_small .description {
    text-align: center;
    margin: 0px 0 26px;
}
.content_center_small .description p{

}
.content_center_small form {
    max-width: 400px;
    margin: 0 auto;
}

.pickup_form_checkout {
    width: 400px;
    margin: 50px auto;
}

.pickup-banner{
background-color: #f6c65b;
}
.pickup-banner-content{
    max-width: 1170px;
    margin: 0 auto;
}
.pickup-banner-content:after{
content: "";
display: block;
clear: both;
}
.pickup-banner-content label {
    float: left;
    font-size: 35px;
}
.pickup-banner-info {
    float: left;
    text-transform: uppercase;
    font-size: 13px;
    font-weight: 400;
    line-height: 120%;
    padding-top: 5px;
    padding-left: 22px;
}
.pickup-banner-button{
    float: left;
}
.pickup-banner-button a {
    display: block;
    border: 2px solid #000;
    font-size: 13px;
    padding: 3px 10px;
    font-weight: 400;
    margin-left: 20px;
    margin-top: 9px;
    color: #000;
}


</style>