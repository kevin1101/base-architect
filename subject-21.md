## 第二十一章节 应急响应
在以无法通过服务治理中心操作解决的问题时 通知到应急响应部门 并尽可能的辅助应急响应部门解决问题

### 21.1 报警机制
当系统 应用服务 流量等出现异常时 会及时的向相关人员发送警报  
场景:  
1)应用服务宕机  
2)网络故障  
3)磁盘写满  
4)cpu/内存/io持续过高  
5)应用服务超时报警  
6)自动熔断降级  

### 21.2 流量实时监控
对各级流量进行实时大屏监控 一旦出现报警或问题 可第一时间采取措施

### 21.3 预警
根据各项参数如(时间 流量 负荷 出错率等) 做一些预警算法来预测是否有需要报警的情况出现 也可通过机器学习来达到预警效果  
场景:     
1)流量突发增大 疑似攻击  
2)出错率无征兆增大  
3)高峰期预算 硬件能力计算

 <a href="subject-20.md">上一章节</a>  <a href="subject-22.md">下一章节</a>