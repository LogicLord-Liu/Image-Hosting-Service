# HELLO EVERYONE!

I'm liu,a lover program.

Now, i will show you how to use Typora+PicGo+GitHub to establish a free Image Hosting Service.

* First,What's the Image Hosting Service?
  >The explanation given by Baidu is: the servers that store pictures are divided into domestic and foreign servers.
  >
  >Due to factors such as spatial distance, the access speed of foreign image beds is very slow, which affects the image display speed.
  >
  >In China, it is also divided into three types: single-line space, multi-line space and CDN acceleration.
  >
  >It is an online space specially used to store pictures and allows you to connect pictures to the outside world. Many picture beds are free.
  >
  >Picture bed is simply a space for storing pictures on the Internet.
* Why we need the Picture bed? 
  
  🎈 当大家使用轻量级标记语言写好了图文并茂的文字，当我们发布在博客网站的时候，发现大多图片都打不开，其实图片储存在你本地相册，发布博客后服务器访问不到地址路径，这个时候我们就需要借助到一个图床。

  🎈 会去接触图床的人通常都是一些喜欢在网上分享博客（编程经验）的人，使用图床的人通常采用Markdown的方式去编辑文字。我们都知道现在通常流行两种方式编辑文字：

  >**富文本编辑**: Word就是其中非常具有代表性的，文字的各种格式都是通过交互按钮设置的，这时候需要频繁的鼠标配合操作（熟悉快捷键的大佬除外）。这种方式操作简单便捷，但是对于大量编辑工作的文字工作者，双手离开键盘使用鼠标往往容易打乱书写节奏和思路，效率低。
  >
  >**Markdown编辑**: 是一种通过Markdown标记语言去规定格式的纯文本编辑方式。这种方式使得文字工作者专注于文字，而非格式，双手可以彻底的解放鼠标，大大提高了效率。Markdown比富文本编辑方式更加具有通用性，word的文字整篇复制到有道云笔记格式会出现差异，这也是富文本编辑的巨大缺陷，只能说轻量级标记语言的优点懂的人很爱。

* How to gain the Picture bed?
  >经过测试，我决定使用“Typora+PicGo+GitHub”来搭建自己的图层。
  >
