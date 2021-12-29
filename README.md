简化安装，ETH以太坊代理矿池，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，web界面管理。开发费0.5~2%

## LINUX(推荐系统ubuntu18+，次选系统centos7+)   

## 一键安装 ##

bash <(curl -s -L https://git.io/JyXGu)  

如果提示 curl: command not found ，那是因为你的 VPS 没装 curl  
ubuntu/debian 系统安装 curl 方法: apt-get update -y && apt-get install curl -y  
centos 系统安装 curl 方法: yum update -y && yum install curl -y  
安装好 curl 之后就能安装脚本了  

## 手动安装 ##
git clone https://github.com/nicococococ/MinerProxyLite.git  
cd MinerProxyLite  
chmod a+x MinerProxyLite  

后台运行命令：
nohup ./MinerProxyLite &  
注意：& 也需要复制，运行完再敲几下回车)、

后台查看命令：
tail -f nohup.out  

退出后台查看：
ctrl+c  

遇到缺少git:  
centos下运行：yum install -y git  
ubuntu下运行：sudo apt-get install git 

centos需要开放端口   
添加指定需要开放的端口：  
firewall-cmd --add-port=18888/tcp --permanent    
重载入添加的端口：    
firewall-cmd --reload   
查询指定端口是否开启成功：   
firewall-cmd --query-port=18888/tcp   

交流群：
https://t.me/MinerProxyLite 
