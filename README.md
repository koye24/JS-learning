# JS-learning

# 李炜业hello world



git status

git add .

git commit -m "本次提交的描述"

git pull https://github.com/koye24/JS-learning.git

git push https://github.com/koye24/JS-learning.git master



```html
<div id="app">
  <!-- 使用组件：就像普通的标签一样使用 -->
  <first></first>
</div>
<script>
  // 组件的创建：不是写在 vm 实例中
  // 1.通过 Vue.extend 和 Vue.component

  // 3.还是通过 Vue.component (组件名称，配置)来创建，
  //   本质上也是调用了 Vue.extend --语法糖
  Vue.component('first',{
    // template 模板的作用就是用来标识当前组件的 dom 结构
    template:'<p>你好啊，我的第一个组件</p>'
  })

  var vm = new Vue({
	el: '#app',
  	data: {

  	}
  })
</script><div id="app">
  <!-- 使用组件：就像普通的标签一样使用 -->
  <first></first>
</div>
<script>
  // 组件的创建：不是写在 vm 实例中
  // 1.通过 Vue.extend 和 Vue.component

  // 3.还是通过 Vue.component (组件名称，配置)来创建，
  //   本质上也是调用了 Vue.extend --语法糖
  Vue.component('first',{
    // template 模板的作用就是用来标识当前组件的 dom 结构
    template:'<p>你好啊，我的第一个组件</p>'
  })

  var vm = new Vue({
	el: '#app',
  	data: {

  	}
  })
</script>
```



