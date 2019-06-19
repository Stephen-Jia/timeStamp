# timeStamp
htm中使用时间戳

把文件 datepicker（时间戳的一些js） 直接导入到项目中

直接使用
<title>时间戳</title>
<body>
	<div>
		时间<input type = "text" onFocus="WdatePicker({dateFmt:'yyyy-MM-dd',minDate:'%y-%M-{%d}'})"/>
	</div>
	<script type="text/javascript" src="../static/js/datepicker/WdatePicker.js"></script>
</body>
