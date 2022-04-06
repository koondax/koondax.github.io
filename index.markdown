---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: homeCustom
---
 <title>Koondi Mitra</title>


<script type="text/javascript">
<!--
var dp0=new Image()
dp0.src="/DP/dp0.jpg"
var dp1=new Image()
dp1.src="/DP/dp1.jpg"
var dp2=new Image()
dp2.src="/DP/dp2.jpg"
//-->
</script>


<div style="
  width: 200px;
  height: 600px
  background: rgba(0, 0, 0, 0.4);
  text-align: center;
  margin: auto;
  margin-top: 2%;
  color: white;
  font-family: 'Century Gothic',sans-serif;
">
  <img src="/DP/dp0.jpg" name="slide" alt="No Picture Available" class="box-img">
<script>
<!--
//variable that will increment through the images
var step=0
function slideit(){
//if browser does not support the image object, exit.
if (!document.images)
return
document.images.slide.src=eval("dp"+step+".src")
if (step<2)
step++
else
step=0
//call function "slideit()" every 2.5 seconds
setTimeout("slideit()",10000)
}
slideit()
//-->
</script>