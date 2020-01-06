Zeroai-Utils README
============

简介
===========

  Zeroai-Utils 是一个CentOS 7.x下的运维环境工具包。

  安装方式: 源码编译为主。

  侧重点:   注重性能。

  推荐系统: CentOS 7.x minimal

  推荐基础硬件:
  			CPU 4/8核，

  			内存16/32G，

  			硬盘SSD+HDD。

安装方式
=======
```shell
   git clone https://github.com/zeroainet/zeroai-utils.git
```

使用方式
=======
```shell
   #安装
   cd zeroai-utils
   ./install.sh -c php,redis,mysql,memcached,openresty
```