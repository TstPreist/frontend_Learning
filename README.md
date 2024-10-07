# frontend_Learning
学习过程记录、每日总结
# 前端线上实践

https://learn.microsoft.com/en-us/microsoft-edge/devtools-guide-chromium/landing/

- [freeCodecamp 在线编程](https://learn.freecodecamp.one/)
- [阿里云前端实战学习](https://edu.aliyun.com/roadmap/frontend)
- [W3Cschool 编程入门实战](https://www.w3cschool.cn/codecamp/)

[[前端学习路线_carl](https://articles.zsxq.com/id_z0iq7bc1koqb.html)](https://www.notion.so/_carl-b5bcdaff846246d9b611aee9a92e28cf?pvs=21) 

# 三件套

## HTML

做网页，HTML是基础骨架，必须要掌握的；

- 1.先通过 HTML 教程 学习大概
- 2.再通过 HTML5 教程 学习哪些新属性，这在做浏览器兼容低版本的时候特别有用
- 3.最后通过 HTML 标签 加深对每个标签的印象

一步一步跟着动手敲代码

这是一段非常枯燥无味的阶段，如果你感觉枯燥无味，不要紧的，*你可以学完 **HTML 教程** 和 **HTML5 教程** 后直接进入CSS的学习阶段，这样会让你学习的乐趣增加不少；*

等以后合适的时候，再回头看逐个研究 **html 标签**也是一个不错的选择

### video

b站上很火的教程有尚硅谷的李立超老师，和黑马的pink老师

https://www.bilibili.com/video/BV14J4114768/

**现在看这个：**

https://www.bilibili.com/video/BV18T411S71R/?spm_id_from=333.337.search-card.all.click&vd_source=e934f4f848019a88d6a09e29adbc4d37

### book/article

- carl：HTML和CSS:MDN和W3school就足够。
    - 从三件套到框架都有，点进去看看。学习 [**HTML 学习路径**](https://developer.mozilla.org/zh-CN/docs/Learn/HTML)部分，第一遍整体浏览一遍，不需要死记硬背
        
        HTML：该教程也包括了 HTML5 新增的内容，但讲得没下面专门讲解 HTML5 的细，所以该教程我建议只看 HTML 基础教程和表单部分即可
        
        HTML5：该教程讲解了 HTML5 的新特性
        
        [使用 HTML 构建 Web - 学习 Web 开发 | MDN](https://developer.mozilla.org/zh-CN/docs/Learn/HTML)
        
    - 学习 HTML 部分，整体浏览一遍，不需要死记硬背
        
        https://www.w3school.com.cn/
        
- 推荐看一看阮一峰的教程，他写的教程都很棒，所以这里我也推荐下大家看一下阮一峰写的这份 HTML 入门教程，可能可以让你理解的更加透彻：
    
    https://wangdoc.com/html/
    
- HTML CSS JS，内容宽泛，当作每个语言刚开始的整体印象建立
    
    https://docs.geeksman.com/front-end/1.front-end-html.html
    
- 《HTML5 与 CSS3 基础教程》（第8版）：这本书里面有**非常多 HTML 标签**

## CSS

### video

b站上很火的教程有尚硅谷的李立超老师，和黑马的pink老师

### book/article

- [w3school 的系列教程](http://www.w3school.com.cn/h.asp)
- 同样MDN：[学习 CSS ：指南与教程](https://developer.mozilla.org/zh-CN/docs/Learn/CSS)

要学习一下 CSS3

## 静态网页练习

仿一个常用网页，**最少重复3次，**遇到JS效果，直接不做；

目的：完成HTML和CSS的大综合联系，建立整体概念

推荐你把整个网页截图下来，然后根据图片来实现；一般的网页都最低会有 **首页** 和 **详情页** 这两个页面；

通过敲代码，能**总结**出来的东西越多越多！可以逐渐提高自己的技术才是**最终目的**

方式：

一个网站，你重复的写，重复的写，然后每一遍都有不错的心得体会

- 第一遍，你只需要仿制的和原来完全一样就可以！
    - 注意：这里说的是***完全一样**！！！最好的是1Px的误差都没有*
    - 不会写的HTML标签，和不会用的CSS属性，**可以查**
    - 然后总结出这次写的内容中，*有哪些可以**优化**的，哪些可以**重复使用的元素**，那些设计不合理，需要**重新布局***
- 第二遍：总结你第一遍的不合理和思路重新设计
    - 一般初学者第一遍写的东西，基本都是面目全非的；**避免掉一些不合理**的地方，抽出一些复用的元素，**重新设计你的实现思路**
    - 这一步能不查资料，就**尽量不要查**资料
    - 注意这一步是**从0开始**，一定**不要在你第一遍的内容上修改**来实现
    - 实现完成以后，记得**总结**下这一边还有哪些**瑕疵**
- 第三遍：**断网**并且**关掉智能提示**再实现一遍
    - 这一遍再对第二遍的优化，并且需要断网和关闭智能提示来实现，可以增强记忆；

通过上面的3次练习，你对静态网页的书写，一般会有自己的心得了，最好每次都用博客的形式记录下来；

## JavaScript

js是很核心的部分，也是相对来说很难的一部分（其实你写着写着会发现，JS其实和CSS一样，基本就是那些事情，做项目的时候重点反而是复杂场景下的逻辑处理）

- js的基础部分比较简单，推荐在**MDN上学完基础语法**

- ES5阶段可以看B站的甲鱼课程
    - ES6高级语法推荐看阮一峰老师的《ES6入门》
- 前期不推荐红宝书，对于初学者来说太细，建议买一本当字典用，重点掌握原型链、作用域、闭包等特性（面试常问）。

### video

大三大四，时间很匆忙，我就不推荐你看上面的教程了，可以看李老师去年新出的课程和pink老师的课程。

我跟的[黑马pink老师的课](https://www.bilibili.com/video/BV1Y84y1L7Nn/?share_source=copy_web&vd_source=f03979ba5042fef3da938997972ca975)，pink老师多无敌我就不说了，他讲的事件循环和原型链真是nmd条理清晰抽丝剥茧太绝了，而且他的js进阶中涉及到了很多es6的知识点

https://www.bilibili.com/video/BV1Y84y1L7Nn/?share_source=copy_web&vd_source=f03979ba5042fef3da938997972ca975

https://www.bilibili.com/video/BV1mG411h7aD/?share_source=copy_web&vd_source=9bb0aa9c2c3cc1b12ca6f343a55b4e80

### book/article

- 廖雪峰JS教程：**（按照下面这个看法，去看MDN）**
    - 第一遍：
        - [ ]  map和set
        - [ ]  iterable
        - [ ]  函数整章
        - [ ]  标准对象整章
        - [ ]  面向对象编程整章
        - [ ]  浏览器整章
        - [ ]  jQuery整章
    
    后面的先别看。
    
    - **第二遍** 简单的内容就别看了，回去**巩固**一下：
        - [ ]  map和set
        - [ ]  iterable
        - [ ]  map/reduce
        - [ ]  filter
        - [ ]  sort
        - [ ]  闭包
        - [ ]  箭头函数
        - [ ]  正则表达式
        - [ ]  JSON
        - [ ]  对象
        - [ ]  DOM操作
        - [ ]  AJAX
        - [ ]  promise
        - [ ]  jQuery
    
    时不时做个小demo出来，增强信心。
    
- __《JavaScript高级程序设计》__ 红宝书：**4/5/6/7/13是要重点看的，8/10/11/12/13是次重点**
    - 第一遍看的时候，**和IE有关的都先别看**。不要陷入细节，先把大体上的意思理解了。**面试题中很多问题都有答案，甚至比网络上面别人贡献出来的答案还要清晰完整。**——@carl（按carl说的来，下面的先留着）
    - 第 1~11 章讲的是**语言特性，必须掌握**；
        - 第 12、14-17 和 23-26 章是**重点内容重点看**；
        - 第 13、19 和 21 章是次**重点内容，**尽量看一下；
        - 第 28 章是最佳实践，看完前面内容后来学习如何写出更好的代码；
        - 第 18 章 Canvas、第 20 章 API、第 22 章 XML 和第 27 章工作者线程，可以在学有余力或者用到的时候看一下，不是初期重点内容。
- **《Javascript重难点实例精讲》**这本书（微信读书上有电子版），这本书把js一些核心内容捋了一遍（也是**面试经常问的基础点，而且讲得很详细**），缺点是没有讲到同步异步这块。@二丙
- [现代 JavaScript 教程](https://zh.javascript.info/)：JS 推荐从这个教程学起，这是我无意间发现的一个宝藏网站，汉化 [learn.javascript.ru](http://learn.javascript.ru/) 而来的（中文翻译的主要主要负责人是leviding，阿里前端工程师，很强），现代 JavaScript 教程是 React 官方文档中与 MDN 并列推荐的 JavaScript 学习教程，学完整个教程，相当于已经学完了所有JavaScript内容。
- JavaScript [权威指南](https://zhida.zhihu.com/search?content_id=173774696&content_type=Article&match_order=2&q=%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97&zhida_source=entity) 有用的部分
    - 这本书只读前面一些章节，主要是语法和方法部分；就是语法，表达式，语句判断，对象类型，数字类型，字符串类型，数组，函数，这些读完以后这本书的对你的学习意义就没有了
    - **JavaScript 高级程序设计：**这本书总体还是不错的，语法和方法部分也可以读下，看看和权威指南的表述区别，重点是读函数/闭包，对象，原型，原型链基础，DOM二级事件，AJAX 这些部分
    - JavaScript 权威指南这本书在函数/[闭包](https://zhida.zhihu.com/search?content_id=173774696&content_type=Article&match_order=2&q=%E9%97%AD%E5%8C%85&zhida_source=entity)和原型链继承一块写的非常的普通，而[高级程序设计](https://zhida.zhihu.com/search?content_id=173774696&content_type=Article&match_order=3&q=%E9%AB%98%E7%BA%A7%E7%A8%8B%E5%BA%8F%E8%AE%BE%E8%AE%A1&zhida_source=entity)就写的非常到位；这就是为什么两本都推荐买的原因，是推荐你有选择的进行阅读；
    - [[web前端开发需要学什么（包含前端学习路线）](https://zhuanlan.zhihu.com/p/385398678)](https://www.notion.so/web-2e4491383d3d484398548bd320d1f16f?pvs=21) 讲的很好 但是太慢了我时间不够，先打基础。

前端[学习建议](https://wx.zsxq.com/group/88511825151142/topic/585251182421154)

一些前端领域的常见**手写题**，比如**函数柯里化、防抖节流**这一类的https://github.com/mqyqingfeng/Blog：往下翻会有js手写

# 前端进阶

是这样的，前端很多很杂，框架vue,react,后续进阶还要学ts,node,webpack,vite,vue还有vue2,vue3,react也有很多版本，对于一个学生全都掌握不太现实，对于校招来说，**基本的前端三件套+vue/react选一+算法+网络是标配**，剩下的你提到的内容都是加分项，**node能让你了解后端的开发方式**，但企业中真正用node开发的还是比较少，**react+ts已经逐渐成为开发标配**，webpack我个人觉得有些难度，在公司一般也不会由没有开发经验的人来配置，中小公司问webpack配置也都是那几个通常的问题，你用过那些loader和plugin,他们的区别是什么?所以总结来说，我觉得优先级可以是**ts>webpack>node**，先把ts应用到项目中，然后尝试webpack在项目中的配置你需要知道的是这些是加分项,会的话当然更好，尤其是webpack打包优化，不会问题也不是特别的大，一个合格的候选人不是说啥都会，是符合公司的要求(当然站着公司角度,肯定优中选优)。而且我感觉这些东西的使用还是要项目驱动，也就是说自己看视频学习是很难学会的，还是要先去实习,在项目中实际操作，配置，这样成长才是更快

## ES6

学了 JavaScript 之后，可以学一学 ES6，面试貌似也经常会问到，可以看一看阮一峰写的一份入门教程：[链接](https://wangdoc.com/es6/)

二丙：但是太厚了，可能初开始没有耐心读下去，而且找不到重点，可以先看下面的视频教程或者我之前挑出来的重点

[【专题】：ES6语法 (yuque.com)](https://www.yuque.com/lijinbudaily/fckugp/aqxc6y)

https://www.bilibili.com/video/BV1w8411s7g3/?share_source=copy_web&vd_source=9bb0aa9c2c3cc1b12ca6f343a55b4e80

## TypeScript

推荐官方的Handbook，重点掌握常见的类型和泛型，以及tsconfig的常用配置（做项目的时候踩坑）。如果想进入深水区，推荐学习类型体操，掘金有神光的小册，github有type challenge这个项目可以练习。

## node.js/**Ajax和Axios**

@二丙[前端就业学习路线 (yuque.com)](https://www.yuque.com/lijinbudaily/fckugp/qq36p5m1qgm6dctv?singleDoc#hHh4u)

## Webpack&Vite

carl：[千锋陆荣涛最新前端webpack5全套教程](https://www.bilibili.com/video/BV1YU4y1g745)

这块知识不多，但是前端项目几乎都会用到，建议过一遍，对后期面试也有帮助。我当初看的是[b站李立超老师的打包工具课程](https://www.bilibili.com/video/BV1Kd4y147gg/?share_source=copy_web&vd_source=f03979ba5042fef3da938997972ca975)，同时推荐大家去看一下我在前面发的coderwhy老师的打包工具的课程，因为李立超老师的课看了一遍我感觉没过脑子...不知道是不是我看的太快，还是讲的比较浅。

## Git&GitHub

这块知识在后期做项目的时候会用来做项目记录，我当初是看了[b站李立超老师的git课程](https://www.bilibili.com/video/BV1124y117Dr/?share_source=copy_web&vd_source=f03979ba5042fef3da938997972ca975)，并且全看完了，但是记不住。建议过一遍，有所了解就可以。

# 框架

## React

> 绝对是国内最好的 React 基础教程
> 

[最新React珠峰全家桶_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV17e411r7TH/?spm_id_from=333.337.search-card.all.click&vd_source=e934f4f848019a88d6a09e29adbc4d37)

land：

[推荐新的官方文档beta.reactjs.org](http://xn--beta-pg9gx62b39cljyct27axs7bfd6a.reactjs.org/)，做一个todo app。可以了解一下函数式编程和单向数据流的理念。现在React已经全面使用函数式组件以及hooks，市面上一切类式组件的课程可以标为过时不看。React社区生态非常好，各种轮子层出不穷，建议每个方向重点掌握一个，以下是个人做项目的最佳实践：

依赖管理：pnpm / yarn
状态管理：Jotai / Recoil /原生hooks
构建工具：Vite
路由管理：React Router
UI框架：Ant Design / Material UI
SSR框架：Next.js
远程数据：React Query
样式方案：CSS Modules / Styled Components / Tailwind / Sass
前后端联调：pont
代码格式：ESLint+Prettier+lint staged+husky

## Vue

至少学会一门主流的前端开发框架（Vue / React），**并配合脚手架、组件库、工具等从 0 开始独立**搭建并开发一个完整的前端网站，可以试着仿一些知名站点。

要求**遵循企业开发规范**，将**项目代码提交到代码仓库**中，并**独立发布上线，供他人访问**。

此外，建议抓住机会参**与一些团队项**目，感受团队开发模式和前端工程化的优势。

不过对于**初学者，可以先学习 Vue**，Vue 可能更好入门一些，慕课网先快速入门看的

[入门课程直达](https://www.imooc.com/coursescore/980)

Vue 和 React 随便选一个重点学习即可，推荐 vue，不过学了 Vue 之后，有时间的话，建议可以了解下 React，快入通过视频了解，感觉几个小时或者一两天就够了。

- [尚硅谷React技术全家桶全套完整版](https://www.bilibili.com/video/BV1wy4y1D7JT)
- [千锋2022版React全家桶教程react零基础入门到项目实战完整版](https://www.bilibili.com/video/BV1dP4y1c7qd)

### Vue2

### Vue3

# 项目

先做一个

[**如何看项目源码，如何做项目**](https://t.zsxq.com/eaeubuV)

精讲：

[精讲pdf](https://wx.zsxq.com/group/88511825151142/topic/181488541258422)：项目难点、项目架构、学习资料、相关面试问题、拓展可以深挖的点，都给大家列出来了，相信对大家冲前端方向会非常有帮助。 

[前端组件库项目文档-知识星球 (zsxq.com)](https://wx.zsxq.com/group/88511825151142/topic/1522412522244522)

项目推荐：

- [尚硅谷VUE项目实战](https://www.bilibili.com/video/BV1Vf4y1T7bw)
- [vue.js项目实战](https://space.bilibili.com/13625996/channel/seriesdetail?sid=291695)
- [尚硅谷Vue.JS教程快速入门到项目实战（Vue3/VueJS技术详解）](https://www.bilibili.com/video/BV1ra4y1H7ih)

# 算法

面试的时候算法题可以用C++写嘛？
2022-11-05 11:27
辰九九 回复 OrangeRuby：如果是前端，个人建议用JS写，前端主打是JS，用c加加写可能给面试官造成对JS不熟悉的印象

[算法学习路线 (zsxq.com)](https://articles.zsxq.com/id_jjaf7ejwl7db.html)

- [代码随想录 (programmercarl.com)](https://programmercarl.com/)
- Github: https://github.com/youngyangyang04/leetcode-master
- [ACM模式练习](https://www.nowcoder.com/test/27976983/summary)

如果【代码随想录】上的题目已经刷了很多篇了，可以试试这里的新题目：

[算法新题目](https://t.zsxq.com/fqVBybA)

[javascript - 字节跳动最常考的 64 道JS算法题 - 个人文章 - SegmentFault 思否](https://segmentfault.com/a/1190000039801667)

[写给前端的算法进阶指南，零基础按分类刷200题思路 - 掘金 (juejin.cn)](https://juejin.cn/post/6847009772500156429)

# 浏览器工作原理

学前端，基本天天和浏览器打交道，因为网页上的各种界面，都是由浏览器来渲染的，所以还是非常有必要学习一下浏览器相关的知识。

如果你在浏览器按 F12，会出现一个「调试」的界面

https://article-images.zsxq.com/Fu7ViKaC4PqXcxyywOqGBEhzRg1n

里面有很多东西，例如各种网络请求数据，各种脚本数据，感兴趣的话，可以去研究研究。

那么具体要学习哪些呢？

至少得了解一下本地 cookie ，localStorage，SessionStorage 存储吧，还有就是，如何查看一个 http 的请求状态，浏览器关闭后会做哪些处理之类的。

总的来说，就是，从我们发起一个 http 请求，到页面展示如初，浏览器都经历了哪些逻辑处理？ 

这一点在这本书里**《网络是怎样连接的》**都详细讲解了。

# 计算机基础

## 计网

推荐**《网络是怎样连接的》**，当故事来看，了解更多细节。

零基础入门可以先看《图解 HTTP》 《图解 TCP/IP》。

然后可以看《计算机网络自顶向下》，这本看三遍，就很稳。

~~进阶，再看《TCP/IP详解》（选看）~~

~~《HTTP权威指南》（选看） 因为太厚了。~~

## OS

# 面经

[前端录友，总结的资料，思维导图](https://t.zsxq.com/057i6uNNf)

## 面试常见题

原型继承，跨域原理，BFC，页面性能优化，nodejs，异步编程(回调 promise)，MVC，前端自动化，响应式布局，移动端的新特性（比如让你封装个tap，解释viewport），web安全，js内存管理，前端模块化，web语义化，最新的前端流行类库。上面的名词如果看了不知道是什么的话，就要去好好加强下了

[最全的手写JS面试题- 掘金 (juejin.cn)](https://juejin.cn/post/6968713283884974088#heading-9)

[两万字三月前端面经（含回答） - 掘金 (juejin.cn)](https://juejin.cn/post/7215226343713620029#heading-81)
