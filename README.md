<html>
<meta name="viewport" content="width=device-width,initial-scale=1"/>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>
            报名
        </title>
<style type="text/css">
div{text-align:center;}
        h1{font-family:"华文行楷";;font-size:40px;color:green}
        p{font-size:14px;color:red}
        h2{font-size:12px;color:grey}
</style>
<style type="text/css">
form{text-align:center;}
</style>
</head>
<body>
<div>
	<h1>
                清泽心雨招新报名入口
	</h1>
	<p class="category">
                一个简单的报名入口,别想在这里了解什么。
	</p>
</div>
<div class="col-sm-5 col-sm-offset-1">
	<div class="form-group solid-80">
		<label>姓名</label><input type="text" class="form-control" name="name" autocomplete="name" placeholder="姓名" value="" required="" aria-required="true">
	</div>
</div>
<div class="col-sm-5">
	<div class="form-group solid-80">
		<label>专业</label><input type="text" class="form-control" name="major" autocomplete="major" placeholder="专业" value="" required="" aria-required="true">
	</div>
</div>
<div>
	<form action="save.php" method="post">
		<label>性别:</label><label>男</label><input type="radio" value="1" name="gender"><label>女</label><input type="radio" value="2" name="gender">
	</form>
</div>
<div class="col-sm-5 col-sm-offset-1">
	<div class="form-group solid-80">
		<label>电话</label><input type="number" class="form-control" name="phone" autocomplete="phone" placeholder="电话号码" value="" required="" aria-required="true">
	</div>
</div>
<div class="col-sm-5">
	<div class="form-group solid-80">
		<label>邮箱</label><input type="email" class="form-control" name="email" autocomplete="email" placeholder="邮箱" value="" required="" aria-required="true">
	</div>
</div>
<div class="row">
	<div class="col-sm-5 col-sm-offset-1">
		<div class="form-group solid-80">
			<label>意向部门</label>
			<select class="form-control" name="aim" datatype="aim" required="" aria-required="true">
				<option disabled selected value="0">
                            请选择部门
				</option>
				<option value="1">
                            综合办公室
				</option>
				<option value="2">
                            公关策划部
				</option>
				<option value="3">
                            网络安全部
				</option>
				<option value="4">
                            视觉设计部
				</option>
				<option value="5">
                            技术开发部
				</option>
				<option value="6">
                            综合媒体集团
				</option>
				<option value="7">
                            新闻集团
				</option>
				<option value="8">
                            视频集团
				</option>
				<option value="9">
                            网络安全部有蓝之青
				</option>
				<option value="10">
                            视频集团有微效坊
				</option>
				<option value="11">
                            影像、电视台（option）
				</option>
				<option value="12">
                            技术开发部有ued
				</option>
				<option value="13">
                            视觉设计部有卡乐坊
				</option>
			</select>
		</div>
		<label>理由</label>
		<textarea class="form-control" name="reasion2" placeholder="请在这里诉说你的故事">
		</textarea>
	</div>
	<div>
		<h2 class="info-text">
                请认真输入，不然我们就找不到你了哦！
		</h2>
	</div>
</div>
<div class="pull-right">
	<input type="button" class="btn btn-finish btn-fill btn-success btn-wd" name="finish" value="提交" id="poster" style="display: inline-block;">
</div>
<style type="text/css">
div{
    width:500px;
    height:px;
	float:left
}
</style>
</body>
</html>
