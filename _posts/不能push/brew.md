brew是一个软件包管理工具,类似于centos下的yum或者ubuntu下的apt-get,非常方便,免去了自己手动编译安装的不便
　　brew 安装目录 /usr/local/Cellar
　　brew 配置目录 /usr/local/etc
　　brew 命令目录 /usr/local/bin   注:homebrew在安装完成后自动在/usr/local/bin加个软连接，所以平常都是用这个路径



常用命令:
brew update                        　　#更新brew可安装包，建议每次执行一下
brew search php55                   #搜索php5.5
brew tap josegonzalez/php        #安装扩展<gihhub_user/repo>   ,可以获得更多的资源
brew tap                            #查看安装的扩展列表
brew install php55                 #安装php5.5
brew remove  php55                 #卸载php5.5
brew upgrade php55                 #升级php5.5
brew options php55                 #查看php5.5安装选项
brew info    php55                 #查看php5.5相关信息
brew home    php55                  #访问php5.5官方网站
brew services list                  #查看系统通过 brew 安装的服务
brew services cleanup               #清除已卸载无用的启动配置文件
brew services restart php55       #重启php-fpm


---------------------

本文来自 sylalak123 的CSDN 博客 ，全文地址请点击：https://blog.csdn.net/yejinxiong001/article/details/80003929?utm_source=copy


