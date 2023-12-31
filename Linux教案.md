# 第一章 环境搭建

## 一、工具介绍

### 1.1 虚拟机软件

#### 1.1.1 获取软件

>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\01_VMware16.0.zip`
>
>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\01_VMware17.0.zip`

安装那个都可以，但是如果是安装的16版本，出现了系统不兼容的问题，则可以卸载16安装17版本。

#### 1.1.2 软件安装

>   资料位置：`\【Linux基础】_06_给学生的资料\01_Linux资料\VMware16.0安装教程.pdf`
>
>   资料位置：`\【Linux基础】_06_给学生的资料\01_Linux资料\VMware17.0安装教程.pdf`

可以根据我们资料中所提供的pdf文档，进行安装。

#### 1.1.3 软件介绍



### 1.2 Linux操作系统 - Ubuntu

#### 1.2.1 获取系统

>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\03_ubuntu1604x64.rar`
>
>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\04_ubuntu-18.04.1-desktop-amd64.iso`

两个都需要进行下载，第一个是我们已经配置好的Linux系统，可以直接使用的，第二个是未进行配置的系统



#### 1.3 Xshell&Xftp

#### 1.3.1 获取软件

>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\05_Xshell7.zip`
>
>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\06_Xftp7.zip`

#### 1.3.2 软件介绍 - Xshell

![image-20231231105938740](./img/image-20231231105938740.png)

Xshell是一款远程ssh登录Linux的软件，在日常的开发中，我们很多时候是服务器 + 本地主机的方式，也就是说，我们通过本地主机链接到远程服务器上进行开发，不会说直接在服务器机房进行开发，有的时候甚至服务器在北京，我们在长沙进行开发。

<img src="./img/image-20231231105810520.png" alt="image-20231231105810520" style="zoom: 50%;" />



我们的Xshell软件就可以实现远程登录的功能，效果如下，当我们配置完成后，就可以看到我们的xshell链接到了Linux系统



![image-20231231113003484](./img/image-20231231113003484.png)



### 1.3.2 软件介绍 - Xftp

![image-20231231113135231](./img/image-20231231113135231.png)

xftp是基于ftp协议的远程文件传输协议，当我们在需要进行服务器和本机文件交互的的时候，就可以使用xftp软件，进行远程的软件交互

链接后的效果如下，我们可以随意的进行Linux和windows的文件传输

![image-20231231113249996](./img/image-20231231113249996.png)

### 1.4 VsCode

![image-20231231115346357](./img/image-20231231115346357.png)

### 1.4.1 获取软件

>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\07_VSCodeUserSetup-x64-1.85.1.exe`
>
>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\08_code_1.85.1-1702462158_amd64.deb`

第一个是windows版本的，第二个是Linux版本的，我们可以只安装Windows版本的



### 1.4.2 软件介绍

VScode全称是Visual Studio Code，是微软推出的一个跨平台的编辑器，能够在windows、Linux、IOS等平台上运行，通过安装一些插件可以让这个编辑器变成一个编译器。 VSCode支持C++、Python、Java、C#、Go等多种语言，功能强大、插件丰富并且启动速度极快，值得每个开发人员尝试一把！



>   vscode是我们后续开发的主力ide工具之一，很多的内容都需要使用到vscode



![image-20231231115507129](./img/image-20231231115507129.png)





### 1.5 辅助工具

### 1.5.1 软件获取

