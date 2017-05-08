# git-flow Playground
这个项目是用来练习 git-flow 的。欢迎大家一起来练习。

## git-flow 介绍
git-flow 定义了一个围绕项目发布的严格分支模型，用于管理多人协作的大型项目，实现高效的协作。

分支的介绍：
* `master` 可发布的内容。
* `develop` 开发分支。从`master`上fork，测试完成后，合并到`master`。
* `feature-x` 功能分支，从`develop`上`fork`，测试完成后，合并到`develop`。
* `bugfix-x` 修复某bug的分支，从`master`上`fork`，测试完成后，合并到`master`。
* `release` 发布分支。某个版本需要发布时，从`master`上`fork`。

流程的示意图如下：  
![release-cycle](images/release-cycle.png)

详细介绍见[这里](https://github.com/xirong/my-git/blob/master/git-workflow-tutorial.md#23-gitflow工作流)。

## 练习方法
1. 在该项目新建 issue，点[这里](https://github.com/iamjoel/git-flow-playground/issues/new)。issue 的标题写 xx（替换成你的昵称）加入。
1. fork 本项目。
1. 下载本项目: `git clone https://github.com/iamjoel/git-flow-playground.git`。
1. 获取最新的develop分支的代码: `git checkout -b develop origin/develop`
1. 在本地建 feature-issueId(替换为你创建的 issue 的id): `git checkout -b feature-issueId(替换为你创建的 issue 的id)`
1. 在 member 文件夹下见一个 `xx（替换成你的昵称）.md` 的文件。
1. 提交代码。
1. pull request。