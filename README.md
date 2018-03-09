# question
## 前端面试题库

如有问题，欢迎指正

## 一、原生Js面试题

 __1、请列举出你所知道的http meathod。__
 
  GET HEAD POST DELETE OPTIONS
  [ 参考地址]( https://www.jianshu.com/p/1a49a7b08ee0)
 
 __2、请写出es6新增的第七个基本数据类型，并简要说明为什么array不是基本数据类型。__
 
   symbol [ 参考地址]( http://es6.ruanyifeng.com/#docs/symbol)
  
   基本类型和引用类型的区别[ 参考地址]( https://www.cnblogs.com/cxying93/p/6106469.html)
 
 __3、请列举出transform属性可以应用的变换的属性名。__
 
   [ 参考地址]( http://www.w3school.com.cn/cssref/pr_transform.asp)
   
 __4、请说明call，apply，bind的异同点，并构想一下怎么实现bind方法。__
 
 
 __5、请说明reference error和type error出现的常见原因。__
 
 __6、请写一个二分搜索的function。__
 
 __7、简单说明并行和并发的区别，队列和栈的区别，为什么使用eval方法会降低js代码的效率。__
 
__8、array的常用方法，数组去重。__

__9、闭包的概念理解。__
 
__10、原型链的理解。__
 
__11、作用域链的理解。__
 
__12、游览器的兼容性。__
 
__13、前后端分离开发引起的跨域和session丢失怎么解决。__
 
__14、setTimeout和setInterval，并简要实现一下setInterval和clearInterval。__
 
__15、列举你所知道的优化页面加载效率的方法(图片加载，js加载，css加载)。__
 
__16、简要构思一下怎么实现一个swiper组件。__
 
__17、怎么判断当前元素是否在可视范围之内。__
 ```
  const inViewport = (el) => {
    const rect = el.getBoundingClientRect()

    return rect.top > 0
      && rect.bottom < window.innerHeight
      && rect.left > 0
      && rect.right < window.innerWidth
  }
  ```
  
__18、理解new 关键字的实现原理。__
__19、获取字符串中的数字并返回数字数组。__
```
str.match(/[0-9]{1,}/g)
```
__20、原型链的继承有哪些。__
```
function fa() {}
1、son.prototype = new fa()
2、son.prototype = fa.prototype
3、son.prototype = Object.create(fa.prototype);

进阶
function son(){
 fa.apply(this)
}
```

## 二、vue
```

  1、vue的算法属性是什么。
  
  2、vue的核心思想是什么。
  
  3、生命周期是什么。
  
  4、什么是单页应用。
  
  6、vue-router的变换原理是什么。
  ```

## 三、angularJs
```
 1、怎么封装一个组件，组件里面的分别是什么，
 
 2、compare和link分别代表什么。
 
 3、service和factory直接的区别是什么。
 ```
 

## 四、css、sass、less
```
  1、怎么实现垂直居中。
  
  2、简要说明transiton的属性。
  
  3、怎么实现一个水波纹效果。
  
 ```

## 五、webpack，gulp，grunt
```
  1、load是什么意思。
```
## 六、node

## 七、h5
```
  1、有哪些特性。
```
## 八、

