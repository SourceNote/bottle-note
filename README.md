# bottle-note
Bottle 源码阅读笔记




标准库里关于网络的代码

+ SocketServer
+ socket
+ 熟悉 TCP/UDP 编程
+ 了解 Mixin 机制： SocketServer.{ForkingMixIn|ThreadingMixIn}
+ thread/threading 模块
+ 并发量 select 模块，深刻理解select/{epoll|kqueue}
+ 接触异步框架 asyncore 和 asynchat


TCP/UDP:
+ greenlet 和 gevent

web:
+ BaseHTTPServer
+ SimpleHTTPServer
+ CGIHTTPServer
+ cgi/cgitb
+ cookielib
+ wsgiref
+ httplib/urllib/urllib/urlparse



---


Web 框架：

+ [wsgi](http://wsgi.readthedocs.io/en/latest/index.html)
+ web.py 接口pythonic，实现非常不pythonic
+ Bottle 但文件，无额外依赖
+ Flask 现实世界
