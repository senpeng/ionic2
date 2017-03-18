# ionic2
创建和打包ionic2

## （一）安装nodejs

    * 下载地址：[https://nodejs.org/en/](https://nodejs.org/en/)
    * 安装好后在命令行中输入 `node -v` 和 `npm -v` 查看是否安装成功

    `Microsoft Windows [版本 10.0.10240]
    (c) 2015 Microsoft Corporation. All rights reserved. 

    C:\WINDOWS\system32>node -v
    v6.10.0

    C:\WINDOWS\system32>npm -v
    3.10.10`

    * 因为国内的网络环境原因，在下载npm包的时候经常会遇到无法正常下载的情况，这时可以使用国内淘宝推出了 npm 镜像
    * 输入以下命令，切换到淘宝镜像源：

        * `npm install -g cnpm --registry=http://registry.npm.taobao.org`

    * 之后所有用到的 npm 命令都可以使用 cnpm 来代替进行 install。但是需要注意 cnpm 不支持 publish 命令
