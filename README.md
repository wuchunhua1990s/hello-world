# 九宫格
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>九宫格</title>
	<style>
       body{
       	margin:0;padding:0;color:#fff;
       	display: block;
       }

       .container{width:100%;margin: 0 auto;
         border-width:1px;
         background-color:#ffa600;

       }

       .left{
       	width:30%;margin:2.5% 2.5% 0 2.5%;height:0;padding-bottom:30%;background: #ffa600;float:left;border-radius:10px;
       }
        
       .middle{
       	width:30%;margin-top:2.5%;height:0;padding-bottom:30%;background: #ffa600;float:left;border-radius:10px;
       } 
       .right{
       	width:30%;margin:2.5% 2.5% 0 2.5%;height:0;padding-bottom:30%;background: #ffa600;float:right;border-radius:10px;
       }

      
	</style>
</head>
<body>
	<div class="container">
        <div class="left"></div>
        <div class="middle"></div>
        <div class="right"></div>
         <div class="left"></div>
        <div class="middle"></div>
        <div class="right"></div>
        <div class="left"></div>
        <div class="middle"></div>
        <div class="right"></div>
       
	</div>
</body>
</html>