>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\09_YoudaoDict_dict_web_product.exe`
>
>   软件位置：`\【Linux基础】_06_给学生的资料\00_软件&系统\10_有道云笔记-7.2.161.exe`



第一个是翻译用的软件，我们在开发过程中很多使用会需要看英文文档，这个软件可以帮助我们进行截图翻译

第二个软件是笔记软件，我们每天的所学各位都需要进行记笔记，并提交到在线表格中去

### 1.6 Git



## 二、系统配置

### 1.2 系统配置 - Linux安装与配置

#### 1.2.1 VMware 虚拟机软件安装

>    这里是 以 vmware16.0 为例

1、解压【vmware16.0】

![解压vm](./img/解压vm-1703996881169-1.png)

2、打开解压后的文件夹，鼠标右击【VMware-workstation-full-15.5.0-14665864】选择【以管理员身份运行】。

![运行vm](./img/运行vm-1703996881179-2.png)

3、点击【下一步】。

![安装vm01](./img/安装vm01-1703996881179-7.png)

4.勾选【我接受许可协议中的条款】，点击【下一步】。

![安装vm02](./img/安装vm02-1703996881179-3.png)

5、点击【更改…】可更改安装位置（建议不要安装在C盘，可以在D盘或其它磁盘下新建一个“VM”文件夹），点击【下一步】。

![安装vm03](./img/安装vm03-1703996881179-4.png)

6、取消勾选【启动时检查……】和【加入VMware……】，点击【下一步】。

![安装vm04](./img/安装vm04-1703996881179-5.png)

7、点击【下一步】。

![安装vm05](./img/安装vm05-1703996881179-6.png)

8、点击【安装】。

![安装vm06.](./img/安装vm06-1703996881179-9.png)

9、等待安装完成

![安装vm078](./img/安装vm07-1703996881179-8.png)

10、点击许可证

![安装vm10](./img/安装vm10-1703996881179-10.png)

11、打开

![安装vm11](./img/安装vm11-1703996881179-12.png)

12、复制其中一个到密钥中，然后点击输入，最后点击完成，到此你的vmware16.0就安装完成了

![安装vm12](./img/安装vm12-1703996881179-11.png)



#### 1.2.2 Linux系统安装

 系统版本为： **ubuntu-16.04.7-desktop-amd64.iso**

1、点击【创建新的虚拟机】，选择【典型】，点击【下一步】。

![安装Linux01](./img/安装Linux01-1703997035822-25.png)

2、选择【稍后安装操作系统】，点击【下一步】。

![安装Linux02](./img/安装Linux02-1703997035823-26.png)

3、操作系统选择【Linux】，版本选择【ubuntu 64位】，点击【下一步】。

![安装Linux03](./img/安装Linux03-1703997035823-27.png)

4、点击【浏览】可更改安装位置（建议不要安装在C盘，可以在D盘或其它磁盘下新建一个“ubuntu”文件夹），点击【下一步】。

![安装Linux04](./img/安装Linux04-1703997035823-28.png)

5、磁盘大小选择20G以上，点击【下一步】。

![安装Linux05](./img/安装Linux05-1703997035823-29.png)

6、点击【自定义硬件】，点击【内存】，设置为【2048MB】。

![安装Linux06](./img/安装Linux06-1703997035823-30.png)

7、选择【新CD/DVD(SATA)】，选择【使用ISO镜像文件】，点击【浏览】。

![安装Linux07](./img/安装Linux07-1703997035823-31.png)

8、选中【USB控制器】,点击【移除】，然后选中【打印机】,点击【移除】，点击【关闭】。

![image-20230723211131111](./img/安装Linux07-1703997035823-31.png)

9、选中【网络适配器】,点击【桥接模式】

![安装Linux08](./img/安装Linux08-1703997035823-33.png)

10、点击【完成】。

![安装Linux09](./img/安装Linux09-1703997035823-32.png)

11、点击【开启此虚拟机】。

![安装Linux10](./img/安装Linux10-1703997035823-34.png)

12、选择【中文(简体)】，点击【安装Ubuntu】。



![安装Linux11](./img/安装Linux11-1703997035823-35.png)

13、直接【继续】

![安装Linux12](./img/安装Linux12-1703997035823-36.png)

14、点击【现在安装】

![安装Linux13](./img/安装Linux13-1703997035823-37.png)



15、点击【继续】。

![安装Linux14](./img/安装Linux14-1703997035823-38.png)



16、点击【继续】。

![安装Linux15](./img/安装Linux15-1703997035823-39.png)

17、点击【继续】。

![安装Linux16](./img/安装Linux16-1703997035823-40.png)

18、输入【姓名、密码】，点击【继续】。

![安装Linux17](./img/安装Linux17-1703997035823-41.png)

19、点击【现在重启】。

![安装Linux18](./img/安装Linux18-1703997035823-42.png)



然后输入密码登录即可，到这里你的Linux系统安装完成





#### 1.2.3 Linux系统配置

>我们很多的设置都是在终端上进行的，所以我们首先需要掌握如何打开终端，通过键盘上的`ctrl + Alt + t` 就可以唤醒我们的终端界面了。

##### 1 设置系统分辨率

当我们打开系统后，会发现我们的Linux系统显示并不完整，所以我们需要设置一下分别率

```shell
# 输入 xrandr查看设备的分辨率
$ xrandr
# 输入 xrandr -s [分辨率]
$ xrandr -s [分辨率]
```

![image-20231231133028933](./img/image-20231231133028933.png)

##### 2 设置root密码 

root是我们Linux的超级用户，相当于我们在使用Windows电脑的管理员权限，这个用户权限很大，各位在使用的过程中一定要注意。

```shell
# 进入终端，修改密码
$ sudo passwd
# 切换成root 用户
$ su - root
```

![image-20231231133231880](./img/image-20231231133231880.png)



##### 3 更换 apt 软件源地址

Linux是可以通过命令行直接进行软件的下载与安装的，但是由于国内网络的问题，我们需要使用国内的一些镜像源才可以进行顺利的软件安装与下载。

在进行下面的操作之前，建议先把原有的软件源进行一下复制，防止后续操作中出现问题，使用下面这条命令

```shell
cp /etc/apt/sources.list /etc/apt/sources_copy.list 
```



###### ① 需要将`/etc/apt/sources.list` 文件打开并删除内部的内容

```shell
$ sudo vim /etc/apt/sources.list
```

![image-20231231135723458](./img/image-20231231135723458.png)



###### ② 清除原有的源

输入 `100dd` 用于清除所有源

![image-20231231140040568](./img/image-20231231140040568.png)



###### ③ 复制源到文件内部

```sh
# 默认注释了源码镜像以提高 apt update 速度，如有需要可自行取消注释
deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
# deb-src http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal main restricted universe multiverse
deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
# deb-src http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-updates main restricted universe multiverse
deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
# deb-src http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-backports main restricted universe multiverse
deb http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
# deb-src http://mirrors.tuna.tsinghua.edu.cn/ubuntu/ focal-security main restricted universe multiverse
```

点击键盘上的`i`进入到插入模式，然后拷贝到文件内部



![image-20231231145415070](./img/image-20231231145415070.png)

当然也可以使用下面的这个清华大学的源

>   清华大学源 ： [ubuntu | 镜像站使用帮助 | 清华大学开源软件镜像站 | Tsinghua Open Source Mirror](https://mirrors.tuna.tsinghua.edu.cn/help/ubuntu/)
>
>   需要注意的是，在这个网站内选择源需要自己选择一下系统版本一定要对应才行



###### ④ 更新镜像源

```shell
$ sudo  apt  update
```

更新中

![image-20231231145702029](./img/image-20231231145702029.png)



更新完成

![image-20231231145717004](./img/image-20231231145717004.png)



当然，我这个是更新了一次的，所以这个内容比较短。

#### 1.2.3 Linux软件安装

更新完成软件源后，我们就可以开始进行软件的安装了，我们很多的软件进行安装都是在终端命令行下进行操作的。

##### 1 安装ssh服务器

一般Ubuntu都会默认安装openssh-client,但是没有安装openssh-server。

```sh
$ sudo apt install openssh-server
```

一般来说，安装完成之后就已经启动了，我们可以通过下面的这条指令进行查看

```sh
& sudo systemctl status ssh
```



>   **如何连接ssh服务器**
>
>   在Windows中 使用 ` ssh username@ip`的方式进行链接到我们的Linux服务器

##### 2 安装VIM编辑器

```sh
$ sudo apr install vim
```

##### 3 安装tftp服务器







#### 1.2.3 Linux网络配置



### 1.2 系统配置 - 懒人版

# 第二章 Linux系统介绍

## 一、操作系统的基本概念

## 二、操作系统的主要组成

## 三、嵌入式操作系统

# 第三章 Linux操作系统基本操作

## 一、Linux基本操作

## 二、shell命令

## 三、Linux基础命令

# 第四章 Linux-文件管理

# 第五章 Linux-用户管理

# 第六章 Linux-软件管理

# 第七章 Linux-网络管理

# 第八章 Linux编程环境搭建

## 一、Git工具

<img src="./img/Git-Logo-1280x800.png" alt="Git for Data Science Applications (A Top Skill for 2020) | R-bloggers" style="zoom:33%;" />

### 1.1 版本控制

#### 1.1.1 版本控制



#### 1.1.2 常见的版本控制工具

>   Git
>
>   SVN（Subversion）
>
>   CVS（Concurrent Versions System）
>
>   VSS（Micorosoft Visual SourceSafe）
>
>   TFS（Team Foundation Server）

### 1.2 Git安装

#### 1.2.1 资料获取

>   官网资料：[Git - Downloading Package (git-scm.com)](https://git-scm.com/download/win)
>
>   本地资料：`【Linux基础】_06_给学生的资料\00_软件&系统`

#### 1.2.2 官网下载

![image-20231229174921256](./img/image-20231229174921256.png)

#### 1.2.3 Git安装

>   直接下一步就好了，没那么复杂，别想那么多



### 1.3 git的配置

#### 1.3.1 查看配置文件

我们这里给大家介绍几个命令，用于查看git的相关配置

```shell
# 查看git配置
git config -l
# 查看系统配置
git config --system --list
# 查看本地配置
git config --global --list
```

#### 1.3.2 git相关的配置文件

我们可以通过下面的路径，去找到我们的配置文件，这里主要是要让大家知道，我们在终端中所看到的内容，都是从系统中各个文件所看到的，也就是说如果我们要去修改，可以通过命令也可以直接修改其文件，对我们的git 进行配置。

```shell
\Git\etc\gitconfig    系统级配置文件  git config --system --list
```

<img src="./img/image-20231229155100110.png" alt="image-20231229155100110" style="zoom:50%;" />



```shell
C:\Users\tanzh\.gitconfig  用户级配置文件			git config --global --list
```

这里的位置是在用户目录下面，在其下面找到.gitconfig，这个文件是一个隐藏文件。

<img src="./img/7e4b51daae30a7f25eafdb92e2fbee6.png" alt="7e4b51daae30a7f25eafdb92e2fbee6" style="zoom:67%;" />

#### 1.3.3git配置用户文件

==设置== ==用户名&邮箱==



在前面，我们已经理解了从什么地方去找我们的配置文件，现在我们需要将我们的`用户名`以及`邮箱` 配置到我们的文件内部，这里尽量使用我们的真实邮箱。

```shell
# 设置用户名
git config --global user.name tan.zhipeng
# 设置邮箱
git config --global user.email tan.zhipeng@outlook.com
```

### 1.4 git基础理论

#### 1.4.1 工作区域

我们所使用的git 是区分了4个工作区域，其中，3个工作区域在本地，即`工作区` 、 `暂存区`、`本地仓库`这三个，此外还有一个`远程仓库`，他们之间的关系如下：

<img src="./img/git-command.jpg" alt="img" style="zoom:200%;" />

-   workspace：工作区
-   staging area：暂存区/缓存区
-   local repository：版本库或本地仓库
-   remote repository：远程仓库

```
【工作区】：workspace 项目文件所在地，即平时存放代码的地方
【暂存区】：index 用于存放临时的改动，其本质上是一个文件，保存即将要提交的列表信息
【本地仓库】：Repository 就是安全存放数据的位置，这里面有你提交到所有版本的数据。其中HEAD指向最新放入仓库的版本
【远程仓库】：Remote 远程仓库是代码托管平台，也就是我们存放代码的分布式服务器，比较有名的有github 、 gitee
```

在我们的工程目录下面，当我们使用了git 后，会出现一个`HEAD`文件

#### 1.4.2 工作流程

Git的工作流程一般如下：

>   1、在工作区中编写代码、文件。
>
>   2、将需要进行版本控制的文件导入到暂存区 index 
>
>   3、将暂存区的文件提交到 本地仓库



基于我们的工作流程，让我们的Git衍生了三种状态 

-   已修改（modified）
-   已缓存（staged）
-   已提交（committed）



### 1.5 Git项目搭建

<img src="./img/git-command.jpg" alt="img" style="zoom:200%;" />

#### 1.5.1 Git项目创建



当我们需要在当前目录下面去创建一个新的目录的时候，我们可以使用下面的目录进行创建

```shell
# 使用指令创建git 工程
$ git init
```

当我们执行完成本命令后，我们的工程目录下面就会多出一个.git的文件夹

#### 1.5.2 Git项目克隆

此外，除了上面的那种直接创建项目，我们也可以在目录中克隆别人的项目，也就是将远程服务器上的项目完整的镜像到本地。

```shell
# 使用指令克隆指定的url 的项目
$ git clone [url]
```

### 1.6 Git文件操作

#### 1.6.1 文件的四种状态

版本控制就是对文件的版本控制，要对文件进行修改、提交等操作，首先要知道文件当前在什么状态，不然可能会提交了现在还不想提交的文件，或者要提交的文件没提交上。

>   **未跟踪** (Untracked): 此文件在文件夹中, 但并没有加入到git库, 不参与版本控制. 通过git add 状态变为Staged.



>   **文件已经入库 ** (Unmodify): 文件入库但是未修改, 即版本库中的文件快照内容与文件夹中完全一致. 这种类型的文件有两种去处, 如果它被修改, 而变为Modified. 如果使用git rm移出版本库, 则成为Untracked文件



>   **文件已修改** (Modified): 文件已修改, 仅仅是修改, 并没有进行其他的操作. 这个文件也有两个去处, 通过git add可进入暂存staged状态, 使用git checkout 则丢弃修改过, 返回到unmodify状态, 这个git checkout即从库中取出文件, 覆盖当前修改 !



>   **暂存状态**  (Staged): . 执行git commit则将修改同步到库中, 这时库中的文件和本地文件又变为一致, 文件为Unmodify状态. 执行git reset HEAD filename取消暂存, 文件状态为Modified

#### 1.6.2 查看文件状态

使用命令进行查看文件的状态

```shell
#查看所有文件状态
$ git status
# 添加所有文件到暂存区
$ git add
# 提交暂存区中的内容到本地仓库
$ git commit
```

使用流程

```shell
# 首先使用git status 查看所有文件的状态
$ git status  				# 查看所有文件状态
$ git status [filename] 	# 查看指定文件状态

