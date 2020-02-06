# gmall0105本地修改
##1.1 duboo 配置启动
1.启动zk

zkServer start

zkServer status

使用duboo时注意将docker和vpn都关了，vpn会虚拟出一个tun虚拟地址，duboo可能会用到

2.到tomcat目录下启动tomcat

3.在浏览器输入

http://localhost:8080/dubbo-admin-2.6.0/

## 1.2 端口使用
#gmall-user用户服务8080,不用了
gmall-user-service用户服务的service层8070

gmall-user-web用户服务的web层8060

gmall-manage-service用户服务的service层8071

gmall-manage-web用户服务的web层8081






