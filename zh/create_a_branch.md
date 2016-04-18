# 第二步：建立分支（Branch）

**Branching** is the way to work on different versions of a repository at one time.

By default your repository has one branch named ```master``` which is considered to be the definitive branch. We use branches to experiment and make edits before committing them to ```master```.

When you create a branch off the``` master ```branch, you’re making a copy, or snapshot, of ```master``` as it was at that point in time. If someone else made changes to the``` master``` branch while you were working on your branch, you could pull in those updates.

This diagram shows:

- The ```master``` branch
- A new branch called ```feature``` (because we’re doing ‘feature work’ on this branch)
- The journey that ```feature``` takes before it’s merged into ```master```

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