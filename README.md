# React Rtcs

## Install

```bash
npm install rtcs --save
```

[详情文档](https://github.com/976500133/rtcs)


# Util


### 项目目录结构
-----------------

|--Date.js （时间处理方法）<br />
|&emsp;&emsp;|-------  Date.prototype.format  <br />
|&emsp;&emsp;|-------  Number.prototype.toDateFormat  <br />
|&emsp;&emsp;|-------  Number.prototype.toDistanceNow  <br />





### 使用展示

##### Date.prototype.format

    /**
     * @class Date 时间格式转换
     * @descrption
     * **使用方式 new Date().format('yyyy-MM-dd  HH:mm:ss w')
     * **返回值 "2018-01-06  13:51:36 星期六"
     **/


##### Number.prototype.toDateFormat

    /**
    * @class Number 时间戳格式转换
    * @descrption  依赖于 Date.prototype.format
    * **使用方式 Number(1514764800).toDateFormat('yyyy-MM-dd HH:mm:ss w')
    * **返回值 "2018-01-01 08:00:00 星期一"
     **/

##### Number.prototype.toDistanceNow

    /**
     * @class Number
     * @descrption 时间戳格式转换成距离现在多久 几 "年","天","小时","分钟","秒钟" 前
     * **使用方式  Number(1514764800).toDistanceNow()
     * **返回值  "5天前"
     **/


​     
​     
​     





# Interview

* [本书简介](README.md)
* [专题系列](zt.md)
    - [如何实现一个 Git Diff 解析器](./interview/zt/zt-diff.md)
    - [react-redux 之 connect 方法详解](./interview/zt/js-redux.md)
    - [细说 webpack 之流程篇](./interview/zt/zt-webpack.md)
    - [git 使用](./interview/zt/zt-git.md)
    - [网络传输](./interview/zt/zt-network.md)
    - [算法题目](./interview/zt/zt-suanfa.md)
    - [说话的艺术](./interview/zt/zt-hr.md)
    - [JavaScript 中的错误隔离](./interview/zt/js-error.md)
    - [学习ES2015](./interview/zt/js-er2015.md)
    - [webpack 常见问题](./interview/zt/zt-webpack-qa.md)
    - [webpack打包原理解析](./interview/zt/zt-webpack-origin.md)
    - [WangEditor点击按钮直接弹出选择文件窗口，不显示下拉框的插件开发](./interview/zt/js-wangeditor.md)
    - [webpack 代码分离](./interview/zt/webpack-code-spliting.md)
    - [前端面试必备——十大经典排序算法](./interview/zt/js-suanfa.md)
* [HTTP系列](README-JAVASCRIPT.md)
    - [99%的人理解错 HTTP 中 GET 与 POST 的区别](./interview/http/http-post-get.md)
    - [HTTP 深入详解](./interview/http/HTTP-analysis.md)
    - [HTTP AJAX 介绍](./interview/http/http-ajax.md)
    - [Ajax 解决浏览器缓存问题](./interview/http/http-ajax-delete-cache.md)
    - [性能优化之路——性能指标体系](./interview/http/http-meituan.md)
    - [一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么](./interview/http/http-render.md)
    - [监控平台前端SDK开发实践](./interview/http/http-watch.md)
    - [首屏、白屏时间如何计算](./interview/http/http-white.md)
    - [Http POST 提交数据的四种方式解析](./interview/http/http-post-urlcode.md)
    - [html全局属性有哪些](./interview/http/html-global.md)
    - [前端性能毫秒必争方案(-) HTTP请求](./interview/http/http-http.md)
    - [前端性能毫秒必争方案(二) HTTP缓存](./interview/http/http-cache.md)
    - [前端性能毫秒必争综合方案](./interview/http/http-01.md)
    - [HTTP METHOD 介绍](./interview/http/http-method.md)
    - [http状态码有那些？分别代表是什么意思](./interview/http/http-status.md)
* [HTML系列](README-JAVASCRIPT.md)
    - [DOCTYPE的作用](./interview/html/DOCTYPE.md)
    - [浏览器渲染原理](./interview/html/html-reflow-repaint.md)
    - [前端SEO](./interview/html/seo.md)
    - [web开发中会话跟踪的方法](./interview/html/web-talk.md)
* [CSS系列](README-JAVASCRIPT.md)
    - [行内块级元素有哪些](./interview/css/block-inline.md)
    - [居中div有哪些方式](./interview/css/css-center.md)
    - [层叠顺序（stacking level）与堆栈上下文（stacking context）知多少？](./interview/css/css-zindex.md)
    - [巧妙地制作背景色渐变动画](./interview/css/css-animation-background.md)
    - [块级格式化上下文bfc](./interview/css/css-bfc.md)
    - [纯CSS绘制三角形](./interview/css/css-triangle.md)
    - [css定义的权重](./interview/css/css-qz.md)
    - [pc 和移动端的区别](./interview/css/pc2mb.md)
    - [position的值relative和absolute定位原点是](./interview/css/css-position-relative.md)
    - [css 清除浮动](./interview/css/css-clear-float.md)
    - [如何清理浮动（2）](./interview/css/css-clear.md)
    - [CSS 继承](./interview/css/css-extend.md)
    - [7种方式解决1px问题](./interview/css/dpr1px.md)
    - [CSS3有哪些新特性](./interview/css/css-new.md)
    - [css单位有哪些](./interview/css/css-pixel.md)
    - [css选择符](./interview/css/css-selected.md)
    - [link和import的区别](./interview/css/link-import.md)
    - [Sass Less SCSS 的抉择](./interview/css/sass-less-scss.md)
    - [单行居中显示文字，多行居左显示，最多两行超过用省略号结尾](./interview/css/css-text-overflow.md)
* [JAVASCRIPT系列](README-JAVASCRIPT.md)
    - [主流浏览器内核介绍和历史](./interview/javascript/js-brower-history.md)
    - [浏览器线程阻塞](./interview/javascript/browser.md)
    - [浏览器内核和JavaScript单线程](./interview/javascript/js-webkit.md)
    - [浏览器进程？线程？傻傻分不清楚！](./interview/javascript/js-webkit-thred.md)
    - [js箭头函数](./interview/javascript/js-arr-func.md)
    - [Object.assign 详细使用](./interview/javascript/js-assign.md)
    - [容易混淆的DOM元素尺寸client-*、scroll-*、 offset-*](./interview/javascript/js-offset-clinet-scroll.md)
    - [通过简单的懒加载了解节流和去抖](./interview/javascript/js-throttle.md)
    - [arguments 详解](./interview/javascript/js-arguments.md)
    - [DOM事件类](./interview/javascript/js-dom.md)
    - [js箭头函数](./interview/javascript/js-arr-func.md)
    - [javascripts 浅拷贝和深拷贝](./interview/javascript/js-copy.md)
    - [一个通用的事件侦听器函数](./interview/javascript/js-addevent.md)
    - [什么是闭包（closure）](./interview/javascript/js-clourse.md)
    - [js数组详解](./interview/javascript/js-array.md)
    - [js字符串详解](./interview/javascript/js-string.md)
    - [浅谈javascript的函数节流](./interview/javascript/js-function.md)
    - [图片懒加载](./interview/javascript/js-img-load.md)
    - [什么是Cookie 隔离](./interview/javascript/js-cookie.md)
    - [js对象的深度克隆](./interview/javascript/js-deepcopy.md)
    - [一个contextmenu的插件](./interview/javascript/js-contextmenu.md)
    - [js数组去重](./interview/javascript/js-duplicate.md)
    - [XSS 和 CSRF 两种跨站攻击](./interview/javascript/js-xss-csrf.md)
    - [web端cookie的设置和获取方法](./interview/javascript/js-cookie-getset.md)
    - [面试问题](./interview/javascript/js-interview.md)
    - [如何实现数组的随机排序](./interview/javascript/js-sort-random.md)
    - [["1", "2", "3"].map(parseInt) 答案是多少？](./interview/javascript/js-parseint-map.md)
    - [如何将浮点数点左边的数每三位添加一个逗号，如12000000.11转化为『12,000,000.11』](./interview/javascript/js-dot.md)
    - [clientX,offsetX,screenX,pageX](./interview/javascript/clientX-offsetX-screenX-pageX.md)
    - [defer 与 async](./interview/javascript/defer-async.md)
    - [ES6 的 Promise实践](./interview/javascript/es6-promise.md)
    - [Highcharts 江湖就这样](./interview/javascript/highcharts-introduce.md)
    - [HTML5无刷新改变当前url](./interview/javascript/html5-history.md)
    - [HTML5 video 详解](./interview/javascript/html5-video.md)
    - [IE-OLD IE 提示](./interview/javascript/ie-old.md)
    - [Js 连线支持随意拖](./interview/javascript/js-canvas-drag.md)
    - [Js 跨域之李代桃僵](./interview/javascript/js-crossorigin.md)
    - [Js 保证产品质量](./interview/javascript/js-error.md)
    - [Markdown的江湖之自定义 （扩展）](./interview/javascript/markdown-extend.md)
    - [通用正则200](./interview/javascript/regexp-common.md)
    - [typeof 的用法](./interview/javascript/typeof.md)
    - [undefined与null的区别](./interview/javascript/undefined-null.md)
    - [var、let、const 区别](./interview/javascript/var-let-const.md)
    - [webServer SSO 原理及实现](./interview/javascript/web-sso.md)
    - [Yun.js 常用封装](./interview/javascript/Yun.js.md)
* [REACT系列](README-JAVASCRIPT.md)
    - [前端路由实现与 react-router 源码分析](./interview/react/js-react-router.md)
    - [如何选择Redux的store和React的state](./interview/react/react-redux-state.md)
    - [React 综合事件 SyntheticEvent](./interview/react/React-SyntheticEvent.md)
    - [React 错误记录](./interview/react/react-error-1.md)
    - [es6的class写法与es5的createClass都有哪些区别？](./interview/react/react-class-createClass.md)
    - [react 扩展运算符](./interview/react/react....md)
    - [react 虚拟DOM](./interview/react/react-dom.md)
    - [react 生命周期](./interview/react/react-life.md)
    - [react 中event 的处理方式](./interview/react/react-event.md)
    - [函数组件 和 类组件的区别](./interview/react/react-function-class.md)
    - [react key 的理解](./interview/react/react-key.md)
    - [这段代码有什么问题](./interview/react/react-question.md)
    - [React 中的ref 介绍， 为什么他们很重要](./interview/react/react-ref.md)
    - [调用setState时会发生什么？](./interview/react/react-setstate.md)
    - [setState 第二个参数](./interview/react/react-setstate-args.md)
    - [在哪个生命周期事件中，你会做出AJAX请求，为什么？](./interview/react/react-ajax.md)
    - [React.Children 和 this.props.children](./interview/react/react-children.md)
    - [受控组件与不受控制的组件有什么区别](./interview/react/react-controller.md)
    - [react 从使用 看定义](./interview/react/react-define.md)
    - [什么是虚拟DOM？](./interview/react/react-dom.md)
    - [Redux从设计到源码](./interview/react/react-redux.md)
    - [React Elements vs React Components](./interview/react/react-elements-components.md)
* [WEB 移动端](README-mobile.md)
    - [viewport详解](./interview/mobile/mb-viewport.md)
* [PYTHON](README-mobile.md)
    - [列表、字典、集合中根据条件筛选数据](./interview/python/python-1.md)
    - [为元组中的每个元素命名](./interview/python/python-2.md)
    - [统计序列中元素的出现频度](./interview/python/python-3.md)
    - [对字典中的项根据其值的大小进行排序](./interview/python/python-4.md)
    - [为Mac 设置Python多版本开发环境](./interview/python/pyenv-mac.md)
* [NODEJS系列](README-JAVASCRIPT.md)
* [SWIFT系列](README-JAVASCRIPT.md)
    - [iOS 微信 QQ 登陆 分享](./interview/swift/swift-share.md)
    - [元芳，iOS 四大邪术之一，你怎么看？](./interview/swift/swift-base-animation.md)
    - [IOS APP 侧边栏滑动](./interview/swift/swift-app.md)
* [SPRING-BOOT系列](README-SPRINT-BOOT.md)
    - [Spring MVC注解篇](./interview/spring-boot/sp-jianshu.md)
* [TOOLS系列](README-JAVASCRIPT.md)
    - [Nginx 经典美文](./interview/tools/nginx.md)
    - [EsLint规则与配置](./interview/tools/eslint-rules.md)
    - [mac osx下环境变量以及加载顺序](./interview/tools/mac-path.md)
    - [Mac自带 SVN 命令简洁操作](./interview/tools/mac-svn.md)
* [数据库](README-JAVASCRIPT.md)





