# interviweSummary
1、js的基础数据类型和引用数据类型区别
   基本数据类型：string，number，boolean,undefined,null,Symbol(es6新的基础数据属性，用来表示独一无二的值)
   引用数据类型：object,array,function  
   
2、原型链，继承
   
3、const、let、var区别
   var声明的变量没有块级作用域，而且存在变量名提升的情况（var其实是有利有弊的，利就是不用去管什么常量与变量的，直接使用var就行，弊就是不存在块级作用域且变量名会提升，这会在无形之中给我们带来许多意想不到的问题）
   const（es6中用来定义常量的一个关键字（当然了，其他语言里也存在着const，这里仅指在js中）。常用来声明常量，且常量不可修改，必须初始化，存在着块级作用域 let在块级作用域中为变量 可修改
   
4、http协议、报文、请求方式、状态码
5、浏览器输入url到页面加载完成过程
6、promise和settimeout以及promise.all实现
7、js几种函数类型的this指向

8、js深拷贝浅拷贝
   判断依据就是是否产生新的数据对象，
   数组浅拷贝的方式：arr.slice(),arr.concact(),
   对象浅拷贝的方式：Object.assign(),{...obj},
   深拷贝：JSON.parse(JSON.stringify(obj/arr))
   
9、vue的双向数据绑定原理

10、vue3.0+相较于2.0+有什么区别
11、vue父子组件传值、状态管理
12、如何解决vue首页加载慢的问题
13、redux状态管理，数据流向
14、react路由拦截、权限配置
15、前端性能优化
16、webpack和gulp打包原理
