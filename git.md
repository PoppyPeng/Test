# GIT

## Introduce

### 工作区（Working Directory）

就是你在电脑里能看到的目录，比如我的`learngit`文件夹就是一个工作区：

### 版本库（Repository）

工作区有一个隐藏目录`.git`，这个不算工作区，而是Git的版本库。

Git的版本库里存了很多东西，==其中最重要的就是称为stage（或者叫index）的暂存区==，还有Git为我们自动创建的第一个分支`master`，以及指向`master`的一个指针叫`HEAD`。

![git-repo](https://www.liaoxuefeng.com/files/attachments/919020037470528/0)

==git 管理的是修改，不是文件==

