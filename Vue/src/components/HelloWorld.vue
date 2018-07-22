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
	<div id="content">
		<div class=login-wrap>
			<div class="w">
				<!-- 登录框 -->
				<div class="login-form">
					<div class="tab login-tab-l">
						<a class="ss" href="javascript:void(0)" >扫码登录</a>
					</div>
					<div class="login-tab login-tab-r">
						<a class="ss" href="javascript:void(0)" style="color:red;">账户登录</a>
					</div>
					<!-- 主体 -->
					<div class="login-box">
						
						
						<!-- 输入框 -->
						<div class="mc">
							<div class="form">
								<form id="formlogin" method="post" onsubmit="return false;">
									<div class="lb">
										
									
									
										<img src="../../img/7.jpg" class="limg">
										<!-- <div class="input-group-addon glyphicon glyphicon-user">aa</div> -->
										<!--<label for="loginanme" class="login-label name-label ">账号</label>-->
										<input  class="itxt" type="text" name="loginname" placeholder="邮箱/用户名/已验证手机">
									
									<div class="">
										<img src="../../img/8.jpg" class="limg bot">
										<!--<label for="loginanme" class="login-label name-label">密码</label>-->
										<input type="text"  class="itxt" name="loginname" placeholder="请输入密码">
									</div>
									
									</div>
									<div class="item item-fore4">
										<div class="safe">
											<input class="jdcheckbox" type="checkbox" name="remember">自动登录
											<a href="#" class="forgetPassword" style="text-align: right;">忘记密码</a>
										</div>
									</div>
									
									<!-- 登录按钮 -->
									<div class="">
										<div class="login-btn btn">
											<a href="javascript:;"   class="btn-img entry"  tabindex="6" id="loginsubmit">
												登  录</a>
										</div>
									</div>
									<a href="#" style="font-size: 12px;position: relative;top: 97px;left: -61px;">QQ</a>
					<a href="#" style="font-size: 12px;position: relative;top: 97px;left:-18px;">微信</a>
					<a href="#" style="font-size: 14px;position: relative;top: 97px;left:110px;color: #B61D1D;">立刻注册</a>
								</form>
							</div>
						</div>
					</div>
				</div>
			</div>
			
			<div class="login-banner" ><!-- style="background-color:#E83753" -->
				<div class="w">
				<img  class="main-img"  height="475px" width="auto" 
					src="../../img/bg.png">
					
					
				<!-- <div id="banner-bg"  class="i-inner" 
						style="background: url(//img11.360buyimg.com/da/jfs/t3154/258/5179306513/128208/9d5b12bd/5864cf6eN542ab244.jpg) "></div> -->
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
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style type="text/css">
.logo {
	margin: 10px 0;
	position: relative;
	width: 300px;
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
  left: 20px;
}
.qi {
	position: relative;
	float: right;
	text-decoration: none;
	color: #999;
	font-size: 12px;
	left: -130px;
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
}
 
 
element.style {
    background-color: #E83753;
}
/**图片样式*/
.login-banner{
	background-color: #E83753;
	position:absolute;
	width: 100%;
	margin-top: 0px;
}
 
/* 底部链接*/
#footer{
	width: 1149px;
	margin-left: 50px;
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
	width: 1149px;
	text-align: center;
	position: absolute;
	/*left: 10px;*/
}
.ws a{
	margin: 0 3px;
}
</style>
