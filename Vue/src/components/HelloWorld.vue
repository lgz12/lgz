<template>
<div>
<div class="w">
		<!-- 头部，logo部分 -->
		<div class="logo">
			<img alt="京东" src="../../img/2.png" /> 
		</div>
		<img class="qi" src="../../img/6.png" />
		<a class="questions" onmouseover="color:red;" target="_blank"
			href="https://surveys.jd.com/index.php?r=survey/index/sid/568245/lang/zh-Hans">登录页面，调查问卷</a>
			
</div>
<table style="background-color: #FFF8F0;width: 100%;margin-bottom:-10px;">
	<tr><td style="text-align:center;"><img src="../../img/1.png"/></td></tr></table>
		<!-- body -->
			<div class="login-banner" ><!-- style="background-color:#E83753" -->
				<img  class="main-img"  height="475px" width="100%" 
					src="../../img/bg.png">
					
					
				<!-- <div id="banner-bg"  class="i-inner" 
						style="background: url(//img11.360buyimg.com/da/jfs/t3154/258/5179306513/128208/9d5b12bd/5864cf6eN542ab244.jpg) "></div> -->
				</div>
	<div id="content">
		<div class=login-wrap>
			<div class="w">
				<!-- 登录框 -->
			
				<div id="box">
					
		<div class="ym" style="width: 350px;" v-show="isshow">
			<div id="">
				<img src="../../img/login_head.jpg" />
			</div>
			<div class="" style="height: 50px;text-align: center;margin: 0 auto;font-family: 黑体 ;font-size: 19px;border-bottom: solid 1px #F4F4F4;">
				<div class="ss"  v-on:click="smlogin()" style="float: left;width: 175px;padding-top: 10px;border-right: solid 1px #F4F4F4;">
					扫码登录
				</div>
				<div class="ss" v-on:click="zhlogin()" style="padding-top: 10px;font-weight: bolder;color:red">
					账户登录
				</div>

			</div>
			<div class="" style="height: 225px; ">

				<div class="" style="border: solid 1px #BDBDBD;margin: 30px 22px 0px 22px;">
					<div style="float: left;"><img src="../../img/pe.png" /></div>
					<div id="">
						<input type="" name="" id="" value="" placeholder="邮箱/用户名/已验证手机" style="height: 36px;border: none;width:83%"/>
					</div>
				</div>

				<div class="" style="border: solid 1px #BDBDBD;margin: 20px 22px 0px 22px;">
					<div style="float: left;"><img src="../../img/unc.png" /></div>
					<div id="">
						<input type="" name="" id="" value="" placeholder="密码"  style="height: 36px;border: none;width:83%"/>
					</div>
				</div>

				<div class="" style="margin: 20px 20px 0px 20px;float:right ;font-size: 12px;">
					忘记密码
				</div>
				
		</div>
	<div id="" style="height: 50px;background-color: #FCFCFC;">
				<div id="" style="float: left;margin-left: 20px;margin-top: 20px;">
					<img src="../../img/3.png" /> <a rel="nofollow" style="margin-top: -8px;" target="_blank" href="//www.jd.com/intro/about.aspx">
                QQ
            </a>
            &nbsp&nbsp<img src="../../img/4.png" /> <a rel="nofollow"  style="margin-bottom: 8px;" target="_blank" href="//www.jd.com/intro/about.aspx">
                微信
            </a>
				</div>
				<div id="" style="float: right;margin-right:20px;margin-top:20px;">
					<img src="../../img/5.png" /><a rel="nofollow" style="line-height: 20px;padding-bottom: 8px;color:red;" target="_blank"  href="//www.jd.com/intro/about.aspx">
                立即注册
            </a>
				</div>
				
			</div>
		</div>
		
			
   <!-- -->
    <div v-show="saoma" style="width: 350px;" class="ym"><div id="" class="">
				<img src="../../img/login_head.jpg" />
			</div>
			<div class="" style="height: 50px;text-align: center;margin: 0 auto;font-family: 黑体 ;font-size: 19px;border-bottom: solid 1px #F4F4F4;">
				<div class="ss"  v-on:click="smlogin()" style="float: left;width: 175px;padding-top: 10px;border-right: solid 1px #F4F4F4;font-weight: bolder;color:red">
					扫码登录
				</div>
				<div class="ss" v-on:click="zhlogin()" style="padding-top: 10px;">
					账户登录
				</div>

			</div>
			<div class="" style="height: 265px; ">
                 <div id="" style="text-align: center; margin: 0 auto;padding-top: 20px;">
                 	<img src="../../img/ewm.png"/>
                 </div>
				<div class="">
					<img src="../../img/ewm_inf.png"/>
				</div>
			</div>
			<div id="" style="height: 50px;background-color: #FCFCFC;">
				<div id="" style="float: left;margin-left: 20px;margin-top: 20px;">
					<img src="../../img/3.png" /> <a rel="nofollow" style="margin-top: -8px;" target="_blank" href="//www.jd.com/intro/about.aspx">
                QQ
            </a>
            &nbsp&nbsp<img src="../../img/4.png" /> <a rel="nofollow"  style="margin-bottom: 8px;" target="_blank" href="//www.jd.com/intro/about.aspx">
                微信
            </a>
				</div>
				<div id="" style="float: right;margin-right:20px;margin-top:20px;">
					<img src="../../img/5.png" /><a rel="nofollow" style="line-height: 20px;padding-bottom: 8px;color:red;" target="_blank"  href="//www.jd.com/intro/about.aspx">
                立即注册
            </a>
				</div>
				
			</div>
		</div>
		
			
		</div>
				
			</div>
			
				
			</div>
			
		</div>
		
		<div class="ws">
			<div id="footer">
				<div class="links">
            <a rel="nofollow" target="_blank" href="//www.jd.com/intro/about.aspx">
                关于我们
            </a>
            |
            <a rel="nofollow" target="_blank" href="//www.jd.com/contact/">
                联系我们
            </a>
            |
            <a rel="nofollow" target="_blank" href="//zhaopin.jd.com/">
                人才招聘
            </a>
            |
            <a rel="nofollow" target="_blank" href="//www.jd.com/contact/joinin.aspx">
                商家入驻
            </a>
            |
            <a rel="nofollow" target="_blank" href="//www.jd.com/intro/service.aspx">
                广告服务
            </a>
            |
            <a rel="nofollow" target="_blank" href="//app.jd.com/">
                手机京东
            </a>
            |
            <a target="_blank" href="/links.vm/club.jd.com/links.aspx">
                友情链接
            </a>
            |
            <a target="_blank" href="//media.jd.com/">
                销售联盟
            </a>
            |
            <a href="//club.jd.com/" target="_blank">
                京东社区
            </a>
            |
            <a href="//gongyi.jd.com" target="_blank">
                京东公益
            </a>
            |
            <a target="_blank" href="//en.jd.com/" clstag="pageclick|keycount|20150112ABD|9">English Site</a>
        </div>
        <div class="copyright">
            Copyright &copy; 2004-2018  京东JD.com 版权所有
        </div>
			</div>
		</div>
    </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
	  isshow:false,
	  saoma:true,
    };
  },
  methods: {
    smlogin() {
	  this.isshow = false;
	  this.saoma=true;
	},
	zhlogin() {
      this.isshow = true;
	  this.saoma=false;
	},
	}
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style type="text/css">
.ym{
	
	position: relative;
	z-index: 1000;
}
.ss:hover{
	color: red;
	font-weight: bolder;
}
* {
	
	margin: 0;
	padding: 0;
	box-sizing: border-box
}

