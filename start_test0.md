### 初次学习sql，之前下载了好像嫌SqlServer自动重启很烦人，就手动禁用了。
### 再次学习时发现打开SqlServer studio时无法建立连接
### 解决方法：
 ### 此电脑>> 管理>> 服务和应用程序>> 服务 >> SQL server(mssqlserver)
   ### 右键属性设置手动
![image](https://github.com/IamNot-GrandmaLi/sql/assets/105012688/614ada38-5d40-4922-a179-6cf562e092cc)
### 此外，打开SqlServer的方法：
  ### 1、如上手动打开
  ### 2、cmd 管理员权限 
    net start mssqlsever
  	net stop mssqlserver
      
