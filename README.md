<html lang="zh-cmn">
<head>
<meta http-equiv="content-type" content="text/html" charset="utf-8";/>
<meta http-equiv="X-UA-Compatible" content="IE-edge">
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
<title>bmi计算器,bmi免费计算,bmi免费计算器,bmi测试,bmi测试器,bmi免费测试</title>
<meta name="keywords" content="bmi计算器,bmi免费计算器,bmi测试,bmi测试器,bmi免费测试"/>
<meta name="description" content="bmi计算器,bmi免费计算器,bmi测试,bmi测试器,bmi免费测试【官网】"/>
<head>
<style>
 * {
  padding: 0;
  margin: 0;
  font-family: "微软雅黑";
  }	
header > h1 {
	margin: 1%;
	font-size: 1.2rem;
}	
header > p {
	margin: 1% 2%;
	padding: 8px 0;
	font-size: .8rem;
}	
header>.lang {
	position: absolute;
	top: 2%; right: 5%;
	font-size: .8rem;
}	
.hr1 {
	margin: 3% 0px 3%;
	padding-top: 10px;
}
main > p {
	margin: 2%;
	font-size: .7rem;
}
main > .input1 {
	padding-top: 5px;
	text-align: center;
}
input {
	color: red;
}
footer {
	text-align: center;
	font-size: .8rem;
	color: #525252;
}

</style>
</head>


<body>
<header>
  <img src="/bmi1/top.png" style="width: 100%;">
  <div class="lang">  
  语言：<a href="" onclick="javascript:alert('您的网络存在问题')">Engilsh</a> | <a href="">简体中文</a> | <a href="" onclick="javascript:alert('您的网络存在问题')">繁体中文</a>    
  </div>
  <div class="c" style="clear: both;"></div>
    <h1>免费在线 BMI 计算器</h1>
    <p>身体质量指数 (Body Mass Index, 简称BMI), 亦称克托莱指数, 是目前国际上常用的衡量人体胖瘦程度以及是否健康的一个标准。BMI 值超标，意味着你需要减肥了。</p>	
</header>	

<main>	
  <img src="/bmi1/bmi.png"  style="margin-left:5%; width: 90%;";>
  <p>BMI主要用于统计分析。肥胖程度的判断不能采用体重的绝对值，它天然与身高有关。因此，BMI 通过人体体重和身高两个数值获得相对客观的参数，并用这个参数所处范围衡量身体质量。</p>
  <div class="input1">
    <input type="button" value="点击计算BMI" onclick="myfunction()">
  </div>
</main>
  
  <div class="hr1">
  <hr style="height: 1px; border: none; border-top: 1px dotted #185598; width: 90%; margin-left: 5%;">
  </div>

<footer>
版权所有 © <a href="mailto: rainsee78@163.com">dawn.</a>保留所有权利
<br/>友情链接：<a href="mailto: rainsee78@163.com">唐</a>
<br/>
<br/>
</footer>
</body>
<script>
function myfunction(){	
'use strict'
alert("欢迎使用 “唐雨晨” 的BMI免费测试器")
var height = parseFloat(prompt('请输入身高(cm):'));
var weight = parseFloat(prompt('请输入体重(kg):'));

var bmi = weight / Math.pow(height,2)*10000
var i;
if (bmi < 18.5){
    i=' 偏瘦。';
}
else if(bmi < 24){
	i=' 正常。';
}
else if(bmi < 28){
	i=' 偏重。';
}
else if(bmi < 32){
	i=' 肥胖。';
}
else if(bmi >= 32){
	i=' 严重肥胖。';
}
else{
	i=' undefined。'
}
alert('亲，你的BMI为 '+ bmi +'，属于'+ i  + '\n（友情提示：科学减肥只需"管住嘴，迈开腿！"）');
}
</script>
</html>
