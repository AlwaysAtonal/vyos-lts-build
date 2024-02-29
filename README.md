# vyos-lts-build

这个仓库专门用于编译VyOS 1.4+ LTS镜像，使用时需要fork至本人账户下使用。

This repository is dedicated to compiling VyOS 1.4+ LTS images, which you need to fork to your own account to use.

使用方法：

Usage：

修改.github/workflow/build-lts.yaml文件第23行`RELEASE_VERSION=1.4.0-epa1`版本为编译目标版本，修改完成并保存文件后添加git tag，连带tag push后会自动开始编译流程并发布release。

Modify .github/workflow/build-lts.yaml file line 23 `RELEASE_VERSION=1.4.0-epa1` version for the target version of the compilation, modification is complete and save the file to add a git tag, along with the tag push will automatically start the compilation process and release.