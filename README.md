# mditor
嵌入网页的markdown编辑器，兼容各种语言环境，可用于技术博客，技术分享的网站使用
***
##使用方法
* 将CSS文件引入到head中
``` javascript
  <link rel="stylesheet" href="css/mditor.min.css" />
```
* 在文本框或者文本域中定义要显示的编辑器
``` javascript
  <textarea name="editor" id="editor"></textarea>
```
* 引入js文件
``` javascript
  <script src="js/mditor.min.js"></script>
	<script>
		var mditor = new Mditor("#editor",{
			height:400,
			fixedHeight:true
		});
		mditor.openPreview();
		function getcontent(){
			var txt=document.getElementById("editor").value;
			alert(txt);
		}
	</script>
	```
详情请看demo.html
