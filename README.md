# drcom-python
将配置生成脚本生成的配置文件更改文件名为drcom.conf
将drcom.conf使用winscp上传到openwrt路由器的/etc文件夹中 
cd /etc/rc.local
在exit 0前一行添加一句drcom 
重启路由器之后 路由器会自动运行drcom.py脚本  模拟登陆drcom客户端！
