# 0. 介绍

该仓库用于 Robomaster2025赛季 辅助Alliance算法组新成员快速上手**git工具**的使用，旨在让新人能通过几个预设情景快速获得以下能力：

- 使用Git工具管理代码（抛弃QQ传压缩包的陋习）
- 让仓库保持整洁小巧（灵活配置`.gitignore`）
- 良好的开发习惯（dev开发分支，清晰的提交记录等）
- 团队协作能力（远程仓库相关）
- 不重复造轮子（`submodule`功能)
- 待添加

该仓库不一定全面~~，但大体上能用~~，希望更深入了解git仍需自行探索



## 开始之前

- 在使用该仓库之前，请确保你已完成**git基础学习**

  > 推荐教程：
  >
  > 文档类:
  >
  > - [廖雪峰的git教程](https://liaoxuefeng.com/books/git/introduction/index.html)
  >
  > 视频类:
  >
  > - [【GeekHour】一小时Git教程](https://www.bilibili.com/video/BV1HM411377j)
  >
  > 实操类（可视化教学，强推，即使你不想完成它的关卡，也可以使用它的沙盒模式)：
  >
  > - https://learngitbranching.js.org/?locale=zh_CN

- 由于部分任务涉及到远程仓库的使用，请确保你在git内配置了github密钥

  > 自行搜索关键字 **github ssh密钥** 按照教程指示完成密钥配置
  
- 安装 **VSCode** 编辑器，并安装 **Git Graph**拓展

  <img src=".\static\Git Graph.png" alt="Git Graph" style="zoom: 50%;" />
  
  

## 该仓库用法

​	本仓库会使用多个分支模拟不同的场景，我们将每个不同的分支称为**关卡**

​	每个关卡内都有对应的情景预设、目标、思考等信息，均位于对应分支根目录下的**README.md**文件下

​	

​	卡关的时候，请擅用工具，自行寻找答案(搜索引擎、gpt等)



​	当你完成了所有操作，请clone本仓库，然后切换到 **start** 分支

> 为了进程能顺利推进，请在切换分支前检查下GitGraph插件是否工作
>
> 请用VSCode打开本地仓库所在文件夹，观察底部工具条：
> ![VSCode底部工具栏](.\static\VSCode_status_bar.png)
>
> 你应该能看到**当前分支名**和**Git Graph**的字样
>
> 现在你可以切换到 `start分支` 了

> 如果你不知道如何切换分支，请在仓库根目录处开启终端，并输入
>
> ```bash
> git switch start
> ```
>
> 但我强烈建议你学习完上述三个git基础教程任一后再回到本仓库
