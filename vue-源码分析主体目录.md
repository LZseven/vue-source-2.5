
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
</head>
<body>
<h3>vue源码结构目录</h3>

<ul>
	<li>^ src 主要源码所在位置</li>
	<li>
		<p>-compiler</p>
			<p><a href="#">--codegen</a> 根据ast生成render函数</p>
			<p><a href="#">--directives</a> 通用生成render函数之前需要处理的指令</p>
			<p><a href="#">--parser</a> 模板解析</p>
	</li>
	<li style="marginLeft:20px;">
		<p>-core 核心代码</p>
			<p><a href="#">--components</a> 全局的组件，这里只有keep-alive</p>
			<p><a href="#">--global-api</a> 全局方法，也就是添加在Vue对象上的方法，比如Vue.use,Vue.extend,,Vue.mixin等</p>
			<p><a href="#">--instance</a> 实例相关内容，包括实例方法，生命周期，事件等</p>
			<p><a href="#">--observer</a> 双向数据绑定相关文件</p>
			<p><a href="#">--util</a> 工具方法</p>
			<p><a href="#">--vdom</a> 虚拟dom相关</p>
	</li>
</ul>
</body>
</html>










