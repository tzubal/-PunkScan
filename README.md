# -PunkScan

 ![image](http://image.3001.net/images/20161020/1476925951160.png!small)
                                               
git clone https://bitbucket.org/punkspider/punkscan.git

PunkSPIDER是一款由PunkSCAN出品的大型WEB漏洞扫描器，我们利用它已经建立了一个稳定的扫描体系，每日可以实现无人值守式的运行。
此外，其中运行了一个Apache Hadoop集群，每天能处理的扫描任务数以万计。
PunkSPIDER的特性
该扫描服务会在网上随机爬行，寻找可能存在漏洞的WEB应用，发起一些诸如SQL盲注、传统SQL注入，以及XSS等攻击。游客可以通过PunkSPIDER
搜索一个URL或者一个关键词，得到相关网站的结果。同时，它采用了如Apache Hadoop等大数据级别的高端技术，但幸运的是这些都是开源的。
  
PunkSPIDER项目的设计思想是，站长可以通过搜索自己的网站来验证其是否做好了基本的安全措施，这个结果可能会激励用户优化自身的安全措施。
当然，如果是那些不怀好意的人使用了PunkSPIDER，可能会让无辜的网站受到的威胁更大。这时候，站长可以选择通过修改robots.txt，或者优化
防火墙和路由的IP规则，退出该扫描器的监控。