* What's the "MarkDown"?
  >![MarkDown](https://img-blog.csdnimg.cn/47b2258afd6e49c1a233fef88e3e66d8.png)
  >
  >您也可以去MarkDown官网去查看[官方文档教程](https://markdown.com.cn/basic-syntax/)
  >
  >千万不要被「标记」、「语言」吓到，Markdown的语法十分简单，常用的标记符号不超过十个，用于日常写作记录绰绰有余，不到半小时就能完全掌握。
  >
  >就是这十个不到的标记符号，却能让人优雅地沉浸式记录，专注内容而不是纠结排版，达到「心中无尘，码字入神」的境界。
  >
  >Now, you can try it on the [online editor](https://dillinger.io/).
  >
* Then, i will introduct 'PicGo' and 'GitHub' for you! Let's go!
  >![PicGo](https://img-blog.csdnimg.cn/24daafddf4534095a00ba5283940f6b1.png)
  
  >一个用于快速上传图片并获取图片 URL 链接的工具.
  >>特色功能
  >>
  >>1.支持拖拽图片上传
  >>
  >>2.支持快捷键上传剪贴板里第一张图片
  >>
  >>3.Windows 和 macOS 支持右键图片文件通过菜单上传 (v2.1.0+)
  >>
  >>4.上传图片后自动复制链接到剪贴板
  >>
  >>5.支持自定义复制到剪贴板的链接格式
  >>
  >>6.支持修改快捷键，默认快速上传快捷键：command+shift+p（macOS）| control+shift+p（Windows\Linux)
  >>
  >>7.支持插件系统，已有插件支持 Gitee、青云等第三方图床
  >>
  >>8.支持通过发送 HTTP 请求调用 PicGo 上传（v2.2.0+)
  >>
* Now, a improtant step is coming.
  * GitHub
    >* Sing Up a GitHub account.
    >
    >* 🌹首先去GitHub官网注册一个属于你的账号，进入后点击**Sign Up**,后接着往下走，这里就不详细的描述注册的过程了，准备一个可以使用的邮箱账号就行。
    >
    >* 🍊注册好账号后：我们的Github主页就是这个样子的。下面会对主页一些内容进行简单的介绍。
    >
    >* ![Interface](https://img-blog.csdnimg.cn/direct/f76a85539e6348fdb40d85088e723e3c.png)
    >
    >>* ### Introduction of interface
    >>
    >>* **Pull Request**: Make a request to the project (including your own submission, or requests submitted to you by others). For example, you find a project very interesting, so you fork the project, and then you find some bugs in the project. After you modify it, you request to merge your modifications. That is, you submit your request to others. If it is reviewed and approved, it is officially merged. , you are contributing to the project.
    >>
    >>* **Issue**: Comment/topic, which raises various discussions on the project and can increase communication between developers and users. (Questions you ask others or questions asked by others, such as bug, build, help, wanted, etc., you can ask all kinds of questions). For example, you open source a warehouse and others see it, or your team friends see it and find a bug! Just click Issues, create a new Issue, tell you the problem, and then set a label to indicate whether it is a bug, a warning, or a document error.
    >>
    >>* ![Issue](https://img-blog.csdnimg.cn/2021080716323932.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3hpYW94aWFuZXIzMjE=,size_16,color_FFFFFF,t_70)
    >>
    >>* **Marketplace**: There are some tools in it, such as continuous integration, code inspection, etc. Most of them cost money for commercial use.
    >>
    >>* **Explore**: There are many things under Explore. In the explore column under Explore, github will recommend some projects to me. Topics are relatively popular projects, and github has also categorized them for us. Treading contains some projects that are rising in popularity quickly, and collections categorize the projects. You can also find projects similar to topics but not popular here. Events are some GitHub news, and GitHub Sponsors are introductions from sponsors and code enthusiasts.
    >>
    >>>* More functions: 
    >>
    >>* **New repository**
    >>
    >>* **Import repository**
    >>
    >>* **New gist**
    >>
    >>* **New organization**
    >>
    >>* **New project**
    >>
    >>* ## Personal setting
    >>
    >>* ![setting](https://img-blog.csdnimg.cn/20210805235542150.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3hpYW94aWFuZXIzMjE=,size_16,color_FFFFFF,t_70)
    >>
    >>* After we learn GitHub's interface, then we can create a new repository.
    >>
    >>>>* More informations, please get this link: https://docs.github.com/zh/get-started
    >>>>
    >* Now, we can install PicGo.
    >
    >* On GitHub: https://github.com/Molunerfinn/PicGo
    >
    >* Official: https://molunerfinn.com/PicGo/
    >
    >* Mirror site: https://github.com/Molunerfinn/picgo/releases
    >
    >>* If install is completed.
    >>
    >>* Run
    >>
    >>* **此电脑—>右键属性—>兼容性—>以兼容模式运行这个程序** 下方以管理员身份运行此程序
    >>
    >>* ![PicGo Run](https://img-blog.csdnimg.cn/c86eb6a6e3ed44e7987b75aca99fab50.png)
    >>
    >>* ![Runing](https://img-blog.csdnimg.cn/9696b61aa9ba42ebb64a6fe3c49eb040.png)
    >>
    >>>* Repository name:[Your GitHub Username]/[First Create Repository's Name]
    >>>
    >>>* Brunch: Default as 'master'
    >>>
    >>>* Setting Token:
    >>>
    >>>>* ![Gain Token](https://img-blog.csdnimg.cn/5ded6ef420c144e094382a7a21bb561f.png)
    >>>>
    >>>>* ![Gain Token](https://img-blog.csdnimg.cn/e5f6004cfc6742e79b9e85703602b15b.png)
    >>>>
    >>>>* ![Gain Token](https://img-blog.csdnimg.cn/d3a0a316080a4ca4ac23dfc87d2f590c.png)
    >>>>
    >>>>* ![Gain Token](https://img-blog.csdnimg.cn/57308546dd4842f687b31d2816300857.png)
    >>>>
    >>* Config Typora
    >>
    >>* ![](https://img-blog.csdnimg.cn/705c443273c34cc99f248fab59bf1544.png)
    >>
* Finally, you can luanch your blogs.
  >![PicGo Basic Operations](https://pic.molunerfinn.com/picgo/docs/34242857-d177930a-e658-11e7-9688-7405851dd5e5.gif)
  >
* Upload:
  >PicGo's upload area supports drag and drop or open your folder to upload images
  >


Please pay attention: If you have better advance about this passage, Please contact me with email.

>Email:luc444175@gmail.com or 769891117@qq.com
>
> You also can visit PicGo official website of configuration: https://picgo.github.io/PicGo-Doc/zh/guide/config.html
>
> And you can visit GitHub official website of configuration: https://docs.github.com/zh/get-started
 
   
    
  
  
