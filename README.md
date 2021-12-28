简化安装，ETH以太坊代理矿池，MinerProxy/矿池代理，支持TCP和SSL协议，支持自定义抽水，高性能高并发，web界面管理。开发费0.5%
## Liunx下 最好是ubuntu18 20
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
centos下运行：  yum install -y git  
ubuntu下运行：sudo apt-get install git 

交流群：
https://t.me/MinerProxyLite 
