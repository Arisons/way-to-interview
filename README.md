前端面试题汇总
=============

这里将列出面试中遇到的面试题，起到查漏补缺的作用。

面试是一个自我提升的过程，不要因为一两次的面试失败而丧失信心，自我很怀疑，而是要通过面试找到自己的不足和优势，不足就赶紧恶补啊，优势尽量在面试中展示出来。

By[@Arisons](https://github.com/Arisons/way-to-interview)

### 概念篇

- ##### 1、说一下` let `, `const` ,` var ` 三者有什么区别 ？？

1、var定义的变量可以修改，如果不初始化会输出undefined，不会报错，会有变量提升。

2、let是块级作用域，函数内部使用let定义后，对函数外部无影响，没有变量提升。

3、const是常量，const定义的变量不可以修改，而且必须初始化。

- ##### 2、简述同步和异步的区别
  1）同步是阻塞模式，异步是非阻塞模式。
  同步就是指一个进程在执行某个请求的时候，若该请求需要一段时间才能返回信息，那么这个进程将会一直等待下去，直到收到返回信息才继续执行下去；

  2）异步是指进程不需要一直等下去，而是继续执行下面的操作，不管其他进程的状态。当有消息返回时系统会通知进程进行处理，这样可以提高执行的效率。

- ##### 3、简述下vue的生命周期

  ###### 它可以总共分为8个阶段：

  beforeCreate（创建前）,

  created（创建后）,

  beforeMount(载入前),

  mounted（载入后）,

  beforeUpdate（更新前）,

  updated（更新后）,

  beforeDestroy（销毁前）,

  destroyed（销毁后）

  参考文档：[https://segmentfault.com/a/1190000011381906](https://segmentfault.com/a/1190000011381906)

- ##### 4、如题
```html
	<div class='blue,red'>你说我什么颜色</div>
	<div class='red,blue'>这时候又是什么颜色</div>
```
```css
 .red{
     color:red;
 }
 .blue{
     color:blue;
 }
```
- ##### 5、如题
 const定义一个数组 `const arr = [1, 2` `arr.push(3)` 会报错吗???
.定义一个 `const obj = {a: 1, b: 2}` `obj.a = 3`    会报错吗???
简单解释下咯？？

  #### 待续.....


By[@smileyby](https://github.com/smileyby/way-to-interview)

1/已知有序数组，查找其中的某个元素并返回其下标（不能使用语言自带的方法，考虑性能）
如果数组有n个数，那最坏的查找结果要查询多少次？

2/js题目如下：

```javascript
function Foo() {
	getName = function () { 
		console.log (1); 
	};
	console.log('this is'+this)
	return this;
}
Foo.getName = function () { 
	console.log (2); 
};
Foo.prototype.getName = function () { 
	console.log('baidu' && 'google'); 
};
var getName = function () { 
	console.log (4);
};
function getName() { 
	console.log (5);
}

// 请写出一下的输出结果
Foo.getName(); 
getName(); 
Foo().getName();  
getName();  
new Foo.getName();  
new Foo().getName();  
new new Foo().getName();
```

3/router-view 常用的钩子函数

4/cdn缓存的原理

5/dns运行机制

6/vue react angular各自的优缺点

7/html css js 浏览器兼容相关问题

8/页面性能优化方案

9/cookie 预防xss攻击

10/firefox 浏览器再开发中遇到的兼容问题

11/webpack 项目性能优化方案

12/v-if和v-show区别

13/使用vue的过程中遇到的报错情况有哪些？

14/关于数据结构，你知道的排序算法有哪些？

