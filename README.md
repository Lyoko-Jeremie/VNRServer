# Visual Novel Reader Lite Server
使用`.NET Core`编写的轻量级`Visual Novel Reader`服务器，可以本地运行。
## 编译
1. 使用`Visual Studio 2019`打开项目
2. 还原所有`NuGget`包
3. 编译
## 运行
1. 在`appsettings.json`中更改本地数据库文件的路径
2. 打开`Package Manager Console`控制台
3. 执行`Add-Migration Init`创建数据库构造代码
4. 执行`Update-Database`创建本地数据库文件
## 客户端配置
+ 替换`ClientFiles`中的文件即可
## 其它备注
+ 已实现基本API
+ 未实现查询缓存
