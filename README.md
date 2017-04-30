<html>
<head>
	<meta charset="utf-8" />
  	<title> BOM</title>
	<script type = "text/javascript">
		function showPic(i){	
			var oImg = document.images[0];
			var link = document.links[i];
			oImg.src = link.href;
		}
	</script>
	<style type="text/css">
		h1{
			padding-bottom:0px;
		}
		ul{
			margin-bottom:3px;
		}
		li{
			display:inline;
		}
		h1{
			text-indent:3em;
		}
		ul{
			text-indent:3em;
		}
	</style>
</head>
<body>
  	<h1>图片链接</h1>
  	<ul>
		<li> <a href="http://img9.3lian.com/c1/vector2/18/41/29.jpg" title="jinyu" onclick = "showPic(0);return false;">金鱼</a> </li>
		<li> <a href="http://dimg04.c-ctrip.com/images/300g080000003c0l5EEB1.jpg" title="caoyuan" onclick = "showPic(1);return false;">草原</a> </li>
		<li> <a href="http://img01.tooopen.com/Downs/images/2009/10/2/sy_20091002215630862380.jpg" title="hehua" onclick = "showPic(2);return false;">荷花</a> </li>
		<li> <a href="http://pic.zhutou.com/html/UploadPic/2010-7/20107824249751.jpg" title="sinlin" onclick = "showPic(3);return false;">森林</a> </li>
  	</ul>
	<img id="placeholder" src="http://pic15.nipic.com/20110724/7995528_114659882000_2.jpg" width="300px" height="200px" alt="图片占位符" />
</body>
</html>
	

