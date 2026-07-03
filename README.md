‹IDOCTYPE html>
‹html lang="zh-Hant">
<head>
‹meta charset="UTF-8">
（title>GA4 教學示範網站</ti le〉
《I-- 將下面的6-X000000000換成你的 GA4 追躍碼--
‹script async src="https://ww.googletagmanager.com/gtag/jsid=G-X00000xx/scripts
(script›
window.datalayer = window.datalayer || [l;
function gtag() (dataLayer.push(arguments);)
gtag('js',new Date()):
gtag("config',"G-XXXXXXXX);
</script>
</head>
‹body>
<h1>歡迎來到GA4 示範網站</h1>
《p>這裡是教學用網站，支援 GA4 數據追躍。《/p>
‹form id="myform">
‹label›&7: cinput name="name" />/label>
‹button type="submit"›#5x</button›
</form›
<button id="testButton”>按我一下e/button》
‹script>
document. getElementById('myForm'), addEventListener(' submit', function(e){
e.preventDefault();
gtag('event","form_submit", (form_id: "myForm"));
alert（"G44 表單提交事件已發送：）；
)):
document. getElement&yId('testButton'). addEventListener'click", function()

  gtag(" event', "button_click", (button_id: "testButton'));
alert（'GA4 按鈕點擊事件已發送”）：
