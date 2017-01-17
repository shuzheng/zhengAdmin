# zhengAdmin

基于bootstrap实现的响应式Material Design风格的通用后台管理系统

# 在线演示

地址： [http://www.zhangshuzheng.cn/zhengAdmin](http://www.zhangshuzheng.cn/zhengAdmin "zhengAdmin")

# 使用方法

* 1、本地编译源码为jar包到本地maven仓库；
* 2、增加zhengAdmin依赖：
``` xml
<dependency>
    <groupId>com.github.shuzheng</groupId>
    <artifactId>zhengAdmin</artifactId>
    <version>1.0.0</version>
</dependency>
``` 
* 3、spring配置文件增加自解压工具类，可在工具类中配置自解压到目标目录等配置。[工具类源码](https://github.com/shuzheng/zheng/blob/master/zheng-upms/zheng-upms-server/src/main/java/com/zheng/upms/admin/util/ZhengAdminUtil.java "工具类源码")
``` xml
<bean id="zhengAdminUtil" class="com.zheng.upms.admin.util.ZhengAdminUtil"></bean>
``` 


![预览效果图](images/zheng-upms-crud.png)

# License
  MIT

