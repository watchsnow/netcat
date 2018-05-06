# netcat
netcat被誉为网络安全界的‘瑞士军刀'，相信没有什么人不认识它吧...... 一个简单而有用的工具，透过使用TCP或UDP协议的网络连接去读写数据。它被设计成一个稳定的后门工具，能够直接由其它程序和脚本轻松驱动。同时，它也是一个功能强大的网络调试和探测工具，能够建立你需要的几乎所有类型的网络连接，还有几个很有意思的内置功能(详情请看下面的使用方法)。 在中国，它的WINDOWS版有两个版本，一个是原创者Chris Wysopal写的原版本，另一个是由‘红与黑'编译后的新‘浓缩'版。‘浓缩'版的主程序只有10多KB（10多KB的NC是不能完成下面所说的第4、第5种使用方法，有此功能的原版NC好象要60KB：P），虽然"体积"小，但很完成很多工作。  


请将解压文件放到C:\Documents and Settings\Administrator\下，然后在cmd下，C:\Documents and Settings\Administrator\nc11nt\nc11nt>下运行
nc。


参数介绍： 
nc.exe -h即可看到各参数的使用方法。 

基本格式：nc [-options] hostname port[s] [ports] ... nc

-l -p port [options] [hostname] [port]

-d 后台模式

-e prog 程序重定向，一旦连接，就执行 [危险!!] 

-g gateway source-routing hop point[s], up to 8 

-G num source-routing pointer: 4, 8, 12, ... 

-h 帮助信息 -i secs 延时的间隔 -l 监听模式，用于入站连接

-L 连接关闭后,仍然继续监听 -n 指定数字的IP地址，不能用hostname 

-o file 记录16进制的传输 -p port 本地端口号 -r 随机本地及远程端口 
-s addr 本地源地址

-t 使用TELNET交互方式 

-u UDP模式 -v 详细输出--用两个

-v可得到更详细的内容 

-w secs timeout的时间 

-z 将输入输出关掉--用于扫描时  端口的表示方法可写为M-N的范围格式。
