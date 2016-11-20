# 简介
本工具用来备份微信的Data文件,防止在撤回后被微信删除.
备份的dat文件将会在微信Data文件夹内,也就是程序运行的文件夹内.
基本原理是在运行时检测到微信生成新的dat文件,然后将dat文件拷贝一份,重命名.
所以例如微信生成了一个名为 a.dat 的文件,那么备份文件将会是 a.dat.bak .

# 下载地址
[百度盘](http://pan.baidu.com/s/1c2EBb3M) 密码: p7mq

# 简要说明
1. 下载软件
2. 解压到微信Data文件夹内,文件夹的路径为 C:\Users\*你的用户名*\Documents\WeChat Files\*微信用户名*\Data
3. 运行软件

# 功能介绍
- 开机自启动,会写入注册表的启动项.
- 启动后最小化,会自动将启动后的程序最小化到右下角.
- 自动清理,将自动清理3天以上的备份文件.
- 托盘图标,双击可以打开界面,右键有其他菜单项.