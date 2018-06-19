
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1.0,maximum-scale=1.0,user-scalable=0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black">
  <meta name="format-detection" content="telephone=no">
  <!--禁止屏幕旋转-->
  <meta name="screen-orientation" content="portrait">
  <meta name="x5-orientation" content="portrait">
  <title>我的ip</title>
</head>
<body>
	<h3>vue源码结构目录</h3>

<ul>
	<li>src 主要源码所在位置</li>
	<li style="listStyle:none;">
		<p>-compiler</p>
			<p style="marginLeft:20px;"><a href="#">--codegen</a> 根据ast生成render函数</p>
			<p style="marginLeft:20px;"><a href="#">--directives</a> 通用生成render函数之前需要处理的指令</p>
			<p style="marginLeft:20px;"><a href="#">--parser</a> 模板解析</p>
	</li>
	<li style="listStyle:none;">
		<p>-core 核心代码</p>
			<p style="marginLeft:20px;"><a href="#">--components</a> 全局的组件，这里只有keep-alive</p>
			<p style="marginLeft:20px;"><a href="#">--global-api</a> 全局方法，也就是添加在Vue对象上的方法，比如Vue.use,Vue.extend,,Vue.mixin等</p>
			<p style="marginLeft:20px;"><a href="#">--instance</a> 实例相关内容，包括实例方法，生命周期，事件等</p>
			<p style="marginLeft:20px;"><a href="#">--observer</a> 双向数据绑定相关文件</p>
			<p style="marginLeft:20px;"><a href="#">--util</a> 工具方法</p>
			<p style="marginLeft:20px;"><a href="#">--vdom</a> 虚拟dom相关</p>
	</li>
</ul>
</body>
</html>










