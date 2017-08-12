
## 一、下载安装包

[Webstorm 2017.1.4 百度云盘下载地址](http://pan.baidu.com/s/1kVqoPJh)

## 二、安装过程（包含输入注册码永久使用）

双击下一步下一步即可，过程中有几个步骤说明一下：

### 1. 配置 Webstorm 安装项

选择 64 位，防止桌面 Webstorm 快捷方式打不开。

![配置 Webstorm 安装项](/assets/install1.png)

### 2. 是否导入 Webstorm 配置信息

这里的意思是之前使用过 Webstorm ，并且配置过，Webstorm 配置信息可以起到优化性能的作用，因为它本身是个比较吃内存的东西，文件多了容易卡顿，可以通过在配置文件中得到优化，后面单独介绍优化。

剧透：Webstorm 安装完成后配置信息位置：`C:\Users\Administrator\.WebStorm2017.1`。

![是否导入 Webstorm 配置信息](/assets/install2.png)

### 3. 激活 Webstorm

免费版的试用期是 30 天，30 天之后各种让人不舒服，比如不能保存，每隔30分钟自动关闭程序等等，所以在开始的时候还是激活成功使用永久版本的比较好。

要填的内容：`http://idea.imsxm.com/`，复制进去即可。

![激活 Webstorm](/assets/install3.png)

### 4. 设置 Webstorm 工具的主题和风格

这里暂时写保持默认设置，后面会单独介绍如何折腾一个独一无二的属于个人审美的 Webstorm 工具。

![设置 Webstorm 工具的主题和风格](/assets/install4.png)

## 三、使用心得

> 关于 Webstorm 大多数配置都在 `File -> Settings` 选项卡中进行的，也许你不得不第一个记住它的快捷键：`Ctrl + Alt + S`。

### 1. 设置开发工具主题/风格

File -> settings -> Editor -> colors&fonts -> scheme name. 

跟人觉得 `Default  Darcula` 这两款主题还可以，如果内置主题都不喜欢，可以去 [主题下载地址](http://phpstorm-themes.com/) 寻找你中意的主题。

### 2. 换成自己熟悉编辑器的快键键：如 Eclipse 的快捷键 + 自定义快捷键组合

![快捷键设置](/assets/keymap.png)

### 3. 集成 Eslint

集成 Eslint 的前提是你的项目里使用了 Eslint。

![集成 Eslint](/assets/jichengeslint.png)

### 4. 取消勾选安全保存时间

这两项取消勾选，否则影响热更新，不能及时将修改的内容反应在浏览器上。

![取消勾选安全保存时间](/assets/regengxin.png)

### 5. 常用开发工具窗口

开发过程中，最常用的工具窗口有以下几个：

- Project 记录项目的层级结构；（快捷键 Alt + 1）
- Structure  记录当前文件内部的层级结构，方便快速定位到某个方法；（快捷键 Alt + 7）
- Npm 使用 npm 构建的工程，Npm 窗口会记录 package.json 里的脚本信息，一般用于快速启动项目；快捷键 （Ctrl + E）
- TODO 项目中难免会预留 TODO 标记用于日后完善，该窗口可以快速定位到哪个文件的哪一行预留了 TODO 标记。（快捷键 Alt + 6）

![常用开发工具窗口](/assets/gongjuchuangkou.png)

## 6. 快捷键 —— 最常用的快捷键最佳应在 10 个以内


- `Ctrl + Shift + R` —— 快速定位到文件并跳转

- `Ctrl + E` —— 打开最近操作过的文件

- `Ctrl + Alt + L` —— 格式化代码（与 QQ 快捷键冲突，自定修改 QQ 快捷键）

- `Ctrl + Y` —— 删除光标所在行

- `Ctrl + Alt + S` —— 打开设置窗口