html {
	font-size: 12px;
	font-family: Ubuntu, simHei, sans-serif;
	font-weight: 400
}

body {
	font-size: 1rem
}

table,
td,
th {
	border-collapse: collapse;
	border-spacing: 0
}

table {
	width: 100%
}

input {
	outline: none
}

input[type=text] {
	border: 1px solid #ccc;
	padding: .5rem .3rem;
}

input[type=text]:focus {
	border-color: #42b983;
}

button {
	outline: none;
	padding: 5px 8px;
	color: #fff;
	border: 1px solid #BCBCBC;
	border-radius: 3px;
	background-color: #009A61;
	cursor: pointer;
}
button:hover{
	opacity: 0.8;
}

#app {
	margin: 0 auto;
	max-width: 100%;
}

.form-group {
	margin: 10px;
}

.form-group > label {
	display: inline-block;
	width: 10rem;
	text-align: right;
}

.form-group > input,
.form-group > select {
	display: inline-block;
	height: 2.5rem;
	line-height: 2.5rem;
}

.text-center{
	text-align: center;
}

.pagination {
	display: inline-block;
	padding-left: 0;
	margin: 21px 0;
	border-radius: 3px;
}

.pagination > li {
	display: inline;
}

.pagination > li > a {
	position: relative;
	float: left;
	padding: 6px 12px;
	line-height: 1.5;
	text-decoration: none;
	color: #009a61;
	background-color: #fff;
	border: 1px solid #ddd;
	margin-left: -1px;
	list-style: none;
}