# 再使用git add 将文件添加到缓存区
$ git add . 				# 将所有文件添加到缓存区
$ git add [filename]		# 将指定文件添加到缓存器

# 当你使用git add 添加到缓存区后 可以使用 git status 命令去查看一下文件是否添加成功
$ git status 

# 成功完成这一步后，就可以将缓存区中的文件导入到本地仓库 命令 ：git commit 
$ git commit 				# 直接推送到本地仓库
$ git commit -m "加备注"	  # 对我们本次的推送加上注释
```

### 1.7 远程仓库— 以码云（gitee）为例

>   由于我们的github访问速度不佳，所以我们本次教学不使用gitee
>
>   当然你也可以自己去搭建一个自己的git仓库， 在你的远程Linux主机上部署gitlab 就可以了

#### 1.7.1 注册码云

>   网址：[Gitee - 基于 Git 的代码托管和研发协作平台](https://gitee.com/)

自己注册账号并完善账号信息

在以后你们找工作可以将我们的项目写到你们的简历上

#### 1.7.2 设置本机绑定SSH公钥，实现免密码登录

当你注册完成后，就可以生成一下你本机的SSH公钥，将这个公钥配置给`gitee`或者`github`，这样在后续的推送中就可以免密码登录了。

1.   在Git中输入ssh-keygne，生成本机的ssh密钥

```shell
# 生成ssh密钥指令     | 下面的指令使用一个人即可
#	单纯的生成ssh密钥
$ ssh-keygne
# 	生成ssh密钥并通过-t rsa 添加  rsa加密算法
$ ssh-keygne -t rsa
```

2.   当你使用完上面的指令后，在C盘的用户目录下面有一个`.ssh`的目录，当你使用了这个指令后，会就生成两个文件

![image-20231230184010499](./img/image-20231230184010499.png)



3.   打开gitee ，点击你的头像，然后点击设置

<img src="./img/image-20231230184135021.png" alt="image-20231230184135021" style="zoom: 50%;" />



4.   点击SSH公钥 ， 后面就是输入密码后就添加完成了

![image-20231230184347722](./img/image-20231230184347722.png)

5.   后面就可以在仓库中去新建仓库了

#### 1.7.3 新建远程仓库



### 1.8 本地代码推送到gitee和github

#### 1.8.1 新建本地仓库

1.   在本地文件夹内，右键点击Git Bash，打开git的命令行窗口
2.   在命令行窗口中 输入 git init 用于初始化

```shell
$ git init	
```

运行完该命令后，会在你的文件夹内生成一个.git的隐藏文件

>   注意：.git文件是隐藏文件，如果看不到就可以根据下图操作打开显示隐藏文件
>
>   ![image-20231230194030177](./img/image-20231230194030177.png)

#### 1.8.2 链接远程仓库 - gitee

1.   复制新建的远程仓库地址

![image-20231230193602537](./img/image-20231230193602537.png)

2.   在git中输入下面的命令，进行与远程仓库的链接

```shell
# 这里的url 就是你远程仓库的地址，进行替换即可
$ git remote add origin [url] 
```

3.   更新本地仓库

```shell
# git pull origin master 是拉取远程仓库中master分支的代码到当前本地分支上
# origin	是远程名
# master	是远程仓库中的一个分支
$ git pull origin master
```

#### 1.8.3 将本地内容推送到远程 - gitee

1.   本地文件上传到缓存区

```shell
# 上传所有文件
$ git add .
# 上传指定文件
$ git add [文件名]
```

2.   提交文件并添加注释

```sh
# "" 中为注释内容
$ git commit -m "注释"
```

3.   将本地内容推送到远程

```sh
$ git push origin master
```

>   完成上面的操作，基本就对推送到远程这个事情就已经做完了， 我们可以去gitee中刷新一下，然后就可以看到我们的文件了

#### 1.8.4 链接远程仓库 - github

1.   查看当前远程仓库的设置

```sh
$ git remote -v
```

在这里会显示你的本地仓库，此时我们已经对gitee 进行远程链接了，所以我们就可以看到这些内容

```
origin-gitee <gitee仓库地址> (fetch)
origin-gitee <gitee仓库地址> (push)
```

2.   将新建好的github链接到本地仓库

```sh
$ git remote add origin-github <github仓库地址>
```

#### 1.8.5 将本地内容推送到远程 - github

1.   本地文件上传到缓存区

```shell
# 上传所有文件
$ git add .
# 上传指定文件
$ git add [文件名]
```

2.   提交文件并添加注释

```sh
# "" 中为注释内容
$ git commit -m "注释"
```

3.   将本地内容推送到远程

```sh
$ git push origin-github master
```

### 1.9 git的分支

分支在GIT中相对较难，分支就是科幻电影里面的平行宇宙，如果两个平行宇宙互不干扰，那对现在的你也没啥影响。不过，在某个时间点，两个平行宇宙合并了，我们就需要处理一些问题了！

![image-20231230200909182](./img/image-20231230200909182.png)

#### 1.9.1 git分支相关命令

```sh

