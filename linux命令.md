### 1 sz rz 命令rz、sz——文件上传下载** 

运行命令Sudo rz，即是接收文件，xshell就会弹出文件选择对话框，选好文件之后关闭对话框，文件就会上传到linux里的当前目录 。 

运行命令Sudo sz file 就是发文件到windows上（保存的目录是可以配置） 比ftp命令方便多了，而且服务器不用再开FTP服务了。 

如果上传大文件失败，可以使用  rz -be 

### 2 nc 监听某个端口接收的数据

nc -l -p 3333

### 3 scp 将远程主机文件复制到本地           

scp 127.0.0.1:/home/chenheng/mydev/devgo/*    .

### 4  netstat 找出程序运行的端口

netstat -anp | grep ':80'

### 5 压缩解压文件
压缩文件
tar -zcvf /home/xahot.tar.gz /xahot
tar -zcvf 打包后生成的文件名全路径 要打包的目录
例子：把/xahot文件夹打包后生成一个/home/xahot.tar.gz的文件。

解压文件
tar -zxvf mall.tar

### 6 
