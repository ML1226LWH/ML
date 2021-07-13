@import url(public.css);

a{}
a:hover{ color:#FF0000}
#header{ padding:32px 0px 0px 0px; margin:0 auto; background:url(../images/index/head.png) top center no-repeat; width:1250px; height:84px;}
.head-wrap{ width:1200px; margin:0 auto;}
/*New Nav Style*/
.english-info{ float:right; height:0px; margin-top:0px}
.english-info a{ color:#FFFFFF}
.english-info a:hover{ color:#FFB422}
#header .mainNav{ margin:0; padding:0;}
#header .mainNav .nav{ width:770px;float:right}
.nav{ padding:0 0px; height:84px; line-height:84px; position:relative; z-index:9998;  }
.nav a{ color:#fff;  }
.nav .nLi{ float:left;  position:relative; display:inline; width:110px;  }
.nav .nLi h3{ float:left;  background:url(../images/index/head-ico.jpg) 8px 37px no-repeat;  }
.nav .nLi h3 a{ display:block; padding:0  0px; font-size:14px; font-weight:bold; width:106px; text-align:center;}
.nav .sub{ display:none; width:138px; left:-15px; top:84px;  position:absolute; background:#99C6DD; line-height:43px;  padding:5px 0; border:1PX solid #75AECB; z-index:9999 }
.nav .sub li{ zoom:1; }
.nav .sub a{
	display: block;
	padding: 0 0px;
	color: #000;
	width: 104px;
	margin: 0 auto;
	background: url(../images/index/sub-li.png) no-repeat;
	height: 39px;
	line-height: 39px;
	text-indent: 1.5em;
}
.nav .sub a:hover{color:#FF0000 }
.nav .on h3 a{ color:#fff;  background:url(../images/index/head-on.png) no-repeat; text-decoration:none }

.container{ width:1250px; margin:0 auto; position:relative; z-index:99; }
.index-menu{ width:1250px; margin:0 auto; position:relative;}
.iosSlider {
				width: 1250px;
				height: 500px;
				
				
			
			}
			
			.iosSlider .slider {
				width: 100%;
				height: 100%;
			}
			
			.iosSlider .slider .item {
				position: relative;
				top: 0;
				left: 0;
				width: 1250px;
				height: 500px;
				background: #fff;
				
				margin: 0 0 0 0;
				cursor:pointer;
			}
			
			.iosSlider .slider #item1 {
				background:url(../images/index/b-1.jpg) no-repeat 50% 0;
			}
			
			.iosSlider .slider #item2 {
				background: url(../images/index/b-2.jpg) no-repeat 50% 0;
			}
			
			.iosSlider .slider #item3 {
				background: url(h-slider-3.jpg) no-repeat 50% 0;
			}
			
			.iosSlider .slider #item4 {
				background: url(h-slider-4.jpg) no-repeat 50% 0;
			}
			
			
			.iosSlider .slider .item .text2 {
				position: absolute;
				top: 300px;
				right: 0;
				background:url(../images/index/item_left.png) no-repeat;
				padding-left:60px;
				height:44px;
				line-height:44px;
				opacity: 0.25;
				filter: alpha(opacity:0.25);
				
			}
			.iosSlider .slider .item .text2 table{}
			
			.iosSlider .slider .item .text2 table td {
				color: #fff;
				font-family:'黑体';
				font-size:24px;
				padding-right:20px;
				height:44px; 
				line-height:44px;
				background:url(../images/index/item_r.png) repeat-x;
				
			}
			.iosSlider .slider .item .text2 table td  a{ color:#FFFFFF}
			.iosSlider .slider .item .text2 table td  a:hover{ color:#FF0000 }
			.iosSliderButtons {
				position: absolute;
				bottom: 80px;
				left: 620px;
				width: 200px;
				height: 10px;
				
			}
			
			.iosSliderButtons .button {
				float: left;
				width: 9px;
				height: 9px;
				background: #999;
				margin: 0 10px 0 0;
				opacity: 25;
				filter: alpha(opacity:25);
				border: 1px solid #000;
			}
			
			.iosSliderButtons .selected {
				background: #000;
				opacity: 1;
				filter: alpha(opacity:100);
			}
			
.iosSliderButtons .prev {
	float: left;
	width: 11px;
	height: 11px;
	background: url(../images/arrow_left.png) no-repeat 50% 0;
}
.iosSliderButtons .next {
	float: left;
	width: 11px;
	height: 11px;
	margin: 0 0 0 10px;
	background:url(../images/arrow_right.png) no-repeat 50% 0;
}
.iosSliderButtons .button {
	float: left;
	width: 9px;
	height: 9px;
	background: #aaa;
	margin: 1px 1px 1px 11px;
	/* opacity: 0.25; */
	filter: alpha(opacity=25);
	border-radius: 10px;
}
.iosSliderButtons .button .first {
	margin-left: 1px;
}
.iosSliderButtons .button .selected {
	FILTER: alpha(opacity=100); MARGIN: 0px 0px 0px 10px; WIDTH: 11px; BACKGROUND: #eee; HEIGHT: 11px; opacity: 1; box-shadow: none
}
	


.iosSliderDemo {
	POSITION: relative; PADDING-BOTTOM: 400px; PADDING-LEFT: 0px; WIDTH: 100%; PADDING-RIGHT: 0px; CLEAR: both; PADDING-TOP: 0px
}
.fluidHeight {
	POSITION: absolute; WIDTH: 100%; HEIGHT: 400px
}
.sliderContainer {
	PADDING-BOTTOM: 0px; PADDING-LEFT: 0px; PADDING-RIGHT: 0px; HEIGHT: 100%; MAX-HEIGHT: 400px; PADDING-TOP: 0px
}
.iosSlider {
	POSITION: relative; WIDTH: 100%; HEIGHT: 100%; OVERFLOW: hidden; TOP: 0px; LEFT: 0px
}
.iosSlider .slider {
	WIDTH: 100%; HEIGHT: 100%
}
.iosSlider .slider .item {
	TEXT-ALIGN: center; PADDING-BOTTOM: 0px; PADDING-LEFT: 0px; WIDTH: 100%; PADDING-RIGHT: 0px; MAX-WIDTH: 1250px; HEIGHT: 100%; PADDING-TOP: 0px
}
.iosSlider .slider .item .inner {
	POSITION: relative; MARGIN: 0px auto; WIDTH: 100%; BACKGROUND-REPEAT: no-repeat; BACKGROUND-POSITION: 50% 0px; HEIGHT: 100%; TOP: 0px; LEFT: 0px; box-shadow: 0 0 10px -5px #000
}
.iosSlider .slider .item .inner IMG {
	POSITION: relative; MARGIN: 0px auto; WIDTH: 100%; TOP: 0px; LEFT: 0px
}
.iosSlider .slider .item .inner .selectorShadow {
	POSITION: absolute; WIDTH: 120px; BOTTOM: 0px; DISPLAY: none; BACKGROUND: url(../_img/selector-shadow.png) no-repeat 0px 0px; HEIGHT: 30px; LEFT: 0px
}
.iosSlider .slider .item .inner .text1 {
	POSITION: absolute; TEXT-ALIGN: left; FILTER: alpha(opacity=0); PADDING-BOTTOM: 0px; PADDING-LEFT: 12px; BOTTOM: 12%; PADDING-RIGHT: 12px; BACKGROUND: #000000 0px 0px; HEIGHT: 50px; PADDING-TOP: 0px; opacity: 0; TOP: 251px;
}
.iosSlider .slider .item .inner .text1 SPAN {
	PADDING-BOTTOM: 0px; LINE-HEIGHT: 50px; PADDING-LEFT: 8px; PADDING-RIGHT: 8px; FONT-FAMILY: "Microsoft Yahei"; COLOR: #fff; FONT-SIZE: 24px; FONT-WEIGHT: 700; PADDING-TOP: 0px
}
.iosSlider .slider .item .inner .text1 SPAN I {
	MARGIN: 0px 0px 0px 5px
}
.iosSlider .slider .item .inner .text2 {
	POSITION: absolute; TEXT-ALIGN: left; FILTER: alpha(opacity=0); PADDING-BOTTOM: 10px; PADDING-LEFT: 12px; PADDING-RIGHT: 12px; BACKGROUND: #000000 0px 0px; PADDING-TOP: 10px; TOP: 251px; LEFT: 100px; opacity: 0
}
.iosSlider .slider .item .inner .text2 SPAN {
	PADDING-BOTTOM: 0px; LINE-HEIGHT: 1.5; PADDING-LEFT: 8px; PADDING-RIGHT: 8px; DISPLAY: block; FONT-FAMILY: "Microsoft Yahei"; COLOR: #fff; FONT-SIZE: 14px; FONT-WEIGHT: 100; PADDING-TOP: 0px
}
.iosSlider .slider .item .inner .more {
	Z-INDEX: 2; POSITION: absolute; TEXT-ALIGN: center; PADDING-BOTTOM: 0px; PADDING-LEFT: 2px; WIDTH: 55px; BOTTOM: 6%; PADDING-RIGHT: 5px; BACKGROUND: #fff 0px 0px; HEIGHT: 25px; RIGHT: 0px; PADDING-TOP: 0px; opacity: 0.4
}
.iosSlider .slider .item .inner .more A {
	LINE-HEIGHT: 25px; FONT-FAMILY: "??????"; COLOR: #000; FONT-SIZE: 14px; TEXT-DECORATION: none
}
.sliderContainer .slideSelectors {
	Z-INDEX: 1; POSITION: relative; MARGIN: 0px auto; WIDTH: 200px; BOTTOM: 40px; HEIGHT: 11px
}
.sliderContainer .slideSelectors .prev {
	WIDTH: 11px; BACKGROUND: url(../images/arrow_left.png) no-repeat 50% 0px; FLOAT: left; HEIGHT: 11px
}
.sliderContainer .slideSelectors .next {
	MARGIN: 0px 0px 0px 10px; WIDTH: 11px; BACKGROUND: url(../images/arrow_right.png) no-repeat 50% 0px; FLOAT: left; HEIGHT: 11px
}
.sliderContainer .slideSelectors .item {
	FILTER: alpha(opacity=25); MARGIN: 1px 1px 1px 11px; WIDTH: 9px; BACKGROUND: #aaa; FLOAT: left; HEIGHT: 9px; border-radius: 10px
}
.sliderContainer .slideSelectors .first.item {
	MARGIN-LEFT: 1px
}
.sliderContainer .slideSelectors .selected {
	FILTER: alpha(opacity=100); MARGIN: 0px 0px 0px 10px; WIDTH: 11px; BACKGROUND: #eee; HEIGHT: 11px; opacity: 1; box-shadow: none
}
.sliderContainer .slideSelectors .first.selected {
	MARGIN-LEFT: 0px
}
.sliderContainer .scrollbarContainer {
	Z-INDEX: 1; POSITION: relative; MARGIN: 0px auto; BOTTOM: 4px; HEIGHT: 4px; LEFT: 0px
}










			


.body-nav{ background:url(../images/index/body-nav.jpg) no-repeat; height:36px; margin:0 auto;  z-index:98;  width:1240px; padding-left:10px; padding-top:12px; position:relative }
.bd-nav{ padding:0 0px; height:28px; line-height:28px; z-index:9997; position:absolute;   }
.bd-nav a{ color:#fff;  }
.bd-nav .bLi{ float:left;  position:relative;  width:137px; z-index:9998; height:28px; line-height:28px;  }
.bd-nav .bLi h3{ float:left;  padding:0 20px 0 18px;  background:url(../images/index/bd-li.jpg) left 3px no-repeat }
.bd-nav .bLi h3 a{ display:block; padding:0  0px; font-size:14px; height:56px; font-weight:bold; width:103px; text-align:center;}
.bd-nav .bsub{ display:none; width:178px; left:-10px; top:36px;  position:absolute; background:#99C6DD; padding:5px 0; border:1PX solid #75AECB; z-index:9999 }
.bd-nav .bsub li{ zoom:1; }
.bd-nav .bsub a{
	display: block;
	padding: 0 0px;
	color: #000;
	width: 144px;
	margin: 0 auto;
	background: url(../images/index/sub-li.png) no-repeat;
	height: 39px;
	line-height: 39px;
	text-indent: 1.5em;
}
.bd-nav .bsub a:hover{color:#FF0000 }
.bd-nav .on h3 a{ color:#fff;  text-decoration:none; background:url(../images/index/bd-nav-on.jpg) repeat-x }

.index-box{ padding-left:80px; width:1171px; background:#FFFFFF url(../images/index/index-box-bc.png) 910px 0 no-repeat; margin:0 auto; }


.index-2{ width:331px; padding-top:26px;}
.index-2 .tabbtn { height:31px; background:url(../images/index/tab-bc.png) repeat-x;}
.index-2 .tabbtn li{ width:124px;  float:left; height:31px;}
.index-2 .tabbtn li a{ width:124px; height:28px; display:block; text-align:center; line-height:28px; padding-top:2px; font-size:14px; background:#E2E2E2; color:#323031; font-weight:bold }
.index-2 .tabbtn a:hover,.index-2 .tabbtn a.current{ text-decoration:none; background:#70C5F7;  color:#FFFFFF}
.index-2 .index-content{ width:311px;  height:337px;  position:relative; z-index:0}

.index-2 .index-content .box{ visibility:hidden;   padding:0px 0 0 0px;  position:absolute; z-index:0; left:0px; top:0px; width:311px; }
.index-2  .box .cnt{ }
 ul.index-ul{ margin:0; padding:0; padding:0px 0px 0px 0px}
 ul.index-ul li{height:26px; line-height:26px; padding-left:5px; padding-right:0px;}
 ul.index-ul li a{ display:block; float:left }
 ul.index-ul li span{}


.index-3{ width:300px; padding-left:80px; padding-top:26px;}
.index-3 .tabbtn { height:31px; background:url(../images/index/tab-bc.png) repeat-x;}
.index-3 .tabbtn li{ width:124px;  float:left; height:31px;}
.index-3 .tabbtn li a{ width:124px; height:28px; display:block; text-align:center; line-height:28px; padding-top:2px; font-size:14px; background:#E2E2E2; color:#323031; font-weight:bold }
.index-3 .tabbtn a:hover,.index-3 .tabbtn a.current{ text-decoration:none; background:#70C5F7;  color:#FFFFFF}
.index-3 .index-content{ width:300px;  height:337px;}

.index-3 .index-content .box{  padding:0px 0 0 0px; width:300px; position:relative }
.index-3  .box .cnt{ }
ul.index-ul-1{ margin:0; padding:0; padding:0px 0px 0px 0px}
ul.index-ul-1 li{height:26px; line-height:26px; padding-left:22px; padding-right:0px; background:url(../images/index/ico-1.png) 4px 10px no-repeat}
ul.index-ul-1 li a{ display:block; float:left }
ul.index-ul-1 li span{ color:#636363;}





.index-4{width:362px;; overflow:hidden;}
.index-4 .index-4-title{ height:53px; #height:40px;}
.index-4 .s-box{}
.index-4 .s-box .s-tit{ height:29px; line-height:29px; width:52px; text-align:center; color:#1B4A6F;}
.index-4 .s-box .s-txt{ background:url(../images/index/s-bc.jpg) no-repeat; width:157px; height:29px;padding-left:10px;}
.index-4 .s-box .s-txt .s-t{ margin-top:2px; line-height:24px; height:24px; border:0; width:150px }
.index-4 .s-box .s-btn .s-st{ background:url(../images/index/s-btn.jpg) no-repeat; width:30px; height:29px; border:0; cursor:pointer}
.index-4 .s-box .s-btn .s-st:hover{ background:url(../images/index/s-btn_f2.jpg) no-repeat}
.index-4 .wb{ width:214px; height:88px;  background:url(../images/index/wb.jpg) 22px 0 no-repeat; padding-left:22px; }
.index-4 .wb-name{ width:212px; padding-left:22px;}

.index-cat{ background:url(../images/index/index-bot.png) no-repeat; height:70px; width:1250px; margin:0 auto;}







#wb .closer{ float:right; background:url(../images/index/c.png) no-repeat; width:21px; height:21px; cursor:pointer}
#wb .closer:hover{ background:url(../images/index/c_f2.png) no-repeat}
#wb .titles{ height:21px;}

