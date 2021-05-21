# zuoye
1.IPersistence_test主要修改：
(1) IPersistenceTest新增了增、删、改测试接口
(2) 修改了UserMapper.xml文件，新增了增、删、改

2.IPersistence主要修改：
(1) DefaultSqlSession修改了getMapper方法，增加增、删、改操作判断
(2) SimpleExecutor增加增、删、改操作接口
