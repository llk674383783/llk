<html>
<H1> JSON教程</ H1>
<P1> JSON是使用Javascript对象的一种，</ BR>也是制作扩展中心必不可少的一部分，本教程主要针对扩展中心的制作</ BR> </ BR> JSON的语法格式简单，要求比较不严格，本教程将会采用图文类比的方法，使得内容易于理解</ P1>

<p2> json文本一般有五种格式：</ br>字符串“a”：“b”</ br>数值“a”：1 </ br>布尔值“a”：true </ br>数组“a”：[1,2] </ br> </ br>先来看一段例子</ br> {“教程”：{“内容”：“json”，“作者”：“炖菜”}} </ BR>这就是一段JSON文本。其中 “教程” 是父标签， “内容” 和 “作者” 都是子标签，用图片表示的形式如下</ P2>
</ br> <img src =“duncai.png”> </ br>
<P3>所以从某种层面上来说，JSON可以理解为有一个最大的文件夹，包着里面的一个个小文件夹，小文件夹同样也可以放更小的文件夹在里面</ BR>而对于“a”：1或者“a”：真这种规定了具体的值的标签，可以类比为文件，存放在文件夹中。
但是对于一段比较长的JSON文本，我们通常需要换行和进退位来使其更美观，例如我们可以把以上例子换成</ BR>
{</ br>“教程”：{</ br>“内容”：“json”，</ br>“作者”：“炖菜”</ br>} </ br>} </ br>值得注意的是，同一级标签之前要用英文逗号隔开，否则会使语法出错</ P3>
<H2>小节训练</ H2>
<input type =“text”id =“num”value =“这里填写答案”/>
	<p>请补全以下例子中方框内缺失的部分</ br> {“中国”：{“语言”：“中文”□“所在大洲”：“亚洲”}} </ p>
	<p id =“demo”> </ p>
<button onclick =“myFunction（）”>验证答案</ button>
<SCRIPT>
function myFunction（）{
	var right =“正确”;
	var wrong =“错误，应填写英文逗号”;
	var a = document.getElementById（“num”）。value;
	if（a ==“，”）{
		document.getElementById（“demo”）。innerHTML = right;
	}
    其他{
        的document.getElementById（ “演示”）的innerHTML =错误。
    }
}
</ SCRIPT>
</ BR> </ BR>
<p4> {“首都”：{“中国首都”：“北京”，“俄国首都”：“莫斯科”，“英国首都”：“伦敦”}} </ br>在以上例子中，“首都”的子标签有几个？</ P4> </ BR>
<button onclick =“function1（）”> 6 </ button>
<button onclick =“function1（）”> 1 </ button>
<button onclick =“function2（）”> 3 </ button>
<button onclick =“function1（）”> 4 </ button> </ br>
<p5 id =“nmsl”> </ p5>
<SCRIPT>
	function function1（）{
		var a1 =“错误”;
		的document.getElementById（ “NMSL”）的innerHTML = A1。
	}
	function function2（）{
		var a2 =“正确”;
		的document.getElementById（ “NMSL”）的innerHTML = A2。
	}
</ SCRIPT>
</html>
