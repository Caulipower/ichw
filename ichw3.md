#### 通用高速缓存存储器
##### 1. 结构
高速缓存存储器主要由三部分组成
Cache存储体：存放由主存调入的指令与数据块。  
地址转换部件：建立目录表以实现主存地址到缓存地址的转换。  
替换部件：在缓存已满时按一定策略进行数据块替换，并修改地址转换部件。  
##### 2. 工作原理