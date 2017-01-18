|         |                                          |         |                                          |
| ------- | ---------------------------------------- | ------- | ---------------------------------------- |
| </head> |                                          | </head> |                                          |
|         | <body>                                   |         | <body>                                   |
|         | <script type="text/javascript">console.log("write in body");</script> |         | <script type="text/javascript">console.log("write in body");</script> |
|         |                                          |         | +  <!-- (주석)                             |
|         | <script type="text/javascript" src="./js/js_step_01.js"></script> |         | <script type="text/javascript" src="./js/js_step_01.js"></script> |
|         |                                          |         | +  --> (주석)                              |
|         | </body>                                  |         | </body>                                  |
|         | </html>                                  |         | </html>                                  |
|         |                                          |         |                                          |
|         |                                          |         |                                          |



| @@ -1,4 +1,6 @@ |                                          |      |                                          |
| --------------- | ---------------------------------------- | ---- | ---------------------------------------- |
|                 | // js_step_01.js                         |      | // js_step_01.js                         |
|                 |                                          |      | +/* */ (주석)                              |
|                 |                                          |      |                                          |
|                 |                                          |      |                                          |
|                 | console.log("write in outFile");         |      | console.log("write in outFile");         |
|                 | document.write("<h1>문서의 제목</h1>");       |      | document.write("<h1>문서의 제목</h1>");       |
|                 | @@ -23,6 +25,25 @@ sel.style.color="#05f"; |      |                                          |
|                 | mySel.style.fontWeight ="bold";          |      | mySel.style.fontWeight ="bold";          |
|                 | mySel.style.fontSize ="5em";             |      | mySel.style.fontSize ="5em";             |
|                 |                                          |      |                                          |
|                 |                                          |      | +h1.addEventListener( 'click', function(){ |
|                 |                                          |      | +	h1.style.color = '#0fc';               |
|                 |                                          |      | +	h1.style.backgroundColor = '#dfdfdf';  |
|                 |                                          |      | +	h1.style.fontSize = '3em';             |
|                 |                                          |      | +});                                     |