Release Notes
-------------

**0.4.8**
* 新增阶梯计价功能

**0.4.7**
* 调用部分接口发生错误时，不抛出异常，包括(alert, get user, billing)

**0.4.6**

* 在执行gring-dbsync时，先检查keystone服务是否可用
* 消费预估API权限改为uos_staff
* 新增公网IP落地备案的功能
* 修复listener状态判断错误
* 修复计费自动修复，检查出虚拟机状态不一致时，自动修复错误
* 根据keystone service-list来动态加载服务
* 自动检查获取资源的准确状态
* 欠费删除路由器/公网IP时，如果绑定了tunnel，就删除不掉
* 新增父子账户间转账功能