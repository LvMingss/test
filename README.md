水晶报表打印"已达到系统管理员的最大报表处理作业数限制”解决

vs2015利用报表打印出现该问题


操作系统windows server 2008中

regedit打开注册表找到

HKEY_LOCAL_MACHINE;SOFTWARE;Wow6432Node;SAP BusinessObjects;Crystal Reports for .NET Framework 4.0;Report Application Server;InprocServer;PrintJobLimit修改为1000

HKEY_LOCAL_MACHINE;SOFTWARE;Wow6432Node;SAP BusinessObjects;Crystal Reports for .NET Framework 4.0;Report Application Server;Server;PrintJobLimit 也修改为1000

转自：
https://blog.csdn.net/hanbingdenuan/article/details/53579791
