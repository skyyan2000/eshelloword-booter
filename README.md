#基于bboss es booter demo 的maven工程
本实例是一个bboss es booter的demo maven工程，可供各种类型项目集成参考


# 工程集成说明
## 快速集成和应用 
非spring boot项目：
https://my.oschina.net/bboss/blog/1801273 

spring boot项目：
https://my.oschina.net/bboss/blog/1835601

详细配置说明，参考文档：
https://my.oschina.net/bboss/blog/1556866

## demo功能说明：

## 2.1 定义实体对象Demo

## 2.2 编写测试功能对象-DocumentCRUD.java
   创建dsl配置文件-esmapper/demo.xml
   
   删除和创建mapping
   
   单文档添加/修改/删除
   
   文档批量添加(elasticsearch不是实时flush记录，所以批量添加后如果立即查询可能查询不到刚添加的记录)
   
   文档批量修改(elasticsearch不是实时flush记录，所以批量修改后如果立即查询可能查询不到刚修改的效果)
   
   文档检索
   
   关键词高亮检索
   
## 2.3 参考文档
https://my.oschina.net/bboss/blog/1556866

## 开发交流群
166471282
  