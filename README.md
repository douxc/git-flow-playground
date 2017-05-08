# git-flow Playground
## 介绍
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
