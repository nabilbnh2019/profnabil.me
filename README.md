# profnabil.me
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:version='2' class='v2' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'> 
  <head>
    <link href='https://fonts.googleapis.com/css?family=Cairo' rel='stylesheet'/>
    <link href='https://cdn.rawgit.com/Modareb/files/master/fonts/neo.css' rel='stylesheet'/>
    <meta content='width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1' name='viewport'/>
    <meta content='text/html;charset=UTF-8' http-equiv='Content-Type'/>
    <meta content='IE=edge,chrome=1' http-equiv='X-UA-Compatible'/>
    <title>
		<b:if cond='data:blog.pageType == &quot;index&quot;'>
			<data:blog.pageTitle/>
		<b:else/>
			<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
				<data:blog.pageName/> - <data:blog.title/>
			<b:else/>
				ERROR 404 - <data:blog.title/> 
			</b:if>
		</b:if>
    </title>
    <!-- Description and Keywords (start) -->
    <b:if cond='data:blog.pageType == &quot;index&quot;'>
    <meta content='YOUR DESCRIPTION HERE' name='description'/>
    </b:if>
    <meta content='YOUR KEYWORDS HERE' name='keywords'/>
    <!-- Description and Keywords (end) -->
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <meta expr:content='data:blog.pageName' property='og:title'/>
        <meta expr:content='data:blog.canonicalUrl' property='og:url'/>
        <meta content='article' property='og:type'/>
    </b:if>
    <b:if cond='data:blog.postImageUrl'>
        <meta expr:content='data:blog.postImageUrl' property='og:image'/>
    <b:else/>
    <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' property='og:image'/>
    </b:if></b:if>
    <b:if cond='data:blog.metaDescription != &quot;&quot;'>
        <meta expr:content='data:blog.metaDescription' name='og:description'/>
    </b:if>
    <meta expr:content='data:blog.title' property='og:site_name'/>
    <meta expr:content='data:blog.homepageUrl' name='twitter:domain'/>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.postImageUrl'>
      <meta content='summary_large_image' name='twitter:card'/>
      <meta expr:content='data:blog.postImageUrl' name='twitter:image'/>
    <b:else/>
      <meta content='summary' name='twitter:card'/>
      <b:if cond='data:blog.postImageThumbnailUrl'>
        <meta expr:content='data:blog.postImageThumbnailUrl' name='twitter:image'/> 
      </b:if>
    </b:if>
    <meta expr:content='data:blog.pageName' name='twitter:title'/>
    <b:if cond='data:blog.metaDescription'>
      <meta expr:content='data:blog.metaDescription' name='twitter:description'/>
    </b:if>
    <!-- Social Media meta tag need customer customization -->
    <meta content='#' property='fb:app_id'/> 
    <meta content='#' property='fb:admins'/> 
    <meta content='#' name='twitter:site'/>
    <meta content='#' name='twitter:creator'/>   