# 列出所有本地分支
git branch

# 列出所有远程分支
git branch -r

# 新建一个分支，但依然停留在当前分支
git branch [branch-name]

# 新建一个分支，并切换到该分支
git checkout -b [branch]

# 切换分支
git checkout [branch]
git switch [branch]

# 合并指定分支到当前分支
$ git merge [branch]

# 删除分支
$ git branch -d [branch-name]

# 删除远程分支
$ git push origin --delete [branch-name]
$ git branch -dr [remote/branch]
```

>   master主分支应该非常稳定，用来发布新版本，一般情况下不允许在上面工作，工作一般情况下在新建的dev分支上工作，工作完后，比如上要发布，或者说dev分支代码稳定后可以合并到主分支master上来。





## 二、VIM 工具

<img src="./img/vim-logo-png.png" alt="vim logo png 10 free Cliparts | Download images on Clipground 2023" style="zoom: 15%;" />

### 2.1 VIM安装

1.   在终端中输入下面的指令进行安装

```shell
$ sudo apt install vim
```



### 2.2 VIM 的介绍

在vim中分为了三种模式，分别是 **命令模式**，**输入模式** ， **底行模式** 

#### 2.2.1 命令行模式

**用户刚刚启动 vi/vim，便进入了命令模式。**

此状态下敲击键盘动作会被 Vim 识别为命令，而非输入字符，比如我们此时按下 **i**，并不会输入一个字符，**i** 被当作了一个命令。



>   以下是普通模式常用的几个命令：
>
>   |     命令      |                   功能描述                   |
>   | :-----------: | :------------------------------------------: |
>   |     **i**     | 切换到输入模式，在光标当前位置开始输入文本。 |
>   |     **x**     |          删除当前光标所在处的字符。          |
>   |     **:**     |  切换到底线命令模式，以在最底一行输入命令。  |
>   |     **a**     | 进入插入模式，在光标下一个位置开始输入文本。 |
>   |     **o**     | 在当前行的下方插入一个新行，并进入插入模式。 |
>   |     **O**     | 在当前行的上方插入一个新行，并进入插入模式。 |
>   |    **dd**     |                 删除当前行。                 |
>   |    **yy**     |                 复制当前行。                 |
>   | **p**（小写） |          粘贴剪贴板内容到光标下方。          |
>   | **P**（大写） |          粘贴剪贴板内容到光标上方。          |
>   |     **u**     |               撤销上一次操作。               |
>   | **Ctrl + r**  |            重做上一次撤销的操作。            |
>   |    **:w**     |                  保存文件。                  |
>   |    **:q**     |              退出 Vim 编辑器。               |
>   |    **:q!**    |      强制退出 Vim 编辑器，不保存修改。       |
>
>   
>
>   若想要编辑文本，只需要启动 Vim，进入了命令模式，按下 **i** 切换到输入模式即可。
>
>   命令模式只有一些最基本的命令，因此仍要依靠**底线命令行模式**输入更多命令。

#### 2.2.2 输入模式

>   在命令模式下按下 **i** 就进入了输入模式，使用 **Esc** 键可以返回到普通模式。
>
>   在输入模式中，可以使用以下按键：
>
>   | 按键                      | 功能描述                                       |
>   | ------------------------- | ---------------------------------------------- |
>   | **字符按键以及Shift组合** | 输入字符                                       |
>   | **ENTER**                 | 回车键，换行                                   |
>   | **BACK SPACE**            | 退格键，删除光标前一个字符                     |
>   | **DEL**                   | 删除键，删除光标后一个字符                     |
>   | **方向键**                | 在文本中移动光标                               |
>   | **HOME/END**              | 移动光标到行首/行尾                            |
>   | **Page Up/Page Down**     | 上/下翻页                                      |
>   | **Insert**                | 切换光标为输入/替换模式，光标将变成竖线/下划线 |
>   | **ESC**                   | 退出输入模式，切换到命令模式                   |

#### 2.2.3 底线命令模式

>   在命令模式下按下 **:**（英文冒号）就进入了底线命令模式。
>
>   底线命令模式可以输入单个或多个字符的命令，可用的命令非常多。
>
>   在底线命令模式中，基本的命令有（已经省略了冒号）：
>
>   | 命令    | 功能描述                          |
>   | ------- | --------------------------------- |
>   | **:w**  | 保存文件。                        |
>   | **:q**  | 退出 Vim 编辑器。                 |
>   | **:wq** | 保存文件并退出 Vim 编辑器。       |
>   | **:q!** | 强制退出 Vim 编辑器，不保存修改。 |





#### 2.2.4 VIM 工作模式

![img](./img/vim-vi-workmodel.png)

#### 2.2.5 VIM 键位图

![img](./img/vi-vim-cheat-sheet-sch1.gif)

# 第九章 shell编程
