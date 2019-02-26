# 将你的代码上传到GitHub上面

![](/Users/jokerhook/Downloads/ludovic-charlet-1131593-unsplash.jpg)

掌握和精通git是每一个工程师必备的能力，但是对于新手，在初次使用GitHub的时候往往非常迷茫。

## 创建你的项目

---

首先我们需要准备好你的GitHub账号，没有的可以去注册一个，注册以后登录你的账号，进入GitHub。进入后界面如下：

![GitHub界面](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.11.52.png)

接着我们要开始创建你的第一个项目啦～～

点击右上角的**加号**，选择**New repository**后就会出现一个新建项目的界面，填写相关信息之后，点击**Create repository**：

![新建项目的界面](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.19.14.png)

点击之后你就会看到你新创建的工程啦。

![新创建的工程](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.20.37.png)



## 在Xcode里面开始进行你的项目

---

现在你的GitHub上面有了这个工程，你要怎么样才能在自己的Mac上面开发呢？

点开你的工程找到**Clone or download**，点击这个按钮，复制出现的**Http**链接：

![复制链接](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.39.11.png)

回到你的MacBook，打开终端，使用**cd**命令来到你想开发项目的地方，输入

```swift
git clone + 刚刚复制的链接
```

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.44.30.png)

静静等待片刻就可以了。接着，你就会在那个地方看到你刚刚创建的工程项目。

打开**Xocde**，新建一个项目：

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.46.39.png)

保存的时候记得保存在你刚刚创建的项目里面：

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 14.47.47.png)

接着你就可以在Xcode里面进行开发了。

## 将项目上传到GitHub上面

---

打开[GitHub Desktop](https://desktop.github.com)，没有的朋友先去下载。

选择**File -> Add local  repository**, 选择你工程的路径，打开即可：

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 15.00.40.png)

接着你就会看到你自己的项目在里面。

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 15.04.31.png)

填写左下方的**Summary**，作为项目的总结，**Description** 可写可不写，接着点击**Commit to master**。

接着你就会看到**Push origin**，点击该按钮。

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 15.09.54.png)

再回到网页的GitHub，你将会看到你的工程项目已经上传到上面了。

![](/Users/jokerhook/Desktop/屏幕快照 2019-02-25 15.10.46.png)