.pagination > li > a:hover {
	background-color: #eee;
}

.pagination .active {
	color: #fff;
	background-color: #009a61;
	border-left: none;
	border-right: none;
}

.pagination .active:hover {
	background: #009a61;
	cursor: default;
}

.pagination > li:first-child > a .p {
	border-bottom-left-radius: 3px;
	border-top-left-radius: 3px;
}

.pagination > li:last-child > a {
	border-bottom-right-radius: 3px;
	border-top-right-radius: 3px;
}
.all {
	height: 700px;
}

.head_st {
	height: 82px;
	text-align: center;
	width: 1000px;
	margin: 0 auto;
}

.login_mid_content {
	width: 100%;
	height: 40px;
	text-align: center;
	background-color: #FFF8F0;
}

.login_mid_content_div2 {
	padding-top: 10px;
	font-size: 12px;
}

.login_mi_lo {
	background-color: #0251C8;
	height: 476px;
}

.login_mi_lo_div2 {
	text-align: center;
	margin: 0 auto;
	width: 1000px;
}

.login_mi_lo_div2_chi2 {
	height: 430px;
	padding-top: 20px;
}

.login_foot {
	text-align: center;
}

input {
	outline: none;
}

.login_div_i {
	width: 350px;
	background-color: white;
}

.login_div_smdd {
	height: 50px;
	text-align: center;
	margin: 0 auto;
	font-size: 17px;
	border-bottom: solid 1px #F4F4F4;
}

.Sweep_code_login {
	float: left;
	width: 175px;
	padding-top: 10px;
	border-right: solid 1px #F4F4F4;
}

.font_hover:hover {
	color: orangered;
	font-weight: bold;
}

.Account_entry {
	padding-top: 10px;
}

.External_login_height {
	height: 225px;
}

.External_login_height2 {
	height: 265px;
}

.Input_area {
	border: solid 1px #BDBDBD;
	margin: 30px 22px 0px 22px;
}

.Input_area2 {
	border: solid 1px #BDBDBD;
	margin: 20px 22px 0px 22px;
}

.Input_area_input {
	height: 36px;
	border: none;
	width: 262px;
}

.Forget_password {
	margin: 20px 20px 0px 20px;
	float: right;
	font-size: 12px;
}

.login_button {
	margin: 60px 20px 0px 22px;
	float: none;
}

.other {
	height: 50px;
	background-color: #FCFCFC;
}

.scan_QR_code {
	text-align: center;
	margin: 0 auto;
	padding-top: 20px;
}
.logo {
	margin: 10px 0;
	position: relative;
	width: 300px;
	left: -200px;
	float:left;
	height:60px;
}
 
.welcome-login {
	margin-top: 15px;
	position: absolute;
	margin-left: 15px;
	color: rgb(51, 51, 51);
}
 .safe{
   position: relative;
   top: 35px;
 }
.questions {
	position: relative;
	float: right;
	text-decoration: none;
	color: #999;
	font-size: 12px;
	outline: rgb(109, 109, 109) none 0px;
	top:52px;
  left: -90px;
}
.qi {
	position: relative;
	float: right;
	text-decoration: none;
	color: #999;
	font-size: 12px;
	left: -260px;
	outline: rgb(109, 109, 109) none 0px;
	top:47px;
}
a{
	text-decoration: none;
	color: #999;
}
a:hover {
	color:red;
	text-decoration: underline;
}
 
.background-img {
	position: relative;
	width: 102%;
	margin-left: -8px;
}
 
.login-form {
	position: absolute;
	margin-top: 180px;
}
.login-wrap{
	background-color: #E83753;
	position:relative;
	height:475px;
	margin:10px 0 20px;
	z-index:5px;
}
.w{
	width:990px;
	margin: 0 auto;
	background-color: transparent;
}
 
#content{
	clear: both;
	width: 100%;
	border-color: #EA3754;
}
 
