# mqtt
Autotools 构建paho.mqtt.c 生成libpaho_mqtt.a 静态库
# 编译
编译平台：cygwin
需要安装：autoconf、automake
目标：生成 libpaho_mqtt.a 静态库
#正常流程
#1
aclocal
#2
autoheader
#3
autoconf
#4
automake --add-missing
#5
./configure
#6
make -j8
备注1.如果修改过configure.ac,请从#1开始重新执行命令
2.如果修改过Makefile.am,请从#4开始执行命令
3.configure.ac主要为环境配置，比如检查某个头文件是否存在等，库是不存在，自己增加一个autotool子模块后等
4.Makefile.am主要是当前目录的代码配置，如果增加了代码文件，等等
