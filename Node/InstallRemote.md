# 远程安装边缘节点
可以通过SSH远程安装节点，省去了手动解压和修改配置文件的麻烦。

1. 可以在"集群节点" -- "安装升级" -- "远程安装" 界面中查看等待安装的边缘节点；
2. 点击列表中的"安装"，即可安装对应的节点；安装过程中可能有一些问题需要解决，会直接弹出窗口修改即可；
3. 通过SSH安装的节点也可以通过SSH远程启动和停止节点。

## 确认启动状态
可以在单个集群的"集群节点"中查看节点的状态：
![集群节点列表](InstallManual1.png)   

正常情况下，状态应该为"运行中"。
   
## 注意事项
1. 单个服务器同时只能启动一个边缘节点。