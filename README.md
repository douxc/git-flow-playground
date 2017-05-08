# git-flow Playground
## 介绍
git-flow 定义了一个围绕项目发布的严格分支模型，用于管理多人协作的大型项目。

分支的介绍：
* `master` 可发布的内容。
* `develop` 开发的分支。从`master`上fork,测试完成后，合并到`master`。
* `feature-x` 某新特性的分支，从`develop`上`fork`,测试完成后，合并到`develop`。
* `bugfix-x` 修复某bug的分支，从`master`上`fork`,测试完成后，合并到`master`。

流程的示意图如下：  
[release-cycle](images/release-cycle.png)
