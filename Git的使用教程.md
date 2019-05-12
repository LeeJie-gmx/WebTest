# Git的使用教程

### 一、Git是什么

Git 与CVS、Subversion一类的集中式版本控制工具不同，它采用了分布式版本库的做法，不需要服务器端软件，就可以运作版本控制，使得源代码的发布和交流极其方便。Git的速度很快，这对于诸如Linux内核这样的大项目来说自然很重要，Git最为出色的是它的合并追踪（merge tracing）能力。

### 二、Git的配置

Git官网下载地址：

Git完成默认配置安装后，在桌面点击鼠标右键，会有两个选项

Git GUI Here 代表图形界面模式

Git Bash Here 代表命令行模式

![鼠标右键](https://upload-images.jianshu.io/upload_images/2552605-f67487a7e0461799?imageMogr2/auto-orient/strip%7CimageView2/2/w/430)

这里选择命令行模式

![命令行模式](https://upload-images.jianshu.io/upload_images/2552605-4850bae68858d20e?imageMogr2/auto-orient/strip%7CimageView2/2/w/595)

之后先设置你的用户名和email地址作为个人标示，这是非常重要的，因为每次Git提交都需要使用该信息

config --global user.name "用户名"

config --global user.email "邮箱地址"

--global选项代表Git将使用该信息来处理你在系统中所做的一切操作，如果希望在一个特定的项目下使用不同的用户名或email地址，可以在该项目中运行该命令二不用--global选项

![配置](https://upload-images.jianshu.io/upload_images/2552605-c7dbbac5cafce8f2?imageMogr2/auto-orient/strip%7CimageView2/2/w/595)

配置完成后可以用以下命令查看个人信息

cat ~/.gitconfig

![查看个人信息](https://upload-images.jianshu.io/upload_images/2552605-3ea24abc85ee707d?imageMogr2/auto-orient/strip%7CimageView2/2/w/595)

