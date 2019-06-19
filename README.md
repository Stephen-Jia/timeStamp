# timeStamp
把文件 datepicker（时间戳的一些js） 直接导入到项目中

直接使用
<!DOCTYPE html>
<html>
	<head>
		<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
		<title>时间戳</title>
	</head>
	
	<body>
		<div>
			时间<input type = "text" onFocus="WdatePicker({dateFmt:'yyyy-MM-dd',minDate:'%y-%M-{%d}'})"/>
		</div>
		<script type="text/javascript" src="../static/js/datepicker/WdatePicker.js"></script>
	</body>
</html>

