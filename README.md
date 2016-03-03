# CordovaIntroduction
=
1.下载并安装 Node.js。
-
  打开一个终端窗口。 运行下面的命令以确认已安装 Node.js。<br/>
    $ node -v<br/>
  如果已安装 node.js，您将会看到版本显示在终端窗口中。<br/>
  注：<br/>
    如果您受到代理的屏蔽，则需要配置 node.js 以使用代理访问网络。可以运行以下命令来设置代理，并将 http://proxy:8080 替换为您的代理。<br/>
    $ sudo npm config set proxy http://proxy:8080<br/>
    $ sudo npm config set https-proxy http://proxy:8080<br/>
  可以运行以下命令来查看当前配置设置。<br/>
    $ npm config list<br/>
2.运行下面的命令以安装 Cordova。
-
  $ npm install -g cordova<br/>
  注：<br/>
    如果您在运行安装命令时在终端窗口中看到错误消息，请确认代理配置正确。<br/>
    可以运行下面的命令将 Cordova 更新为最新版本。<br/>
      $ npm update -g cordova<br/>
    运行下面的命令以确认 Cordova 已安装并查看版本。<br/>
      $ cordova --version<br/>
  如果已安装 Cordova，您将会看到版本显示在终端窗口中。<br/>
3.下载并安装 Git 版本控制系统。
-
  可以从 Git 站点下载此安装程序。<br/>
  注：需要将 Git 添加到 Path 环境中。<br/>
  运行下面的命令以确认已安装 Git。<br/>
    $ git --version<br/>
  如果已安装 Git，您将会看到版本显示在终端窗口中。<br/>
  注：<br/>
  如果您受到代理的屏蔽，则需要配置 Git 以使用代理访问网络。可以运行以下命令来设置代理，并将 http://proxy:8080 替换为您的代理。<br/>
    $ git config --global http.proxy http://proxy:8080<br/>
    $ git config --global https.proxy http://proxy:8080<br/>
  可以运行以下命令来查看当前配置设置。<br/>
    $ git config --list<br/>
4.终端窗口新建项目
-
  1).cd /Users/jingkang/Desktop/Test<br/>
  2).cordova create Test com.test.www Test<br/>
  3).cd Test<br/>
  4).cordova platform add ios<br/>
     cordova platform add android<br/>
