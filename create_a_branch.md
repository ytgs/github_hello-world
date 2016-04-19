# 第二步：建立分支（Branch）

**分支**是实现同时对同一个仓库的不同版本进行操作的方法。

默认情况下，仓库有一个```master```分支，同时它也是最终要完成的分支， 其他分支是用来进行试探编辑的，但最重要提交合并到```master```中.

每当基于``` master ```建立一个其他分支时，同时也就意味着在这个时点建立了一个```master```的拷贝或者叫做快照， 如果有其他人这时修改了``` master```分支，你可以将它们的修改合并到你的分支中.

以下图示显示了:

-  ```master``` 分支
- 一个被称为 ```feature（特性）```的分支 (因为我们要在这个分支上完成一个特别工作 ‘feature work’ )
-  ```feature``` 合并到 ```master```分支前的旅程

![a branch](branching.png)


Have you ever saved different versions of a file? Something like:

*    story.txt
*    story-joe-edit.txt
*    story-joe-edit-reviewed.txt


Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our ```master``` (production) branch. When a change is ready, they merge their branch into ```master```.
## 建立新分支
1.   进入仓库 ```hello-world```.
2.   点击顶部标识**branch: master**的下拉菜单 。
3.   输入分支名称：```readme-edits```.
4.   选中蓝色的 **Create branch** ，按回车（“Enter”）键.

    

![branch gif](readme-edits.gif)


现在，你有了两个分支```master``` 和 ```readme-edits```. 目前他们是一样的，但不久我们就会在新分支中进行变更修改.