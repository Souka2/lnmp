### 高可用的网站架构拓扑图

![](E:\desktop\lnmp\structure.png)
![](structure.png)

###### 项目目标

• 保证数据的安全高可用性，增强服务器性能，提高用户的体验度  

###### 项目环境

• DNS 域名解析：方便用户记忆，可以适当的提高上网速度，突出网站个性化  
• Lvs+Keepalived：代理服务器，为服务器提供健康检查功能，当有漏洞时可以及时维护  
• LNMP 部署 Web 网站: 网站多功能化, 集群可实现负载均衡, 实现网站高可用  
• 数据读写分离技术: 减轻数据库服务器压力, 提高读写效率, 提升用户体验度  
• Ceph 分布式存储数据: 利用 Ceph 的可扩展和高可用性，满足业务增长导致的海量数据存储的需求

###### 项目收获

• Lvs 加强了我对网络的认知,Ceph 存储提高了我对数据的管理效率  
• Web 网站的搭建使得我更加了解客户需求, 力图全方面满足客户需求
