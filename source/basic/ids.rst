入侵检测
================================

溯源
--------------------------------
- 源码分析，检查源码改动
- 查杀后门
- 查看日志
- ``w`` 命令，查看用户及其进程
- 分析开机自启程序
    - ``/etc/init.d``
    - ``~/.bashrc``
- 查看端口占用

重点分析文件
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
- ``/var/log/wtmp`` 登录进入，退出，数据交换、关机和重启纪录
- ``/var/run/utmp`` 有关当前登录用户的信息记录
- ``/var/log/lastlog`` 文件记录用户最后登录的信息，可用 lastlog 命令来查看。
- ``/var/log/secure`` 记录登入系统存取数据的文件，例如 pop3/ssh/telnet/ftp 等都会被记录。
- ``/var/log/cron`` 与定时任务相关的日志信息
- ``/var/log/message`` 系统启动后的信息和错误日志
- ``/var/log/apache2/access.log`` apache access log
- ``/etc/passwd`` 用户列表
- ``~/.ssh``

参考链接
--------------------------------
- `Web日志安全分析系统实践 <https://xz.aliyun.com/t/2136>`_
- `Web日志安全分析浅谈 <https://xz.aliyun.com/t/1121>`_
- `大型互联网企业入侵检测实战总结 <https://xz.aliyun.com/t/1626/>`_
- `同程入侵检测系统 <https://mp.weixin.qq.com/s/kzeAEvz-ejLD71fgb5t8tA>`_
