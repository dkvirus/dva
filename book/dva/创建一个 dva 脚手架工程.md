# 1.2 创建一个 dva 脚手架工程
使用 dva-cli 命令行工具安装 dva。（本文假设已掌握 npm 基础知识）

## 安装 dva-cli 
- **dva-cli 是什么**
    
    dva-cli 是命令行工具，使用 npm 进行安装，用处是通过命令行很方便的创建一个 dva 脚手架工程。
    
- **安装 dva-cli**
  
      $ npm install dva-cli -g            // 全局安装 dva-cli
    
- **查看 dva-cli 版本**
 
       $ dva -v        // 要求最低版本 0.7.0
    
## 创建dva脚手架

现在要在 d 盘根目录下创建一个 dva 脚手架工程 dva-demo。（下面操作都是在命令行中完成的）

- **第一步：切换到 d 盘**
    
        $ cd d:
    
- **第二步：使用 dva new 指令创建工程**
        
        $ dva new dva-demo

- **第三步：等待....**

    这个过程需要下载 dva 的目录结构，这个很快；
    
    还需要 npm install 目录结构中 package.json 中的包，这很费时间；
    
    最终出现下图所示标识 dva 安装成功了！！
    
    ![dva 安装成功标识](https://static.oschina.net/uploads/img/201706/28170406_zJSn.png "dva 安装成功标识")
    
## 测试是否安装成功
- **切换到刚创建的 dva-demo 目录下**

        $ cd dva-demo
    
- **启动服务**

        $ npm start

- **自动弹出欢迎页面**

    过几秒后会自动弹出浏览器，显示欢迎页面就说明安装成功了
![dva欢迎页面](https://static.oschina.net/uploads/img/201706/28171022_ezDW.png "dva欢迎页面")
    
## 到此为止
到此为止，你已经成功的创建了一个 dva 工程，并且切切实实的看到了它的互动（欢迎页面里的那只小丑）。但是你不满足于认识它，还想要深入浅出的掌握它，用它来简化你的开发，提高你的效率，节约下来时间去走一场说走就走的旅行。

****别着急**，接着往下看。**
