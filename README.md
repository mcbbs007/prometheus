# prometheus 普罗米修斯计划
关于为什么起这个么个名字：普罗米修斯是古希腊的神之一，人教版小学课本中有一篇他的文章，说他从太阳神阿波罗那里盗取了火种带到了人间，给人间带来光明，是人类不在茹毛饮血，而这个程序则是帮助你从单位机构手里面获取食物帮助苦逼的你减少经济上的负担

# 这个程序如何使用？
这个程序是在Linux上才能运行的而且是apt包管理器的系统
使用方法：
```shell
1. git clone https://github.com/MCKN007/prometheus.git
2. cd prometheus
3. lua prometheus_main.lua
```
软请确保软件第一次运行时连接网络，需要下载必须的库
输入1是安装软件驱动程序，比如libnfc，同时也会安装mfoc和mfuck之类的nfc工具安装完成之后会设置nfc文件
输入2是运行卡片扫描程序,也就是扫描卡片类型这里是使用os.execute函数去调用系统执行命令扫描ic卡
输入3是读取卡片内容并且保存为文件方便你以后的写入和对密钥的读取
#其他的功能还在开发之中，敬请期待
