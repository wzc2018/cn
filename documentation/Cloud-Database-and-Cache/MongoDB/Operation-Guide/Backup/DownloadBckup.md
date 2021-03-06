# 下载备份文件

云数据库 MongoDB 支持备份下载功能，用户可以根据需要自行下载备份文件。

## 操作步骤：
1. 登录 [MongoDB 控制台](https://mongodb-console.jdcloud.com/mongodb)。
1. 在实例列表页面，选择目标实例，点击实例名称，进入实例详情页面。
1. 在实例详情页面，点击备份与恢复， 查看备份数据。
1. 选择要下载的备份，在操作项中，点击“下载”，打开下载弹窗。
	
   ![](https://github.com/jdcloudcom/cn/blob/master/image/mongodb/mongo-020.png)

1. 下载备份文件到本地。

	说明
	
	- 内网地址和外网地址有效期为24小时；
	- 使用wget下载时需要对URL添加英文引号；
	- 若云主机与云数据库在同一地域，建议您采用内网地址下载；

## 相关参考

- [数据恢复](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Operation-Guide/Backup/RestoreInstance.md)
- [根据备份创建实例](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Operation-Guide/Backup/CreateInstance2.md)
- [根据时间点创建实例](https://github.com/jdcloudcom/cn/blob/master/documentation/Cloud-Database-and-Cache/MongoDB/Operation-Guide/Backup/CreateInstance3.md)
