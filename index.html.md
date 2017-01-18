# index.html

	<!DOCTYPE html>
	<html lang="ko-KR">
	 <head>
	   <meta charset="utf-8">
	   <title>js 기초 익히기</title>
	   <script type="text/javascript">
		 console.log("write in head");
	  </script>
	 </head>
	 <body>
	   <script type="text/javascript">console.log("write in body");</script>
	   <script type="text/javascript" src="./js/js_step_01.js"> </script>
	 </body>
	 </html>


# js_step_01.js

// js_step_01.js

console.log("write in outFile");
document.write("<h1>문서의 제목</h1>");
document.write('<p>-1-다양한 내용을 작성해서확인하세요.</p>');
document.write('<p>-2-다양한 내용을 작성해서확인하세요.</p>');
document.write('<p class ="colorSelect">-3-다양한 내용을 작성해서확인하세요.</p>');
document.write('<p id="mySel">-4-다양한 내용을 작성해서확인하세요.</p>');
document.write( ' <a href="http://naver.com">네이버로 이동</a>');
var h1 = document.getElementsByTagName( 'h1' )[0];
var p1 =  document.getElementsByTagName ( 'p' )[0];
var p2 =  document.getElementsByTagName ( 'p' )[1];
var sel = document.getElementsByClassName ( 'colorSelect' ) [0];
var my = document.getElementById ('mySel') ;
h1.style.color = "#fa0";
h1.style.backgroundColor="0a0";
p1.style.color="#fcf";
p1.style.fontSize=50 + 'px' ;
p2.style.color="#f0f";
sel.style.color="#05f" ;
mySel.style.fontWeight ="bold" ;
mySel.style.fontSize ="5em" ;



     h1.addEventListener ( 'click' , function (){
     h1.style.color = '#0fc' ;
       h1.style.backgroundColor = '#dfdfdf' ;
       h1.style.fontSize = '3em' ;
       });
