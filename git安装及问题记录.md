###
系统：win64
###
下载地址：https://git-scm.com/download/win
###
安装选项：默认
###
问题1：
Windows中安装Git后在CMD中出现错误'git' 不是内部或外部命令，也不是可运行的程序
解决：
需要加入环境变量，环境变量path中加入D:\git\Git\mingw32\libexec\git-core 和 D:\git\Git\bin（注意改成自己安装的Git的路径，路径以;号隔开），重启cmd
