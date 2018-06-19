
<h3>vue源码结构目录</h3>

<ul>
	<h3>src 主要源码所在位置</h3>
	<li>
		<p>compiler</p>
			<p style="marginLeft:20px;">--codegen 根据ast生成render函数</p>
			<p style="marginLeft:20px;">--directives 通用生成render函数之前需要处理的指令</p>
			<p style="marginLeft:20px;">--parser 模板解析</p>
	</li>
	<li>
		<p>core 核心代码</p>
			<p style="marginLeft:20px;">--components 全局的组件，这里只有keep-alive</p>
			<p style="marginLeft:20px;">--global-api 全局方法，也就是添加在Vue对象上的方法，比如Vue.use,Vue.extend,,Vue.mixin等</p>
			<p style="marginLeft:20px;">--instance 实例相关内容，包括实例方法，生命周期，事件等</p>
			<p style="marginLeft:20px;">--observer 双向数据绑定相关文件</p>
			<p style="marginLeft:20px;">--util 工具方法</p>
			<p style="marginLeft:20px;">--vdom 虚拟dom相关</p>
	</li>
</ul>