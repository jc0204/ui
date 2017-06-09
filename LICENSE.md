<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>无标题文档</title>
</head>

<body>

<script type="text/javascript">
function fun(){
	 var month= window.prompt("请输入一个整数表示月份，（1-12）：");
  switch(month){
	  case "1":
	      document.write("31天");
		  break;
	  case "2":
	  		var dt=new Date();
			var year=dt.getFullYear();
			if(year%4==0&&year%100!=0||year%400==0){
				document.write("闰年：29天");
				}else{
				document.write("平年：28天");	
					}
		  break;
	  case "3":
	      document.write("31天");
		  break;
	 case "4":
	      document.write("30天");
		  break;
	  case "5":
	      document.write("31天");
		  break;
	 case "6":
	      document.write("30天");
		  break;
	 case "7":
	      document.write("31天");
		  break;
	case "8":
	      document.write("31天");
		  break;
	  case "9":
	      document.write("30天");
		  break;
	  case "10":
	      document.write("31天");
		  break;
	 case "11":
	      document.write("30天");
		  break;
	  case "12":
	      document.write("31天");
		  break;
	  default:
	    document.write("输入错误，请输入1-12的整数.");
		  break;
	     
  }
}
fun();
</script>
<script type="text/javascript">
function fun(){
	 var month= window.prompt("请输入一个整数表示月份，（1-12）：");
  switch(month){
	  case "1":
	  case "3":
	  case "5":
	  case "7":
	  case "8":
	  case "10":
	  case "12":
	      document.write("31天");
		  break;
	  case "2":
	  		var dt=new Date();
			var year=dt.getFullYear();
			if(year%4==0&&year%100!=0||year%400==0){
				document.write("闰年：29天");
				}else{
				document.write("平年：28天");	
					}
		  break;
	  
	 case "4":
	 case "6":
	 case "9":
	 case "11":
	      document.write("30天");
		  break;
	
	  default:
	    document.write("输入错误，请输入1-12的整数.");
		  break;
	     
  }
}
fun();
</script>

<!--数组方法：-->

<script>
     var m = window.prompt("请输入一个整数（1-12）");
	var ms=new Array("31","28","31","30","31","30","31","31","30","31","30","31");
	document.write(ms[m-1]);
</script>

</body>
</html>
