1 使用系统代理，不能使用公司内网代理

2 网络代理使用  ，网页代理和网络安全代理 ，并且配置安全网页代理服务器为127.0.0.0.1， 端口配置为跟charles中的Proxy->proxy setting中的端口一致

3 在tools的map remote中配置映射关系

4 需要登录线下测试账号，不然娶不到cookie

5 使用前在help ，ssl proxying中安装证书

6 使用时需要关掉switchomega   chrome域名切换工具s

7 使用前需要把已经打开的所有chrome浏览器使用Q快捷键关掉，不然显示权限有问题

8 终端启动chrome:  /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --ignore-certificate-errors &> /dev/null &
