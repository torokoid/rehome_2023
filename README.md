# rehome_2023

<html>
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #ffffff;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff; blinking;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{

-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20210704_Utsunomiya_swim/20210704_002.JPG) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}


</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>



<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
より見やすくご覧頂けます。
</p>

<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="20230320.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~hada</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="alternate">!!! 2023/03/04 リフォーム見積もり !!!</marquee></span></h1>	




<h1>各社見積一覧</h1>
<a href="20230320_000.png" data-lightbox="abc"><img src="20230320_000.png" alt="サンプル画像" width="900" /></a>
<p>※アルミサイディングは、さらに広告掲載料として約55万円の特別値引き提示</p>

<br><br>

<a href="20230320_001.JPG" data-lightbox="abc"><img src="20230320_001.JPG" alt="サンプル画像" width="450" /></a>
<a href="20230320_002.JPG" data-lightbox="abc"><img src="20230320_002.JPG" alt="サンプル画像" width="450" /></a>


<br><br><br>
	
<p>東方ハウジング、鈴木さん</p>
<iframe width="700" height="1000" src="https://torokoid.github.io/rehome_2023/20230320_002.pdf"></iframe>
	

<p>住居時間、竹内さん</p>
<iframe width="700" height="1000" src="https://torokoid.github.io/rehome_2023/20230320_001.pdf"></iframe>

<iframe width="700" height="1000" src="https://torokoid.github.io/rehome_2023/20230320_003.pdf"></iframe>

<iframe width="700" height="1000" src="https://torokoid.github.io/rehome_2023/20230320_004.pdf"></iframe>

	<br><br><br><br><br><br><br><br><br><br><br><br>
	
<p>同じもの、表示サイズ違い</p><br><br>
<p>東方ハウジング、鈴木さん</p>
<iframe src="https://torokoid.github.io/rehome_2023/20230320_002.pdf" width="80%" height="300%"></iframe><br>
<p>住居時間、竹内木さん</p>
<iframe src="https://torokoid.github.io/rehome_2023/20230320_001.pdf" width="80%" height="300%"></iframe><br>
<iframe src="https://torokoid.github.io/rehome_2023/20230320_003.pdf" width="80%" height="300%"></iframe><br>
<iframe src="https://torokoid.github.io/rehome_2023/20230320_004.pdf" width="80%" height="300%"></iframe><br>
	

<!--本体はここまで-->


<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<span class="white">Copyright 2023/103/20 S.Hada、背景は自宅近くの紫陽花</span>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>



</body>

</html>
