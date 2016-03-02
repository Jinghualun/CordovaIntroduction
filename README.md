# CordovaIntroduction
1.下载并安装 Node.js。打开一个终端窗口。 运行下面的命令以确认已安装 Node.js。
  $ node -v
  如果已安装 node.js，您将会看到版本显示在终端窗口中。
注：
如果您受到代理的屏蔽，则需要配置 node.js 以使用代理访问网络。可以运行以下命令来设置代理，并将 http://proxy:8080 替换为您的代理。
$ sudo npm config set proxy http://proxy:8080
$ sudo npm config set https-proxy http://proxy:8080
可以运行以下命令来查看当前配置设置。
$ npm config list
2.运行下面的命令以安装 Cordova。
$ npm install -g cordova
注：
如果您在运行安装命令时在终端窗口中看到错误消息，请确认代理配置正确。
可以运行下面的命令将 Cordova 更新为最新版本。
$ npm update -g cordova
运行下面的命令以确认 Cordova 已安装并查看版本。
$ cordova --version
如果已安装 Cordova，您将会看到版本显示在终端窗口中。
3.下载并安装 Git 版本控制系统（如果尚未安装）。
可以从 Git 站点下载此安装程序。
注：需要将 Git 添加到 Path 环境中。
运行下面的命令以确认已安装 Git。
$ git --version
如果已安装 Git，您将会看到版本显示在终端窗口中。
注：
如果您受到代理的屏蔽，则需要配置 Git 以使用代理访问网络。可以运行以下命令来设置代理，并将 http://proxy:8080 替换为您的代理。
$ git config --global http.proxy http://proxy:8080
$ git config --global https.proxy http://proxy:8080
可以运行以下命令来查看当前配置设置。
$ git config --list
4.终端窗口新建项目
1).cd /Users/jingkang/Desktop/Test
2).cordova create Test com.test.www Test
3).cd Test
4).cordova platform add ios
  cordova platform add android