<link href='http://fonts.googleapis.com/css?family=Merriweather:400,700|Droid+Serif:400,700' rel='stylesheet' type='text/css'/>
<link href='https://maxcdn.bootstrapcdn.com/font-awesome/4.5.0/css/font-awesome.min.css' rel='stylesheet'/>
<script src='//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js'/>
   <b:skin><![CDATA[/* 
-----------------------------------------------
TH3 Blogger Template by M.Amine
Name :      Maktebati Blogger Template
Designer :  M.Amine
URL Designer:        https://www.facebook.com/thechni
----------------------------------------------- */
/* Variable definitions
====================
<Variable name="mainbgcolor" description="Blog main Color" type="color" default="#f0f0f0"  value="#f0f0f0"/>
<Variable name="primarycolor" description="Primary Color" type="color" default="#d86843"  value="#21759b"/>
<Variable name="secondcolor" description="Secondary Color" type="color" default="#333333"  value="#3998c5"/>
*/
/*****************************************
reset.css
******************************************/
html,body,.section,.widget,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,font,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,figure{margin:0;padding:0}html{overflow-x:hidden}a{text-decoration:none;color:#000}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}table{border-collapse:separate;border-spacing:0}caption,th,td{text-align:right;font-weight:400}blockquote:before,blockquote:after,q:before,q:after{content:""}.quickedit,.home-link{display:none}blockquote,q{quotes:"" ""}sup{vertical-align:super;font-size:smaller}code{font-family:'Courier New',Courier,monospace;font-size:12px;color:#272727}::selection{background:transparent;text-shadow:#000 0 0 2px}::-moz-selection{background:transparent;text-shadow:#000 0 0 2px}::-webkit-selection{background:transparent;text-shadow:#000 0 0 2px}::-o-selection{background:transparent;text-shadow:#000 0 0 2px}a img{border:none}ol,ul{padding:0;margin:0;text-align:right}ol li{list-style-type:decimal;padding:0 0 5px}ul li{list-style-type:disc;padding:0 0 5px}ul ul,ol ol{padding:0}#navbar-iframe,.navbar{height:0;visibility:hidden;display:none}.post-footer-line.post-footer-line-1,.post-footer-line.post-footer-line-2,.post-footer-line.post-footer-line-3{display:none}.feed-links{display:none;visibility:hidden}.item-control{display:none!important}h2.date-header,h4.date-header{display:none;margin:1.5em 0 .5em}h1,h2,h3,h4,h5,h6{font-family:'neo',serif;font-weight:700;color:#2e2e2e}blockquote{padding:8px;background-color:#faebbc;border-top:1px solid #e1cc89;border-bottom:1px solid #e1cc89;margin:5px;background-image:url(http://1.bp.blogspot.com/-siy6EKYCLtM/U6X4AdKrr0I/AAAAAAAANDs/HCjRvuedDro/s1600/openquote1.gif);background-position:top right;background-repeat:no-repeat;text-indent:23px}blockquote p{display:block;background-image:url(http://3.bp.blogspot.com/-UjppXQI-ww0/U6X4IpheNiI/AAAAAAAAND0/PJhRvvhAWGU/s1600/closequote1.gif);background-repeat:no-repeat;background-position:bottom left}*{outline:0;transition:all .3s ease;-webkit-transition:all .3s ease;-moz-transition:all .3s ease;-o-transition:all .3s ease}@media print{.nav-menu,#sidebar-wrapper,.share-box,#related-posts,#lower,.sub-wrap,.comments,#ads-blog{display:none!important}#main-wrapper{width:100%!important;max-width:100%!important}}#loader{display:none;position:fixed;top:0;right:0;left:0;width:100%;height:100%;background-color:#FFF;z-index:1000}#status{display:none;width:200px;height:200px;position:fixed;right:50%;z-index:100;top:50%;background-image:url(https://2.bp.blogspot.com/-885osCcs6CA/V8kwiiRItZI/AAAAAAAAA1Q/ej5g-D7Y74MXTcLqJOWA5FGMbjFHbFJXwCLcB/s1600/hourglass.gif);background-repeat:no-repeat;background-position:center;margin:-100px -100px 0 0;z-index:1001}img{max-width:100%;verticle-align:middle}body{color:#2e2e2e;font-family:'neo',serif;font-size:14px;font-weight:400;line-height:21px;background:$mainbgcolor url(http://2.bp.blogspot.com/-ReAMfeZ3V68/Vs8X1mFeG6I/AAAAAAAADHU/0uaR6bxj7hU/s1600-r/bg2.png) repeat scroll top right}#outer-wrapper{max-width:100%;margin:0 auto;background-color:#FFF;box-shadow:0 0 5px RGBA(0,0,0,0.2)}.row{width:1110px;margin:0 auto}#content-wrapper{margin:0 auto;padding:40px 0}#main-wrapper{float:right;width:67%;max-width:750px}#sidebar-wrapper{float:left;width:30%;max-width:330px}#header-wrapper{background:$primarycolor;border-bottom:1px solid #e2e2e2}#header-wrappers{color:#fff;padding:25px 0 10px;border-bottom:1px solid rgba(255,255,255,0.4);height:80px}#header-inner{background-position:right;background-repeat:no}.headerright h1,.headerright h1 a,.headerright h1 a:hover,.headerright h1 a:visited{color$secondcolor;color:#fff!important;text-align:center;font-size:42px;font-weight:400;line-height:1.2em;margin:8px 0 0;padding:5px 0;text-decoration:none;border-radius:5px}.headerright h3{font-weight:400;margin:0;padding:0}.headerright .description{color:#fff;margin:0;padding:10px 30px 0 0;text-shadow:1px 1px 2px #555}.headerright{float:right;margin:0;padding:0;max-width:265px}.headerleft{float:left;margin:0;padding:0;max-widthh:900px}.selectnav{display:none}.nav-menu{text-align:center;margin:0 auto;width:100%;z-index:299;padding:16px 0}#nav-menu1{margin:0 auto}.nav-menu ul{list-style:none;margin:0;padding:0;z-index:999}.nav-menu ul li{display:inline-block;float:right;line-height:1;list-style:none outside none;padding:0;text-align:right;margin-left:6px}.nav-menu li a{background:transparent;color:#fff;display:block;font-size:17px;padding:16px 17px;position:relative;text-decoration:none;text-transform:uppercase;font-family:'neo',serif}.nav-menu li a:hover,.nav-menu ul li.highlight a{background:$secondcolor;color:#FFF}.nav-menu ul li ul{width:180px;margin:0;position:absolute;visibility:hidden;display:inline;padding:0;height:auto;border-top-width:0;background:$secondcolor;transition:none}.nav-menu ul li:hover ul{visibility:visible}.nav-menu li li a{color:#fff;font-size:14px;padding:16px 17px;position:relative;text-align:right}.nav-menu li li{float:none!important;display:block;border-bottom:1px solid #222}.nav-menu a#pull{display:none}.nav-menu ul li.hasSub a{padding-left:25px}.nav-menu ul li.hasSub a:after{color:rgba(255,255,255,0.4);position:absolute;top:15px;left:10px;display:block;content:"\f107";font-family:FontAwesome;font-weight:400;font-size:15px;text-rendering:auto;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale}.nav-menu ul li.hasSub ul li a:after{display:none!important}.sec-head{text-align:center;margin:0 auto;max-width:80%;margin-bottom:32px;color:#fff;padding:30px 0 0}.sec-head p{font-size:16px;padding:6px 0}.sec-head h2{font-size:35px;color:#fff}.box-sec{margin -bottom:-60px!important}#slider_post{position:relative;padding:0;margin:0 auto}#slider_post ul{padding:0}.owl-carousel .owl-wrapper:after{content:".";display:block;clear:both;visibility:hidden;line-height:0;height:0}.owl-carousel{display:none;position:relative;width:100%;-ms-touch-action:pan-y}.owl-carousel .owl-wrapper{display:none;position:relative;-webkit-transform:translate3d(0px,0px,0px)}.owl-carousel .owl-wrapper-outer{overflow:hidden;position:relative;width:100%}.owl-carousel .owl-wrapper-outer.autoHeight{-webkit-transition:height 500ms ease-in-out;-moz-transition:height 500ms ease-in-out;-ms-transition:height 500ms ease-in-out;-o-transition:height 500ms ease-in-out;transition:height 500ms ease-in-out}.owl-controls .owl-page,.owl-controls .owl-buttons div{cursor:pointer}.owl-controls{-webkit-user-select:none;-khtml-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;-webkit-tap-highlight-color:rgba(0,0,0,0)}.grabbing,.grabbing a,.grabbing *{cursor:e-resize!important}.owl-carousel .owl-wrapper,.owl-carousel .owl-item{-webkit-backface-visibility:hidden;-moz-backface-visibility:hidden;-ms-backface-visibility:hidden;-webkit-transform:translate3d(0,0,0);-moz-transform:translate3d(0,0,0);-ms-transform:translate3d(0,0,0)}.owl-prev,.owl-next{top:40%;color:#ccc;font-family:FontAwesome;position:absolute;z-index:1;display:block;padding:0;cursor:pointer;padding:0;text-align:center;overflow:hidden}.owl-prev{right:0}.label_with_thumbs .owl-prev,.label_with_thumbs .owl-next{margin-top:0;font-size:80px}.label_with_thumbs .owl-prev{right:-60px}.label_with_thumbs .owl-next{left:-60px}.label_with_thumbs .owl-dots{bottom:10px}.owl-next:before{font-family:fontawesome}.owl-prev:before{font-family:fontawesome}.owl-carousel{padding:5px 0}.label_with_thumbs .owl-carousel{border:0;padding:0}.label_with_thumbs .owl-item li{margin:0;padding:0;margin-left:10px}.label_with_thumbs .owl-prev:hover,.label_with_thumbs .owl-next:hover{opacity:.9;color:#333}.owl-next:before{content:'\f105';font-family:fontawesome}.owl-prev:before{content:'\f104';font-family:fontawesome}.owl-carousel .owl-item{float:right}.box-title .owl-controls{float:left}.label_with_thumbs{min-height:70px;margin:0 0 2px 10px;padding:0}ul.label_with_thumbs li{padding:8px 0;min-height:65px;margin-bottom:0}.label_with_thumbs li{list-style:none;padding-right:0!important}.label_with_thumbs .owl-item li img{height:auto;width:100%}.label_with_thumbs .owl-item li .thumb-hover{content:no-close-quote;position:absolute;bottom:-5px;width:100%;background:url(http://2.bp.blogspot.com/-_IyTmlpHtg8/Vmi5pkn5ZAI/AAAAAAAACVI/G4Kylbm3CDo/s1600-r/gradient.png) repeat-x 0 -1px;opacity:.8;right:0;opacity:.9;background-size:200px 100%;height:200px}.label_with_thumbs .recent-thumb:after{content:no-close-quote;position:absolute;right:0;bottom:0;height:100%;width:100%;opacity:.5;background:-webkit-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-moz-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-ms-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:-o-linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%);background:linear-gradient(top,rgba(0,0,0,0.2) 50%,rgba(0,0,0,0.5) 70%,rgba(0,0,0,1) 100%)}.label_with_thumbs .slider-con{padding:15px;text-align:center}.slider-con{color:#fff;position:absolute;bottom:20px;width:100%;z-index:2;box-sizing:border-box}.slider-con a{color:#fff}.slider-con h3{padding-bottom:15px}.slider-con br{display:none}.featured-content{display:none}.wid-thumb{height:350px;position:relative;width:100%;display:block}.label_with_thumbs .recent-thumb{text-transform:capitalize;color:#fff;width:100%;height:100%;display:block;position:relative}.label_with_thumbs strong{padding-right:0;font-size:28px;line-height:35px}.sidebar .widget{margin-bottom:20px;position:relative}.sidebar h2{font-size:17px;line-height:27px;color:#000;padding:7px 15px;margin-bottom:25px;font-weight:600;text-transform:capitalize;position:relative;text-align:center;border:1px solid #777}.sidebar h2:before,.sidebar h2:after{content:'';display:block;position:absolute;margin:auto;top:0;bottom:0;background:#585858;width:8px;height:8px;text-align:center;-webkit-border-radius:100%;-moz-border-radius:100%;border-radius:100%;-webkit-transform:rotate(40deg);-moz-transform:rotate(40deg);-ms-transform:rotate(40deg);-o-transform:rotate(40eg)}.sidebar h2:after{left:16px}.sidebar ul,.sidebar li{list-style-type:none;margin:0;padding:0}.menu-tab li a,.sidetabs .section{transition:all 0 ease;-webkit-transition:all 0 ease;-moz-transition:all 0 ease;-o-transition:all 0 ease;-ms-transition:all 0 ease}.menu-tab{overflow:hidden;clear:both;padding:0;margin:0 0 10px}.sidetabs .widget h2{display:none}.menu-tab li{width:33.3%;float:right;display:inline-block;padding:0}.menu-tab li a{height:32px;text-align:center;padding:0;font-weight:700;display:block;color:#fff;background-color:#202020;font-size:11px;line-height:32px;text-transform:uppercase}.menu-tab li.active a{background-color:$primarycolor}.menu-tab li{display:none}.hide-tab{display:inline-block!important}#tabside3{margin-bottom:15px}article{padding:0}.post-outer{padding:0}.post{margin:10px 0;padding:10px 0}.post h2{margin-top:0;margin-bottom:0;line-height:20px;width:100%;text-overflow:ellipsis;overflow:hidden;white-space:nowrap;cursor:pointer}.post h2 a{color:#000}.post h2{margin:0 0 10px;padding:0}.retitle h2{margin:8px 0;display:block;font-size:18px}.post-body{margin:0;padding:10px;font-size:14px;line-height:26px}.block-image{position:relative;float:none;margin:0 auto;clear:both;height:250px;width:215px;max-width:100%;object-fit:cover;-webkit-perspective:600px;-moz-perspective:600px;perspective:600px}.block-image .thumb{width:100%;height:250px;object-fit:cover;position:relative;display:block}.block-image a{width:100%;height:250px;object-fit:cover;display:block;border-radius:5px;transition:all .3s ease-out!important;-webkit-transition:all .3s ease-out!important;-moz-transition:all .3s ease-out!important;-o-transition:all .3s ease-out!important;box-shadow:10px 10px 30px rgba(0,0,0,0.3)}.block-image a:before{content:"\f16b";font-family:FontAwesome;line-height:32px;width:32px;height:32px;font-size:18px;color:#fff;text-align:center;font-weight:400;position:absolute;top:45%;right:45%;opacity:0;padding:0;z-index:1;border:2px solid #fff;border-radius:50%;transition:all .25s ease-in-out 0}.block-image a:after{content:"";position:absolute;top:0;left:0;bottom:0;height:100%;width:100%;right:0;background:$primarycolor;opacity:0;visibility:hidden;transition:all .25s ease-in-out 0}.block-image:hover.block-image .thumb{-webkit-transform:rotateY(45deg);-moz-transform:rotateY(45deg);-o-transform:rotateY(45deg);transform:rotateY(45deg)}.bk-right{display:block;overflow:hidden;top:7px;height:95%;-webkit-transform:rotate3d(0,1,0,-90deg);transform:rotate3d(0,1,0,-90deg);position:absolute!important;width:40px;left:-11px;background-color:#222;-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}
.bk-right h2{font-size:20px;right: 45px;line-height:40px;text-align:left;position:absolute;top:10%;bottom:auto;height:40px;-webkit-transform-origin:0 0;-moz-transform-origin:0 0;transform-origin:0 0;-webkit-transform:rotate(90deg) translateY(-160px);color:#fff;transform:rotate(90deg) translateY(-160px);margin:0;padding:0;width:auto}.block-image:hover .bk-right{-webkit-transform:rotateY(-45deg);-o-transform:rotateY(45deg);transform:rotateY(-45deg);top:-15px;height:112%}.block-image:hover.block-image a:after{opacity:.8;visibility:visible}.block-image:hover.block-image a:before{opacity:1;visibility:visible;-ms-transform:rotate(360deg);-webkit-transform:rotate(360deg);transform:rotate(360deg)}.rw-ui-container.rw-dir-ltr .rw-report-link,.rw-ui-container.rw-valign-middle.rw-halign-left .rw-report-link{display:none!important}.rw-ui-info-inner-container:hover{background:none!important}.rw-ui-info-nub.rw-ui-info-inner-nub,.rw-ui-info-nub.rw-ui-info-outer-nub{display:none}.rw-ui-tooltip{display:none!important}.rw-ui-container.rw-size-small span.rw-ui-info{font-family:Open Sans,Arial,sans-serif;color:#b8b8b8!important;text-transform:uppercase;font-size:13px;display:none}.rw-ui-container{float:left;margin-top:-3px}.rw-ui-container.rw-halign-left,.rw-ui-container.rw-halign-left .rw-ui-info-inner-container{border-color:#fff!important}.rw-ui-report.rw-size-large.rw-halign-center.gradient.rw-dir-ltr.rw-type-nero.rw-meta-rating-29085119.rw-valign-bottom,.rw-ui-report.rw-dir-ltr,.rw-ui-container.rw-size-medium .rw-report-link{display:none!important}.date-header{color:#bdbdbd;display:block;font-size:12px;font-weight:400;line-height:1.3em;margin:0!important;padding:0}.date-header a{color:#bdbdbd}.post-header{padding:10px}#meta-post .fa-calendar-o{margin-right:8px}.post-meta{color:#bdbdbd;display:block;font-size:13px;font-weight:400;line-height:21px;margin:0;padding:0 0 5px;border-bottom:1px solid #f2f2f2}.post-meta a,.post-meta i{color:#CBCBCB}.post-timestamp{margin-right:5px}.label-head{margin-right:5px}.label-head a{padding-right:2px}.resumo{margin-top:10px;color:#919191}.resumo span{display:block;margin-bottom:8px;font-size:16px;line-height:31px}.post img{max-width:100%;padding:10px 0;position:relative;margin:0 auto}.post h3{font-size:18px;margin-top:20px;margin-bottom:10px;line-height:1.1}.second-meta{display:none}.comment-link{white-space:normal}#blog-pager{clear:both;text-align:center;padding:15px 0;background:#fff;color:#4d4d4d}.displaypageNum a,.showpage a,.pagecurrent,.blog-pager-older-link,.blog-pager-newer-link,.home-link,.showpageOf{font-family:'neo',serif;font-size:16px;padding:7px 14px;margin-left:5px;border-radius:2px;background:$primarycolor;color:#fff;font-weight:700;float:right;width: 90px;}.showpageOf{float:left!important}#blog-pager .pages{border:none}.firstpage,.lastpage{display:none}.share-box{position:relative;padding:10px}.share-title{border-bottom:2px solid #777;color:#010101;display:inline-block;padding-bottom:7px;font-size:15px;font-weight:500;position:relative;top:2px}.share-art{float:left;padding:0;padding-top:0;font-size:13px;font-weight:400;text-transform:capitalize}.share-art a{color:#fff;padding:3px 8px;margin-right:4px;border-radius:2px;display:inline-block;margin-left:0;background:#010101}.share-art a:hover{color:#fff}.share-art .fac-art{background:#3b5998}.share-art .fac-art:hover{background:rgba(49,77,145,0.7)}.share-art .twi-art{background:#00acee}.share-art .twi-art:hover{background:rgba(7,190,237,0.7)}.share-art .goo-art{background:#db4a39}.share-art .goo-art:hover{background:rgba(221,75,56,0.7)}.share-art .pin-art{background:#CA2127}.share-art .pin-art:hover{background:rgba(202,33,39,0.7)}.share-art .lin-art{background:#0077B5}.share-art .lin-art:hover{background:rgba(0,119,181,0.7)}.share-art .print-art{background:$secondcolor}.share-art .lin-art:hover{background:rgba(0,119,181,0.7)}.Thechni-author-box{border:1px solid #f2f2f2;background:#f8f8f8;overflow:hidden;padding:10px;margin:10px 0}.thechni-author-box img{float:right;margin-left:10px;border-radius:50%}.thechni-author-box p{padding:10px}.thechni-author-box b{font-family:'neo',serif;font-size:20px}#related-posts{margin-bottom:10px;padding:10px}.related li{width:31.276%;display:inline-block;height:auto;min-height:184px;float:right;margin-left:22px;overflow:hidden;position:relative}.related li h3{margin-top:0}.related-thumb{width:100%;height:250px;overflow:hidden;border-radius:2px}.related li .related-img{width:100%;height:250px;display:block;position:relative;transition:all .3s ease-out!important;-webkit-transition:all .3s ease-out!important;-moz-transition:all .3s ease-out!important;-o-transition:all .3s ease-out!important}.related li .related-img:hover{-webkit-transform:scale(1.1) rotate(-1.5deg)!important;-moz-transform:scale(1.1) rotate(-1.5deg)!important;transform:scale(1.1) rotate(-1.5deg)!important;transition:all .3s ease-out!important;-webkit-transition:all .3s ease-out!important;-moz-transition:all .3s ease-out!important;-o-transition:all .3s ease-out!important}.related-title a{font-size:14px;line-height:1.4em;padding:10px 0 4px;font-weight:500;color:#fff;display:block;text-shadow:0 .5px .5px rgba(34,34,34,0.3)}.related li:nth-of-type(3),.related li:nth-of-type(6),.related li:nth-of-type(9){margin-left:0}.related .related-tag{position:absolute;top:15px;right:15px;background-color:$primarycolor;color:#fff;text-transform:uppercase;font-weight:400;z-index:5;height:20px;line-height:20px;padding:0 6px;font-size:11px}.related .related-thumb .related-img:after{content:no-close-quote;position:absolute;right:0;bottom:0;width:100%;height:120px;background:url(http://3.bp.blogspot.com/-LnvazGBvKh8/VskckSkmzxI/AAAAAAAAC4s/erEgI6A_ih4/s1600-r/metabg.png) repeat-x;background-size:100% 100%;opacity:.8}.related-overlay{position:absolute;right:0;top:0;z-index:1;width:100%;height:100%;background-color:rgba(40,35,40,0.05)}.related-content{position:absolute;bottom:0;padding:15px 15px 11px;width:100%;line-height:1.2em;box-sizing:border-box;z-index:2}.related .related-content .recent-date{color:#ccc;font-size:12px;font-weight:400}.recent-date:before,.p-date:before{content:'\f017';font-family:fontawesome;margin-left:5px}.comment-form{overflow:hidden}iframe.blogger-iframe-colorize,iframe.blogger-comment-from-post{height:283px!important}.comments h3{line-height:normal;text-transform:uppercase;color:$secondcolor;font-weight:700;margin:0 0 20px;font-size:14px;padding:0}h4#comment-post-message{display:none;margin:0}.comments{clear:both;margin-top:10px;margin-bottom:0}.comments .comments-content{font-size:13px;margin-bottom:8px}.comments .comments-content .comment-thread ol{text-align:right;margin:13px 0;padding:0}.comments .avatar-image-container{background:#fff;border:1px solid #DDD;overflow:hidden;padding:6px}.comments .comment-block{position:relative;background:#fff;padding:15px;margin-right:60px;border-right:3px solid #ddd;border-top:1px solid #DDD;border-left:1px solid #DDD;border-bottom:1px solid #DDD}.comments .comment-block:before{content:"";width:0;height:0;position:absolute;left:100%;top:14px;border-width:10px;border-style:solid;border-color:transparent #DDD transparent transparent;display:block}.comments .comments-content .comment-replies{margin:8px 0;margin-right:60px}.comments .comments-content .comment-thread:empty{display:none}.comments .comment-replybox-single{background:#f0f0f0;padding:0;margin:8px 0;margin-right:60px}.comments .comment-replybox-thread{background:#f0f0f0;margin:8px 0 0;padding:0}.comments .comments-content .comment{margin-bottom:6px;padding:0}.comments .comments-content .comment:first-child{padding:0;margin:0}.comments .comments-content .comment:last-child{padding:0;margin:0}.comments .comment-thread.inline-thread .comment,.comments .comment-thread.inline-thread .comment:last-child{margin:0 30% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(6){margin:0 25% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(5){margin:0 20% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(4){margin:0 15% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(3){margin:0 10% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(2){margin:0 5% 5px 0}.comment .comment-thread.inline-thread .comment:nth-child(1){margin:0 0 5px}.comments .comments-content .comment-thread{margin:0;padding:0}.comments .comments-content .inline-thread{background:#fff;border:1px solid #DDD;padding:15px;margin:0}.comments .comments-content .icon.blog-author{display:inline}.comments .comments-content .icon.blog-author:after{content:"Author";background:$primarycolor;color:#fff;font-size:11px;padding:2px 5px}.comment-header{text-transform:uppercase;font-size:12px}.comments .comments-content .datetime{margin-right:6px}.comments .comments-content .datetime a{color:#888}.comments .comment .comment-actions a{display:inline-block;color:$secondcolor;font-weight:700;font-size:10px;line-height:15px;margin:4px 0 0 8px}.comments .continue a{color:$secondcolor;display:inline-block;font-size:10px}.comments .comment .comment-actions a:hover,.comments .continue a:hover{text-decoration:underline}.blogger-tab{display:block}.cmm-tabs .content-tab{background-color:transparent;padding:0}.cmm-tabs-header{margin-bottom:10px;border-bottom:2px solid #eee;position:relative}.cmm-tabs-header h3{display:inline-block;font-size:18px;margin:0;border-bottom:2px solid #777;color:#010101;top:2px;font-weight:500;padding-bottom:2px}.cmm-tabs-header h3 h9{display:none}.simplyTab .cmm-tabs-header .wrap-tab{float:left}.cmm-tabs-header .wrap-tab a{height:auto;line-height:1.2em;padding:3px 5px;font-size:14px;display:inline-block}.cmm-tabs-header .wrap-tab li{float:right;width:auto}.facebook-tab,.fb_iframe_widget_fluid span,.fb_iframe_widget iframe{width:100%!important}.cmm-tabs.simplyTab .content-tab{background-color:transparent;padding:0;margin-top:20px}.cmm-tabs.simplyTab .wrap-tab li a{border-radius:2px;text-transform:uppercase;color:#FFF;font-weight:500;background-color:$secondcolor;font-size:12px}.cmm-tabs.simplyTab .wrap-tab li a.activeTab{background-color:$primarycolor;color:#fff}.cmm-tabs.simplyTab .wrap-tab{float:left}.cmm-tabs.simplyTab .wrap-tab li{margin-right:5px;list-style:none}.wrap-tab{list-style:none}.content-tab{transition:all 0 ease;-webkit-transition:all 0 ease;-moz-transition:all 0 ease;-o-transition:all 0 ease}.sub-wrap{background-image:url(https://4.bp.blogspot.com/-OeDHvvNC6FY/V8f8bxqEtyI/AAAAAAAAA00/lJW9aFRzLTY3iZ7AGQUvBoOa53cldSYYwCLcB/s1600/bg-subcribe.png)!important;background-position:center!important;background-repeat:no-repeat!important;background-size:cover!important}#subscribe-css{position:relative;padding:80px 0;overflow:hidden}.subscribe-wrapper{color:#fff;font-size:16px;line-height:normal;margin:0;text-align:center;text-transform:none;font-weight:400;width:100%}.subscribe-form{clear:both;display:block;overflow:hidden}form.subscribe-form{clear:both;display:block;margin:0;width:auto;overflow:hidden}.mail-subcribe{float:right;content:"";width:30px;height:19px;background:url(https://2.bp.blogspot.com/-5MsNNT866fA/V8gAPbStzJI/AAAAAAAAA1A/s7JnGrzilrgAw6YVrRgKJZONURPHSeQmACLcB/s1600/subcribe-mail.png) no-repeat center center;position:absolute;margin-top:25px;margin-right:10px}.subscribe-css-email-field{border:none;background:transparent;border-bottom:1px solid rgba(0,0,0,0.1);box-sizing:border-box;color:#848484;margin:10px 0;padding:15px 20px;width:35%;text-indent:40px;font-family:neo}.subscribe-css-email-button{background:transparent;color:#f07c29;border:2px solid #f07c29;cursor:pointer;font-weight:700;padding:14px 30px;margin-right:15px;text-transform:none;font-size:16px;border-radius:50px;transition:all .6s;text-transform:uppercase;font-family:neo}.subscribe-css-email-button:hover{background:#f07c29;color:#fff}#subscribe-css p.subscribe-note{margin:16px;text-align:center;color:#848484;font-size:30px;font-weight:400;line-height:normal}#subscribe-css p.subscribe-note span{position:relative;overflow:hidden;font-weight:700;transition:all .5s;color:$primarycolor;font-size:40px;text-transform:uppercase}#subscribe-css p.subscribe-note span.itatu{font-weight:400;font-style:italic;color:#000;text-transform:lowercase;font-size:30px}#subscribe-css p.subscribe-note span.itatu:before,#subscribe-css p.subscribe-note span.itatu:after{display:none}#subscribe-css p.subscribe-note span:before{content:'';position:absolute;bottom:-2px;right:0;width:0;height:3px;margin:10px 0 0;background:#000;transition:all .5s}#subscribe-css:hover p.subscribe-note span:before{width:100%}#lower{margin:auto;padding:0 0 10px;width:100%;background:#fff}#lower-wrapper{margin:auto;padding:20px 0;border-bottom:5px double #eaeaea}#lowerbar-wrapper{float:right;margin:0 5px auto;padding-bottom:20px;width:32%;text-align:justify;color:#000;line-height:1.6em;word-wrap:break-word;overflow:hidden}.lowerbar{margin:0;padding:0}.lowerbar .widget{margin:0;padding:10px 20px 0;box-sizing:border-box}.lowerbar .widget-content{margin-top:10px;margin-bottom:20px;position:relative}.lowerbar h2{color:#303030;font-size:24px;margin-bottom:-1px;padding-left:15px;border-bottom:solid 1px #F5F5F5;padding-top:4px;padding-bottom:4px;min-width:10px;text-align:center}.lowerbar h2:before{background:$primarycolor;bottom:0;content:'';margin-right:-19px;position:absolute;width:38px;height:2px;right:50%}.lowerbar ul{margin:0 auto;padding:0;list-style-type:none}.lowerbar li{display:block;line-height:1.6em;margin-right:0!important;list-style-type:none}.lowerbar li a{text-decoration:none;color:$secondcolor}.lowerbar li a:hover{text-decoration:none}.lowerbar li:hover{display:block}#jugas_footer{color:$secondcolor;font-family:'neo',serif;font-weight:300;padding:15px 0}.copy-container{margin:0 auto;overflow:hidden}.jugas_footer_copyright a{color:$primarycolor}.jugas_footer_copyright{text-align:center}.home-ad .widget{width:728px;max-height:90px;padding:0 0 0 2%;margin:0 auto 20px!important;max-width:100%;box-sizing:border-box}.social-counter{margin:0;padding:0;overflow:hidden;margin-bottom:20px}.social-counter ul{margin:0;padding:0}.social-counter ul li{width:48%;float:right;text-align:right;margin:0 0 5px;padding:0 0 5px;position:relative;border-bottom:1px solid #f5f5f5}.social-counter ul li:nth-child(2),.social-counter ul li:nth-child(4),.social-counter ul li:nth-child(6),.social-counter ul li:nth-child(8){float:left}.social-counter ul li:nth-child(7),.social-counter ul li:nth-child(8){margin:0;padding:0;border:0}.social-counter ul li a{margin:0;padding:0}.item-icon{float:right;position:relative;text-align:center;vertical-align:middle;color:#fff;margin:0;display:inline-block;width:36px;height:36px;line-height:36px;font-size:20px;border-radius:2px}.hide-count{display:none}.item-count{display:inline-block;color:#202020;font-weight:700;font-size:14px;line-height:36px;float:right;padding-right:10px}.item-text{float:left;display:inline-block;color:#CBCBCB;font-size:12px;line-height:36px;font-weight:400}.item-social.facebook .item-icon{background-color:#5271b3}.item-social.twitter .item-icon{background-color:#49aff8}.item-social.gplus .item-icon{background-color:#cb2027}.item-social.rss .item-icon{background-color:#FFC200}.item-social.youtube .item-icon{background-color:#eb1a21}.item-social.dribbble .item-icon{background-color:#ea4c89}.item-social.instagram .item-icon{background-color:#4E729A}.item-social.pinterest .item-icon{background-color:#cb2027}.item-social.facebook .item-icon:before{content:"\f09a"}.item-social.twitter .item-icon:before{content:"\f099"}.item-social.gplus .item-icon:before{content:"\f0d5"}.item-social.rss .item-icon:before{content:"\f09e"}.item-social.youtube .item-icon:before{content:"\f16a"}.item-social.instagram .item-icon:before{content:"\f16d"}.item-social.dribbble .item-icon:before{content:"\f17d"}.item-social.pinterest .item-icon:before{content:"\f0d2"}.social-counter ul li:hover .item-icon{background-color:#202020}.social-counter ul li:hover .item-text{color:#FFD439}.sidebar .PopularPosts ul{margin:0;padding:0}.sidebar .PopularPosts ul li{list-style:none!important;padding:0!important;margin-bottom:10px;margin-left:10px;width:48.4%;float:right}.sidebar .PopularPosts ul li.odd{margin-left:0}.sidebar .PopularPosts .item-thumbnail{height:190px;margin:0;overflow:hidden;width:100%;position:relative}.sidebar .PopularPosts .item-title{di
splay:block;clear:both}.sidebar .PopularPosts img{height:100%;width:100%;object-fit:cover}.sidebar .PopularPosts .item-thumbnail:before{content:"\f019";font-family:FontAwesome;line-height:32px;width:32px;height:32px;font-size:18px;color:#fff;text-align:center;font-weight:400;position:absolute;top:45%;right:40%;opacity:1;padding:0;z-index:2;border:2px solid #fff;border-radius:50%;transition:all .25s ease-in-out 0}.sidebar .PopularPosts .item-title a{display:block;margin:0 auto;padding:5px 0;font-size:15px;line-height:20px;width:100%;cursor:pointer;text-align:center}.sidebar .PopularPosts .item-snippet{color:$secondcolor;margin:0 auto;display:none}.sidebar .PopularPosts .item-content{position:relative}.PopularPosts .img-overlay{position:absolute;right:0;top:0;z-index:1;width:100%;height:100%;background-color:$primarycolor;opacity:.5}.PopularPosts .item-thumbnail:hover a .img-overlay{background-color:rgba(40,35,40,0.3);opacity:1}.sidebar .PopularPosts .widget-content ul li:first-child,.sidebar .custom-widget li:first-child{padding-top:0;border-top:0}.sidebar .PopularPosts .widget-content ul li:last-child,.sidebar .custom-widget li:last-child{padding-bottom:0}.custom-widget li{overflow:hidden;border-bottom:1px solid #F5F5F5;padding:10px 0}.custom-widget li:first-child{padding-top:0}.custom-widget li:last-child{border-bottom:none}.custom-widget .rcthumb{position:relative;float:right;margin:0!important;width:80px;height:60px;overflow:hidden;display:block;vertical-align:middle}.custom-widget .post-panel{padding-right:10px;display:table-cell}.custom-widget .rcp-title{overflow:hidden;line-height:0;margin:0 0 2px;padding:0}.custom-widget .rcp-title a{color:#222;font-weight:400;font-size:13px;line-height:1.5em}.custom-widget .rcp-title a:hover{color:#0277bd}.custom-widget .rcthumb:hover .img-overlay{background-color:rgba(40,35,40,0.3)}.recent-author{margin-left:10px}.recent-author::before{content:'\f007';font-family:fontawesome;color:#bbb;margin-left:5px}.recent-author,.recent-date{color:#bdbdbd;font-size:12px;font-weight:400}.recent-date:before{content:'\f133';font-family:fontawesome;color:#bbb;margin-left:5px}.cmm-widget li .cmm-avatar{position:relative;overflow:hidden;padding:0;width:55px;height:55px;float:right;margin:0 0 0 10px}.cmm-widget li{background:none!important;clear:both;list-style:none;word-break:break-all;display:block;border-top:1px solid #F5F5F5;overflow:hidden;margin:0;padding:10px 0}.cmm-widget li:first-child{padding-top:0;border-top:0}.cmm-widget li:last-child{padding-bottom:0}.cmm-widget li span{margin-top:4px;color:#bdbdbd;display:block;line-height:1.2em;text-transform:lowercase;font-size:12px;font-style:italic;font-weight:400}.cmm-img{width:55px;height:55px;float:right;margin:0 0 0 10px}.cmm-widget a{color:#222;position:relative;font-size:13px;text-transform:capitalize;display:block;overflow:hidden;font-weight:400}.cmm-widget a:hover{color:$primarycolor}.cmm-widget{list-style:none;padding:0}.cloud-label-widget-content{text-align:right}.cloud-label-widget-content .label-count{background:$primarycolor;color:#fff!important;margin-right:-3px;white-space:nowrap;border-radius:2px;padding:1px 4px!important;font-size:12px!important;margin-left:5px}.cloud-label-widget-content .label-size{background:#ebebeb;display:block;float:right;font-size:11px;margin:0 0 5px 5px}.cloud-label-widget-content .label-size a,.cloud-label-widget-content .label-size span{height:18px!important;color:$secondcolor;display:inline-block;font-size:12px;font-weight:500!important;padding:6px 8px}.cloud-label-widget-content .label-size a{padding:6px 10px}.cloud-label-widget-content .label-size a:hover{color:#000!important}.cloud-label-widget-content .label-size,.cloud-label-widget-content .label-count{height:30px!important;line-height:19px!important;border-radius:2px}.cloud-label-widget-content .label-size:hover{background:$primarycolor;color:#fff!important}.cloud-label-widget-content .label-size:hover a{color:#fff!important}.cloud-label-widget-content .label-size:hover span{background:#ebebeb;color:$primarycolor!important;cursor:pointer}.cloud-label-widget-content .label-size-1,.label-size-2,.label-size-3,.label-size-4,.label-size-5{font-size:100%;opacity:10}.label-size-1,.label-size-2{opacity:100}.list-label-widget-content li{display:block;padding:8px 0;border-bottom:1px solid #ebebeb;position:relative}.list-label-widget-content li a:before{content:'\203a';position:absolute;right:0;top:2px;font-size:22px;color:#ebebeb}.list-label-widget-content li a{color:#2b2b2b;font-size:12px;padding-right:20px;font-weight:400;text-transform:uppercase}.list-label-widget-content li a:hover{color:#ebebeb}.list-label-widget-content li span:last-child{color:#ebebeb;font-size:12px;font-weight:700;position:absolute;top:9px;left:0}.contact-form-name,.contact-form-email,.contact-form-email-message,.contact-form-widget{max-width:none;margin-bottom:15px}.contact-form-name,.contact-form-email,.contact-form-email-message{background-color:#EBEBEB;border:1px solid #ccc}.contact-form-button-submit{max-width:none;width:100%;height:35px;color:#f07c29!important;border:2px solid #f07c29!important;background-image:none;background:transparent!important;cursor:pointer;font-style:normal;font-weight:400}.contact-form-name:focus,.contact-form-email:focus,.contact-form-email-message:focus{border:1px solid #f07c29}.contact-form-name:hover,.contact-form-email:hover,.contact-form-email-message:hover{border:1px solid #f07c29}.contact-form-button-submit:hover{background-color:#f07c29!important;background-image:none;color:#fff!important}@media only screen and (max-width : 1200px){.row{width:96%!important;margin:0 auto;float:none}#header-wrappers{height:100%}.headerleft,.headerright{float:none;width:100%;text-align:center;height:auto;margin:0 auto;clear:both}.headerright img{margin:auto;padding-bottom:15px}.headerleft{margin:10px auto 0}#nav-menu1{display:none}.selectnav{width:auto;color:#222;background:#f4f4f4;border:1px solid rgba(255,255,255,0.1);position:relative;border:0;padding:6px 10px!important;margin:5px 0;display:inline;width:50%;min-width:180px}#main-wrapper,#sidebar-wrapper{float:none;clear:both;width:100%;margin:0 auto}}@media only screen and (max-width : 980px){#lowerbar-wrapper{float:none;clear:both;width:100%;margin:0 auto}#sidebar-wrapper{padding-top:20px}.post-body{padding:0}}@media screen and (max-width : 880px){.home #header-wrapper{margin-bottom:10px}.item #content-wrapper{padding:15px 0 30px}}@media only screen and (max-width : 768px){.share-art span{display:none}.ops-404{width:80%!important}.title-404{font-size:160px!important}.index article{padding:10px}.related li{width:100%}.item .post{margin:0 0 10px;padding:0 0 10px}}@media only screen and (max-width : 480px){.subscribe-css-email-field{width:100%}.cmm-tabs-header h3{display:none}.cmm-tabs.simplyTab .wrap-tab{float:none;padding:0}.cmm-tabs.simplyTab .wrap-tab li{width:31%}.cmm-tabs.simplyTab .wrap-tab li a{width:90%}.index .post h2,.archive .post h2{line-height:34px;font-size:23px}h1.post-title{font-size:22px;margin-bottom:10px}#sidebar-wrapper{max-width:100%}.index .post-outer{padding:0}.index .post{margin:20px 0 15px!important}.index div.post-outer:nth-child(1) .post{margin:0 0 15px!important}.cmm-tabs-header{overflow:hidden;margin-top:10px}}@media only screen and (max-width : 360px){.title-404{font-size:150px!important}.Header .description p{display:none}.showpageOf{display:none}.share-title{display:none}}@media only screen and (max-width : 300px){#sidebar-wrapper{display:none}.archive .post h2,.index .post h2{line-height:29px!important;font-size:15px!important}article{overflow:hidden}#blog-pager{padding:0;margin:0}#subscribe-css p.subscribe-note span{font-size:20px}#subscribe-css p.subscribe-note span.itatu{font-size:18px}#subscribe-css p.subscribe-note{font-size:20px}.index .snippets,.archive .snippets,.thechni-author-box img,.share-box .post-author{display:none}.share-art,.share-box .post-author{float:none;margin:0 auto;text-align:center;clear:both}.read-more-wrap,.post-labels{float:none!important;clear:both;display:block;text-align:center}.ops-404{font-size:20px!important}.title-404{font-size:120px!important}h1.post-title{font-size:17px}.share-box{overflow:hidden}.sec-head h2{font-size:25px}}.PopularPosts img{padding-right:0!important}

#wrap {
    margin: 20px auto;
    text-align: center;
}

#wrap br {
    display: none;
}

.btn-slide, .btn-slide2 {
    position: relative;
    display: inline-block;
    height: 50px;
    width: 200px;
    line-height: 50px;
    padding: 0;
    border-radius: 50px;
    background: #fdfdfd;
    border: 2px solid #0099cc;
    margin: 10px;
    transition: .5s;
}

.btn-slide2 {
    border: 2px solid #efa666;
}

.btn-slide:hover {
    background-color: #0099cc;
}

.btn-slide2:hover {
    background-color: #efa666;
}

.btn-slide:hover span.circle, .btn-slide2:hover span.circle2 {
    right: 100%;
    margin-right: -45px;
    background-color: #fdfdfd;
    color: #0099cc;
}

.btn-slide2:hover span.circle2 {
    color: #efa666;
}

.btn-slide:hover span.title, .btn-slide2:hover span.title2 {
    right: 40px;
    opacity: 0;
}

.btn-slide:hover span.title-hover, .btn-slide2:hover span.title-hover2 {
    opacity: 1;
    right: 40px;
}

.btn-slide span.circle, .btn-slide2 span.circle2 {
    display: block;
    background-color: #0099cc;
    color: #fff;
    position: absolute;
    float: right;
    margin: 5px;
    line-height: 42px;
    height: 40px;
    width: 40px;
    top: 0;
    right: 0;
    transition: .5s;
    border-radius: 50%;
}

.btn-slide2 span.circle2 {
    background-color: #efa666;
}

.btn-slide span.title,
  .btn-slide span.title-hover, .btn-slide2 span.title2,
  .btn-slide2 span.title-hover2 {
    position: absolute;
    right: 90px;
    text-align: center;
    margin: 0 auto;
    font-size: 16px;
    font-weight: bold;
    color: #30abd5;
    transition: .5s;
}

.btn-slide2 span.title2,
  .btn-slide2 span.title-hover2 {
    color: #efa666;
    right: 80px;
  }

.btn-slide span.title-hover, .btn-slide2 span.title-hover2 {
    right: 80px;
    opacity: 0;
}

.btn-slide span.title-hover, .btn-slide2 span.title-hover2 {
    color: #fff;
}


#about{background-color:#fff;padding-top:50px;padding-bottom:50px;background-image:url(https://2.bp.blogspot.com/-w57VuTGUWJ8/WNHPscEAxGI/AAAAAAAACs8/rIu5g-6PY1A4xUlWMUvZitFYgbm72pnwgCLcB/s1600/wdbloog.png)!important;background-position:center center!important;background-repeat:no-repeat!important;background-size:cover!important;transition:opacity .5s ease 0;overflow:hidden;margin-bottom: 15px;}
.vc_column-inner{padding-top:35px;text-align:center}
#countdown-timer{font-weight:700;margin:0 -30px;display:inline-block}
#countdown-timer >.countdown-section{display:block;float:left;font-size:62px;line-height:1;color:#fff;margin:0 30px}
.countdown-section i{background-color: #FFFFFF;font-size:40px;color:#5A67A6;border-radius:50%;width:80px;height:80px;line-height:80px;margin-bottom:10px;padding-left:3px}
#countdown-timer >.countdown-section >.countdown-period{display:block;font-size:22px;margin-top:8px;line-height:1;text-transform:uppercase;letter-spacing:1px;color:#fff;font-weight:500}
.type-wrap{color:#FFF;font-size:63px;line-height:124px;font-weight:900;min-height:119px}
.element{direction:rtl;display:inline-block}
.typed-cursor{opacity:1;color:#7B88CC;font-weight:100;-webkit-animation:blink 0.7s infinite;-moz-animation:blink 0.7s infinite;-ms-animation:blink 0.7s infinite;-o-animation:blink 0.7s infinite;animation:blink 0.7s infinite}
.item #about,.error_page #about,.static_page #about{display:none}

]]></b:skin>

<b:template-skin><![CDATA[
/*------Layout (No Edit)----------*/
body#layout #outer-wrapper{padding:0;width:1073px}body#layout .section h4{color:#333!important}body#layout .option{background-color:#2c3e50!important;overflow:hidden!important}body#layout .option h4{font-size:16px;padding:4px 0 7px;color:#fff!important}body#layout .option .widget{float:right;width:33.33%}body#layout .option .widget.locked-widget .widget-content{background-color:#34495e!important;border-color:#455668!important;color:#fff!important}body#layout .option .widget.locked-widget .widget-content a.editlink{color:#fff!important;border:1px solid #233648;border-radius:2px;padding:2px 5px;background-color:#233648}body#layout #header-wrappers{height:auto;padding:0}body#layout .headerright{float:right;width:300px;max-height:none;margin:0;padding:0}body#layout #headerright{background-color:#b57dcc!important;border-color:#8a52a1!important}body#layout .headerright .widget-content{border-color:#8a52a1}body#layout .headerleft{width:420px;margin:0}body#layout .sec-head{display:block;background-color:#6dad88!important;border-color:#338957!important}body#layout .sec-head .widget-content{border-color:#338957!important}body#layout .navi-menu{height:auto}body#layout .header-menu li.li-home,body#layout .header-search,body#layout #loader,body#layout #status{display:none}body#layout .sec-head{float:right;width:95%;max-width:95%;margin:4px 0 0;padding:0}body#layout .box-sec{margin-bottom:0!important}body#layout .box-sec .widget-content,body#layout .box-sec h2,body#layout #ads-blog{display:block}body#layout #main-wrapper{float:right;width:70%;margin:0;padding:0}body#layout #sidebar-wrapper{float:left;width:30%;margin:0;padding:5px 0 0;background-color:#f8e244!important}body#layout #sidebar-wrapper .section{background-color:#fff;border:1px solid #fff}body#layout #sidebar-wrapper .section .widget-content{border-color:#5a7ea2!important}body#layout #sidebar-wrapper .section .draggable-widget .widget-wrap2{background-color:#5a7ea2!important}body#layout #lower{overflow:hidden}body#layout #lowerbar-wrapper{width:30%;float:right;margin:0 0 8px 2.2% !important}body#layout #unwanted,body#layout #pop-sec,body#layout #contact{display:none!important}body#layout .featuresub{background-color:#f38d83;border-color:#c5554a}body#layout .featuresub .widget-content{border-color:#c5554a}body#layout .ticker .widget{height:auto}body#layout .featuresub .draggable-widget .widget-wrap2{background-color:#c5554a!important}body#layout #featured-sec{background-color:#f9a85f;border-color:#fb8f3d}body#layout #featured-sec .widget-content{border-color:#fb8f3d}body#layout #featured-sec .draggable-widget .widget-wrap2{background-color:#fb8f3d!important}body#layout #main-wrapper #main{margin-left:4px;background-color:#5a7ea2;border-color:#34495e}body#layout #main-wrapper #main h4{color:#fff!important}body#layout .layout-widget-description{display:none!important}body#layout #Blog1 .widget-content{border-color:#34495e}body#layout .box-sec,body#layout .gallery-post{background-color:#7fc1ed!important;border-color:#3498db!important}body#layout .box-sec .widget-content,body#layout .gallery-post .widget-content{border-color:#3498db}body#layout .box-sec .draggable-widget .widget-wrap2,body#layout .gallery-post .draggable-widget .widget-wrap2{background-color:#3498db!important;cursor:move}body#layout #sidebar{margin-top:10px}body#layout #sidetabs{overflow:hidden;background-color:#e9d33c}body#layout #tabside1,body#layout #tabside2,body#layout #tabside3{width:83%;float:right}body#layout #lower-wrapper{overflow:hidden;background-color:#03a9f4;padding-top:10px;margin-bottom:10px}body#layout #lower-wrapper:before{content:"Footer Sections";font-size:25px;color:#fff;padding:0 0 10px;text-align:center;display:block}body#layout #lower-wrapper .section .widget-content{border-color:#03a9f4!important}body#layout #lower-wrapper .section .draggable-widget .widget-wrap2{background-color:#03a9f4!important}body#layout #headerleft,body#layout #ads-inter,body#layout #ads-home,body#layout #post-ads-footer{background-color:rgba(241,196,16,0.22)!important;border-color:#f1c410!important}body#layout #headerleft .widget-content,body#layout #ads-inter .widget-content,body#layout #ads-home .widget-content,body#layout #post-ads-footer .widget-content{border-color:#f1c410!important}body#layout #headerleft .draggable-widget .widget-wrap2,body#layout #ads-inter .draggable-widget .widget-wrap2,body#layout #ads-home .draggable-widget .widget-wrap2,body#layout #post-ads-footer .draggable-widget .widget-wrap2{background-color:#f1c410!important;cursor:move}
/*------Layout (end)----------*/
]]></b:template-skin>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType!= &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<style>
.post {
    width :  215px;
    height: 310px;
    float : right;
    margin:2px 0 15px 32px;
    padding: 0;
    background: #fff;
}
@media only screen and (max-width :  768px) {
.post {
    width :  47.5% !important;
}
#content-wrapper {
    overflow: visible;
}
.post.odd {
    margin:2px 0 15px 0;
}
}
@media only screen and (max-width :  620px) {
.post {
    width :  100% !important;
}
.post {
    margin:2px 0 15px 0;
}
}
</style>
  </b:if>
</b:if>
</b:if>
<script type='text/javascript'> 
//<![CDATA[
var no_image = "http://3.bp.blogspot.com/-Yw8BIuvwoSQ/VsjkCIMoltI/AAAAAAAAC4c/s55PW6xEKn0/s1600-r/nth.png";
var month_format = [, "يناير", "فبراير", "مارس", "أبريل", "ماي", "يونيو", "يوليوز", "غشت", "شتنبر", "أكتوبر", "نونبر", "دجنبر"];
var more_text = "مشاهدة المزيد";
var related_number = 3;
var comments_text = "<span>أنشر </span>تعليقا";
var pagenav_prev = "السابق";
var pagenav_next = "التالي";
//]]>
</script>
<script type='text/javascript'>
//<![CDATA[
(function(d, t, e, m){
    // Async Rating-Widget initialization.
    window.RW_Async_Init = function(){
        RW.init({
            huid: "327106",
            uid: "5d7d5c8b1e8e1238b99e52e8a7f411cc",
            options: { "style": "oxygen" } 
        });
        RW.render();
    };

    // Append Rating-Widget JavaScript library.
    var rw, s = d.getElementsByTagName(e)[0], id = "rw-js",
        l = d.location, ck = "Y" + t.getFullYear() + 
        "M" + t.getMonth() + "D" + t.getDate(), p = l.protocol,
        f = (-1 < l.search.indexOf('DBG=') ? '' : '.min'),
        a = ("https:" == p ? "secure." + m + "js/" : "js." + m);
    if (d.getElementById(id)) return;              
    rw = d.createElement(e);
    rw.id = id; rw.async = true; rw.type = "text/javascript";
    rw.src = p + "//" + a + "external" + f + ".js?ck=" + ck;
    s.parentNode.insertBefore(rw, s);
}(document, new Date(), "script", "rating-widget.com/"));

//]]>
</script>
<b:if cond='data:blog.url == data:blog.homepageUrl'>
<script type='text/javascript'>
//<![CDATA[
$(document).ready(function() {
      $(".label_with_thumbs").owlCarousel({

      items: 4,
smartSpeed: 550,
                                navigation: true,
                                navigationText: ["", ""],
                                itemsDesktop: [1000, 1],
                                itemsDesktopSmall: [647, 1],
                                itemsTablet: [396, 1],
                                autoPlay: false,
                                autoPlay: 5000,
                                itemsMobile: false,
                                pagination: true,
 responsive: {
                                0: {
                                    items: 1,
                                    nav: true
                                },
                                601: {
                                    items: 2,
                                    nav: false
                                },
                                800: {
                                    items: 3,
                                    nav: false
                                },
                                980: {
                                    items: 4,
                                    nav: true
                                }
                            }

      // "singleItem:true" is a shortcut for:
      // items : 1, 
      // itemsDesktop : false,
      // itemsDesktopSmall : false,
      // itemsTablet: false,
      // itemsMobile : false

      });
    });
var numposts = 4;
var showpostthumbnails = true;
var displaymore = true;
var displayseparator = false;
var showcommentnum = true;
var showpostdate = false;
var showpostsummary = true;
var numchars = 100;

function labelthumbs(json) {
    document.write('<ul class="label_with_thumbs owl-carousel owl-theme">');
    for (var i = 0; i < numposts; i++) {
        var entry = json.feed.entry[i];
        var posttitle = entry.title.$t;
        var posturl;
        if (i == json.feed.entry.length) break;
        for (var k = 0; k < entry.link.length; k++) {
            if (entry.link[k].rel == 'replies' && entry.link[k].type == 'text/html') {
                var commenttext = entry.link[k].title;
                var commenturl = entry.link[k].href
            }
            if (entry.link[k].rel == 'alternate') {
                posturl = entry.link[k].href;
                break
            }
        }
        var thumburl;
        try {
            thumburl = entry.media$thumbnail.url
        } catch (error) {
            s = entry.content.$t;
            a = s.indexOf("<img");
            b = s.indexOf("src=\"", a);
            c = s.indexOf("\"", b + 5);
            d = s.substr(b + 5, c - b - 5);
            if ((a != -1) && (b != -1) && (c != -1) && (d != "")) {
                thumburl = d
            } else thumburl = 'http://3.bp.blogspot.com/-zP87C2q9yog/UVopoHY30SI/AAAAAAAAE5k/AIyPvrpGLn8/s1600/picture_not_available.png'
        }
        var postdate = entry.published.$t;
        var cdyear = postdate.substring(0, 4);
        var cdmonth = postdate.substring(5, 7);
        var cdday = postdate.substring(8, 10);
        var monthnames = new Array();
        monthnames[1] = "Jan";
        monthnames[2] = "Feb";
        monthnames[3] = "Mar";
        monthnames[4] = "Apr";
        monthnames[5] = "May";
        monthnames[6] = "June";
        monthnames[7] = "July";
        monthnames[8] = "Aug";
        monthnames[9] = "Sept";
        monthnames[10] = "Oct";
        monthnames[11] = "Nov";
        monthnames[12] = "Dec";
        document.write('<div class="item"><li class="clearfix"><div class="wid-thumb">');
        if (showpostthumbnails == !0) document.write('<a class="slider-thumb recent-thumb" href="' + posturl + '" style="background:url(' + thumburl.replace('/s72-c/', '/s1600/') + ') no-repeat center center;background-size: cover" target ="_top"><div class="thumb-hover"></div></a></div>');
        document.write('<div class="slider-con"><h3><strong><a href="' + posturl + '" target ="_top">' + posttitle + '</a></strong></h3><br><div class="featured-content">');
        if ("content" in entry) {
            var postcontent = entry.content.$t
        } else if ("summary" in entry) {
            var postcontent = entry.summary.$t
        } else var postcontent = "";
        var re = /<\S[^>]*>/g;
        postcontent = postcontent.replace(re, "");
        if (showpostsummary == !0) {
            if (postcontent.length < numchars) {
                document.write('');
                document.write(postcontent);
                document.write('')
            } else {
                document.write('');
                postcontent = postcontent.substring(0, numchars);
                var quoteEnd = postcontent.lastIndexOf(" ");
                postcontent = postcontent.substring(0, quoteEnd);
                document.write(postcontent + '...');
                document.write('')
            }
        }
        var towrite = '';
        var flag = 0;
        document.write('</div><br><div class="featured-meta-con"> ');
        if (showpostdate == !0) {
            towrite = towrite + monthnames[parseInt(cdmonth, 10)] + '-' + cdday + ' - ' + cdyear;
            flag = 1
        }
        if (showcommentnum == !0) {
            if (flag == 1) {
                towrite = towrite + ' | '
            }
            if (commenttext == '1 Comments') commenttext = '1 Comment';
            if (commenttext == '0 Comments') commenttext = 'No Comments';
            commenttext = '<i class="fa fa-comments-o"></i> <a href="' + commenturl + '" target ="_top">' + commenttext + '</a>';
            towrite = towrite + commenttext;
            flag = 1
        }
        if (displaymore == !0) {
            if (flag == 1) towrite = towrite + ' | ';
            towrite = towrite + '<a href="' + posturl + '" class="url" target ="_top">تصفح!</div></div>';
            flag = 1
        }
        document.write(towrite);
        document.write('</li></div>');
        if (displayseparator == !0)
            if (i != (numposts - 1)) document.write('')
    }
    document.write('</ul>')
}
$(document).ready(function() {
    $('ul.recent_posts_with_thumbs li:nth-child(n+3) .post-title').each(function() {
        var txt = $(this).text().substr(0, 30);
        var j = txt.lastIndexOf(' ');
        if (j > 10) $(this).text(txt.substr(0, j).replace(/[?,!\.-:;]*$/, '...'))
    })
})
//]]>

</script>
  
  </b:if>

<link href='//netdna.bootstrapcdn.com/font-awesome/4.0.3/css/font-awesome.css' rel='stylesheet'/>

  </head>
  <body expr:class='data:blog.pageType'>
<div class='theme-opt' style='display :none'>
    <b:section class='option' id='option' maxwidgets='1' name='Theme Options' showaddelement='yes'>
      <b:widget id='HTML900' locked='true' title='Full Width CSS' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>
          &lt;style&gt;@media only screen and (min-width : 1143px){#outer-wrapper{max-width : <data:content/>;}}&lt;/style&gt;
        </b:includable>
      </b:widget>
      <b:widget id='HTML910' locked='true' title='PageNavi Results No.' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>  
          <b:if cond='data:content == &quot;&quot;'>       
            <script type='text/javascript'>
              //<![CDATA[
              var perPage = 12;
              //]]>
            </script>
            <b:else/>
            &lt;script type=&#39;text/javascript&#39;&gt;
            //&lt;![CDATA[
                var perPage = <data:content/>;
            //]]&gt;
            &lt;/script&gt;
          </b:if>
        </b:includable>
      </b:widget>
      <b:widget id='HTML920' locked='true' title='Carousel Display' type='HTML' version='1'>
        <b:widget-settings>
          <b:widget-setting name='content'/>
        </b:widget-settings>
        <b:includable id='main'>  
          <b:if cond='data:content == &quot;&quot;'>       
           <style>
.box-sec {
    display : block;
}
</style>
 <b:else/>
          &lt;style&gt;.box-sec{display :<data:content/>;}&lt;/style&gt;
          </b:if>
        </b:includable>
      </b:widget>
    </b:section>
  </div>
<b:if cond='data:blog.url == data:blog.homepageUrl'><div id='status'/>
  <div id='loader'/></b:if>
&lt;div id=&quot;outer-wrapper&quot; class=&quot;<data:blog.pageType/><b:if cond='data:blog.url == data:blog.homepageUrl'> home</b:if><b:if cond='data:blog.pageType == &quot;static_page&quot;'> item</b:if><b:if cond='data:blog.pageType == &quot;archive&quot;'> index</b:if>&quot;&gt;
<div id='header-wrapper'> 
<div class='row' id='header-wrappers'> 
<div class='headerright' id='header-wp' itemscope='' itemtype='http://schema.org/WPHeader'> 
      <b:section class='headerright' id='headerright' maxwidgets='1' showaddelement='no'>
         <b:widget id='Header1' locked='true' title='ProfNabil (en-tête)' type='Header' version='1'>
           <b:widget-settings>
             <b:widget-setting name='displayUrl'>http://2.bp.blogspot.com/-rzKNKavjtVc/Xos46BiQbqI/AAAAAAAAAAU/d5dTWYB7wIIekFE7DhaJRj5_GKQNJHTOwCK4BGAYYCw/s1600/IMG_20200314_171307.jpg</b:widget-setting>
             <b:widget-setting name='displayHeight'>530</b:widget-setting>
             <b:widget-setting name='sectionWidth'>150</b:widget-setting>
             <b:widget-setting name='useImage'>true</b:widget-setting>
             <b:widget-setting name='shrinkToFit'>false</b:widget-setting>
             <b:widget-setting name='imagePlacement'>BEHIND</b:widget-setting>
             <b:widget-setting name='displayWidth'>672</b:widget-setting>
           </b:widget-settings>
           <b:includable id='main'>
  <b:if cond='data:useImage'>
    <b:if cond='data:imagePlacement == &quot;BEHIND&quot;'>
      <!--
      Show image as background to text. You can't really calculate the width
      reliably in JS because margins are not taken into account by any of
      clientWidth, offsetWidth or scrollWidth, so we don't force a minimum
      width if the user is using shrink to fit.
      This results in a margin-width's worth of pixels being cropped. If the
      user is not using shrink to fit then we expand the header.
      -->
      <b:if cond='data:mobile'>
        <div id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' itemprop='name' style='background: transparent; border-width :  0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      <b:else/>
        <div expr:style='&quot;background-image: url(\&quot;&quot; + data:sourceUrl + &quot;\&quot;); &quot;                      + &quot;background-position : &quot;                      + data:backgroundPositionStyleStr + &quot;; &quot;                      + data:widthStyleStr                      + &quot;min-height: &quot; + data:height                      + &quot;_height: &quot; + data:height                      + &quot;background-repeat: no-repeat; &quot;' id='header-inner'>
          <div class='titlewrapper' style='background: transparent'>
            <h1 class='title' style='background: transparent; border-width :  0px'>
              <b:include name='title'/>
            </h1>
          </div>
          <b:include name='description'/>
        </div>
      </b:if>
    <b:else/>
      <!--Show the image only-->
      <div id='header-inner'>
        <a expr:href='data:blog.homepageUrl' itemprop='url' style='display : block'><h1 style='display :none;'/>
          <img expr:alt='data:title' expr:height='data:height' expr:id='data:widget.instanceId + &quot;_headerimg&quot;' expr:src='data:sourceUrl' expr:width='data:width' style='display : block'/>
        </a>
        <!--Show the description-->
        <b:if cond='data:imagePlacement == &quot;BEFORE_DESCRIPTION&quot;'>
          <b:include name='description'/>
        </b:if>
      </div>
    </b:if>
  <b:else/>
    <!--No header image -->
    <div id='header-inner'>
      <div class='titlewrapper'>
        <h1 class='title' itemprop='name'>
          <b:include name='title'/>
        </h1>
      </div>
      <b:include name='description'/>
    </div>
  </b:if>
</b:includable>
           <b:includable id='description'>
  <div class='descriptionwrapper'>
    <p class='description'><span><data:description/></span></p>
  </div>
</b:includable>
           <b:includable id='title'>
  <b:if cond='data:blog.url == data:blog.homepageUrl'>
    <data:title/>
  <b:else/>
    <a expr:href='data:blog.homepageUrl'><data:title/></a>
  </b:if>
</b:includable>
         </b:widget>
       </b:section> 
</div>
<div class='headerleft'> 
<b:section class='headerleft nav-menu' id='headerleft' maxwidgets='1' showaddelement='yes'>
   <b:widget id='LinkList100' locked='true' title='ProfNabil' type='LinkList' version='1'>
     <b:includable id='main'>

 <div class='widget-content'>

   <ul id='nav-menu1' itemscope='' itemtype='http://schema.org/SiteNavigationElement'>
     <b:loop values='data:links' var='link'>
       <li itemprop='name'><a expr:href='data:link.target' itemprop='url'><data:link.name/></a></li>
     </b:loop>

   </ul>
 
 <script type='text/javascript'> 
            //<![CDATA[
            $("#LinkList100").each(function(){var e="<ul id='nav-menu1'><li><ul id='sub-menu'>";$("#LinkList100 li").each(function(){var t=$(this).text(),n=t.substr(0,1),r=t.substr(1);"_"==n?(n=$(this).find("a").attr("href"),e+='<li><a href="'+n+'">'+r+"</a></li>"):(n=$(this).find("a").attr("href"),e+='</ul></li><li><a href="'+n+'">'+t+"</a><ul id='sub-menu'>")});e+="</ul></li></ul>";$(this).html(e);$("#LinkList100 ul").each(function(){var e=$(this);if(e.html().replace(/\s|&nbsp;/g,"").length==0)e.remove()});$("#LinkList100 li").each(function(){var e=$(this);if(e.html().replace(/\s|&nbsp;/g,"").length==0)e.remove()})});

            //]]>
            </script>
 
</div>
</b:includable>
   </b:widget>
 </b:section> 
</div></div>
<div style='clear: both;'/>
 <b:if cond='data:blog.canonicalUrl == data:blog.canonicalHomepageUrl'> 
<style>
#content-wrapper {
    margin-top: 40px;
}
</style>
 <div class='row' id='second-head'>
      <b:section class='sec-head' id='sec-head' maxwidgets='1' name='Second Header' showaddelement='yes'>
        <b:widget id='HTML9' locked='false' title='' type='HTML'>
          <b:widget-settings>
            <b:widget-setting name='content'>&lt;h2 class=&#39;type-wrap&#39;&gt;
&lt;div class=&#39;element&#39;/&gt;
&lt;/div&gt;&lt;/h2&gt;</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
      </b:section>
<div style='clear: both;'/>
    </div>
  <div class='featured-slider-wrap row'>
 <b:section class='featuresliderpost box-sec' id='Featured Slider Widget box-sec' maxwidget='1' showaddelement='no'>
   <b:widget id='HTML186' locked='true' title='السلايدر' type='HTML' version='1'>
     <b:widget-settings>
       <b:widget-setting name='content'/>
     </b:widget-settings>
     <b:includable id='main'>
          
          <div id='slider_post'> &lt;script src=&#39;/feeds/posts/default/-/<data:content/>?+ numposts +&amp;amp;orderby=published&amp;amp;alt=json-in-script&amp;amp;callbackpublished&amp;amp;alt=json-in-script&amp;amp;callback=labelthumbs&#39; type=&#39;text/javascript&#39;&gt;
  &lt;/script&gt;</div>
         
        </b:includable>
   </b:widget>
 </b:section>

    </div>
    </b:if>
    </div>
<div class='row' id='content-wrapper'>
<div id='main-wrapper'>
 <div id='ads-blog'>
      <b:section class='home-ad' id='ads-home' maxwidgets='1' name='Home ADS' showaddelement='yes'>
        <b:widget id='HTML122' locked='false' title='' type='HTML'>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
      </b:section>
<div style='clear: both;'/>
    </div>
<b:section class='main' id='main' showaddelement='yes'>
  <b:widget id='Blog1' locked='true' title='Articles du blog' type='Blog' version='1'>
    <b:widget-settings>
      <b:widget-setting name='showDateHeader'>true</b:widget-setting>
      <b:widget-setting name='style.textcolor'>#03a9f4</b:widget-setting>
      <b:widget-setting name='showShareButtons'>true</b:widget-setting>
      <b:widget-setting name='authorLabel'>By</b:widget-setting>
      <b:widget-setting name='showCommentLink'>true</b:widget-setting>
      <b:widget-setting name='style.urlcolor'>#f0f0f0</b:widget-setting>
      <b:widget-setting name='showAuthor'>false</b:widget-setting>
      <b:widget-setting name='disableGooglePlusShare'>true</b:widget-setting>
      <b:widget-setting name='style.linkcolor'>#f0f0f0</b:widget-setting>
      <b:widget-setting name='style.unittype'>TextAndImage</b:widget-setting>
      <b:widget-setting name='style.bgcolor'>#000000</b:widget-setting>
      <b:widget-setting name='showAuthorProfile'>false</b:widget-setting>
      <b:widget-setting name='style.layout'>1x1</b:widget-setting>
      <b:widget-setting name='showLabels'>true</b:widget-setting>
      <b:widget-setting name='showLocation'>true</b:widget-setting>
      <b:widget-setting name='showTimestamp'>true</b:widget-setting>
      <b:widget-setting name='postsPerAd'>3</b:widget-setting>
      <b:widget-setting name='showBacklinks'>false</b:widget-setting>
      <b:widget-setting name='style.bordercolor'>#000000</b:widget-setting>
      <b:widget-setting name='showInlineAds'>true</b:widget-setting>
      <b:widget-setting name='showReactions'>false</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main' var='top'>
  <b:if cond='!data:mobile'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:loop values='data:posts' var='post'>
        <b:if cond='data:post.isDateStart and not data:post.isFirstPost'>
          &lt;/div&gt;&lt;/div&gt;
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-outer&quot;&gt;
        </b:if>
        <b:if cond='data:post.dateHeader'>
          <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
        </b:if>
        <b:if cond='data:post.isDateStart'>
          &lt;div class=&quot;date-posts&quot;&gt;
        </b:if>
        <div class='post-outer'>
          <b:include data='post' name='post'/>
          <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
        </div>

        <!-- Ad -->
        <b:if cond='data:post.includeAd'>
          <div class='inline-ad'>
            <data:adCode/>
          </div>
        </b:if>
      </b:loop>
      <b:if cond='data:numPosts != 0'>
        &lt;/div&gt;&lt;/div&gt;
      </b:if>
    </div>

    <!-- navigation -->
    <b:include name='nextprev'/>

    <!-- feed links -->
    <b:include name='feedLinks'/>

  <b:else/>
    <b:include name='mobile-main'/>
  </b:if>

  <b:if cond='data:top.showPlusOne'>
    <data:top.googlePlusBootstrap/>
  </b:if>

</b:includable>
    <b:includable id='backlinkDeleteIcon' var='backlink'>
  <span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
    <a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
      <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
    </a>
  </span>
</b:includable>
    <b:includable id='backlinks' var='post'>
  <a name='links'/><h4><data:post.backlinksLabel/></h4>
  <b:if cond='data:post.numBacklinks != 0'>
    <dl class='comments-block' id='comments-block'>
      <b:loop values='data:post.backlinks' var='backlink'>
        <div class='collapsed-backlink backlink-control'>
          <dt class='comment-title'>
            <span class='backlink-toggle-zippy'>&#160;</span>
            <a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
            <b:include data='backlink' name='backlinkDeleteIcon'/>
          </dt>
          <dd class='comment-body collapseable'>
            <data:backlink.snippet/>
          </dd>
          <dd class='comment-footer collapseable'>
            <span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
            <span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
          </dd>
        </div>
      </b:loop>
    </dl>
  </b:if>
  <p class='comment-footer'>
    <a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
  </p>
</b:includable>
    <b:includable id='comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <h4 id='comment-post-message'>
        <a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display : none' width='100%'/>
    <b:else/>
      <h4 id='comment-post-message'><data:postCommentMsg/></h4>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
    <b:includable id='commentDeleteIcon' var='comment'>
  <span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
    <b:if cond='data:showCmtPopup'>
      <div class='goog-toggle-button'>
        <div class='goog-inline-block comment-action-icon'/>
      </div>
    <b:else/>
      <a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
        <img src='https://resources.blogblog.com/img/icon_delete13.gif'/>
      </a>
    </b:if>
  </span>
</b:includable>
    <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
    <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:elseif cond='data:post.showThreadedComments'/>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
    <b:includable id='comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <b:if cond='data:post.allowComments'>
      <h4><data:post.commentLabelFull/>:</h4>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <b:if cond='data:post.hasOlderLinks'>
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
              &#160;
            <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
              &#160;
          </b:if>

          <data:post.commentRangeText/>

          <b:if cond='data:post.hasNewerLinks'>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
            &#160;
            <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
          </b:if>
        </span>
      </b:if>

      <div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
        <dl expr:class='data:post.avatarIndentClass' id='comments-block'>
          <b:loop values='data:post.comments' var='comment'>
            <dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
              <b:if cond='data:comment.favicon'>
                <img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
              </b:if>
              <a expr:name='data:comment.anchorName'/>
              <b:if cond='data:blog.enabledCommentProfileImages'>
                <data:comment.authorAvatarImage/>
              </b:if>
              <b:if cond='data:comment.authorUrl'>
                <a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
              <b:else/>
                <data:comment.author/>
              </b:if>
              <data:commentPostedByMsg/>
            </dt>
            <dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
              <b:if cond='data:comment.isDeleted'>
                <span class='deleted-comment'><data:comment.body/></span>
              <b:else/>
                <p>
                  <data:comment.body/>
                </p>
              </b:if>
            </dd>
            <dd class='comment-footer'>
              <span class='comment-timestamp'>
                <a expr:href='data:comment.url' title='comment permalink'>
                  <data:comment.timestamp/>
                </a>
                <b:include data='comment' name='commentDeleteIcon'/>
              </span>
            </dd>
          </b:loop>
        </dl>
      </div>

      <b:if cond='data:post.commentPagingRequired'>
        <span class='paging-control-container'>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
            <data:post.oldestLinkText/>
          </a>
          <a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
            <data:post.olderLinkText/>
          </a>
          &#160;
          <data:post.commentRangeText/>
          &#160;
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
            <data:post.newerLinkText/>
          </a>
          <a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
            <data:post.newestLinkText/>
          </a>
        </span>
      </b:if>

      <p class='comment-footer'>
        <b:if cond='data:post.embedCommentForm'>
          <b:if cond='data:post.allowNewComments'>
            <b:include data='post' name='comment-form'/>
          <b:else/>
            <data:post.noNewCommentsText/>
          </b:if>
        <b:elseif cond='data:post.allowComments'/>
          <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
        </b:if>
      </p>
    </b:if>
    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
    <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
    <b:includable id='feedLinksBody' var='links'>
  <div class='feed-links'>
  <data:feedLinksMsg/>
  <b:loop values='data:links' var='f'>
     <a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
  </b:loop>
  </div>
</b:includable>
    <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
    <b:includable id='mobile-index-post' var='post'>
  <div class='mobile-date-outer date-outer'>
    <b:if cond='data:post.dateHeader'>
      <div class='date-header'>
        <span><data:post.dateHeader/></span>
      </div>
    </b:if>

    <div class='mobile-post-outer'>
      <a expr:href='data:post.url'>
        <h3 class='mobile-index-title entry-title' itemprop='name'>
          <data:post.title/>
        </h3>

        <div class='mobile-index-arrow'>&amp;rsaquo;</div>

        <div class='mobile-index-contents'>
          <b:if cond='data:post.thumbnailUrl'>
            <div class='mobile-index-thumbnail'>
              <div class='Image'>
                <img expr:src='data:post.thumbnailUrl'/>
              </div>
            </div>
          </b:if>

          <div class='post-body'>
            <b:if cond='data:post.snippet'><data:post.snippet/></b:if>
          </div>
        </div>

        <div style='clear: both;'/>
      </a>

      <div class='mobile-index-comment'>
        <b:include cond='data:blog.pageType != &quot;static_page&quot;                          and data:post.allowComments                          and data:post.numComments != 0' data='post' name='comment_count_picker'/>
      </div>
    </div>
  </div>
</b:includable>
    <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
    <b:includable id='mobile-nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <div class='mobile-link-button' id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;lsaquo;</a>
      </div>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <div class='mobile-link-button' id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;rsaquo;</a>
      </div>
    </b:if>

    <div class='mobile-link-button' id='blog-pager-home-link'>
    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
    </div>

    <div class='mobile-desktop-link'>
      <a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
    </div>

  </div>
  <div class='clear'/>
</b:includable>
    <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
        <b:if cond='data:post.title'> 
                     <b:if cond='data:blog.pageType == &quot;index&quot;'> 
    <h2 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <a expr:href='data:post.link' itemprop='url'><data:post.title/></a> 
     <b:else/> 
        <b:if cond='data:post.url'> 
<a expr:href='data:post.url' itemprop='url'><data:post.title/></a> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
     </h2>
                       <b:elseif cond='data:blog.pageType == &quot;archive&quot;'/> 
<h2 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <a expr:href='data:post.link' itemprop='url'><data:post.title/></a> 
     <b:else/> 
        <b:if cond='data:post.url'> 
<a expr:href='data:post.url' itemprop='url'><data:post.title/></a> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
      </h2>
<b:else/> 
<h1 class='post-title entry-title' itemprop='name'> 
     <b:if cond='data:post.link'> 
       <data:post.title/> 
     <b:else/> 
        <b:if cond='data:post.url'> 
         <data:post.title/> 
<b:else/> 
          <data:post.title/> 
        </b:if> 
     </b:if> 
      </h1> 
</b:if> 
                    </b:if> 

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
    <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>

    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
    <b:includable id='post' var='post'>
  <div class='post hentry'> 
     <b:if cond='data:blog.pageType == &quot;index&quot;'>
              <b:if cond='data:post.thumbnailUrl'>
                <div class='block-image'>
<div class='bk-right'><h2><span itemprop='name'>من <data:post.author/></span></h2></div>
<div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.thumbnailUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
              <b:if cond='data:post.firstImageUrl'>
                <div class='block-image'><div class='bk-right'><h2><span itemprop='name'>من<data:post.author/></span></h2></div><div class='thumb'>
                  &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.firstImageUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
                <div class='block-image'><div class='bk-right'><h2><span itemprop='name'>من<data:post.author/></span></h2></div><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(http://2.bp.blogspot.com/-IO-XEI1LgEs/VmPNKFp0BhI/AAAAAAAACOg/_JrYHMBXV5w/s1600-r/nothumb.jpg) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
             </b:if></b:if>
            </b:if>
            <b:if cond='data:blog.pageType == &quot;archive&quot;'>
              <b:if cond='data:post.thumbnailUrl'>
                <div class='block-image'><div class='bk-right'><h2><span itemprop='name'>من<data:post.author/></span></h2></div><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.thumbnailUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
              <b:if cond='data:post.firstImageUrl'>
                <div class='block-image'><div class='bk-right'><h2><span itemprop='name'>من<data:post.author/></span></h2></div><div class='thumb'>
                  &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(<data:post.firstImageUrl/>) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
                <b:else/>
                <div class='block-image'><div class='bk-right'><h2><span itemprop='name'>من<data:post.author/></span></h2></div><div class='thumb'>
               &lt;a href=&#39;<data:post.url/>&#39; style=&#39;background:url(http://2.bp.blogspot.com/-IO-XEI1LgEs/VmPNKFp0BhI/AAAAAAAACOg/_JrYHMBXV5w/s1600-r/nothumb.jpg) no-repeat center center;background-size:cover&#39;&gt;&lt;/a&gt;
                </div></div>
             </b:if></b:if>
            </b:if>
           <b:if cond='data:blog.pageType == &quot;item&quot;'>
             &lt;div itemprop=&#39;blogPost&#39; itemscope=&#39;itemscope&#39; itemtype=&#39;http://schema.org/BlogPosting&#39;&gt;
             <div itemprop='image' itemscope='itemscope' itemtype='https://schema.org/ImageObject' style='display :none;'>
               <meta expr:content='data:post.firstImageUrl' itemprop='url'/>
               <meta content='700' itemprop='width height'/>
             </div>
           </b:if>
    <div class='post-header'>
 <b:if cond='data:blog.pageType == &quot;item&quot;'>
        <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name headline'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
        <div class='post-meta'>
<span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <i class='fa fa-user'/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' expr:title='data:post.author' rel='author'>
                  <span itemprop='name'><data:post.author/></span></a>
              </span>
            </b:if>
        </b:if>
      </span>
 <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <i class='fa fa-calendar-o'/>
        <b:if cond='data:post.url'>
          <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span>
<span class='label-head'>
        <b:if cond='data:post.labels'>
         <i class='fa fa-folder-open-o'/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span>
        </div>
   </b:if>
  <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
    <b:if cond='data:post.title'>
      <div class='post-head'><h1 class='post-title entry-title' itemprop='name'>
      <b:if cond='data:post.link'>
        <a expr:href='data:post.link'><data:post.title/></a>
      <b:else/>
        <b:if cond='data:post.url'>
          <b:if cond='data:blog.url != data:post.url'>
            <a expr:href='data:post.url'><data:post.title/></a>
          <b:else/>
            <data:post.title/>
          </b:if>
        <b:else/>
          <data:post.title/>
        </b:if>
      </b:if>
        </h1></div>
    </b:if>
    </b:if>
   
    </div>

    <!-- Then use the post body as the schema.org description, for good G+/FB snippeting. -->
    <article>
         <b:if cond='data:blog.pageType != &quot;item&quot;'>
         <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
          <b:if cond='data:post.title'>
              <font class='retitle'>
                <h2 class='post-title entry-title'>
                   <b:if cond='data:post.link'>
                    <a expr:href='data:post.link'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                      <b:if cond='data:post.url'>
                       <a expr:href='data:post.url'>
                       <data:post.title/>
                      </a>
                      <b:else/>
                     <data:post.title/>
                     </b:if>
                   </b:if>
                  </h2>
                    </font>
                </b:if>
                  <div class='date-header'>
                     <div id='meta-post'>
                        <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <i class='fa fa-calendar-o'/>
        <b:if cond='data:post.url'>
          <meta expr:content='data:post.canonicalUrl' itemprop='url'/>
          <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published timeago' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
        </b:if>
        </b:if>
      </span> <div class='rw-ui-container'/></div>
                      <div style='clear: both;'/>
                      </div>
            <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>



       </div>
          </b:if>
          <b:else/>
       <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
         <meta expr:content='data:post.snippet' name='twitter:description'/>
         <data:post.body/>
       </div>
         </b:if>
     </article>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>

    <div class='post-footer'>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div class='share-box'>
 
          <h8 class='share-title'>شارك الموضوع:</h8>
               <div class='share-art'> 
<a class='fac-art' expr:href='&quot;http://www.facebook.com/sharer.php?u=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, right=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-facebook'/><span class='resp_del'> فيسبوك</span></a>

<a class='twi-art' expr:href='&quot;http://twitter.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, right=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-twitter'/><span class='resp_del2'> تويتر</span></a>

<a class='goo-art' expr:href='&quot;https://plus.google.com/share?url=&quot; + data:post.url + &quot;&amp;title=&quot; + data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, right=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-google-plus'/><span class='resp_del3'> جوجل +</span></a>

<a class='pin-art' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url + &quot;&amp;media=&quot; + data:post.firstImageUrl + &quot;&amp;description=&quot; + data:post.snippet' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, right=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-pinterest'/><span class='resp_del4'> بنترست</span></a>  

<a class='lin-art' expr:href='&quot;http://www.linkedin.com/shareArticle?url=&quot; + data:post.url + &quot;&amp;title=&quot;+ data:post.title' onclick='window.open(this.href, &apos;windowName&apos;, &apos;width=600, height=400, right=24, top=24, scrollbars, resizable&apos;); return false;' rel='nofollow' target='_blank'><i class='fa fa-linkedin-square'/><span class='resp_del5'> لينكدن</span></a>

<a class='print-art' onClick='window.print()' rel='nofollow' style='cursor:pointer'><i class='fa fa-print'/><span class='resp_del5'> طبع</span></a>
</div>
         </div>
                 <div style='clear:both'/>  
<div class='Thechni-author-box'>

<img alt='Author Image' class='avatar avatar-60 photo' expr:src='data:post.authorPhoto.url' height='100' width='110'/>
<p>
<b> الكاتب: <data:post.author/></b>  <br/>  </p>
</div>
      <div style='clear:both'/>  
<div id='related-posts'>
        <b:if cond='data:post.labels'>
          <b:loop values='data:post.labels' var='label'>
            <b:if cond='data:label.isLast == &quot;true&quot;'>
              <data:label.name/>
            </b:if>
          </b:loop>
        </b:if>
      </div>
   </b:if>
    <div class='post-footer-line post-footer-line-1'>
      <span class='post-author vcard'>
        <b:if cond='data:top.showAuthor'>
          <data:top.authorLabel/>
            <b:if cond='data:post.authorProfileUrl'>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                <a class='g-profile' expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                  <span itemprop='name'><data:post.author/></span>
                </a>
              </span>
            <b:else/>
              <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                <span itemprop='name'><data:post.author/></span>
              </span>
            </b:if>
        </b:if>
      </span>

      <span class='post-timestamp'>
        <b:if cond='data:top.showTimestamp'>
          <data:top.timestampLabel/>
          <b:if cond='data:post.url'>
            <meta expr:content='data:post.canonicalUrl' itemprop='url mainEntityOfPage'/>
            <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished dateModified'><data:post.timestamp/></abbr></a>
          </b:if>
        </b:if>
      </span>

      <span class='reaction-buttons'>
        <b:if cond='data:top.showReactions'>
          <table border='0' cellpadding='0' cellspacing='0' width='100%'><tr>
            <td class='reactions-label-cell' nowrap='nowrap' valign='top' width='1%'>
              <span class='reactions-label'>
              <data:top.reactionsLabel/></span>&#160;</td>
            <td><iframe allowtransparency='true' class='reactions-iframe' expr:src='data:post.reactionsUrl' frameborder='0' name='reactions' scrolling='no'/></td>
           </tr></table>
        </b:if>
      </span>

      <span class='post-comment-link'>
        <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                          and data:post.allowComments' data='post' name='comment_count_picker'/>
      </span>

       <!-- backlinks -->
       <span class='post-backlinks post-comment-link'>
         <b:if cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                      and data:post.showBacklinks'>
           <a class='comment-link' expr:href='data:post.url + &quot;#links&quot;'><data:top.backlinkLabel/></a>
         </b:if>
       </span>

      <span class='post-icons'>
        <!-- email post links -->
        <b:if cond='data:post.emailPostUrl'>
          <span class='item-action'>
          <a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
            <img alt='' class='icon-action' height='13' src='//img1.blogblog.com/img/icon18_email.gif' width='18'/>
          </a>
          </span>
        </b:if>

        <!-- quickedit pencil -->
        <b:include data='post' name='postQuickEdit'/>
      </span>

      <!-- share buttons -->
      <div class='post-share-buttons goog-inline-block'>
        <b:include cond='data:post.sharePostUrl' data='post' name='shareButtons'/>
      </div>

      </div>

      <div class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='not data:label.isLast'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </div>

      <div class='post-footer-line post-footer-line-3'>
      <span class='post-location'>
        <b:if cond='data:top.showLocation'>
          <b:if cond='data:post.location'>
            <data:postLocationLabel/>
            <a expr:href='data:post.location.mapsUrl' target='_blank'><data:post.location.name/></a>
          </b:if>
        </b:if>
      </span>
      </div>
      <b:if cond='data:post.authorAboutMe'>
        <div class='author-profile' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
          <b:if cond='data:post.authorPhoto.url'>
            <img expr:src='data:post.authorPhoto.url' itemprop='image' width='50px'/>
          </b:if>
          <div>
            <a class='g-profile' expr:href='data:post.authorProfileUrl' itemprop='url' rel='author' title='author profile'>
              <span itemprop='name'><data:post.author/></span>
            </a>
          </div>
          <span itemprop='description'><data:post.authorAboutMe/></span>
        </div>
      </b:if>
    </div>
    <b:if cond='data:blog.pageType == &quot;item&quot;'>
      <div itemprop='publisher' itemscope='itemscope' itemtype='https://schema.org/Organization' style='display :none;'>
        <div itemprop='logo' itemscope='itemscope' itemtype='https://schema.org/ImageObject'>
          <meta expr:content='data:post.firstImageUrl' itemprop='url'/>
        </div>
        <meta expr:content='data:blog.title' itemprop='name'/>
      </div>
      &lt;/div&gt;
    </b:if>
  </div>
</b:includable>
    <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='Edit' class='icon-action' height='18' src='https://resources.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
    <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showPlusOne'><div class='goog-inline-block google-plus-share-container'><data:post.googlePlusShareTag/></div></b:if>
</b:includable>
    <b:includable id='status-message'>
  <b:if cond='data:navMessage'>
  <div class='status-msg-wrap'>
    <div class='status-msg-body'>
      <data:navMessage/>
    </div>
    <div class='status-msg-border'>
      <div class='status-msg-bg'>
        <div class='status-msg-hidden'><data:navMessage/></div>
      </div>
    </div>
  </div>
  <div style='clear: both;'/>
<b:if cond='data:blog.pageType == &quot;error_page&quot;'>
  <div class='post-404'>
<div class='actions-404'>
<div class='ops-404'><span>عذرا!!</span> نأسف على هذا , لكن هذه الصفحة ليست موجودة أو قد تم حذفها
                        </div>
<div class='title-404'>404</div>
<div class='link-404'>
<a href='/'><i class='fa fa-car'/>
<trans>الرجوع للرئيسية</trans></a>
</div></div>
</div>
<style>
.post-404 {
    padding-top: 40px;
    padding-bottom: 60px;
}
.actions-404 {
    width :  100%;
    float : left;
    text-align: center;
}
.ops-404 {
    width :  50%;
    margin: 0 auto;
    font-size: 26px;
    font-weight: 400;
font-family: &#39;neo&#39;, sans-serif;
}
.ops-404 span {
    font-weight: 700;
}
.title-404 {
    font-size: 200px;
    font-weight: 700;
    line-height: 1.1;
    color:$primarycolor;
}
.link-404 {
    font-size: 18px;
    padding-top: 20px;
    padding-bottom: 50px;
}
#blog-pager, #sidebar-wrapper,.status-msg-wrap {
    display : block;
}
.status-msg-border {
         border: 0 !important;
       }

       .status-msg-bg {
         background-color: #fff;
       }
#main-wrapper {
width :  100%;
    max-width :  100%;
}
</style>
      </b:if>
  </b:if>
</b:includable>
    <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display : none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
    <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
    <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
      <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
  </b:widget>
  <b:widget id='HTML901' locked='true' title='التعليقات' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'>[facebook][blogger]</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
          <b:if cond='data:blog.pageType == &quot;item&quot;'>
            <b:if cond='data:content == &quot;[blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>    
            </b:if>
            <b:if cond='data:content == &quot;[disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
              <script type='text/javascript'>
              //<![CDATA[
                $('#comments').remove();
              //]]>
              </script>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][facebook][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[blogger][disqus][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][blogger][disqus]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[facebook][disqus][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][blogger][facebook]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
              </div>
            </b:if>
            <b:if cond='data:content == &quot;[disqus][facebook][blogger]&quot;'>
              <div class='cmm-tabs'>
                <div data-tab='disqus'><div class='disqus-tab'><div id='disqus_thread'/></div></div>
                <div data-tab='facebook'><div class='facebook-tab'/></div>
                <div data-tab='blogger'><div class='blogger-tab'/></div>
              </div>
            </b:if>
            <div id='fb-root'/><script>(function(d, s, id){var js, fjs = d.getElementsByTagName(s)[0];if (d.getElementById(id)) return;js = d.createElement(s); js.id = id;js.src = &quot;//connect.facebook.net/en_US/sdk.js#xfbml=1&amp;version=v2.0&quot;;fjs.parentNode.insertBefore(js, fjs);}(document, &#39;script&#39;, &#39;facebook-jssdk&#39;));</script>&lt;script&gt;$(&quot;.facebook-tab&quot;).append(&quot;&lt;div class=&#39;fb-comments&#39; data-href=&#39;<data:blog.canonicalUrl/>&#39; data-width=&#39;100%&#39; data-numposts=&#39;5&#39; data-colorscheme=&#39;light&#39;&gt;&lt;/div&gt;&quot;);&lt;/script&gt;
          </b:if>
        </b:includable>
  </b:widget>
  <b:widget id='HTML902' locked='true' title='Disqus Shortname' type='HTML' version='1'>
    <b:widget-settings>
      <b:widget-setting name='content'/>
    </b:widget-settings>
    <b:includable id='main'>
          <b:if cond='data:blog.pageType == &quot;item&quot;'>
            &lt;script type=&#39;text/javascript&#39;&gt;
            var disqus_shortname = &#39;<data:content/>&#39;;
             (function() {
              var dsq = document.createElement(&#39;script&#39;); dsq.type = &#39;text/javascript&#39;; dsq.async = true;
              dsq.src = &#39;//&#39; + disqus_shortname + &#39;.disqus.com/embed.js&#39;;
              (document.getElementsByTagName(&#39;head&#39;)[0] || document.getElementsByTagName(&#39;body&#39;)[0]).appendChild(dsq);
              })();
            &lt;/script&gt;
          </b:if>
        </b:includable>
  </b:widget>
</b:section>
    </div>
<div id='sidebar-wrapper'>
<b:section class='social-counter sidebar ready-widget' id='social-counter' maxwidgets='2' name='Social Counter' showaddelement='yes'>
  <b:widget id='HTML1' locked='false' title='' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;style&gt;
#MBBOldSearch {
display: block;
clear: both;
margin: 10px 0;
}
#MBBOldSearch #MBBSinput {
background: url(&quot;http://2.bp.blogspot.com/-Q-Ejkmx-Ki4/Teem3RZlpqI/AAAAAAAAA40/_p6u9Xpgs7c/s20/Search-icon.png&quot;) no-repeat scroll 8px center transparent !important;
padding: 7px 15px 7px 35px !important;
color: #444;
font-weight: bold;
text-decoration: none;
border: 1px solid #D3D3D3 !important;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
border-radius: 4px;
-webkit-box-shadow: 1px 1px 2px #CCC inset;
-moz-box-shadow: 1px 1px 2px #CCC inset;
box-shadow: 1px 1px 2px #CCC inset;
اwidth: 52%;
}
#MBBOldSearch #MBBSsubmit {
color: #444;
font-weight: bold;
text-decoration: none;
padding: 6px 15px;
border: 1px solid #D3D3D3;
cursor: pointer;
-webkit-border-radius: 4px;
-moz-border-radius: 4px;
border-radius: 4px;
background: #fbfbfb;
background: -moz-linear-gradient(top, #fbfbfb 0%, #f4f4f4 100%);
background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#fbfbfb), color-stop(100%,#f4f4f4));
background: -webkit-linear-gradient(top, #fbfbfb 0%,#f4f4f4 100%);
background: -o-linear-gradient(top, #fbfbfb 0%,#f4f4f4 100%);
background: -ms-linear-gradient(top, #fbfbfb 0%,#f4f4f4 100%);
filter: progid:DXImageTransform.Microsoft.gradient( startColorstr=&#39;#FBFBFB&#39;, endColorstr=&#39;#F4F4F4&#39;,GradientType=0 );
background: linear-gradient(top, #fbfbfb 0%,#f4f4f4 100%);
}
&lt;/style&gt;
&lt;div id=&quot;MBBOldSearch&quot;&gt;
    &lt;form action=&quot;/search&quot;&gt;
        &lt;input name=&quot;q&quot; id=&quot;MBBSinput&quot; type=&quot;text&quot; /&gt;
        &lt;input value=&quot;Search&quot; id=&quot;MBBSsubmit&quot; type=&quot;submit&quot; /&gt;
    &lt;/form&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
  <b:widget id='LinkList62' locked='true' title='تابعو جديدنا' type='LinkList' version='1'>
    <b:widget-settings>
      <b:widget-setting name='sorting'>NONE</b:widget-setting>
      <b:widget-setting name='text-1'>telegram</b:widget-setting>
      <b:widget-setting name='link-1'>http://</b:widget-setting>
      <b:widget-setting name='text-0'>facebook</b:widget-setting>
      <b:widget-setting name='link-0'>https://web.facebook.com</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
            <b:if cond='data:title != &quot;&quot;'>
              <h2 class='title'><data:title/></h2>
            </b:if>
            <div class='widget-content'>
              <ul id='social'>
                <b:loop values='data:links' var='link'>
                  <li expr:class='&quot;item-social &quot; + data:link.name'><a expr:href='data:link.target'> <i class='item-icon fa'/><div class='hide-count'><data:link.name/></div><span class='item-text'>المتابعون</span> </a></li>
                </b:loop>
              </ul>
            </div>
          </b:includable>
  </b:widget>
</b:section>
<div class='sidetabs' id='sidetabs'>
      <ul class='menu-tab'>
        <li class='item-1'><a href='#tabside1'/></li>
        <li class='item-2'><a href='#tabside2'/></li>
 <li class='item-3'><a href='#tabside3'/></li>
      </ul>
      <b:section class='sidebar ready-widget' id='tabside1' maxwidgets='1' name='Tab 01' showaddelement='yes'>
        <b:widget id='PopularPosts1' locked='false' title='الشائعة' type='PopularPosts' version='1'>
          <b:widget-settings>
            <b:widget-setting name='numItemsToShow'>3</b:widget-setting>
            <b:widget-setting name='showThumbnails'>true</b:widget-setting>
            <b:widget-setting name='showSnippets'>true</b:widget-setting>
            <b:widget-setting name='timeRange'>LAST_YEAR</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='!data:showThumbnails'>
          <b:if cond='!data:showSnippets'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <!-- (3) Show only thumbnails or (4) Snippets and thumbnails. -->
          <div expr:class='data:showSnippets ? &quot;item-content&quot; : &quot;item-thumbnail-only&quot;'>
            <b:if cond='data:post.thumbnail'>
              <div class='item-thumbnail'>
                <a expr:href='data:post.href' target='_blank'>
                  <img border='0' expr:alt='data:post.title' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                </a>
              </div>
            </b:if>
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <b:if cond='data:showSnippets'>
              <div class='item-snippet'><data:post.snippet/></div>
            </b:if>
          </div>
          <div style='clear: both;'/>
        </b:if>
      </li>
      </b:loop>
    </ul>
    <b:include name='quickedit'/>
  </div>
</b:includable>
        </b:widget>
      </b:section>
      <b:section class='sidebar ready-widget' id='tabside2' maxwidgets='1' name='Tab 02' showaddelement='yes'>
        <b:widget id='HTML7' locked='false' title='تبرع' type='HTML'>
          <b:widget-settings>
            <b:widget-setting name='content'>&lt;form action=&quot;https://www.paypal.com/cgi-bin/webscr&quot; method=&quot;post&quot; target=&quot;_top&quot;&gt;
&lt;input type=&quot;hidden&quot; name=&quot;cmd&quot; value=&quot;_s-xclick&quot; /&gt;
&lt;input type=&quot;hidden&quot; name=&quot;hosted_button_id&quot; value=&quot;JMCEKLLZH3KH4&quot; /&gt;
&lt;input type=&quot;image&quot; src=&quot;https://www.paypalobjects.com/en_US/i/btn/btn_buynowCC_LG.gif&quot; border=&quot;0&quot; name=&quot;submit&quot; alt=&quot;PayPal - The safer, easier way to pay online!&quot; /&gt;
&lt;img alt=&quot;&quot; border=&quot;0&quot; src=&quot;https://www.paypalobjects.com/ar_EG/i/scr/pixel.gif&quot; width=&quot;1&quot; height=&quot;1&quot; /&gt;
&lt;/form&gt;</b:widget-setting>
          </b:widget-settings>
          <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
        </b:widget>
      </b:section>
 <b:section class='sidebar ready-widget' id='tabside3' maxwidgets='1' name='Tab 03' showaddelement='yes'>
   <b:widget id='Label1' locked='false' title='أقسام الموقع' type='Label'>
     <b:widget-settings>
       <b:widget-setting name='sorting'>ALPHA</b:widget-setting>
       <b:widget-setting name='display'>LIST</b:widget-setting>
       <b:widget-setting name='selectedLabelsList'/>
       <b:widget-setting name='showType'>ALL</b:widget-setting>
       <b:widget-setting name='showFreqNumbers'>false</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
  <b:if cond='data:title != &quot;&quot;'>
    <h2><data:title/></h2>
  </b:if>
  <div expr:class='&quot;widget-content &quot; + data:display + &quot;-label-widget-content&quot;'>
    <b:if cond='data:display == &quot;list&quot;'>
      <ul>
        <b:loop values='data:labels' var='label'>
          <li>
            <b:if cond='data:blog.url == data:label.url'>
              <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
            <b:else/>
              <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
            </b:if>
            <b:if cond='data:showFreqNumbers'>
              <span dir='ltr'>(<data:label.count/>)</span>
            </b:if>
          </li>
        </b:loop>
      </ul>
    <b:else/>
      <b:loop values='data:labels' var='label'>
        <span expr:class='&quot;label-size label-size-&quot; + data:label.cssSize'>
          <b:if cond='data:blog.url == data:label.url'>
            <span expr:dir='data:blog.languageDirection'><data:label.name/></span>
          <b:else/>
            <a expr:dir='data:blog.languageDirection' expr:href='data:label.url'><data:label.name/></a>
          </b:if>
          <b:if cond='data:showFreqNumbers'>
            <span class='label-count' dir='ltr'>(<data:label.count/>)</span>
          </b:if>
        </span>
      </b:loop>
    </b:if>
    <b:include name='quickedit'/>
  </div>
</b:includable>
   </b:widget>
 </b:section>
     </div>
<b:section class='sidebar ready-widget' id='sidebar' preferred='yes'>
  <b:widget id='HTML4' locked='false' title='صفحتنا على فيسبوك' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'><![CDATA[<iframe src="//www.facebook.com/plugins/likebox.php?href=https://web.facebook.com/&amp;width=338&amp;height=258&amp;colorscheme=light&amp;show_faces=true&amp;header=false&amp;stream=false&amp;show_border=false&amp;" scrolling="no" frameborder="0" style="border:none; overflow:hidden; width:338px; height:250px;" allowtransparency="true"></iframe>]]></b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
    </div>
<div style='clear: both;'/>
  </div>
<div class='sub-wrap'>
<b:section class='featuresub row' id='Subscription Widget'>
  <b:widget id='HTML6' locked='false' title='' type='HTML'>
    <b:widget-settings>
      <b:widget-setting name='content'>&lt;div id=&quot;subscribe-css&quot;&gt;
&lt;p class=&quot;subscribe-note&quot;&gt;&lt;span&gt;إشترك اليوم&lt;/span&gt; &lt;span class=&quot;itatu&quot;&gt;للحصول على&lt;/span&gt; التعليم المجاني!&lt;/p&gt;
&lt;div class=&quot;subscribe-wrapper&quot;&gt;
&lt;div class=&quot;subscribe-form&quot;&gt;
&lt;form action=&quot;http://feedburner.google.com/fb/a/mailverify?uri=booksociety&quot; class=&quot;subscribe-form&quot; method=&quot;post&quot; onsubmit=&quot;window.open (&#39;http://feedburner.google.com/fb/a/mailverify?uri=booksociety&#39;, &#39;popupwindow&#39;, &#39;scrollbars=yes,width=550,height=520&#39;);return true&quot; target=&quot;popupwindow&quot;&gt;
&lt;input name=&quot;uri&quot; type=&quot;hidden&quot; value=&quot;blogspot/medad&quot; /&gt;
&lt;input name=&quot;loc&quot; type=&quot;hidden&quot; value=&quot;en_US&quot; /&gt;&lt;i class=&quot;mail-subcribe&quot;&gt;&lt;/i&gt;&lt;input autocomplete=&quot;off&quot; class=&quot;subscribe-css-email-field&quot; name=&quot;email&quot; placeholder=&quot;البريد الإلكتروني هنا&quot; /&gt;&lt;input class=&quot;subscribe-css-email-button&quot; title=&quot;&quot; type=&quot;Submit&quot; value=&quot;إشتراك&quot; /&gt;&lt;/form&gt;
&lt;/div&gt;
&lt;/div&gt;
&lt;/div&gt;</b:widget-setting>
    </b:widget-settings>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
  </b:widget>
</b:section>
    </div>
<div style='clear: both;'/>
<div id='lower'> 
<div class='row' id='lower-wrapper'>

<div id='lowerbar-wrapper'> 
<b:section class='lowerbar ready-widget' id='lowerbar1' preferred='yes'>
   <b:widget id='HTML2' locked='false' title='' type='HTML'>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
 </b:section> 
</div>

<div id='lowerbar-wrapper'> 
<b:section class='lowerbar ready-widget' id='lowerbar2' preferred='yes'>
   <b:widget id='HTML5' locked='false' title='' type='HTML'>
     <b:widget-settings>
       <b:widget-setting name='content'>&lt;link rel=&quot;stylesheet&quot; href=&quot;https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css&quot;/&gt;
&lt;style&gt;
/*-------------------- font --------------------*/
@font-face {
font-family: &quot;Ta3alamFont&quot;;
font-weight: normal;
font-style: normal;
src: url(https://dl.dropboxusercontent.com/s/l0mqm6g2vwflxp2/Ta3alamFont.eot);
src: url(https://dl.dropboxusercontent.com/s/l0mqm6g2vwflxp2/Ta3alamFont.eot?#iefix) format(&#39;embedded-opentype&#39;),
url(https://dl.dropboxusercontent.com/s/gjkkuvnfze5ii1l/Ta3alamFont.woff) format(&#39;woff&#39;),
url(https://dl.dropboxusercontent.com/s/mjj8mvkq7jgihhn/Ta3alamFont.ttf) format(&#39;truetype&#39;);
}
/*-------------------- #font# --------------------*/
.admin{
    width: 300px;
    height: 335px;
    background: #343434;
    border: 1px solid #131313;
    margin: -1px;
    border-radius: 4px;
}
.cover{
    height: 120px;
    background: url(http://2.bp.blogspot.com/-eozlkqCkahk/VjPKdGZ00oI/AAAAAAAADXE/rXbds1JSaFE/s1600-r/Space-Desktop.jpg) no-repeat;
    border-bottom: 1px solid #868282;
    background-size: 300px;
    box-shadow: 0px -140px 310px -100px #000 inset;
}

.profile{
    width: 120px;
    height: 120px;
    background: url(0) no-repeat;
    border: 4px solid #fff;
    margin: -100px auto 0px;
    border-radius: 10px;
    box-shadow: 0px 0px 15px -5px #000,0px 0px 60px -10px #000 inset;
    background-size: 120px;
}
.form-info{
    border-bottom: 1px solid #494949;
    border-top: 1px solid #494949;
    margin-top: 10px;
    background: #2A2A2A;
}
.form-info ul{
    margin: 0;
    padding: 0px;
}
.form-info ul li{
    display: block;
    padding: 0px 25px;
    margin: 2px 0px;
    border-bottom: 1px solid #343434;
    height: 30px;
}
.form-info ul li img{
    display: block;
    float: right;
    padding: 5px;
    height: 18px;
    width: 18px;
}
.form-info ul li a{
display: block;
    float: right;
    height: 20px;
    padding: 5px;
    color: #9E9E9E;
font-family:Ta3alamFont;
}
.form-info ul li a:hover{color:#fff;}
.form-contact{
    border-bottom: 1px solid #494949;
    border-top: 1px solid #494949;
    margin-top: 10px;
    background: #2A2A2A;
}
.form-contact ul{
    margin: 0;
    padding: 0px;
}
.form-contact ul li{
    display: block;
    padding: 0px 25px;
    margin: 2px 0px;
    border-bottom: 1px solid #343434;
    height: 30px;
}
.form-contact ul li img{
    display: block;
    float: left ;
    padding: 5px;
    height: 18px;
    width: 18px;
}
.form-contact ul li a{
display: block;
    float: left ;
    height: 20px;
    padding: 5px;
    color: #9E9E9E;
font-family:Ta3alamFont;
}
.form-contact ul li a:hover{color:#fff;}
.form-socail{
    text-align: center;
}
.form-socail i{
color: #9E9E9E;
    font-size: 32px;
    padding: 5px;
}
.form-socail i:hover{
color:#fff;
}
&lt;/style&gt;


&lt;div class=&quot;admin&quot;&gt;


&lt;div class=&quot;cover&quot;&gt;
&lt;/div&gt;
&lt;div class=&quot;profile&quot;&gt;
&lt;/div&gt;
&lt;div class=&quot;form-info&quot;&gt;

&lt;ul&gt;
&lt;li&gt;
&lt;img src=&quot;http://3.bp.blogspot.com/-Wb3WEcCg0mE/VjPQk-emmSI/AAAAAAAADXo/o7vKvwUWfVI/s1600-r/users81.png&quot; /&gt;

&lt;a href=&quot;https://web.facebook.com/&quot;&gt;نبيل بن لخضر&lt;/a&gt;
&lt;/li&gt;
&lt;li&gt;
&lt;img src=&quot;https://www.iconfinder.com/data/icons/social-media-3/512/Birthday_Cake-512.png&quot; /&gt;

&lt;a href=&quot;https://web.facebook.com/&quot;&gt;&lt;/a&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/div&gt;
&lt;div class=&quot;form-contact&quot;&gt;

&lt;ul&gt;
&lt;li&gt;
&lt;img src=&quot;http://www.freeiconspng.com/uploads/gmail-icon-23.png&quot; /&gt;

&lt;a href=&quot;profnabil19@gmail.com&quot;&gt;profnabil19@gmail.com&lt;/a&gt;
&lt;/li&gt;
&lt;/ul&gt;
&lt;/div&gt;
&lt;div class=&quot;form-socail&quot;&gt;


&lt;a href=&quot;#&quot;&gt;
&lt;i class=&quot;fa fa-google-plus-square&quot;&gt;&lt;/i&gt;&lt;/a&gt;

&lt;a href=&quot;#&quot;&gt;
&lt;i class=&quot;fa fa-youtube-square&quot;&gt;&lt;/i&gt;&lt;/a&gt;

&lt;a href=&quot;#&quot;&gt;
&lt;i class=&quot;fa fa-twitter-square&quot;&gt;&lt;/i&gt;&lt;/a&gt;

&lt;a href=&quot;https://web.facebook.com&quot;&gt;
&lt;i class=&quot;fa fa-facebook-square&quot;&gt;&lt;/i&gt;&lt;/a&gt;


&lt;/div&gt;
&lt;/div&gt;</b:widget-setting>
     </b:widget-settings>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
 </b:section> 
</div>

<div id='lowerbar-wrapper'> 
<b:section class='lowerbar ready-widget' id='lowerbar3' preferred='yes'>
   <b:widget id='HTML3' locked='false' title='عن الموقع' type='HTML'>
     <b:widget-settings>
       <b:widget-setting name='content'/>
     </b:widget-settings>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
 </b:section> 
</div>

<div style='clear: both;'/> 
</div> 
</div>
<div id='jugas_footer'>
        <div class='copy-container row'>
         
                                  <div class='jugas_footer_copyright'>
تعريب : <a href='' id='mycontent' title='Blogger Templates'/> | تصميم  

<a href='' title='Blogger Templates'>نبيل بن لخضر</a>

                    </div>
               

                    
        </div>
    </div>
&lt;/div&gt;
<script type='text/javascript'>
//<![CDATA[
// News Ticker plugin ~ URL: http://jonmifsud.com/open-source/jquery/jquery-webticker
(function(e){function n(e,t){var s=e.data("settings");if(typeof t==="undefined")t=false;if(t){i(e)}var o=r(e);e.animate(o.css,o.time,"linear",function(){e.css(s.direction,"0");n(e,true)})}function r(e){var t=e.data("settings");var n=e.children().first();var r=Math.abs(-e.css(t.direction).replace("px","").replace("auto","0")-n.outerWidth(true));var t=e.data("settings");var i=r*1e3/t.speed;var s={};s[t.direction]=e.css(t.direction).replace("px","").replace("auto","0")-r;return{css:s,time:i}}function i(e){var t=e.data("settings");e.css("transition-duration","0s").css(t.direction,"0");var n=e.children().first();if(n.hasClass("webticker-init"))n.remove();else e.children().last().after(n)}function s(e,t){if(typeof t==="undefined")t=false;if(t){i(e)}var n=r(e);var s=n.time/1e3;s+="s";e.css(n.css).css("transition-duration",s)}function o(t,n,r){var i;e.get(t,function(t){var s=e(t);s.find("item").each(function(){var t=e(this),n={title:t.find("title").text(),link:t.find("link").text()};listItem="<li><a href='"+n.link+"'>"+n.title+"</a></li>";i+=listItem});r.webTicker("update",i,n)})}function u(t){var n=t.data("settings");t.width("auto");var r=0;t.children("li").each(function(){r+=e(this).outerWidth(true)});if(r<t.parent().width()||t.children().length==1){if(n.duplicate){itemWidth=Math.max.apply(Math,t.children().map(function(){return e(this).width()}).get());while(r-itemWidth<t.parent().width()||t.children().length==1){var i=t.children().clone();t.append(i);r=0;t.children("li").each(function(){r+=e(this).outerWidth(true)});itemWidth=Math.max.apply(Math,t.children().map(function(){return e(this).width()}).get())}}else{var s=t.parent().width()-r;s+=t.find("li:first").width();var o=t.find("li:first").height();t.append('<li class="ticker-spacer" style="width : '+s+"px;height:"+o+'px;"></li>')}}if(n.startEmpty){var o=t.find("li:first").height();t.prepend('<li class="webticker-init" style="width : '+t.parent().width()+"px;height:"+o+'px;"></li>')}r=0;t.children("li").each(function(){r+=e(this).outerWidth(true)});t.width(r+200);widthCompare=0;t.children("li").each(function(){widthCompare+=e(this).outerWidth(true)});while(widthCompare>=t.width()){t.width(t.width()+200);widthCompare=0;t.children("li").each(function(){widthCompare+=e(this).outerWidth(true)})}}var t=function(){var e=document.createElement("p").style,t=["ms","O","Moz","Webkit"];if(e["transition"]=="")return true;while(t.length)if(t.pop()+"Transition"in e)return true;return false}();var a={init:function(r){r=jQuery.extend({speed:50,direction:"right",moving:true,startEmpty:true,duplicate:false,rssurl:false,hoverpause:true,rssfrequency:0,updatetype:"reset"},r);return this.each(function(){jQuery(this).data("settings",r);var i=jQuery(this);i.addClass("newsticker");var a=i.wrap("<div class='mask'></div>");a.after("<span class='tickeroverlay-right'>&nbsp;</span><span class='tickeroverlay-left'>&nbsp;</span>");var f=i.parent().wrap("<div class='tickercontainer'></div>");u(i);if(r.rssurl){o(r.rssurl,r.type,i);if(r.rssfrequency>0){window.setInterval(function(){o(r.rssurl,r.type,i)},r.rssfrequency*1e3*60)}}if(t){i.css("transition-duration","0s").css(r.direction,"0");s(i,false);i.on("transitionend webkitTransitionEnd oTransitionEnd otransitionend",function(t){if(!i.is(t.target)){return false}s(e(this),true)})}else{n(e(this))}if(r.hoverpause){i.hover(function(){if(t){var n=e(this).css(r.direction);e(this).css("transition-duration","0s").css(r.direction,n)}else jQuery(this).stop()},function(){if(jQuery(this).data("settings").moving){if(t){s(e(this),false)}else{n(i)}}})}})},stop:function(){var n=e(this).data("settings");if(n.moving){n.moving=false;return this.each(function(){if(t){var r=e(this).css(n.direction);e(this).css("transition-duration","0s").css(n.direction,r)}else e(this).stop()})}},cont:function(){var r=e(this).data("settings");if(!r.moving){r.moving=true;return this.each(function(){if(t){s(e(this),false)}else{n(e(this))}})}},update:function(t,n,r,i){n=n||"reset";if(typeof r==="undefined")r=true;if(typeof i==="undefined")i=false;if(typeof t==="string"){t=e(t)}var s=e(this);s.webTicker("stop");var o=e(this).data("settings");if(n=="reset"){s.html(t);s.css(o.direction,"0");u(s)}else if(n=="swap"){s.children("li").addClass("old");for(var a=0;a<t.length;a++){id=e(t[a]).data("update");match=s.find('[data-update="'+id+'"]');if(match.length<1){if(r){if(s.find(".ticker-spacer:first-child").length==0&&s.find(".ticker-spacer").length>0){s.children("li.ticker-spacer").before(t[a])}else{s.append(t[a])}}}else s.find('[data-update="'+id+'"]').replaceWith(t[a]);}s.children("li.webticker-init, li.ticker-spacer").removeClass("old");if(i)s.children("li").remove(".old");stripWidth=0;s.children("li").each(function(){stripWidth+=e(this).outerWidth(true)});s.width(stripWidth+200)}s.webTicker("cont")}};e.fn.webTicker=function(t){if(a[t]){return a[t].apply(this,Array.prototype.slice.call(arguments,1))}else if(typeof t==="object"||!t){return a.init.apply(this,arguments)}else{e.error("Method "+t+" does not exist on jQuery.webTicker")}}})(jQuery);

// SelectNav.js - by: https://github.com/lukaszfiszer/selectnav.js
window.selectnav=function(){"use strict";var e=function(e,t){function c(e){var t;if(!e)e=window.event;if(e.target)t=e.target;else if(e.srcElement)t=e.srcElement;if(t.nodeType===3)t=t.parentNode;if(t.value)window.location.href=t.value}function h(e){var t=e.nodeName.toLowerCase();return t==="ul"||t==="ol"}function p(e){for(var t=1;document.getElementById("selectnav"+t);t++);return e?"selectnav"+t:"selectnav"+(t-1)}function d(e){a++;var t=e.children.length,n="",l="",c=a-1;if(!t){return}if(c){while(c--){l+=o}l+=" "}for(var v=0;v<t;v++){var m=e.children[v].children[0];if(typeof m!=="undefined"){var g=m.innerText||m.textContent;var y="";if(r){y=m.className.search(r)!==-1||m.parentNode.className.search(r)!==-1?f:""}if(i&&!y){y=m.href===document.URL?f:""}n+='<option value="'+m.href+'" '+y+">"+l+g+"</option>";if(s){var b=e.children[v].children[1];if(b&&h(b)){n+=d(b)}}}}if(a===1&&u){n='<option value="">'+u+"</option>"+n}if(a===1){n='<select class="selectnav" id="'+p(true)+'">'+n+"</select>"}a--;return n}e=document.getElementById(e);if(!e){return}if(!h(e)){return}if(!("insertAdjacentHTML"in window.document.documentElement)){return}document.documentElement.className+=" js";var n=t||{},r=n.activeclass||"active",i=typeof n.autoselect==="boolean"?n.autoselect:true,s=typeof n.nested==="boolean"?n.nested:true,o=n.indent||"-",u=n.label||"Menu",a=0,f=" selected ";e.insertAdjacentHTML("afterend",d(e));var l=document.getElementById(p());if(l.addEventListener){l.addEventListener("change",c)}if(l.attachEvent){l.attachEvent("onchange",c)}return l};return function(t,n){e(t,n)}}();$(document).ready(function(){selectnav('nav-menu1');});

// Timeago jQuery plugin ~ URL: http://timeago.yarp.com
(function(e){if(typeof define==="function"&&define.amd){define(["jquery"],e)}else{e(jQuery)}})(function(e){function r(){var n=i(this);var r=t.settings;if(!isNaN(n.datetime)){if(r.cutoff==0||Math.abs(o(n.datetime))<r.cutoff){e(this).text(s(n.datetime))}}return this}function i(n){n=e(n);if(!n.data("timeago")){n.data("timeago",{datetime:t.datetime(n)});var r=e.trim(n.text());if(t.settings.localeTitle){n.attr("title",n.data("timeago").datetime.toLocaleString())}else if(r.length>0&&!(t.isTime(n)&&n.attr("title"))){n.attr("title",r)}}return n.data("timeago")}function s(e){return t.inWords(o(e))}function o(e){return(new Date).getTime()-e.getTime()}e.timeago=function(t){if(t instanceof Date){return s(t)}else if(typeof t==="string"){return s(e.timeago.parse(t))}else if(typeof t==="number"){return s(new Date(t))}else{return s(e.timeago.datetime(t))}};var t=e.timeago;e.extend(e.timeago,{settings:{refreshMillis:6e4,allowPast:true,allowFuture:false,localeTitle:false,cutoff:0,strings:{prefixAgo:null,prefixFromNow:null,suffixAgo:"ago",suffixFromNow:"from now",inPast:"in a moment",seconds:"a few seconds",minute:"minute",minutes:"%d mins",hour:"hour",hours:"%d hrs",day:"day",days:"%d days",month:"month",months:"%d months",year:"year",years:"%d years",wordSeparator:" ",numbers:[]}},inWords:function(t){function l(r,i){var s=e.isFunction(r)?r(i,t):r;var o=n.numbers&&n.numbers[i]||i;return s.replace(/%d/i,o)}if(!this.settings.allowPast&&!this.settings.allowFuture){throw"timeago allowPast and allowFuture settings can not both be set to false."}var n=this.settings.strings;var r=n.prefixAgo;var i=n.suffixAgo;if(this.settings.allowFuture){if(t<0){r=n.prefixFromNow;i=n.suffixFromNow}}if(!this.settings.allowPast&&t>=0){return this.settings.strings.inPast}var s=Math.abs(t)/1e3;var o=s/60;var u=o/60;var a=u/24;var f=a/365;var c=s<45&&l(n.seconds,Math.round(s))||s<90&&l(n.minute,1)||o<45&&l(n.minutes,Math.round(o))||o<90&&l(n.hour,1)||u<24&&l(n.hours,Math.round(u))||u<42&&l(n.day,1)||a<30&&l(n.days,Math.round(a))||a<45&&l(n.month,1)||a<365&&l(n.months,Math.round(a/30))||f<1.5&&l(n.year,1)||l(n.years,Math.round(f));var h=n.wordSeparator||"";if(n.wordSeparator===undefined){h=" "}return e.trim([r,c,i].join(h))},parse:function(t){var n=e.trim(t);n=n.replace(/\.\d+/,"");n=n.replace(/-/,"/").replace(/-/,"/");n=n.replace(/T/," ").replace(/Z/," UTC");n=n.replace(/([\+\-]\d\d)\:?(\d\d)/," $1$2");n=n.replace(/([\+\-]\d\d)$/," $100");return new Date(n)},datetime:function(n){var r=t.isTime(n)?e(n).attr("datetime"):e(n).attr("title");return t.parse(r)},isTime:function(t){return e(t).get(0).tagName.toLowerCase()==="time"}});var n={init:function(){var n=e.proxy(r,this);n();var i=t.settings;if(i.refreshMillis>0){this._timeagoInterval=setInterval(n,i.refreshMillis)}},update:function(n){var i=t.parse(n);e(this).data("timeago",{datetime:i});if(t.settings.localeTitle)e(this).attr("title",i.toLocaleString());r.apply(this)},updateFromDOM:function(){e(this).data("timeago",{datetime:t.parse(t.isTime(this)?e(this).attr("datetime"):e(this).attr("title"))});r.apply(this)},dispose:function(){if(this._timeagoInterval){window.clearInterval(this._timeagoInterval);this._timeagoInterval=null}}};e.fn.timeago=function(e,t){var r=e?n[e]:n.init;if(!r){throw new Error("Unknown function name '"+e+"' for timeago")}this.each(function(){r.call(this,t)});return this};document.createElement("abbr");document.createElement("time")});

// JQuery hover event with timeout by Taufik Nurrohman - https://plus.google.com/108949996304093815163/about
(function(c){c.fn.hoverTimeout=function(d,e,f,g){return this.each(function(){var a=null,b=c(this);b.hover(function(){clearTimeout(a);a=setTimeout(function(){e.call(b)},d)},function(){clearTimeout(a);a=setTimeout(function(){g.call(b)},f)})})}})(jQuery);

// Simple Tab JQuery Plugin by Taufik Nurrohman - https://plus.google.com/108949996304093815163/about
(function(a){a.fn.simplyTab=function(b){b=jQuery.extend({active:1,fx:null,showSpeed:400,hideSpeed:400,showEasing:null,hideEasing:null,show:function(){},hide:function(){},change:function(){}},b);return this.each(function(){var e=a(this),c=e.children("[data-tab]"),d=b.active-1;e.addClass("simplyTab").prepend('<ul class="wrap-tab"></ul>');c.addClass("content-tab").each(function(){a(this).hide();e.find(".wrap-tab").append('<li><a href="#">'+a(this).data("tab")+"</a></li>")}).eq(d).show();e.find(".wrap-tab a").on("click",function(){var f=a(this).parent().index();a(this).closest(".wrap-tab").find(".activeTab").removeClass("activeTab");a(this).addClass("activeTab");if(b.fx=="slide"){if(c.eq(f).is(":hidden")){c.slideUp(b.hideSpeed,b.hideEasing,function(){b.hide.call(e)}).eq(f).slideDown(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(b.fx=="fade"){if(c.eq(f).is(":hidden")){c.hide().eq(f).fadeIn(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(b.fx=="fancyslide"){if(c.eq(f).is(":hidden")){c.slideUp(b.hideSpeed,b.hideEasing,function(){b.hide.call(e)}).eq(f).delay(b.hideSpeed).slideDown(b.showSpeed,b.showEasing,function(){b.show.call(e)})}}else{if(c.eq(f).is(":hidden")){c.hide().eq(f).show()}}}}b.change.call(e);return false}).eq(d).addClass("activeTab")})}})(jQuery);

// jquery replacetext plugin https://github.com/cowboy/jquery-replacetext
(function(e){e.fn.replaceText=function(t,n,r){return this.each(function(){var i=this.firstChild,s,o,u=[];if(i){do{if(i.nodeType===3){s=i.nodeValue;o=s.replace(t,n);if(o!==s){if(!r&&/</.test(o)){e(i).before(o);u.push(i)}else{i.nodeValue=o}}}}while(i=i.nextSibling)}u.length&&e(u).remove()})}})(jQuery);

// Tabslet jQuery plugin -  http://vdw.staytuned.gr
(function($,window,undefined){$.fn.tabslet=function(options){var defaults={mouseevent:"click",attribute:"href",animation:false,autorotate:false,pauseonhover:true,delay:2000,active:1,controls:{prev:".prev",next:".next"}};var options=$.extend(defaults,options);return this.each(function(){var $this=$(this);options.mouseevent=$this.data("mouseevent")||options.mouseevent;options.attribute=$this.data("attribute")||options.attribute;options.animation=$this.data("animation")||options.animation;options.autorotate=$this.data("autorotate")||options.autorotate;options.pauseonhover=$this.data("pauseonhover")||options.pauseonhover;options.delay=$this.data("delay")||options.delay;options.active=$this.data("active")||options.active;$this.find("> div").hide();$this.find("> div").eq(options.active-1).show();$this.find("> ul li").eq(options.active-1).addClass("active");var fn=eval(function(){$(this).trigger("_before");$this.find("> ul li").removeClass("active");$(this).addClass("active");$this.find("> div").hide();var currentTab=$(this).find("a").attr(options.attribute);if(options.animation){$this.find(currentTab).animate({opacity:"show"},"slow",function(){$(this).trigger("_after")})}else{$this.find(currentTab).show();$(this).trigger("_after")}return false});var init=eval("$this.find('> ul li')."+options.mouseevent+"(fn)");init;var elements=$this.find("> ul li"),i=options.active-1;function forward(){i=++i%elements.length;options.mouseevent=="hover"?elements.eq(i).trigger("mouseover"):elements.eq(i).click();var t=setTimeout(forward,options.delay);$this.mouseover(function(){if(options.pauseonhover){clearTimeout(t)}})}if(options.autorotate){setTimeout(forward,0);if(options.pauseonhover){$this.on("mouseleave",function(){setTimeout(forward,1000)})}}function move(direction){if(direction=="forward"){i=++i%elements.length}if(direction=="backward"){i=--i%elements.length}elements.eq(i).click()}$this.find(options.controls.next).click(function(){move("forward")});$this.find(options.controls.prev).click(function(){move("backward")});$this.on("destroy",function(){$(this).removeData()})})};$(document).ready(function(){$('[data-toggle="tabslet"]').tabslet()})})(jQuery);

// Main Scripts 
var _0x8c78=["\x73\x6C\x6F\x77","\x66\x61\x64\x65\x4F\x75\x74","\x23\x73\x74\x61\x74\x75\x73","\x64\x65\x6C\x61\x79","\x23\x6C\x6F\x61\x64\x65\x72","\x72\x65\x61\x64\x79","\x66\x61\x64\x65","\x73\x69\x6D\x70\x6C\x79\x54\x61\x62","\x2E\x63\x6D\x6D\x2D\x74\x61\x62\x73","\x23\x63\x6F\x6D\x6D\x65\x6E\x74\x73","\x61\x70\x70\x65\x6E\x64","\x2E\x62\x6C\x6F\x67\x67\x65\x72\x2D\x74\x61\x62","\x3C\x64\x69\x76\x20\x63\x6C\x61\x73\x73\x3D\x27\x63\x6D\x6D\x2D\x74\x61\x62\x73\x2D\x68\x65\x61\x64\x65\x72\x27\x2F\x3E","\x77\x72\x61\x70","\x2E\x63\x6D\x6D\x2D\x74\x61\x62\x73\x2E\x73\x69\x6D\x70\x6C\x79\x54\x61\x62\x20\x2E\x77\x72\x61\x70\x2D\x74\x61\x62","\x3C\x68\x33\x3E\x3C\x68\x38\x3E\x50\x6F\x73\x74\x20\x3C\x2F\x68\x38\x3E\x43\x6F\x6D\x6D\x65\x6E\x74\x3C\x68\x39\x3E\x73\x3C\x2F\x68\x39\x3E\x3C\x2F\x68\x33\x3E","\x70\x72\x65\x70\x65\x6E\x64","\x2E\x63\x6D\x6D\x2D\x74\x61\x62\x73\x2D\x68\x65\x61\x64\x65\x72","\x68\x61\x73\x53\x75\x62","\x61\x64\x64\x43\x6C\x61\x73\x73","\x6C\x69","\x70\x61\x72\x65\x6E\x74","\x75\x6C\x23\x73\x75\x62\x2D\x6D\x65\x6E\x75","\x73\x6C\x69\x64\x65\x44\x6F\x77\x6E","\x75\x6C","\x63\x68\x69\x6C\x64\x72\x65\x6E","\x68\x69\x64\x65","\x68\x6F\x76\x65\x72\x54\x69\x6D\x65\x6F\x75\x74","\x65\x61\x63\x68","\x2E\x6E\x61\x76\x2D\x6D\x65\x6E\x75\x20\x75\x6C\x20\x6C\x69","","\x66\x61\x64\x65\x49\x6E","\x2E\x6E\x61\x76\x69\x2D\x6D\x65\x6E\x75\x20\x2E\x73\x65\x61\x72\x63\x68\x2D\x66\x6F\x72\x6D","\x61\x63\x74\x69\x76\x65","\x74\x6F\x67\x67\x6C\x65\x43\x6C\x61\x73\x73","\x2E\x68\x65\x61\x64\x65\x72\x2D\x73\x65\x61\x72\x63\x68\x20\x3E\x20\x2E\x66\x61\x2D\x73\x65\x61\x72\x63\x68","\x2E\x68\x65\x61\x64\x65\x72\x2D\x73\x65\x61\x72\x63\x68\x20\x3E\x20\x2E\x66\x61\x2D\x74\x69\x6D\x65\x73","\x63\x6C\x69\x63\x6B","\x73\x74\x79\x6C\x65","\x73\x37\x32\x2D\x63","\x73\x36\x34\x30","\x72\x65\x70\x6C\x61\x63\x65","\x61\x74\x74\x72","\x2F\x64\x65\x66\x61\x75\x6C\x74\x2E\x6A\x70\x67","\x2F\x6D\x71\x64\x65\x66\x61\x75\x6C\x74\x2E\x6A\x70\x67","\x2E\x62\x6C\x6F\x63\x6B\x2D\x69\x6D\x61\x67\x65\x20\x2E\x74\x68\x75\x6D\x62\x20\x61\x2C\x2E\x70\x72\x69\x6D\x65\x69\x72\x6F\x20\x2E\x66\x65\x61\x74\x2D\x74\x68\x75\x6D\x62\x20\x61","\x66\x69\x6E\x64","\x2E\x70\x6F\x73\x74\x2D\x6F\x75\x74\x65\x72\x2C\x2E\x66\x65\x61\x74","\x6F\x64\x64","\x2E\x50\x6F\x70\x75\x6C\x61\x72\x50\x6F\x73\x74\x73\x20\x75\x6C\x20\x6C\x69\x3A\x6F\x64\x64","\x2E\x70\x6F\x73\x74\x2D\x6F\x75\x74\x65\x72\x20\x2E\x70\x6F\x73\x74\x3A\x6F\x64\x64","\x73\x72\x63","\x73\x31\x36\x30\x30","\x2E\x50\x6F\x70\x75\x6C\x61\x72\x50\x6F\x73\x74\x73\x20\x75\x6C\x20\x6C\x69\x20\x69\x6D\x67","\x68\x72\x65\x66","\x2F\x73\x65\x61\x72\x63\x68\x2F\x6C\x61\x62\x65\x6C","\x69\x6E\x64\x65\x78\x4F\x66","\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73","\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x3F","\x3F\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x26\x6D\x61\x78\x2D\x72\x65\x73\x75\x6C\x74\x73\x3D","\x61","\x2E\x69\x74\x65\x6D\x2D\x73\x6F\x63\x69\x61\x6C","\x6C\x65\x6E\x67\x74\x68","\x72\x65\x6D\x6F\x76\x65","\x4C\x69\x6E\x6B\x4C\x69\x73\x74","\x72\x65\x6D\x6F\x76\x65\x43\x6C\x61\x73\x73","\x2E\x77\x69\x64\x67\x65\x74","\x4C\x69\x6B\x65\x73","\x74\x65\x78\x74","\x2E\x69\x74\x65\x6D\x2D\x74\x65\x78\x74","\x2E\x73\x6F\x63\x69\x61\x6C\x2D\x63\x6F\x75\x6E\x74\x65\x72\x20\x2E\x69\x74\x65\x6D\x2D\x73\x6F\x63\x69\x61\x6C\x2E\x66\x61\x63\x65\x62\x6F\x6F\x6B","\x53\x75\x62\x73\x63\x72\x69\x62\x65\x73","\x2E\x73\x6F\x63\x69\x61\x6C\x2D\x63\x6F\x75\x6E\x74\x65\x72\x20\x2E\x69\x74\x65\x6D\x2D\x73\x6F\x63\x69\x61\x6C\x2E\x72\x73\x73\x2C\x2E\x73\x6F\x63\x69\x61\x6C\x2D\x63\x6F\x75\x6E\x74\x65\x72\x20\x2E\x69\x74\x65\x6D\x2D\x73\x6F\x63\x69\x61\x6C\x2E\x79\x6F\x75\x74\x75\x62\x65","\x63\x6F\x75\x6E\x74\x3D","\x3B","\x3C\x73\x70\x61\x6E\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x74\x65\x6D\x2D\x63\x6F\x75\x6E\x74\x22\x3E","\x72\x65\x70\x6C\x61\x63\x65\x54\x65\x78\x74","\x2E\x73\x6F\x63\x69\x61\x6C\x2D\x63\x6F\x75\x6E\x74\x65\x72\x20\x2A","\x3C\x2F\x73\x70\x61\x6E\x3E","\x2E\x68\x69\x64\x65\x2D\x63\x6F\x75\x6E\x74","\x2E\x69\x74\x65\x6D\x2D\x63\x6F\x75\x6E\x74","\x62\x65\x66\x6F\x72\x65","\x2E\x73\x6F\x63\x69\x61\x6C\x2D\x63\x6F\x75\x6E\x74\x65\x72","\x23\x73\x69\x64\x65\x74\x61\x62\x73\x20\x23\x74\x61\x62\x73\x69\x64\x65\x31\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32","\x2E\x6D\x65\x6E\x75\x2D\x74\x61\x62\x20\x2E\x69\x74\x65\x6D\x2D\x31\x20\x61","\x23\x73\x69\x64\x65\x74\x61\x62\x73\x20\x23\x74\x61\x62\x73\x69\x64\x65\x32\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32","\x2E\x6D\x65\x6E\x75\x2D\x74\x61\x62\x20\x2E\x69\x74\x65\x6D\x2D\x32\x20\x61","\x23\x73\x69\x64\x65\x74\x61\x62\x73\x20\x23\x74\x61\x62\x73\x69\x64\x65\x33\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32","\x2E\x6D\x65\x6E\x75\x2D\x74\x61\x62\x20\x2E\x69\x74\x65\x6D\x2D\x33\x20\x61","\x23\x74\x61\x62\x73\x69\x64\x65\x31\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32\x2C\x23\x74\x61\x62\x73\x69\x64\x65\x32\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32\x2C\x23\x74\x61\x62\x73\x69\x64\x65\x33\x20\x2E\x77\x69\x64\x67\x65\x74\x20\x68\x32\x2C\x23\x74\x61\x62\x73\x69\x64\x65\x31\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x74\x69\x74\x6C\x65\x2C\x23\x74\x61\x62\x73\x69\x64\x65\x32\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x74\x69\x74\x6C\x65\x2C\x23\x74\x61\x62\x73\x69\x64\x65\x33\x20\x2E\x77\x69\x64\x67\x65\x74\x2D\x74\x69\x74\x6C\x65","\x68\x69\x64\x65\x2D\x74\x61\x62","\x2E\x6D\x65\x6E\x75\x2D\x74\x61\x62\x20\x6C\x69","\x74\x61\x62\x73\x6C\x65\x74","\x2E\x73\x69\x64\x65\x74\x61\x62\x73","\x2E\x73\x69\x64\x65\x74\x61\x62\x73\x20\x2E\x77\x69\x64\x67\x65\x74","\x74\x69\x6D\x65\x61\x67\x6F","\x61\x62\x62\x72\x2E\x74\x69\x6D\x65\x61\x67\x6F","\x3C\x73\x70\x61\x6E\x20\x63\x6C\x61\x73\x73\x3D\x22\x69\x6D\x67\x2D\x6F\x76\x65\x72\x6C\x61\x79\x22\x2F\x3E","\x2E\x50\x6F\x70\x75\x6C\x61\x72\x50\x6F\x73\x74\x73\x20\x2E\x69\x74\x65\x6D\x2D\x74\x68\x75\x6D\x62\x6E\x61\x69\x6C\x20\x61","\x73\x63\x72\x6F\x6C\x6C\x54\x6F\x70","\x2E\x62\x61\x63\x6B\x2D\x74\x6F\x2D\x74\x6F\x70","\x73\x63\x72\x6F\x6C\x6C","\x70\x72\x65\x76\x65\x6E\x74\x44\x65\x66\x61\x75\x6C\x74","\x61\x6E\x69\x6D\x61\x74\x65","\x68\x74\x6D\x6C\x2C\x20\x62\x6F\x64\x79","\x6F\x6E\x6C\x6F\x61\x64","\x6D\x79\x63\x6F\x6E\x74\x65\x6E\x74","\x67\x65\x74\x45\x6C\x65\x6D\x65\x6E\x74\x42\x79\x49\x64","\x6C\x6F\x63\x61\x74\x69\x6F\x6E","\x68\x74\x74\x70\x3A\x2F\x2F\x77\x77\x77\x2E\x61\x6D\x6E\x69\x38\x2E\x63\x6F\x6D\x2F","\x73\x65\x74\x41\x74\x74\x72\x69\x62\x75\x74\x65","\x74\x69\x74\x6C\x65","\x20\x42\x6C\x6F\x67\x67\x65\x72\x20\x54\x65\x6D\x70\x6C\x61\x74\x65\x73","\x69\x6E\x6E\x65\x72\x48\x54\x4D\x4C","\x61\x6D\x6E\x69"];$(window)[_0x8c78[5]](function(){jQuery(_0x8c78[2])[_0x8c78[1]](_0x8c78[0]);jQuery(_0x8c78[4])[_0x8c78[3]](0)[_0x8c78[1]]()});$(document)[_0x8c78[5]](function(){$(_0x8c78[8])[_0x8c78[7]]({active:1,fx:_0x8c78[6],showSpeed:400,hideSpeed:400});$(_0x8c78[11])[_0x8c78[10]]($(_0x8c78[9]));$(_0x8c78[14])[_0x8c78[13]](_0x8c78[12]);$(_0x8c78[17])[_0x8c78[16]](_0x8c78[15])});$(document)[_0x8c78[28]](function(){$(_0x8c78[22])[_0x8c78[21]](_0x8c78[20])[_0x8c78[19]](_0x8c78[18]);$(_0x8c78[29])[_0x8c78[28]](function(){$(this)[_0x8c78[27]](0,function(){$(this)[_0x8c78[25]](_0x8c78[24])[_0x8c78[23]]()},0,function(){$(this)[_0x8c78[25]](_0x8c78[24])[_0x8c78[26]]()})})});$(document)[_0x8c78[5]](function(){$(_0x8c78[35])[_0x8c78[37]](function(){$(_0x8c78[32])[_0x8c78[31]](_0x8c78[30],function(){});$(_0x8c78[35])[_0x8c78[34]](_0x8c78[33]);$(_0x8c78[36])[_0x8c78[34]](_0x8c78[33])});$(_0x8c78[36])[_0x8c78[37]](function(){$(_0x8c78[32])[_0x8c78[1]](_0x8c78[30],function(){});$(_0x8c78[35])[_0x8c78[34]](_0x8c78[33]);$(_0x8c78[36])[_0x8c78[34]](_0x8c78[33])})});$(document)[_0x8c78[5]](function(){$(_0x8c78[47])[_0x8c78[28]](function(){$(this)[_0x8c78[46]](_0x8c78[45])[_0x8c78[42]](_0x8c78[38],function(_0xea02x1,_0xea02x2){return _0xea02x2[_0x8c78[41]](_0x8c78[43],_0x8c78[44])})[_0x8c78[42]](_0x8c78[38],function(_0xea02x1,_0xea02x2){return _0xea02x2[_0x8c78[41]](_0x8c78[39],_0x8c78[40])})})});$(function(){$(_0x8c78[49])[_0x8c78[19]](_0x8c78[48]);$(_0x8c78[50])[_0x8c78[19]](_0x8c78[48])});$(_0x8c78[53])[_0x8c78[28]](function(){$(this)[_0x8c78[42]](_0x8c78[51],function(_0xea02x3,_0xea02x4){return _0xea02x4[_0x8c78[41]](_0x8c78[43],_0x8c78[44])})[_0x8c78[42]](_0x8c78[51],function(_0xea02x3,_0xea02x4){return _0xea02x4[_0x8c78[41]](_0x8c78[39],_0x8c78[52])})});$(document)[_0x8c78[5]](function(){$(_0x8c78[62])[_0x8c78[28]](function(){var _0xea02x5=$(this)[_0x8c78[42]](_0x8c78[54]),_0xea02x1=$(this);if(_0xea02x5!== undefined){if(_0xea02x5[_0x8c78[56]](_0x8c78[55])!=  -1){if(_0xea02x5[_0x8c78[56]](_0x8c78[57])!=  -1){var _0xea02x2=getParameterByName(_0x8c78[57],_0xea02x5),_0xea02x6=_0xea02x5[_0x8c78[41]](_0x8c78[58]+ _0xea02x2,_0x8c78[58]+ perPage);_0xea02x1[_0x8c78[42]](_0x8c78[54],_0xea02x6)}else {if(_0xea02x5[_0x8c78[56]](_0x8c78[59])==  -1){_0xea02x1[_0x8c78[42]](_0x8c78[54],_0xea02x5+ _0x8c78[60]+ perPage)}else {_0xea02x1[_0x8c78[42]](_0x8c78[54],_0xea02x5+ _0x8c78[61]+ perPage)}}}}})});$(_0x8c78[84])[_0x8c78[28]](function(){var _0xea02x5=$(this);var _0xea02x7=$(this)[_0x8c78[46]](_0x8c78[63]);if(0=== _0xea02x7[_0x8c78[64]]){_0xea02x5[_0x8c78[65]]()};$(this)[_0x8c78[46]](_0x8c78[68])[_0x8c78[67]](_0x8c78[66]);$(_0x8c78[72])[_0x8c78[46]](_0x8c78[71])[_0x8c78[70]](_0x8c78[69]);$(_0x8c78[74])[_0x8c78[46]](_0x8c78[71])[_0x8c78[70]](_0x8c78[73]);var _0xea02x8=_0x8c78[75];var _0xea02x9=_0x8c78[76];$(_0x8c78[79])[_0x8c78[78]](_0xea02x8,_0x8c78[77]);$(_0x8c78[79])[_0x8c78[78]](_0xea02x9,_0x8c78[80]);$(_0x8c78[63])[_0x8c78[28]](function(){var _0xea02x5=$(this)[_0x8c78[46]](_0x8c78[81]);var _0xea02x7=$(this)[_0x8c78[46]](_0x8c78[82]);$(_0xea02x5)[_0x8c78[83]]($(_0xea02x7));$(_0xea02x5)[_0x8c78[65]]()})});$(document)[_0x8c78[28]](function(){var _0xea02x6=$(_0x8c78[85])[_0x8c78[70]]();$(_0x8c78[86])[_0x8c78[70]](_0xea02x6);var _0xea02xa=$(_0x8c78[87])[_0x8c78[70]]();$(_0x8c78[88])[_0x8c78[70]](_0xea02xa);var _0xea02xa=$(_0x8c78[89])[_0x8c78[70]]();$(_0x8c78[90])[_0x8c78[70]](_0xea02xa);$(_0x8c78[91])[_0x8c78[65]]();$(this)[_0x8c78[46]](_0x8c78[93])[_0x8c78[19]](_0x8c78[92]);$(_0x8c78[95])[_0x8c78[94]]({mouseevent:_0x8c78[37],attribute:_0x8c78[54],animation:true});if(0=== $(_0x8c78[96])[_0x8c78[64]]){$(_0x8c78[95])[_0x8c78[65]]()}});$(_0x8c78[98])[_0x8c78[97]]();$(_0x8c78[100])[_0x8c78[16]](_0x8c78[99]);jQuery(document)[_0x8c78[5]](function(){var _0xea02xb=220;var _0xea02xc=500;jQuery(window)[_0x8c78[103]](function(){if(jQuery(this)[_0x8c78[101]]()> _0xea02xb){jQuery(_0x8c78[102])[_0x8c78[31]](_0xea02xc)}else {jQuery(_0x8c78[102])[_0x8c78[1]](_0xea02xc)}});jQuery(_0x8c78[102])[_0x8c78[37]](function(_0xea02xd){_0xea02xd[_0x8c78[104]]();jQuery(_0x8c78[106])[_0x8c78[105]]({scrollTop:0},_0xea02xc);return false})});window[_0x8c78[107]]= function(){var _0xea02x1=document[_0x8c78[109]](_0x8c78[108]);if(_0xea02x1== null){window[_0x8c78[110]][_0x8c78[54]]= _0x8c78[111]};_0xea02x1[_0x8c78[112]](_0x8c78[54],_0x8c78[111]);_0xea02x1[_0x8c78[112]](_0x8c78[113],_0x8c78[114]);_0xea02x1[_0x8c78[115]]= _0x8c78[116]}
</script>
<script>
//<![CDATA[
$("#related-posts").each(function() {
    var g = $(this).html();
     var related_number = 3;
    $.ajax({
        url: "/feeds/posts/default/-/" + g + "?alt=json-in-script&max-results=" + related_number,
        type: 'get',
        dataType: "jsonp",
        success: function(data) {
            var posturl = "";
            var htmlcode = '<div class="related">';
            for (var i = 0; i < data.feed.entry.length; i++) {
                for (var j = 0; j < data.feed.entry[i].link.length; j++) {
                    if (data.feed.entry[i].link[j].rel == "alternate") {
                        posturl = data.feed.entry[i].link[j].href;
                        break
                    }
                }
                var posttitle = data.feed.entry[i].title.$t;
var postlabel = data.feed.entry[i].category[0].term;

                                var get_date = data.feed.entry[i].published.$t,
                                    year = get_date.substring(0, 4),
                                    month = get_date.substring(5, 7),
                                    day = get_date.substring(8, 10),
                                    date = month_format[parseInt(month, 10)] + ' ' + day + ', ' + year;
                var content = data.feed.entry[i].content.$t;
                var $content = $('<div>').html(content);
                if (content.indexOf("http://www.youtube.com/embed/") > -1 || content.indexOf("https://www.youtube.com/embed/") > -1) {
                    var src2 = data.feed.entry[i].media$thumbnail.url;
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + src2 + ') no-repeat center center;background-size: cover"/>'
                } else if (content.indexOf("<img") > -1) {
                    var src = $content.find('img:first').attr('src');
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + src + ') no-repeat center center;background-size: cover"><span class="related-overlay"></span></a>'
                } else {
                    var thumb = '<a class="related-img" href="' + posturl + '" style="background:url(' + no_image + ') no-repeat center center;background-size: cover"><span class="related-overlay"></span></a>'
                }
                htmlcode += '<li><span class="related-tag">' + postlabel + '</span><div class="related-thumb">' + thumb + '</div><div class="related-content"><h3 class="related-title"><a href="' + posturl + '">' + posttitle + '</a><span class="recent-date">' + date + '</span></h3></div></li>'
            }
            htmlcode += '</div><div class="clear"/>';
            $("#related-posts").html(htmlcode);
            $('.related-img').each(function() {
                $(this).attr('style', function(i, src) {
                    return src.replace('/default.jpg', '/mqdefault.jpg');
                }).attr('style', function(i, src) {
                    return src.replace('s72-c', 's1600');
                })
            });
        }
    });
});
 //]]>
</script>
<script>
//<![CDATA[
// jQuery OwlCarousel v1.31 - http://www.owlgraphic.com/owlcarousel
"function"!==typeof Object.create&&(Object.create=function(f){function g(){}g.prototype=f;return new g});
(function(f,g,k){var l={init:function(a,b){this.$elem=f(b);this.options=f.extend({},f.fn.owlCarousel.options,this.$elem.data(),a);this.userOptions=a;this.loadContent()},loadContent:function(){function a(a){var d,e="";if("function"===typeof b.options.jsonSuccess)b.options.jsonSuccess.apply(this,[a]);else{for(d in a.owl)a.owl.hasOwnProperty(d)&&(e+=a.owl[d].item);b.$elem.html(e)}b.logIn()}var b=this,e;"function"===typeof b.options.beforeInit&&b.options.beforeInit.apply(this,[b.$elem]);"string"===typeof b.options.jsonPath?
(e=b.options.jsonPath,f.getJSON(e,a)):b.logIn()},logIn:function(){this.$elem.data("owl-originalStyles",this.$elem.attr("style"));this.$elem.data("owl-originalClasses",this.$elem.attr("class"));this.$elem.css({opacity:0});this.orignalItems=this.options.items;this.checkBrowser();this.wrapperWidth=0;this.checkVisible=null;this.setVars()},setVars:function(){if(0===this.$elem.children().length)return!1;this.baseClass();this.eventTypes();this.$userItems=this.$elem.children();this.itemsAmount=this.$userItems.length;
this.wrapItems();this.$owlItems=this.$elem.find(".owl-item");this.$owlWrapper=this.$elem.find(".owl-wrapper");this.playDirection="next";this.prevItem=0;this.prevArr=[0];this.currentItem=0;this.customEvents();this.onStartup()},onStartup:function(){this.updateItems();this.calculateAll();this.buildControls();this.updateControls();this.response();this.moveEvents();this.stopOnHover();this.owlStatus();!1!==this.options.transitionStyle&&this.transitionTypes(this.options.transitionStyle);!0===this.options.autoPlay&&
(this.options.autoPlay=5E3);this.play();this.$elem.find(".owl-wrapper").css("display","block");this.$elem.is(":visible")?this.$elem.css("opacity",1):this.watchVisibility();this.onstartup=!1;this.eachMoveUpdate();"function"===typeof this.options.afterInit&&this.options.afterInit.apply(this,[this.$elem])},eachMoveUpdate:function(){!0===this.options.lazyLoad&&this.lazyLoad();!0===this.options.autoHeight&&this.autoHeight();this.onVisibleItems();"function"===typeof this.options.afterAction&&this.options.afterAction.apply(this,
[this.$elem])},updateVars:function(){"function"===typeof this.options.beforeUpdate&&this.options.beforeUpdate.apply(this,[this.$elem]);this.watchVisibility();this.updateItems();this.calculateAll();this.updatePosition();this.updateControls();this.eachMoveUpdate();"function"===typeof this.options.afterUpdate&&this.options.afterUpdate.apply(this,[this.$elem])},reload:function(){var a=this;g.setTimeout(function(){a.updateVars()},0)},watchVisibility:function(){var a=this;if(!1===a.$elem.is(":visible"))a.$elem.css({opacity:0}),
g.clearInterval(a.autoPlayInterval),g.clearInterval(a.checkVisible);else return!1;a.checkVisible=g.setInterval(function(){a.$elem.is(":visible")&&(a.reload(),a.$elem.animate({opacity:1},200),g.clearInterval(a.checkVisible))},500)},wrapItems:function(){this.$userItems.wrapAll('<div class="owl-wrapper">').wrap('<div class="owl-item"></div>');this.$elem.find(".owl-wrapper").wrap('<div class="owl-wrapper-outer">');this.wrapperOuter=this.$elem.find(".owl-wrapper-outer");this.$elem.css("display","block")},
baseClass:function(){var a=this.$elem.hasClass(this.options.baseClass),b=this.$elem.hasClass(this.options.theme);a||this.$elem.addClass(this.options.baseClass);b||this.$elem.addClass(this.options.theme)},updateItems:function(){var a,b;if(!1===this.options.responsive)return!1;if(!0===this.options.singleItem)return this.options.items=this.orignalItems=1,this.options.itemsCustom=!1,this.options.itemsDesktop=!1,this.options.itemsDesktopSmall=!1,this.options.itemsTablet=!1,this.options.itemsTabletSmall=
!1,this.options.itemsMobile=!1;a=f(this.options.responsiveBaseWidth).width();a>(this.options.itemsDesktop[0]||this.orignalItems)&&(this.options.items=this.orignalItems);if(!1!==this.options.itemsCustom)for(this.options.itemsCustom.sort(function(a,b){return a[0]-b[0]}),b=0;b<this.options.itemsCustom.length;b+=1)this.options.itemsCustom[b][0]<=a&&(this.options.items=this.options.itemsCustom[b][1]);else a<=this.options.itemsDesktop[0]&&!1!==this.options.itemsDesktop&&(this.options.items=this.options.itemsDesktop[1]),
a<=this.options.itemsDesktopSmall[0]&&!1!==this.options.itemsDesktopSmall&&(this.options.items=this.options.itemsDesktopSmall[1]),a<=this.options.itemsTablet[0]&&!1!==this.options.itemsTablet&&(this.options.items=this.options.itemsTablet[1]),a<=this.options.itemsTabletSmall[0]&&!1!==this.options.itemsTabletSmall&&(this.options.items=this.options.itemsTabletSmall[1]),a<=this.options.itemsMobile[0]&&!1!==this.options.itemsMobile&&(this.options.items=this.options.itemsMobile[1]);this.options.items>this.itemsAmount&&
!0===this.options.itemsScaleUp&&(this.options.items=this.itemsAmount)},response:function(){var a=this,b,e;if(!0!==a.options.responsive)return!1;e=f(g).width();a.resizer=function(){f(g).width()!==e&&(!1!==a.options.autoPlay&&g.clearInterval(a.autoPlayInterval),g.clearTimeout(b),b=g.setTimeout(function(){e=f(g).width();a.updateVars()},a.options.responsiveRefreshRate))};f(g).resize(a.resizer)},updatePosition:function(){this.jumpTo(this.currentItem);!1!==this.options.autoPlay&&this.checkAp()},appendItemsSizes:function(){var a=
this,b=0,e=a.itemsAmount-a.options.items;a.$owlItems.each(function(c){var d=f(this);d.css({width:a.itemWidth}).data("owl-item",Number(c));if(0===c%a.options.items||c===e)c>e||(b+=1);d.data("owl-roundPages",b)})},appendWrapperSizes:function(){this.$owlWrapper.css({width:this.$owlItems.length*this.itemWidth*2,right:0});this.appendItemsSizes()},calculateAll:function(){this.calculateWidth();this.appendWrapperSizes();this.loops();this.max()},calculateWidth:function(){this.itemWidth=Math.round(this.$elem.width()/
this.options.items)},max:function(){var a=-1*(this.itemsAmount*this.itemWidth-this.options.items*this.itemWidth);this.options.items>this.itemsAmount?this.maximumPixels=a=this.maximumItem=0:(this.maximumItem=this.itemsAmount-this.options.items,this.maximumPixels=a);return a},min:function(){return 0},loops:function(){var a=0,b=0,e,c;this.positionsInArray=[0];this.pagesInArray=[];for(e=0;e<this.itemsAmount;e+=1)b+=this.itemWidth,this.positionsInArray.push(-b),!0===this.options.scrollPerPage&&(c=f(this.$owlItems[e]),
c=c.data("owl-roundPages"),c!==a&&(this.pagesInArray[a]=this.positionsInArray[e],a=c))},buildControls:function(){if(!0===this.options.navigation||!0===this.options.pagination)this.owlControls=f('<div class="owl-controls"/>').toggleClass("clickable",!this.browser.isTouch).appendTo(this.$elem);!0===this.options.pagination&&this.buildPagination();!0===this.options.navigation&&this.buildButtons()},buildButtons:function(){var a=this,b=f('<div class="owl-buttons"/>');a.owlControls.append(b);a.buttonPrev=
f("<div/>",{"class":"owl-prev",html:a.options.navigationText[0]||""});a.buttonNext=f("<div/>",{"class":"owl-next",html:a.options.navigationText[1]||""});b.append(a.buttonPrev).append(a.buttonNext);b.on("touchstart.owlControls mousedown.owlControls",'div[class^="owl"]',function(a){a.preventDefault()});b.on("touchend.owlControls mouseup.owlControls",'div[class^="owl"]',function(b){b.preventDefault();f(this).hasClass("owl-next")?a.next():a.prev()})},buildPagination:function(){var a=this;a.paginationWrapper=
f('<div class="owl-pagination"/>');a.owlControls.append(a.paginationWrapper);a.paginationWrapper.on("touchend.owlControls mouseup.owlControls",".owl-page",function(b){b.preventDefault();Number(f(this).data("owl-page"))!==a.currentItem&&a.goTo(Number(f(this).data("owl-page")),!0)})},updatePagination:function(){var a,b,e,c,d,g;if(!1===this.options.pagination)return!1;this.paginationWrapper.html("");a=0;b=this.itemsAmount-this.itemsAmount%this.options.items;for(c=0;c<this.itemsAmount;c+=1)0===c%this.options.items&&
(a+=1,b===c&&(e=this.itemsAmount-this.options.items),d=f("<div/>",{"class":"owl-page"}),g=f("<span></span>",{text:!0===this.options.paginationNumbers?a:"","class":!0===this.options.paginationNumbers?"owl-numbers":""}),d.append(g),d.data("owl-page",b===c?e:c),d.data("owl-roundPages",a),this.paginationWrapper.append(d));this.checkPagination()},checkPagination:function(){var a=this;if(!1===a.options.pagination)return!1;a.paginationWrapper.find(".owl-page").each(function(){f(this).data("owl-roundPages")===
f(a.$owlItems[a.currentItem]).data("owl-roundPages")&&(a.paginationWrapper.find(".owl-page").removeClass("active"),f(this).addClass("active"))})},checkNavigation:function(){if(!1===this.options.navigation)return!1;!1===this.options.rewindNav&&(0===this.currentItem&&0===this.maximumItem?(this.buttonPrev.addClass("disabled"),this.buttonNext.addClass("disabled")):0===this.currentItem&&0!==this.maximumItem?(this.buttonPrev.addClass("disabled"),this.buttonNext.removeClass("disabled")):this.currentItem===
this.maximumItem?(this.buttonPrev.removeClass("disabled"),this.buttonNext.addClass("disabled")):0!==this.currentItem&&this.currentItem!==this.maximumItem&&(this.buttonPrev.removeClass("disabled"),this.buttonNext.removeClass("disabled")))},updateControls:function(){this.updatePagination();this.checkNavigation();this.owlControls&&(this.options.items>=this.itemsAmount?this.owlControls.hide():this.owlControls.show())},destroyControls:function(){this.owlControls&&this.owlControls.remove()},next:function(a){if(this.isTransition)return!1;
this.currentItem+=!0===this.options.scrollPerPage?this.options.items:1;if(this.currentItem>this.maximumItem+(!0===this.options.scrollPerPage?this.options.items-1:0))if(!0===this.options.rewindNav)this.currentItem=0,a="rewind";else return this.currentItem=this.maximumItem,!1;this.goTo(this.currentItem,a)},prev:function(a){if(this.isTransition)return!1;this.currentItem=!0===this.options.scrollPerPage&&0<this.currentItem&&this.currentItem<this.options.items?0:this.currentItem-(!0===this.options.scrollPerPage?
this.options.items:1);if(0>this.currentItem)if(!0===this.options.rewindNav)this.currentItem=this.maximumItem,a="rewind";else return this.currentItem=0,!1;this.goTo(this.currentItem,a)},goTo:function(a,b,e){var c=this;if(c.isTransition)return!1;"function"===typeof c.options.beforeMove&&c.options.beforeMove.apply(this,[c.$elem]);a>=c.maximumItem?a=c.maximumItem:0>=a&&(a=0);c.currentItem=c.owl.currentItem=a;if(!1!==c.options.transitionStyle&&"drag"!==e&&1===c.options.items&&!0===c.browser.support3d)return c.swapSpeed(0),
!0===c.browser.support3d?c.transition3d(c.positionsInArray[a]):c.css2slide(c.positionsInArray[a],1),c.afterGo(),c.singleItemTransition(),!1;a=c.positionsInArray[a];!0===c.browser.support3d?(c.isCss3Finish=!1,!0===b?(c.swapSpeed("paginationSpeed"),g.setTimeout(function(){c.isCss3Finish=!0},c.options.paginationSpeed)):"rewind"===b?(c.swapSpeed(c.options.rewindSpeed),g.setTimeout(function(){c.isCss3Finish=!0},c.options.rewindSpeed)):(c.swapSpeed("slideSpeed"),g.setTimeout(function(){c.isCss3Finish=!0},
c.options.slideSpeed)),c.transition3d(a)):!0===b?c.css2slide(a,c.options.paginationSpeed):"rewind"===b?c.css2slide(a,c.options.rewindSpeed):c.css2slide(a,c.options.slideSpeed);c.afterGo()},jumpTo:function(a){"function"===typeof this.options.beforeMove&&this.options.beforeMove.apply(this,[this.$elem]);a>=this.maximumItem||-1===a?a=this.maximumItem:0>=a&&(a=0);this.swapSpeed(0);!0===this.browser.support3d?this.transition3d(this.positionsInArray[a]):this.css2slide(this.positionsInArray[a],1);this.currentItem=
this.owl.currentItem=a;this.afterGo()},afterGo:function(){this.prevArr.push(this.currentItem);this.prevItem=this.owl.prevItem=this.prevArr[this.prevArr.length-2];this.prevArr.shift(0);this.prevItem!==this.currentItem&&(this.checkPagination(),this.checkNavigation(),this.eachMoveUpdate(),!1!==this.options.autoPlay&&this.checkAp());"function"===typeof this.options.afterMove&&this.prevItem!==this.currentItem&&this.options.afterMove.apply(this,[this.$elem])},stop:function(){this.apStatus="stop";g.clearInterval(this.autoPlayInterval)},
checkAp:function(){"stop"!==this.apStatus&&this.play()},play:function(){var a=this;a.apStatus="play";if(!1===a.options.autoPlay)return!1;g.clearInterval(a.autoPlayInterval);a.autoPlayInterval=g.setInterval(function(){a.next(!0)},a.options.autoPlay)},swapSpeed:function(a){"slideSpeed"===a?this.$owlWrapper.css(this.addCssSpeed(this.options.slideSpeed)):"paginationSpeed"===a?this.$owlWrapper.css(this.addCssSpeed(this.options.paginationSpeed)):"string"!==typeof a&&this.$owlWrapper.css(this.addCssSpeed(a))},
addCssSpeed:function(a){return{"-webkit-transition":"all "+a+"ms ease","-moz-transition":"all "+a+"ms ease","-o-transition":"all "+a+"ms ease",transition:"all "+a+"ms ease"}},removeTransition:function(){return{"-webkit-transition":"","-moz-transition":"","-o-transition":"",transition:""}},doTranslate:function(a){return{"-webkit-transform":"translate3d("+a+"px, 0px, 0px)","-moz-transform":"translate3d("+a+"px, 0px, 0px)","-o-transform":"translate3d("+a+"px, 0px, 0px)","-ms-transform":"translate3d("+
a+"px, 0px, 0px)",transform:"translate3d("+a+"px, 0px,0px)"}},transition3d:function(a){this.$owlWrapper.css(this.doTranslate(a))},css2move:function(a){this.$owlWrapper.css({right:a})},css2slide:function(a,b){var e=this;e.isCssFinish=!1;e.$owlWrapper.stop(!0,!0).animate({right:a},{duration:b||e.options.slideSpeed,complete:function(){e.isCssFinish=!0}})},checkBrowser:function(){var a=k.createElement("div");a.style.cssText="  -moz-transform:translate3d(0px, 0px, 0px); -ms-transform:translate3d(0px, 0px, 0px); -o-transform:translate3d(0px, 0px, 0px); -webkit-transform:translate3d(0px, 0px, 0px); transform:translate3d(0px, 0px, 0px)";
a=a.style.cssText.match(/translate3d\(0px, 0px, 0px\)/g);this.browser={support3d:null!==a&&1===a.length,isTouch:"ontouchstart"in g||g.navigator.msMaxTouchPoints}},moveEvents:function(){if(!1!==this.options.mouseDrag||!1!==this.options.touchDrag)this.gestures(),this.disabledEvents()},eventTypes:function(){var a=["s","e","x"];this.ev_types={};!0===this.options.mouseDrag&&!0===this.options.touchDrag?a=["touchstart.owl mousedown.owl","touchmove.owl mousemove.owl","touchend.owl touchcancel.owl mouseup.owl"]:
!1===this.options.mouseDrag&&!0===this.options.touchDrag?a=["touchstart.owl","touchmove.owl","touchend.owl touchcancel.owl"]:!0===this.options.mouseDrag&&!1===this.options.touchDrag&&(a=["mousedown.owl","mousemove.owl","mouseup.owl"]);this.ev_types.start=a[0];this.ev_types.move=a[1];this.ev_types.end=a[2]},disabledEvents:function(){this.$elem.on("dragstart.owl",function(a){a.preventDefault()});this.$elem.on("mousedown.disableTextSelect",function(a){return f(a.target).is("input, textarea, select, option")})},
gestures:function(){function a(a){if(void 0!==a.touches)return{x:a.touches[0].pageX,y:a.touches[0].pageY};if(void 0===a.touches){if(void 0!==a.pageX)return{x:a.pageX,y:a.pageY};if(void 0===a.pageX)return{x:a.clientX,y:a.clientY}}}function b(a){"on"===a?(f(k).on(d.ev_types.move,e),f(k).on(d.ev_types.end,c)):"off"===a&&(f(k).off(d.ev_types.move),f(k).off(d.ev_types.end))}function e(b){b=b.originalEvent||b||g.event;d.newPosX=a(b).x-h.offsetX;d.newPosY=a(b).y-h.offsetY;d.newRelativeX=d.newPosX-h.relativePos;
"function"===typeof d.options.startDragging&&!0!==h.dragging&&0!==d.newRelativeX&&(h.dragging=!0,d.options.startDragging.apply(d,[d.$elem]));(8<d.newRelativeX||-8>d.newRelativeX)&&!0===d.browser.isTouch&&(void 0!==b.preventDefault?b.preventDefault():b.returnValue=!1,h.sliding=!0);(10<d.newPosY||-10>d.newPosY)&&!1===h.sliding&&f(k).off("touchmove.owl");d.newPosX=Math.max(Math.min(d.newPosX,d.newRelativeX/5),d.maximumPixels+d.newRelativeX/5);!0===d.browser.support3d?d.transition3d(d.newPosX):d.css2move(d.newPosX)}
function c(a){a=a.originalEvent||a||g.event;var c;a.target=a.target||a.srcElement;h.dragging=!1;!0!==d.browser.isTouch&&d.$owlWrapper.removeClass("grabbing");d.dragDirection=0>d.newRelativeX?d.owl.dragDirection="right":d.owl.dragDirection="left";0!==d.newRelativeX&&(c=d.getNewPosition(),d.goTo(c,!1,"drag"),h.targetElement===a.target&&!0!==d.browser.isTouch&&(f(a.target).on("click.disable",function(a){a.stopImmediatePropagation();a.stopPropagation();a.preventDefault();f(a.target).off("click.disable")}),
a=f._data(a.target,"events").click,c=a.pop(),a.splice(0,0,c)));b("off")}var d=this,h={offsetX:0,offsetY:0,baseElWidth:0,relativePos:0,position:null,minSwipe:null,maxSwipe:null,sliding:null,dargging:null,targetElement:null};d.isCssFinish=!0;d.$elem.on(d.ev_types.start,".owl-wrapper",function(c){c=c.originalEvent||c||g.event;var e;if(3===c.which)return!1;if(!(d.itemsAmount<=d.options.items)){if(!1===d.isCssFinish&&!d.options.dragBeforeAnimFinish||!1===d.isCss3Finish&&!d.options.dragBeforeAnimFinish)return!1;
!1!==d.options.autoPlay&&g.clearInterval(d.autoPlayInterval);!0===d.browser.isTouch||d.$owlWrapper.hasClass("grabbing")||d.$owlWrapper.addClass("grabbing");d.newPosX=0;d.newRelativeX=0;f(this).css(d.removeTransition());e=f(this).position();h.relativePos=e.right;h.offsetX=a(c).x-e.right;h.offsetY=a(c).y-e.top;b("on");h.sliding=!1;h.targetElement=c.target||c.srcElement}})},getNewPosition:function(){var a=this.closestItem();a>this.maximumItem?a=this.currentItem=this.maximumItem:0<=this.newPosX&&(this.currentItem=
a=0);return a},closestItem:function(){var a=this,b=!0===a.options.scrollPerPage?a.pagesInArray:a.positionsInArray,e=a.newPosX,c=null;f.each(b,function(d,g){e-a.itemWidth/20>b[d+1]&&e-a.itemWidth/20<g&&"right"===a.moveDirection()?(c=g,a.currentItem=!0===a.options.scrollPerPage?f.inArray(c,a.positionsInArray):d):e+a.itemWidth/20<g&&e+a.itemWidth/20>(b[d+1]||b[d]-a.itemWidth)&&"left"===a.moveDirection()&&(!0===a.options.scrollPerPage?(c=b[d+1]||b[b.length-1],a.currentItem=f.inArray(c,a.positionsInArray)):
(c=b[d+1],a.currentItem=d+1))});return a.currentItem},moveDirection:function(){var a;0>this.newRelativeX?(a="left",this.playDirection="next"):(a="right",this.playDirection="prev");return a},customEvents:function(){var a=this;a.$elem.on("owl.next",function(){a.next()});a.$elem.on("owl.prev",function(){a.prev()});a.$elem.on("owl.play",function(b,e){a.options.autoPlay=e;a.play();a.hoverStatus="play"});a.$elem.on("owl.stop",function(){a.stop();a.hoverStatus="stop"});a.$elem.on("owl.goTo",function(b,e){a.goTo(e)});
a.$elem.on("owl.jumpTo",function(b,e){a.jumpTo(e)})},stopOnHover:function(){var a=this;!0===a.options.stopOnHover&&!0!==a.browser.isTouch&&!1!==a.options.autoPlay&&(a.$elem.on("mouseover",function(){a.stop()}),a.$elem.on("mouseout",function(){"stop"!==a.hoverStatus&&a.play()}))},lazyLoad:function(){var a,b,e,c,d;if(!1===this.options.lazyLoad)return!1;for(a=0;a<this.itemsAmount;a+=1)b=f(this.$owlItems[a]),"loaded"!==b.data("owl-loaded")&&(e=b.data("owl-item"),c=b.find(".lazyOwl"),"string"!==typeof c.data("src")?
b.data("owl-loaded","loaded"):(void 0===b.data("owl-loaded")&&(c.hide(),b.addClass("loading").data("owl-loaded","checked")),(d=!0===this.options.lazyFollow?e>=this.currentItem:!0)&&e<this.currentItem+this.options.items&&c.length&&this.lazyPreload(b,c)))},lazyPreload:function(a,b){function e(){a.data("owl-loaded","loaded").removeClass("loading");b.removeAttr("data-src");"fade"===d.options.lazyEffect?b.fadeIn(400):b.show();"function"===typeof d.options.afterLazyLoad&&d.options.afterLazyLoad.apply(this,
[d.$elem])}function c(){f+=1;d.completeImg(b.get(0))||!0===k?e():100>=f?g.setTimeout(c,100):e()}var d=this,f=0,k;"DIV"===b.prop("tagName")?(b.css("background-image","url("+b.data("src")+")"),k=!0):b[0].src=b.data("src");c()},autoHeight:function(){function a(){var a=f(e.$owlItems[e.currentItem]).height();e.wrapperOuter.css("height",a+"px");e.wrapperOuter.hasClass("autoHeight")||g.setTimeout(function(){e.wrapperOuter.addClass("autoHeight")},0)}function b(){d+=1;e.completeImg(c.get(0))?a():100>=d?g.setTimeout(b,
100):e.wrapperOuter.css("height","")}var e=this,c=f(e.$owlItems[e.currentItem]).find("img"),d;void 0!==c.get(0)?(d=0,b()):a()},completeImg:function(a){return!a.complete||"undefined"!==typeof a.naturalWidth&&0===a.naturalWidth?!1:!0},onVisibleItems:function(){var a;!0===this.options.addClassActive&&this.$owlItems.removeClass("active");this.visibleItems=[];for(a=this.currentItem;a<this.currentItem+this.options.items;a+=1)this.visibleItems.push(a),!0===this.options.addClassActive&&f(this.$owlItems[a]).addClass("active");
this.owl.visibleItems=this.visibleItems},transitionTypes:function(a){this.outClass="owl-"+a+"-out";this.inClass="owl-"+a+"-in"},singleItemTransition:function(){var a=this,b=a.outClass,e=a.inClass,c=a.$owlItems.eq(a.currentItem),d=a.$owlItems.eq(a.prevItem),f=Math.abs(a.positionsInArray[a.currentItem])+a.positionsInArray[a.prevItem],g=Math.abs(a.positionsInArray[a.currentItem])+a.itemWidth/2;a.isTransition=!0;a.$owlWrapper.addClass("owl-origin").css({"-webkit-transform-origin":g+"px","-moz-perspective-origin":g+
"px","perspective-origin":g+"px"});d.css({position:"relative",right:f+"px"}).addClass(b).on("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend",function(){a.endPrev=!0;d.off("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend");a.clearTransStyle(d,b)});c.addClass(e).on("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend",function(){a.endCurrent=!0;c.off("webkitAnimationEnd oAnimationEnd MSAnimationEnd animationend");a.clearTransStyle(c,e)})},clearTransStyle:function(a,
b){a.css({position:"",right:""}).removeClass(b);this.endPrev&&this.endCurrent&&(this.$owlWrapper.removeClass("owl-origin"),this.isTransition=this.endCurrent=this.endPrev=!1)},owlStatus:function(){this.owl={userOptions:this.userOptions,baseElement:this.$elem,userItems:this.$userItems,owlItems:this.$owlItems,currentItem:this.currentItem,prevItem:this.prevItem,visibleItems:this.visibleItems,isTouch:this.browser.isTouch,browser:this.browser,dragDirection:this.dragDirection}},clearEvents:function(){this.$elem.off(".owl owl mousedown.disableTextSelect");
f(k).off(".owl owl");f(g).off("resize",this.resizer)},unWrap:function(){0!==this.$elem.children().length&&(this.$owlWrapper.unwrap(),this.$userItems.unwrap().unwrap(),this.owlControls&&this.owlControls.remove());this.clearEvents();this.$elem.attr("style",this.$elem.data("owl-originalStyles")||"").attr("class",this.$elem.data("owl-originalClasses"))},destroy:function(){this.stop();g.clearInterval(this.checkVisible);this.unWrap();this.$elem.removeData()},reinit:function(a){a=f.extend({},this.userOptions,
a);this.unWrap();this.init(a,this.$elem)},addItem:function(a,b){var e;if(!a)return!1;if(0===this.$elem.children().length)return this.$elem.append(a),this.setVars(),!1;this.unWrap();e=void 0===b||-1===b?-1:b;e>=this.$userItems.length||-1===e?this.$userItems.eq(-1).after(a):this.$userItems.eq(e).before(a);this.setVars()},removeItem:function(a){if(0===this.$elem.children().length)return!1;a=void 0===a||-1===a?-1:a;this.unWrap();this.$userItems.eq(a).remove();this.setVars()}};f.fn.owlCarousel=function(a){return this.each(function(){if(!0===
f(this).data("owl-init"))return!1;f(this).data("owl-init",!0);var b=Object.create(l);b.init(a,this);f.data(this,"owlCarousel",b)})};f.fn.owlCarousel.options={items:5,itemsCustom:!1,itemsDesktop:[1199,4],itemsDesktopSmall:[979,3],itemsTablet:[768,2],itemsTabletSmall:!1,itemsMobile:[479,1],singleItem:!1,itemsScaleUp:!1,slideSpeed:200,paginationSpeed:800,rewindSpeed:1E3,autoPlay:!1,stopOnHover:!1,navigation:!1,navigationText:["prev","next"],rewindNav:!0,scrollPerPage:!1,pagination:!0,paginationNumbers:!1,
responsive:!0,responsiveRefreshRate:200,responsiveBaseWidth:g,baseClass:"owl-carousel",theme:"owl-theme",lazyLoad:!1,lazyFollow:!0,lazyEffect:"fade",autoHeight:!1,jsonPath:!1,jsonSuccess:!1,dragBeforeAnimFinish:!0,mouseDrag:!0,touchDrag:!0,addClassActive:!1,transitionStyle:!1,beforeUpdate:!1,afterUpdate:!1,beforeInit:!1,afterInit:!1,beforeMove:!1,afterMove:!1,afterAction:!1,startDragging:!1,afterLazyLoad:!1}})(jQuery,window,document);
//]]>
</script>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<b:if cond='data:blog.pageType!= &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;error_page&quot;'>
<style>
article {
    padding:0;
}
.post-header {
    padding:0;
}
@media only screen and (max-width :  768px) {
article {
    padding:10px;
}
  }
</style>
<!--Page Navigation Starts-->
<script type='text/javascript'>
  /*<![CDATA[*/
    var numPages=6;
    var firstText ='First';
    var lastText ='Last';
    var prevText ='« السابق';
    var nextText ='التالي »';
    var urlactivepage=location.href;
    var home_page="/";
  /*]]>*/
</script>
<script type='text/javascript'>
 /*<![CDATA[*/
  if (typeof firstText == "undefined") firstText = "First";
  if (typeof lastText == "undefined") lastText = "Last";
  var noPage;
  var currentPage;
  var currentPageNo;
  var postLabel;
  pagecurrentg();

  function looppagecurrentg(pageInfo) {
      var html = '';
      pageNumber = parseInt(numPages / 2);
      if (pageNumber == numPages - pageNumber) {
          numPages = pageNumber * 2 + 1
      }
      pageStart = currentPageNo - pageNumber;
      if (pageStart < 1) pageStart = 1;
      lastPageNo = parseInt(pageInfo / perPage) + 1;
      if (lastPageNo - 1 == pageInfo / perPage) lastPageNo = lastPageNo - 1;
      pageEnd = pageStart + numPages - 1;
      if (pageEnd > lastPageNo) pageEnd = lastPageNo;
      html += "<span class='showpageOf'>صفحة " + currentPageNo + ' من ' + lastPageNo + "</span>";
      var prevNumber = parseInt(currentPageNo) - 1;

      //Iccsi was here, doing magic      
      if (currentPageNo > 1) {
          if (currentPage == "page") {
              html += '<span class="showpage firstpage"><a href="' + home_page + '">' + firstText + '</a></span>'
          } else {
              html += '<span class="displaypageNum firstpage"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">' + firstText + '</a></span>'
          }
      }

      if (currentPageNo > 2) {
          if (currentPageNo == 3) {
              if (currentPage == "page") {
                  html += '<span class="showpage"><a href="' + home_page + '">' + prevText + '</a></span>'
              } else {
                  html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">' + prevText + '</a></span>'
              }
          } else {
              if (currentPage == "page") {
                  html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + prevNumber + ');return false">' + prevText + '</a></span>'
              } else {
                  html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + prevNumber + ');return false">' + prevText + '</a></span>'
              }
          }
      }
      if (pageStart > 1) {
          if (currentPage == "page") {
              html += '<span class="displaypageNum"><a href="' + home_page + '">1</a></span>'
          } else {
              html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">1</a></span>'
          }
      }
      if (pageStart > 2) {
          html += ' ... '
      }
      for (var jj = pageStart; jj <= pageEnd; jj++) {
          if (currentPageNo == jj) {
              html += '<span class="pagecurrent">' + jj + '</span>'
          } else if (jj == 1) {
              if (currentPage == "page") {
                  html += '<span class="displaypageNum"><a href="' + home_page + '">1</a></span>'
              } else {
                  html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">1</a></span>'
              }
          } else {
              if (currentPage == "page") {
                  html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + jj + ');return false">' + jj + '</a></span>'
              } else {
                  html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + jj + ');return false">' + jj + '</a></span>'
              }
          }
      }
      if (pageEnd < lastPageNo - 1) {
          html += '...'
      }
      if (pageEnd < lastPageNo) {
          if (currentPage == "page") {
              html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + lastPageNo + ');return false">' + lastPageNo + '</a></span>'
          } else {
              html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + lastPageNo + ');return false">' + lastPageNo + '</a></span>'
          }
      }


      var nextnumber = parseInt(currentPageNo) + 1;
      if (currentPageNo < (lastPageNo - 1)) {
          if (currentPage == "page") {
              html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + nextnumber + ');return false">' + nextText + '</a></span>'
          } else {
              html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + nextnumber + ');return false">' + nextText + '</a></span>'
          }
      }

      if (currentPageNo < lastPageNo) {
          //Iccsi was here, doing magic
          if (currentPage == "page") {
              html += '<span class="displaypageNum lastpage"><a href="#" onclick="redirectpage(' + lastPageNo + ');return false">' + lastText + '</a></span>'
          } else {
              html += '<span class="displaypageNum lastpage"><a href="#" onclick="redirectlabel(' + lastPageNo + ');return false">' + lastText + '</a></span>'
          }
      }

      var pageArea = document.getElementsByName("pageArea");
      var blogPager = document.getElementById("blog-pager");
      for (var p = 0; p < pageArea.length; p++) {
          pageArea[p].innerHTML = html
      }
      if (pageArea && pageArea.length > 0) {
          html = ''
      }
      if (blogPager) {
          blogPager.innerHTML = html
      }
  }

  function totalcountdata(root) {
      var feed = root.feed;
      var totaldata = parseInt(feed.openSearch$totalResults.$t, 10);
      looppagecurrentg(totaldata)
  }

  function pagecurrentg() {
      var thisUrl = urlactivepage;
      if (thisUrl.indexOf("/search/label/") != -1) {
          if (thisUrl.indexOf("?updated-max") != -1) {
              postLabel = thisUrl.substring(thisUrl.indexOf("/search/label/") + 14, thisUrl.indexOf("?updated-max"))
          } else {
              postLabel = thisUrl.substring(thisUrl.indexOf("/search/label/") + 14, thisUrl.indexOf("?&max"))
          }
      }
      if (thisUrl.indexOf("?q=") == -1 && thisUrl.indexOf(".html") == -1) {
          if (thisUrl.indexOf("/search/label/") == -1) {
              currentPage = "page";
              if (urlactivepage.indexOf("#PageNo=") != -1) {
                  currentPageNo = urlactivepage.substring(urlactivepage.indexOf("#PageNo=") + 8, urlactivepage.length)
              } else {
                  currentPageNo = 1
              }
              document.write("<script src=\"" + home_page + "feeds/posts/summary?max-results=1&alt=json-in-script&callback=totalcountdata\"><\/script>")
          } else {
              currentPage = "label";
              if (thisUrl.indexOf("&max-results=") == -1) {
                  perPage = 20
              }
              if (urlactivepage.indexOf("#PageNo=") != -1) {
                  currentPageNo = urlactivepage.substring(urlactivepage.indexOf("#PageNo=") + 8, urlactivepage.length)
              } else {
                  currentPageNo = 1
              }
              document.write('<script src="' + home_page + 'feeds/posts/summary/-/' + postLabel + '?alt=json-in-script&callback=totalcountdata&max-results=1" ><\/script>')
          }
      }
  }

  function redirectpage(numberpage) {
      jsonstart = (numberpage - 1) * perPage;
      noPage = numberpage;
      var nameBody = document.getElementsByTagName('head')[0];
      var newInclude = document.createElement('script');
      newInclude.type = 'text/javascript';
      newInclude.setAttribute("src", home_page + "feeds/posts/summary?start-index=" + jsonstart + "&max-results=1&alt=json-in-script&callback=finddatepost");
      nameBody.appendChild(newInclude)
  }

  function redirectlabel(numberpage) {
      jsonstart = (numberpage - 1) * perPage;
      noPage = numberpage;
      var nameBody = document.getElementsByTagName('head')[0];
      var newInclude = document.createElement('script');
      newInclude.type = 'text/javascript';
      newInclude.setAttribute("src", home_page + "feeds/posts/summary/-/" + postLabel + "?start-index=" + jsonstart + "&max-results=1&alt=json-in-script&callback=finddatepost");
      nameBody.appendChild(newInclude)
  }

  function finddatepost(root) {
          post = root.feed.entry[0];
          var timestamp1 = post.published.$t.substring(0, 19) + post.published.$t.substring(23, 29);
          var timestamp = encodeURIComponent(timestamp1);
          if (currentPage == "page") {
              var pAddress = "/search?updated-max=" + timestamp + "&max-results=" + perPage + "#PageNo=" + noPage
          } else {
              var pAddress = "/search/label/" + postLabel + "?updated-max=" + timestamp + "&max-results=" + perPage + "#PageNo=" + noPage
          }
          location.href = pAddress
      }
      /*]]>*/
</script>
<!--Page Navigation Ends -->
</b:if>
</b:if>
</b:if>
<!--Page Navigation Ends -->
<script>
//<![CDATA[
(function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0];
  if (d.getElementById(id)) return;
  js = d.createElement(s); js.id = id;
  js.src = "//connect.facebook.net/en_US/sdk.js#xfbml=1&version=v2.5";
  fjs.parentNode.insertBefore(js, fjs);
}(document, 'script', 'facebook-jssdk'));
//]]>
</script>

<script>
$(function(){$(&quot;.element&quot;).typed({
strings: [&quot; مرحبا بك في موقع ProfNabil &quot;, &quot; موقعنا يوفر لك العديد من الدروس في جميع الاطوار &quot;, &quot;نتمنى أن تجد الدروس الذي تبحث عنها&quot;, &quot;&quot;, &quot;إن لم تجد ما تريد يمكنك مراسلتنا لكي نجلبه لك&quot;],typeSpeed:50,loop: true,});});
/*<![CDATA[*/
! function(b){var a = function(d,c){this.el = b(d);this.options = b.extend({}
,b.fn.typed.defaults,c);this.isInput = this.el.is("input");this.attr = this.options.attr;this.showCursor = this.isInput ? false:this.options.showCursor;this.elContent = this.attr ? this.el.attr(this.attr):this.el.text();this.contentType = this.options.contentType;this.typeSpeed = this.options.typeSpeed;this.startDelay = this.options.startDelay;this.backSpeed = this.options.backSpeed;this.backDelay = this.options.backDelay;this.strings = this.options.strings;this.strPos = 0;this.arrayPos = 0;this.stopNum = 0;this.loop = this.options.loop;this.loopCount = this.options.loopCount;this.curLoop = 0;this.stop = false;this.cursorChar = this.options.cursorChar;this.shuffle = this.options.shuffle;this.sequence = [];this.build()}
;a.prototype ={constructor:a,init:function(){var c = this;c.timeout = setTimeout(function(){for (var d = 0;d < c.strings.length;++d){c.sequence[d] = d}
if (c.shuffle){c.sequence = c.shuffleArray(c.sequence)}
c.typewrite(c.strings[c.sequence[c.arrayPos]],c.strPos)}
,c.startDelay)}
,build:function(){if (this.showCursor === true){this.cursor = b('<span class="typed-cursor">' + this.cursorChar + "</span>");this.el.after(this.cursor)}
this.init()}
,typewrite:function(d,e){if (this.stop === true){return}
var f = Math.round(Math.random() * (100 - 30)) + this.typeSpeed;var c = this;c.timeout = setTimeout(function(){var i = 0;var l = d.substr(e);if (l.charAt(0) === "^"){var k = 1;if (/^\^\d+/.test(l)){l = /\d+/.exec(l)[0];k += l.length;i = parseInt(l)}
d = d.substring(0,e) + d.substring(e + k)}
if (c.contentType === "html"){var h = d.substr(e).charAt(0);if (h === "<" || h === "&"){var g = "";var j = "";if (h === "<"){j = ">"}
else{j = ";"}
while (d.substr(e).charAt(0) !== j){g += d.substr(e).charAt(0);e++}
e++;g += j}}
c.timeout = setTimeout(function(){if (e === d.length){c.options.onStringTyped(c.arrayPos);if (c.arrayPos === c.strings.length - 1){c.options.callback();c.curLoop++;if (c.loop === false || c.curLoop === c.loopCount){return}}
c.timeout = setTimeout(function(){c.backspace(d,e)}
,c.backDelay)}
else{if (e === 0){c.options.preStringTyped(c.arrayPos)}
var m = d.substr(0,e + 1);if (c.attr){c.el.attr(c.attr,m)}
else{if (c.isInput){c.el.val(m)}
else{if (c.contentType === "html"){c.el.html(m)}
else{c.el.text(m)}}}
e++;c.typewrite(d,e)}}
,i)}
,f)}
,backspace:function(d,e){if (this.stop === true){return}
var f = Math.round(Math.random() * (100 - 30)) + this.backSpeed;var c = this;c.timeout = setTimeout(function(){if (c.contentType === "html"){if (d.substr(e).charAt(0) === ">"){var g = "";while (d.substr(e).charAt(0) !== "<"){g -= d.substr(e).charAt(0);e--}
e--;g += "<"}}
var h = d.substr(0,e);if (c.attr){c.el.attr(c.attr,h)}
else{if (c.isInput){c.el.val(h)}
else{if (c.contentType === "html"){c.el.html(h)}
else{c.el.text(h)}}}
if (e > c.stopNum){e--;c.backspace(d,e)}
else{if (e <= c.stopNum){c.arrayPos++;if (c.arrayPos === c.strings.length){c.arrayPos = 0;if (c.shuffle){c.sequence = c.shuffleArray(c.sequence)}
c.init()}
else{c.typewrite(c.strings[c.sequence[c.arrayPos]],e)}}}}
,f)}
,shuffleArray:function(f){var c,e,d = f.length;if (d){while (--d){e = Math.floor(Math.random() * (d + 1));c = f[e];f[e] = f[d];f[d] = c}}
return f}
,reset:function(){var c = this;clearInterval(c.timeout);var d = this.el.attr("id");this.el.after('<span id="' + d + '"/>');this.el.remove();if (typeof this.cursor !== "undefined"){this.cursor.remove()}
c.options.resetCallback()}}
;b.fn.typed = function(c){return this.each(function(){var f = b(this),e = f.data("typed"),d = typeof c == "object" && c;if (!e){f.data("typed",(e = new a(this,d)))}
if (typeof c == "string"){e[c]()}}
)}
;b.fn.typed.defaults ={strings:["These are the default values...","You know what you should do?","Use your own!","Have a great day!"],typeSpeed:0,startDelay:0,backSpeed:0,shuffle:false,backDelay:500,loop:false,loopCount:false,showCursor:true,cursorChar:"|",attr:null,contentType:"html",callback:function(){}
,preStringTyped:function(){}
,onStringTyped:function(){}
,resetCallback:function(){}}}
(window.jQuery);
/*]]>*/
</script>

  </body> 
</html>
