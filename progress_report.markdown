Progress report
=====================
包括完成的工作和2014.5.5之前v1.0需要完成的任务

Review
-----------
### Client 
1. 搜索机票
 * 出发到达时间完成
 * 机场搜索条件完成
 * 时间段搜索完成
2. 机票结果
 * 机票列表完成
 * 价格走势界面完成
2. 个人中心
 * 界面完成
3. 登录注册模块
 * 界面完成
5. 订单模块
 * 订单信息填写完成
6. 订阅模块
 * 界面完成


### Server 
1. 用户模块
 * 登录已完成
 * 注册已完成
 * 修改账户信息已完成
 * 修改推送设置已完成
2. 订阅模块
 * 添加已完成
 * 修改已完成
 * 取消接口已完成
 * 订阅与用户用关系表绑定，多个用户可以共用同一订阅，订阅历史价格保存在单独数据表中
3. 推送模块
持续刷新订阅价格逻辑完成
推送测试通过

### Data
 * 去哪儿爬虫demo完成

TODO
---------------
### Client
1. 搜索机票
 * 往返
 * 航空公司排序：可否主流航空公司在前？
 * 舱位选择
 * Picker配色调整
2. 机票结果
 * 价格走势网络问题
 * 进一步筛选
 * 航空logo，
2. 个人中心
 * 首次打开应用时，点击个人中心跳往welcome页
 * 各类订单数据
 * 用户数据
3. 登录模块
 * 登录／注册数据与后台连接
4. 订单模块
 * 添加到Passbook
 * webview 支付
5. 订阅模块
 * 与后台数据连接

### 以下不包含在v1.0内
#### Server
1. 推送模块
 * 尚未解决合适的运行／部署方案
2. 机票模块
 * 机票数据库待建，接口未开始
3. 分布式运行与部署

#### Data
1. 去哪儿机票数据库待建
2. 部署在俱乐部服务器测试
3. 往返机票
