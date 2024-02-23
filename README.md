# 前端架构师进阶之路

## [架构](./架构/README.md)

- [npm-yarn-pnpm](./架构/cmd.md)
- [脚手架](./架构/脚手架.md)
- [ejs 和 glob 用法](./架构/ejs和glob用法.md)
- [前端监控](./架构/前端监控.md)

## 笔记

- [前端进阶](./前端进阶/README.md)
- [移动端响应式布局开发的方案](./前端进阶/移动端响应式布局开发的方案.md)
- [前端主题切换方案详解](./前端进阶/前端主题切换方案详解.md)
- [vue3 前端自适应的终及解决方案](./前端进阶/前端自适应的终及解决方案.md)
- [Grid 布局](./前端进阶/Grid.Html)
- [实现 iconfont 图标渐变](./前端进阶/实现iconfont图标渐变.md) 或者[参考](https://github.com/RyanLYC/web-vue3-template/blob/main/src/components/SvgIcon/index.vue)
- 保留一天数据，生成一个 demo 网站用于无网络地方展示或者固定显示那一天数据
  1. axios 返回后 用 FileSaver.js 以 url 和请求方法参数作为 url 保存文件
  2. 全部页面点击一次
  3. 拦截 axios 请求，直接使用对应的接口文件
- [图片懒加载](https://github.com/RyanLYC/ImgLazyLoad)
- [工具函数库](https://github.com/RyanLYC/zg-utils)
- [monorepo](https://github.com/RyanLYC/monorepo)
- [大文件上传](https://github.com/RyanLYC/file_upload)[后台](https://github.com/RyanLYC/koa-mongodb)
- [网页置灰方案](https://github.com/RyanLYC/pagegray)
- [传统部署模式-pm2-eggJS-cluster](./笔记/传统部署模式.md)
- 基于 Github Actions & docker compose 的 CI & CD
  1. [服务器设置以及登录最佳实践](./笔记/服务器设置以及登录最佳实践.md)
  2. [CentOS7 安装 docker&docker-compose](./笔记/安装docker.md)
  3. [Github Actions](./笔记/GithubActions.md)
  4. [Docker](./笔记/Docker.md)
  5. [Docker-redis-mongo 配置](./笔记/Docker-redis-mongo配置.md)
- [el-table 导出为 Excel](./笔记/XLSX.md)
- [基于 nexus3 搭建 npm 私库](./笔记/基于nexus3搭建npm私库.md)
- [centos7 设置虚拟内存](./笔记/centos7设置虚拟内存.md)

## Vue

- [vue3-CHANGELOG](https://github.com/vuejs/core/blob/main/CHANGELOG.md)
- [Vue3.2setup 语法糖](./VUE/Vue3.2setup语法糖.md)
- [vue-router4.0 钩子函数&执行流程](https://github.com/RyanLYC/vue-router4-course)
- [vue3.3 组件库](https://github.com/RyanLYC/vite-components) & [文档地址](https://ryanlyc.github.io/vite-components-last/components/button)
- [vue3 企业级项目模板搭建](https://github.com/RyanLYC/vue3-template)
- [vue3 企业后台管理功能模版](https://github.com/RyanLYC/web-vue3-template)
- [min-vue3](https://github.com/RyanLYC/mini-vue3)
- [mini-vuex](https://github.com/RyanLYC/mini-vuex)
- [esbuild 构建 Vue3 组件库](https://github.com/RyanLYC/vue3-component-library-esbuild)

## React

## NodeJS

- [Express 与 Koa2 之间的区别](./NodeJS/Express与Koa2.md)
- [koa2-mongodb5](https://github.com/RyanLYC/koa-mongodb)
- [数据库](./NodeJS/数据库.md)
- [cookie 与 Session](./NodeJS/cookie与Session.md)
- [跨域](./NodeJS/跨域.md)
  - [基于 iframe 的跨域解决方案](./跨域/基于iframe的跨域解决方案.md)
  - 三个标签是允许跨域加载资源 `<img src=XXX> <link href=XXX> <script src=XXX>`
  - [CORS 跨域资源共享](./跨域/CORS跨域资源共享.md)
  - [jsonP](./跨域/jsonP.md)
  - [nginx 反向代理](./跨域/nginx反向代理.md)
  - [websocket](./跨域/websocket.md)
  - 多种跨域方式样例代码
- [eggJs](./NodeJS/eggjs.md)
- [数据库](./NodeJS/数据库.md)
- [JWT](./NodeJS/JWT.md)
- [mongoDB](./NodeJS/mongoDB.md)
- [RBAC(role based access control)根据角色完成权限的控制](./NodeJS/RBAC.md)

## 夸端

- [uni-app](https://uniapp.dcloud.net.cn/) 是一个使用 Vue.js 开发所有前端应用的框架，开发者编写一套代码，可发布到 iOS、Android、Web（响应式）、以及各种小程序（微信/支付宝/百度/头条/飞书/QQ/快手/钉钉/淘宝）、快应用等多个平台。
- [uni-app x](https://doc.dcloud.net.cn/uni-app-x/)是下一代 uni-app，是一个跨平台应用开发引擎。uni-app x 没有使用 js 和 webview，它基于 uts 语言。在 App 端，uts 在 iOS 编译为 swift、在 Android 编译为 kotlin，完全达到了原生应用的功能、性能。
- [Taro](https://taro-docs.jd.com/docs/version)是一个开放式跨端跨框架解决方案，支持使用 React/Vue/Nerv 等框架来开发 微信 / 京东 / 百度 / 支付宝 / 字节跳动 / QQ / 飞书 小程序 / H5 / RN 等应用。Taro 3 可以支持转换到 H5、ReactNative 以及任意小程序平台。

## ThreeJS

- [储能站模型交互](https://github.com/RyanLYC/threejs-cn)
- [vue3 ThreeJS 项目模版](https://github.com/RyanLYC/three-js-template)
- [园区模型](https://github.com/RyanLYC/threejs-park)
- [ThreeJS 基础知识](https://github.com/RyanLYC/threejs-base)
- [webGL 基础知识](https://github.com/RyanLYC/webgl-base)
- [三维机房](https://github.com/RyanLYC/computer-room-3d)

## 构建工具

- [vite](./构建工具/vite/README.md)
  - [mini-vite](https://github.com/RyanLYC/mini-vite)
- [webpack](./构建工具/webpack/README.md)
  - [webpack5 federation](https://github.com/RyanLYC/module-federation-webpack5)
  - [mini-webpack](https://github.com/RyanLYC/mini-webpack-js)
- [vite、webpack、rollup 原理](./构建工具/原理.md)

## CLI

- [move-folder-cli](https://www.npmjs.com/package/move-folder-cli) 在命令行上复制或移动文件夹
- [create-vite](https://github.com/RyanLYC/zg-create-app)

## 手写代码

- [apply](./手写代码/apply.js)
- [call](./手写代码/call.js)
- [bind](./手写代码/bind.js)
- [debounce](./手写代码/debounce.js)
- [throtte](./手写代码/throtte.js)
- [input throtte demo](./手写代码/input-throtte.html)
- [deepClone](./手写代码/deepClone.js)
- [清除字符串前后的空格的函数](./手写代码/清除字符串前后的空格的函数.js)

## 工具

- [Git 命令速查表](https://shfshanyue.github.io/cheat-sheets/git)

## 八股文

- [计算机网络部分](./八股文/计算机网络部分.md)
- [浏览器部分](./八股文/浏览器部分.md)
- [前端工程化部分](./八股文/前端工程化部分.md)
- [性能优化部分](./八股文/性能优化部分.md)
- [HTML 部分](./八股文/HTML部分.md)
- [CSS 部分](./八股文/CSS部分.md)
- [JavaScript 部分](./八股文/JavaScript部分.md)
- [React 部分](./八股文/React部分.md)
- [VUE 部分](./八股文/VUE部分.md)

## ECMAScript

- [ECMAScript](./ECMAScript/index.md)
- [ES6 新特性-2015](./ECMAScript/ES6新特性-2015.md)
- [ES7 新特性-2016](./ECMAScript/ES7新特性-2016.md)
- [ES8 新特性-2017](./ECMAScript/ES8新特性-2017.md)
- [ES9 新特性-2018](./ECMAScript/ES9新特性-2018.md)
- [ES10 新特性-2019](./ECMAScript/ES10新特性-2019.md)
- [ES11 新特性-2020](./ECMAScript/ES11新特性-2020.md)
- [ES12 新特性-2021](./ECMAScript/ES12新特性-2021.md)
- [ES13 新特性-2022](./ECMAScript/ES13新特性-2022.md)

## 视频库

- [flv.js mpegts.js](./视频库/flvjs.md)

## 面试

- 浏览器相关
  - [浏览器的一个请求从发送到返回都经历了什么？](./面试题/网络相关/浏览器的一个请求从发送到返回都经历了什么.md)
  - [浏览器页面的渲染阶段?](./面试题/网络相关/浏览器页面的渲染阶段.md)
  - [cookie、session、localStorage、sessionStorage?](./面试题/网络相关/存储.md)
  - [http 状态码](./面试题/网络相关/http状态码.md)
  - [XSS 和 CSRF](./面试题/网络相关/XSS和CSRF.md)
- [CSS](./面试题/CSS/CSS.md)
- [HTML](./面试题/HTML/HTML.md)
- [JavaScript](./面试题/JavaScript/JavaScript.md)
  - [箭头函数](./面试题/JavaScript/箭头函数.md)
  - [`==&===`](./面试题/JavaScript/==&===.md)
  - [['1', '2', '3'].map(parseInt)](./面试题/JavaScript/parseInt.md)
  - [闭包](./面试题/JavaScript/闭包.md)
  - !! - 双非操作可以把字符串和数字转换为布尔值 - !!2 true - !![] true - [] == false true 因为[].toString() = "" ; Number( "" ) = 0; 所有 0 == false 返回 true
  - [遍历数组的 n 种方法](./面试题/JavaScript/遍历数组的n种方法.md)
  - [继承](./面试题/JavaScript/继承.md)
  - [面向对象面试题](./面试题/JavaScript/面向对象面试题.md)
  - [输出以下代码的执行结果并解释为什么](./面试题/JavaScript/输出以下代码的执行结果并解释为什么.md)
  - [数组](./面试题/JavaScript/数组.md)
  - [变量提升](./面试题/JavaScript/变量提升.md)
  - [call-apply-bind 区别](./面试题/JavaScript/call-apply-bind区别.md)
  - [类型检测](./面试题/JavaScript/类型检测.md)
  - [let-const-var](./面试题/JavaScript/let-const-var.md)
  - [let-const-var 区别的实现原理是什么](./面试题/JavaScript/let-const-var区别的实现原理是什么.md)
  - [new 做了些什么](./面试题/JavaScript/new做了些什么.md)
  - [原型改造输出](./面试题/JavaScript/原型改造输出.md)
  - [EventLoop](./面试题/JavaScript/EventLoop.md)
  - [Set-Map-WeakSet-WeakMap 的区别](./面试题/JavaScript/Set-Map-WeakSet-WeakMap的区别.md)
- VUE
  - [vue 组件间通信方式](./VUE/vue组件间传值方式.md)
  - [vue3 内置指令](https://cn.vuejs.org/api/built-in-directives.html#v-text)
  - [vue-router 有几种模式](./VUE/vue-router有几种模式.md)
  - vue 首屏渲染优化有哪些? `图片压缩/懒加载 - 禁止生成 .map 文件 - 路由懒加载 - cdn 引入公共库 - 开启 GZIP 压缩`
  - [watch 和 computed 区别和使用场景](./VUE/watch和computed区别和使用场景.md)
  - vue2.0&vue3.0 双向绑定的实现原理
  - [vue 生命周期函数](./VUE/vue生命周期函数.md)
  - [v-show 和 v-if 有什么区别](./VUE/v-show和v-if有什么区别.md)
  - [什么是 SPA-有什么优点和缺点](./VUE/什么是SPA-有什么优点和缺点.md)
  - v-if 与 v-for 那个优先级更高？怎么优化？
    - v-for 优先级更高，因为源码中优先判断 el.for 再到 el.if
    - 同一个标签中的时候，每次渲染都会先执行循环再判断条件，浪费性能
    - 优化方式一是外层增加一个 template 标签做 v-if 判断，内部 v-for 循环
    - 优化方式二 使用 computed 得到最终结果渲染
  - Vue 组件 data 为何必须是个函数？Vue 的根实例则没有此限制？
    - data 必须为函数是为了同个组件多个实例的时候，使用不同的 data（源码中，初始化 data 的时候会检测是否是个 function，是则执行然后赋值给 data，否则使用传入的 data。实际是运行不了，vue 报错提示 data 必须是个函数）
    - 根实例没有限制是因为每次创建是使用 new Vue() 创建不同实例
  - key 的作用&工作原理？
    - key 的作用是高效地更新虚拟 Dom
    - 原理是 Vue 在 patch 过程中通过 key 可以精准判断两个节点是否是同一个，从而避免频繁更新不同元素，使 patch 过程更加高效，减少 dom 操作，提高性能。
    - 如果不设置 key，key 就会=undefined，每个元素的 key 都是相等的，可能会引发 bug
  - vue 的 diff 算法？
    - diff 是新旧虚拟 Dom 的对比，将变化的的 Dom 更新到真实的 Dom 上。高效的 diff 算法降低对比的时间复杂度
    - vue 中每个组件都会有一个 watch，组件改变的时候触发更新函数，此时会执行 diff，他会比对上一次渲染结果 oldVnode 和新的渲染结果 newVnode，此过程是 patch-打补丁
    - vue 的 diff 算法遵循深度优先、同层比较的策略；两个节点之间比较会根据他们是否拥有子节点或者文本节点做不同的操作；比较两组子节点的时候，是假设头尾节点可能相同做 4 次对比尝试，如果没有找到相同的节点才按照通用方式遍历查找，查找结束批量删除或者新增处理剩余的节点；借助 key 通常可以非常精确找到相同节点，因此整个 patch 过程非常高效。
  - vue 组件化的理解？
    - 组件系统是 Vue 的核心特效，频繁更新的数据显示定义为组件可以优化性能，因为每个组件有一个 watch，改变后更新组件
    - 组件化可以提供开发效率、复用性等
    - 组件一般分为页面组件、业务组件、通用组件
    - vue 的组件是基于配置的，我们编写的 template 组件的 vue 文件是组件配置，框架会生成其构造函数，它们基于 VueComponent，扩展与 Vue
    - vue 的组件化技术：属性 props、自定义事件、插槽，自定义指令等，用于组件的通信和扩展
    - 组件要遵循单向数据流
    - 组件要高内聚、低耦合
  - MVC、MVP、MVVM 的理解？
    - MVC - user -> C -> M -> V 、 M -> V 、 C -> V ； C 可以操作 V，M 也可以操作 V，user 通过 V 调用 C
    - MVP - M -> <- P -> <- V ; P 负责管理一切操作
    - MVVM - VM 是 ViewModel 类似 P，
    - 三个都是框架模式，主要是为了解决 Model 和 View 的耦合问题
    - MVC 很早期，前端还是模版时期
    - MVP 是 MVC 的进化，P 层处理 MV 之间的通信
    - MVVM 主要是前端中使用，类似于 MVP，VM 解决两者的映射关系
  - [Vue 性能优化方法有哪些？](./VUE/Vue性能优化.md)
  - [Vue3.0 新特性](./VUE/Vue3.0新特性.md)
  - VueX 的使用以及理解
    - vue component ->dispatch -> Action(后端 API 获取数据) ->commit -> Mutations(Devtools) ->Mutate -> State ->Render -> vue component
    - vuex 是 vue 的专用状态管理库，以全局方式管理应用的状态
    - vuex 解决多个组件之间的状态共享问题
    - vuex 并非必须使用
    - vuex 实现单向数据流醉倒数据的响应式
  - vue 的 nextTick，是什么？干什么？实现原理？
    - 在下次 DOM 更新循环结束之后执行延迟回调。在修改数据之后立即使用这个方法，可以获取到更新后的 Dom
    - Vue 在更新 DOM 的时候是异步的。只要侦听到数据变化，Vue 将开启一个队列，并缓存在同一个事件循环中发生的所有数据变更。如果同一个 watcher 被多次出发，只会被推入到队列中一次，避免不必要的 DOM 计算。nextTick 方法会在队列中加入一个回调函数，确保该函数前面的 DOM 操作全部完成后才调用
  - Vue 响应式的理解？
    - 响应式：就是能够使数据变化可以被检测到并对这种变化做出响应的机制
    - MVVM 框架中要解决的一个核心问题就是连接数据层和视图层，通过数据驱动视图更新
    - vue 的数据响应式结合虚拟 DOM 和 patch 算法，让我们只需要操作数据，不用繁琐的操作 DOM
    - Vue2 中数据响应式会根据不同的数据类型进行处理，如果是对象会采用 Object.defineProperty()的方式定义数据的拦截，当数据被访问或者发生变化时，做出响应。对象初始化后在追加属性是不会有响应式的，需要使用 Vue.set/delete 才能生效。如果是数组则通过覆盖数组原型的方法，扩展它的 7 个变更方法，使这些方法可以做出响应。对于 es6 的 Map、Set 这些数据结构不支持等问题
    - Vue3 重写了这部分，使用了 es6 的 proxy 机制代理要这些需要响应式的数据。
  - [如何扩展某个 Vue 组件？](https://cn.vuejs.org/api/options-composition.html#provide)
    - 扩展的方式 mixins（vue3 推荐使用 composition api）、slots、extends
    - mixins:一个包含组件选项对象的数组，这些选项都将被混入到当前组件的实例中。
    - extends:使一个组件可以继承另一个组件的组件选项。
    - slots
    - composition api 逻辑复用
