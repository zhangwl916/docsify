# Linux的sz和rz命令

工作中需要在Linux和Windows之间传输文件时，一般使用winscp或者ftp工具来完成，最近才知道有sz和rz这两个命令，方便好用。 

## sz  下载 

从Linux下载文件到本机 , 在Linux终端输入命令回车后，选择本地存储路径即可。 

命令格式：    

sz filename         下载文件filename 

sz file1 file2        下载多个文件 

sz dir/*                下载dir目录下所有文件

##  rz   上传

 从本地上传文件到Linux，在Linux终端输入命令回车后，选择本地要上传的文件即可，可一次指定多个文件

 命令格式：    rz 

### 注意： 

1.如果机器上没有安装过 lrzsz 安装包，则无法使用rz和sz命令。 可使用yum命令安装：yum install -y lrzsz 或者下载源码进行安装。下载地址：https://ohse.de/uwe/software/lrzsz.html 

2.上传和下载都默认使用Linux当前登录的用户，使用时要根据个人需要修改文件的权限。
