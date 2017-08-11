
# 为什么写这篇 Blog
起初，是由于项目的需要，开始正式接触 dva。

dva 的开发模式不同于传统页面的开发，学习起来有一定的技术门槛。

 在 [dva](https://github.com/dvajs/dva) 的作者[sorrycc Blog](https://github.com/sorrycc/blog/issues) 里逗留了数个日夜，对新的开发模式好像是理解了，于是就迫不及待的下载了一个 demo，准备开发 CRUD。

故事情节的发展往往不会这么顺利，开发过程中发现，学会 dva 和在项目中使用 dva 进行完整开发完全是两码事：因为项目不仅仅是代码开发，还要关注项目的整体生命周期，代码规范，打包上线等等。

![初学 dva 时心里变化](https://static.oschina.net/uploads/img/201706/28145521_JbhX.png "初学 dva 时心里变化")

如果你和我一样，不能容忍在你的项目存在看不懂的东东，哪怕是一个配置文件，存在必有价值，不明白的东东就该 ~~DELETE~~ 掉，那么来到这里就对了，本文就是对 dva 做一次“大手术”，肢解它的技术组成，掌握项目中的 dva。

学习的过程中，难免会花费很多时间去查阅资料，有时候整篇英文文档看的让人直抓狂，本文总结作者在学习过程中看到的一些好的技术 Blog，贴上相关技术比较友好的 API 文档，帮助各位节约时间。


# 项目中的 dva
![项目中的 dva](https://static.oschina.net/uploads/img/201706/28150817_mtXq.png "项目中的 dva")

# 开发环境
- npm@3.10.10
- dva@0.7.8
- antd@2.11.1

# 目录
- 初识 dva
    - [dva 简介](https://github.com/dkvirus/dva/blob/master/doc/dva/dva%20%E7%AE%80%E4%BB%8B.md)
    - [创建一个 dva 脚手架工程](https://github.com/dkvirus/dva/blob/master/doc/dva/%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AA%20dva%20%E8%84%9A%E6%89%8B%E6%9E%B6%E5%B7%A5%E7%A8%8B.md)
    - [脚手架目录分析](https://github.com/dkvirus/dva/blob/master/doc/dva/dva%20%E8%84%9A%E6%89%8B%E6%9E%B6%E7%9B%AE%E5%BD%95%E5%88%86%E6%9E%90.md)
- 语言基础
    - ES6
    - React
- 工具
    - [包管理工具 Npm](https://github.com/dkvirus/dva/blob/master/doc/npm/npm%20%E7%9B%AE%E5%BD%95.md)	    
    - [版本控制工具 Git](https://github.com/dkvirus/dva/blob/master/doc/git/0%20%E7%9B%AE%E5%BD%95.md)
    - 开发工具 Webstorm
    - 项目启动打包工具 Roadhog
    - [代码格式化工具 ESLint](https://github.com/dkvirus/dva/blob/master/doc/eslint/Eslint%20%E8%B6%85%E7%AE%80%E5%8D%95%E5%85%A5%E9%97%A8%E6%95%99%E7%A8%8B.md)
    - 前后台接口规范工具 Swagger
    - es6 编译工具 Babel
    - 模拟后台提供接口工具 json-server
- 核心技术
    - react-router
    - react-redux
    - axios
    - antd






