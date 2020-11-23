## 远程仓库的使用

    - 1、介绍远程仓库github
        + github是一个开源的代码分享平台；每一个github账户都可以把自己的代码分享到这个平台上，那他就是充当中央服务器的角色，把代码提交到这个平台上之后，你可以在任何一个有网络的地方去下载代码，当然了，谁有下载的权限是有你来配置的

    - 2、创建一个远程仓库(点击左上角绿色的按钮 New)
        + Repository name：新建仓库的名称
        + Description：新建仓库的描述
        + Public/Private:新建仓库是公开还是私密的
        + Initialize this repository with:为仓库增加初始化文件(暂时不选)
        + 绿色按钮 Create repository: 创建新的仓库

    - 3、把本地仓库的代码提交到远程仓库
        + 1、本地仓库和远程仓库建立连接
            + git remove -v(查看本地和远程仓库的连接状态)
            + git remove add origin 远程仓库地址(和远程仓库的某个新项目建立连接，origin这个名可以改，但是大家都统一叫这个)
        + 2、git pull origin master (拉取远程仓库的代码到本地)
        + 3、git push origin master (推送本地的代码到远程仓库)

    - 4、git clone 远程仓库地址 仓库的名字(如果不写默认原仓库名)
        + 其真正的开发中，大家都使用这个
        + 你们的项目老大把项目骨架搭建好之后你们每一个项目小组成员都去把远程的代码拉取到你们的本地去开发
        + git clone(相当于git init  git remove add  git pull)