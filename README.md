# XarrPay-for-1Panel
XarrPay-for-1Panel

* * *
## 目录

- [目录](#目录)
- [1. 简介](#1-简介)
- [2. 使用方式](#2-使用方式)
  - [2.1 使用 git 命令获取应用](#221-使用-git-命令获取应用)
  - [2.2 使用压缩包方式获取应用](#222-使用压缩包方式获取应用)

***

## 1. 简介
这是一个专门针对 xiexiaosheng997/xarr-pay-merchant 这个 docker 容器在 1Panel 商店进行适配的项目。我们的目标是通过一系列专业的适配工作，让该容器能够无缝融入 1Panel 商店的生态环境之中，使用户在使用该商店时可以轻松便捷地部署、运行 xiexiaosheng997/xarr-pay-merchant 容器，无需再为复杂的配置而烦恼，进而高效地开展与之相关的各类业务操作或者功能体验，为用户打造更加流畅、省心的使用感受。

## 2. 使用方式

默认`1Panel`安装在`/opt/`路径下，如果不是按需修改以下。

#### 2.1 使用 git 命令获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，
```shell
git clone https://github.com/xiexiaosheng/XarrPay-for-1Panel /opt/1panel/resource/apps/local/XarrPay-for-1Panel

cp -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel
```

然后应用商店刷新本地应用即可。

#### 2.2 使用压缩包方式获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，
```shell
wget -P /opt/1panel/resource/apps/local https://github.com/xiexiaosheng/XarrPay-for-1Panel/archive/refs/heads/XarrPay-for-1Panel.zip

unzip -o -d /opt/1panel/resource/apps/local/ /opt/1panel/resource/apps/local/XarrPay-for-1Panel.zip

cp -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel.zip
```

然后应用商店刷新本地应用即可。
