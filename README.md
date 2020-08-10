校园网自动登录

# 文件说明
Curl 包装curl库的get请求

NetworkManager 负责登录和登出

UserManager 负责保存读取用户信息

Utils 工具类 添加删除开机启动

注意UserInfo中的用户名并不是单纯的学号, 而是学号+@+运行商缩写 UserManager中的OperateChangeUserInfo函数有所体现

# 使用
使用vs2019打开 sln文件 选择Debug或者Release x86模式可以直接编译可执行文件

# 注意
由于是静态编译 需要给vs安装MFC, 
安装方式 工具->获取新的功能->单个组件->搜索MFC->安装最下方的 适用于最新v142生成工具的C++MFC X86和X64
