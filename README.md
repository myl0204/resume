# 这是一份简历，面向前端。

## 基础信息
姓名：缪云良

出生年月: 1994.02


学历： 本科/浙江科技学院/2016年


电话： 18968979900

Email: yunliangmiao@gmail.com

blog: https://segmentfault.com/blog/fehaha
## 项目经验
### [网易产品教育部首页](https://myl0204.github.io/Netease-Edu/) 
> 只是一个页面。
- 使用/实现了雪碧图、轮播图、滚动列表、登陆表单、Ajax、cookie、响应式、组件化的思想，兼容IE8+

收获及反思
- 算是入门了前端，写滚动列表的过程中也知道了出于性能，浏览器会尽可能的把最近的需要渲染的动作整合到一起执行。
- 代码风格不好；命名不规范；对resize事件也没有使用函数节流。

[github地址](https://github.com/myl0204/Netease-Edu)

### [仿didi项目](https://github.com/myl0204/XiXi)

> 简单而五脏俱全的spa，从打车变为撸猫:cat:
- 使用了vue全家桶
- 实现了多个组件，组件复用度高。

收获及反思
- 了解学习了移动端的`touch`事件
    - 多个组件用到了`touch`事件
- 复用组件，提升代码利用率
    - 封装了`modal`组件，在此基础上写了`message`和`logIn`组件
- 对移动端响应式有了进一步理解
    - 布局方面，采用`vh`来写
- 对vuex的使用还停留在非常浅显的水平
    + 只是简单的提交mutation来更改state
- app复原程度低，功能少
    + 有待完善

### [tab-slider](https://github.com/myl0204/tab-slider) 滑动切换路由组件
> 算是一个轮子吧
- 仿didi项目中的一个功能，抽离出来改写为一个公共组件，并发布到npm。

收获和反思
- 之前项目中的写法重复代码多，写法固定
    + 抽离后代码复用度高，支持多个tab之间切换。
- 对webpack不够熟悉，打包后的文件总是无法被正常使用
    + 增加output选项中的library属性
## 其他
- 熟练使用ES6及Vue框架。
- 了解使用过前端构建工具gulp,webpack;css预处理器Sass
