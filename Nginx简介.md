## Nginx简介

#### 一、<font color = red>Nginx</font>功能介绍

Nginx是高性能的Http和反向代理Web的服务器，具有十分强大的高并发能力。Nginx 可以作为静态页面的 web 服务器，同时还支持 CGI 协议的动态语言，比如 perl、php 等。但是不支持 java。Java 程序只能通过与 tomcat 配合完成。Nginx 专为性能优化而开发， 性能是其最重要的考量,实现上非常注重效率 ，能经受高负载的考验,有报告表明能支持高 达 50,000 个并发连接数。



#### 二、Nginx可以提供的服务

1. Web服务

2. 负载均衡

3. Web cache（动静分离）

    

#### 三、Nginx的优点

> 1. 高并发。静态小文件
> 2. 占用资源少。2万并发、10个线程，内存消耗几百M。
> 3. 功能种类比较多。web,cache,proxy。每一个功能都不是特别强。
> 4. 支持epoll模型，使得nginx可以支持高并发。
> 5. nginx 配合动态服务和Apache有区别。（FASTCGI 接口）
> 6. 利用nginx可以对IP限速，可以限制连接数。
> 7. 配置简单，更灵活。



#### 四、nginx应用场合

> 1. 静态服务器(图片，视频服务)，另个lighttpd。并发几万，html，js，css，flv，jpg，gif等。
> 2. 动态服务，nginx—fastcgi 方式运行PHP，jsp。(PHP并发约500-1500，MySQL 并发约300-1500）。
> 3. 反向代理，负载均衡。日pv2000W以下，都可直接用nginx做代理。
> 4. 缓存服务。类似 SQUID,VARNISH。



