# Good morning 🙏

> 本文由人类亲手编写，没有任何AI 撰写或者修改，建议由人类阅读而不是AI 总结概括

## 写在前面📚

感谢大家今天加入3G 移动应用开发实验室，欢迎加入iOS 部门

很荣幸能为各位写下这些文字，与各位相聚在这里

在正式开始之前，我想讲讲 [Apple 开发者](https://developer.apple.com/) 这个职位对我个人而言到底意味着什么

前CEO [tim cook](https://www.apple.com/leadership/tim-cook/) 在最后一次 [WWDC](https://developer.apple.com/wwdc/) 演讲中这样说到：



“**I want to take a moment to express how important WWDC is to me personally and how deeply meaningful it has been to meet so many of our wonderful developers.**
（我想借此机会说一说，WWDC 对我个人而言有多么重要。能够认识如此多杰出的开发者，对我来说意义非凡。）

**I've loved hearing your stories and learning about how you're enriching the lives of so many people around the world.**
（我一直很喜欢聆听你们的故事，了解你们如何让世界各地无数人的生活变得更加美好。）

**Your imagination and ingenuity have inspired me for the past 15 years, and I am deeply grateful to have been on this journey with you. Thank you.**
（在过去 15 年里，你们的想象力与创造力始终激励着我。我由衷感谢能够与你们共同走过这段旅程。谢谢大家。）

**That same creativity will continue to shape experiences that bring people closer together, unlock new possibilities, and change the world in ways we can only begin to imagine.**
（这份创造力将继续塑造新的体验，让人与人之间联系得更加紧密，开启更多可能，并以我们目前才刚刚能够想象的方式改变世界。）”



对我而言，成为一个Apple 开发者，并不意味着你只需要学好实验室的东西，背会一些内容，熟悉技术，找到工作



更重要的是自己学的东西，掌握到的东西能不能创造出一些令人惊叹的作品

开发者正在创造比以往更多的 App，[App Store](https://www.apple.com/app-store/) 每小时收到的提交数量远超 1,000 个

我希望借助这些文字延续这股蓬勃势头，激发你们更多令人惊叹的创作



## 开始实验室的学习💻

对于进入实验室的同学，考虑到可能之前并没有接触过Apple 的产品（或者接触了也并不熟练Mac 的使用），所以除了一些基本的学习内容，我还在这篇文档里准备了一些Mac 的基本使用说明

### Markdown语法

对于刚入门的新生，第一堂课应该都是Markdown 语法

[教程](https://www.runoob.com/markdown/md-tutorial.html)

对于Markdown文本格式，你的学长学姐可能会让你下载 [Typora](https://typora.io/) 这款软件

应当了解的是，学长学姐的要求实际上是下载一个Markdown 编辑器，所以并不只有Typora 可以选

如果你有搭建自己知识库的想法，[Obsidian](https://obsidian.md/) 或者 [Notion](https://www.notion.com/) 显然是更好的选择，如果想要更加漂亮的UI，也可以选择 [妙言](https://miaoyan.app/) 或者 [Markdown Preview](https://markdownpreview.app/)

### Git版本控制

[Git](https://git-scm.com/) 仓库版本管理可以说是Agent 时代非常重要的一部分，通过管理你的工作让Agent不至于直接把你之前的工作清零

[Git 教程](https://learngitbranching.js.org/?locale=zh_CN)

注意，git 提交的注释规范在教程里并没有写，需要单独学习：[提交注释规范](https://xiaochenstudio.com/blog/gitConventionalCommits/)

同时，对于 [GitHub](https://github.com/) 的学习也是非常必要的，这是多人协作的基石

[GitHub 入门](https://github.com/skills/introduction-to-github)



### 科学上网

不说什么，也不敢多说

但是为了之后的Agent 使用，应当选择尽可能好的代理节点

部分同学可能之前已经有过相关的经验

这里只给出一个比较好的[自用节点](https://buy.cloudss.org/aff.php?aff=10358)

和一个[IP 检测工具](https://net.coffee/)（可以测试你的节点是否纯净好用）

### Mac使用

Apple开发不用Mac 是不大可能的，这里给出了一些mac 的基本使用指南，包括常用的 [Homebrew](https://brew.sh/) 下载使用，和盗版Mac App 下载：

- [买了Mac，先看这个！18个让Mac更好用的新手设置建议](https://www.bilibili.com/video/BV1iXN76bEaS/)
- [Mac隐藏的App Store - Homebrew全方位入门指南](https://www.bilibili.com/video/BV1NKabz9EAL/)
- [Mac基础教程01-了解桌面：程序坞](https://www.bilibili.com/video/BV1KH4y1y7p5/)
- [MacKed](https://macked.app/)

一些比较好用的软件我也会在这里给出，可以按需下载安装：

| 软件 | 简介 | 官网 | Homebrew |
| --- | --- | --- | --- |
| [Raycast](https://www.raycast.com/) | 快捷启动器，用快捷键控制常用工具 | [raycast.com](https://www.raycast.com/) | `brew install --cask raycast` |
| [Ghostty](https://ghostty.org/) | 原生 UI、GPU 加速的终端模拟器 | [ghostty.org](https://ghostty.org/) | `brew install --cask ghostty` |
| [Phi](https://phibrowser.com/) | 专为 macOS 打造的原生 AI 浏览器 | [phibrowser.com](https://phibrowser.com/) | `brew install --cask phibrowser/tap/phi` |
| [Tabbit](https://www.tabbit.com/) | AI 原生浏览器，可对话网页并执行任务 | [tabbit.com](https://www.tabbit.com/) | 官网下载 |
| [CleanShot X](https://cleanshot.com/) | 截图、录屏与标注工具 | [cleanshot.com](https://cleanshot.com/) | `brew install --cask cleanshot` |
| [Prowl](https://prowl.onev.cat/) | 面向 coding agent 的原生终端环境 | [prowl.onev.cat](https://prowl.onev.cat/) | `brew install --cask onevcat/tap/prowl` |
| [Fork](https://fork.dev/) | Git 图形客户端 | [fork.dev](https://fork.dev/) | `brew install --cask fork` |
| [UU远程](https://uuyc.163.com/) | 网易远程桌面，跨设备访问与控制 | [uuyc.163.com](https://uuyc.163.com/) | `brew install --cask uuremote` |

一些软件可能为付费，可以按需购买或转战至 [MacKed](https://macked.app/)



### 提问问题

学长学姐虽然一般情况下都是很友好的，但是干软件的肯定会有厌蠢或者正好因为一些问题很生气的时候

提问问题之前建议先阅读[提问的智慧](https://mp.weixin.qq.com/s/q461so9lWk4FKJGZ-p7Vcg?scene=1)一文



### iOS内容学习

实验室的大纲基本为 `OC` + `UIKit` 的学习内容，即一开始学习的是 `OC` 的基本语法

作为实验室的标准用书《疯狂iOS 讲义》这本书实在是难堪此大任

可以考虑其他书用作首次学习，学完之后转至《疯狂iOS 讲义》查缺补漏

`UIKit` 的上手课程则更加老旧，为上古时代的网易云免费公开课

作为入门学习倒不是不行，只是内容过于浅薄，在做项目的时候很容易被迫造轮子——使用一些基本的组件来构建一个其实苹果已经帮你实现好的组件

在做项目的时候可以考虑多问AI，扩展自己在 `UIKit` 的学习面，也可以使用在组织仓库里的 [Raycast](https://www.raycast.com/) 扩展：[Raycast-Apple-Developer-Docs](https://github.com/XiyouMobile3G-iOS/Raycast-Apple-Developer-Docs)

来实时查找Apple 的[官方学习文档](https://developer.apple.com/documentation/)

### 代码格式

实验室代码格式采用小驼峰格式，即首字母小写，接下来的单词大写

对于类名，则需要加入自己的前缀来表示作者或者该类的归属（）

例如 `NSObject` 属于 Next Step 公司，此类为从该公司继承的类（所有 `NS` 开头的类名同样）

`CALayer`，`CFData` 则分别属于 Core Animation 和 Core Foundation 框架




## 写在后面

作为实验室首要学习的一些内容，基本就只有这些了

掌握了这些内容，你就已经算是入门了，在做完第一二三四五个项目之后，可以考虑其他内容的学习

新手文档只包含了我在实验室内学习时觉得可以改进注意的部分

在你们的学习中，如果发现该文档有需要改写，或更新的部分，也可以实时提 [PR](https://docs.github.com/en/pull-requests) 或者 [issue](https://docs.github.com/en/issues) 来进行更正更新

对于组织仓库内其他的学习内容也是相同的

那最后祝各位在学习过程中，都能找到属于自己的智慧果