.login-wrap .login-form{
	float:right;
	top:-140px;
}
.login-form{
	position:relative;
	z-index:4;
	background:#fff;
	overflow:visible;
	width:345px;
	left: -20px;
}
.login-form .login-tab{
	margin-top:15px;
	height:39px;
	font-size:18px;
	font-family:"microsoft yahei";
	text-align: center;
	border-bottom:1px solid #f4f4f4;
	position:absolute;
	background:#ffff;
	display:block;
}
.tab{
 	margin-top:15px;
	height:39px;
	font-size:18px;
	font-family:"microsoft yahei";
	text-align: center;
	border-bottom:1px solid #f4f4f4;
	position:absolute;
	background:#ffff;
	display:block;
}
.login-tab{
	position:relative;
	margin-left:500px;
}
.login-form .login-tab-r{
	right:0;
}
.login-form .login-tab-l, .login-form .login-tab-r {
    width: 173px;
}
a, address, b, big, blockquote, body, center, cite, code, dd, del, div, dl, dt, em, fieldset, font, form, h1, h2, h3, h4, h5, h6, html, i, iframe, img, ins, label, legend, li, ol, p, pre, small, span, strong, u, ul, var {
    margin: 0;
    padding: 0;
}
.msg-wrap{
	width:306px;
	margin-left: 20px;
}
.msg-warn{
	color:#666;
	border: solid 1px ;
	border-color:orange;
	background-color: #FFEEDD;
	margin-top: 60px;
	text-align: center;
	font-size: 12px;
	padding-top: 3px;
	padding-bottom:3px;
}
#box{
	background-color: white;
	position: absolute;
	display: block;
	z-index: 9999;
	top: 20px;
	left: 864px;
}
.form{
	margin-left: 20px;
	width:280px;
	margin-top: 10px;
	font-size: 20px;
}
.item .item-fore1 .item .item-fore2{
	border:1px solider #bdbdbd;
 
}

.form .item{
	position:relative;
	margin-bottom:20px;
} 
.item .item-fore2{
	margin-top:10px;
	
}
.form .itxt {
  clear:all;
  position: relative;
  top: 30px;
  left: 26px;
   line-height:18px;
   height:16px;
   padding:10px 0 10px 10px;
   width:240px;
   float: none;
   overflow:hidden;
   font-size:14px;
   border-top-color: #E6E6E6;
   border-color:#E6E6E6;
	 /*margin-left: 100px;*/
	 /*background-color: transparent;*/
}
.item-fore4{
	font-size:12px;
	margin-top: 10px;
	height: 18px;
	/* width: 306px; */
}
.forgetPassword{
/* 	margin-left:182px; */
	position:absolute;
	right:0;
	top:0;
	margin:0;
}
.jdcheckbox{
	float: none;
	vertical-align: bottom;
	margin:0 3px 0 0;
	padding:0;
}
.item-fore5{
	text-align: center;
}

.login-form .login-box .login-btn {
	border:1px solid #cb2a2d;
	width:99%;
	position:relative;
	height:32px;
}
.btn{
  top:56px;
  width:279px; 
}
.login-form .login-box .login-btn .btn-img{
	border:1px solid #e85356;
	background: #e4393c;
	width:307px;
	font-size: 20px;
	color:#fff;
	display:block;
	height:33px;
	line-height:31px;
	font-family:'Micraosoft YaHei';
}
 a.btn-img:hover{
	color:#000;
	text-decoration: none;
}
a.ss:hover{
	color:red;
  font-weight: bolder;
	text-decoration: none; 
}
.main-img{
	width: 990px;
	height:475px;
	position: absolute;
	top: 110px;
	left: 900px;
}
 
 
element.style {
    background-color: #E83753;
}
/**图片样式*/
.login-banner{
	background-color: #E83753;
	position:relative;
	display: block;
	z-index: 1;
	top: -100px;
	left: -700px;
	width: 100%;
	margin-top: 0px;
}
 
/* 底部链接*/
#footer{
	width: 100%;
	/* margin-left: 50px; */
	text-align:center;
	padding-bottom:30px;
	font-size:12px;
	color:#666;
}
.copyright{
	margin-top:10px;
}
.limg{
	float: left;
	position: relative;
	top: 70px;
	margin-bottom: 0;
}
.bot{
   margin-top: -15px;
 }
.entry{
	margin-top: -2px;
	margin-left: -1px;
}

.ws{
	width: 100%;
	text-align: center;
	position: absolute;
	/*left: 10px;*/
}
.ws a{
	margin: 0 3px;
}
</style>
