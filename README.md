# Junit-assert
junit验证你的应用程序可以按照预期的方式正常运行，尽早发现错误。
Junit最佳实践：重构
逻辑单元测试：针对一个单独的方法，mock objects or stub控制某个特定测试方法的边界
集成单元测试：真实环境中不同组建的相互作用，测试一段访问数据库的代码是否有效调用了数据库。
功能单云测试：确认一个刺激响应
让测试改善代码：检查待测试代码中的不同分支路径（if 子句、switch子句、try/catch块的结果）。
cobertura覆盖率测量工具
减少依赖关系：在隔离的情况下测试你的代码（1）实例化new对象（2）为应用程序提供逻辑方法
创造简单的构造函数
Singleon
多态优于条件语句
生成模拟对象：mock objects和stub
不要在mocks中写入业务代码
成功的秘诀在于真诚，如果你装的像，那么你就成功了
Convention over configuration-maven
HtmlUnit处理JavaScript
单元测试必须执行隔离代码，但是持久层需要和外部实体数据库交互。
