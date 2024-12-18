# XarrPay-for-1Panel

## 仅自用

#### 使用 git 命令获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，
```shell
git clone https://github.com/xiexiaosheng/XarrPay-for-1Panel /opt/1panel/resource/apps/local/XarrPay-for-1Panel

cp -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel
```

然后应用商店刷新本地应用即可。

#### 使用压缩包方式获取应用

`1Panel`计划任务类型`Shell 脚本`的计划任务框里，添加并执行以下命令，或者终端运行以下命令，
```shell
wget -P /opt/1panel/resource/apps/local https://github.com/xiexiaosheng/XarrPay-for-1Panel/archive/refs/heads/XarrPay-for-1Panel.zip

unzip -o -d /opt/1panel/resource/apps/local/ /opt/1panel/resource/apps/local/XarrPay-for-1Panel.zip

cp -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel/apps/* /opt/1panel/resource/apps/local/

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel

rm -rf /opt/1panel/resource/apps/local/XarrPay-for-1Panel.zip
```

然后应用商店刷新本地应用即可。
