# Junit-assert
junit验证你的应用程序可以按照预期的方式正常运行，尽早发现错误。</br>
Junit最佳实践：重构<\b>
逻辑单元测试：针对一个单独的方法，mock objects or stub控制某个特定测试方法的边界</br>
集成单元测试：真实环境中不同组建的相互作用，测试一段访问数据库的代码是否有效调用了数据库。</br>
功能单云测试：确认一个刺激响应</br>
让测试改善代码：检查待测试代码中的不同分支路径（if 子句、switch子句、try/catch块的结果）。</br>
cobertura覆盖率测量工具</br>
减少依赖关系：在隔离的情况下测试你的代码（1）实例化new对象（2）为应用程序提供逻辑方法</br>
创造简单的构造函数</br>
Singleon</br>
多态优于条件语句</br>
生成模拟对象：mock objects和stub</br>
不要在mocks中写入业务代码</br>
Convention over configuration-maven</br>
HtmlUnit处理JavaScript</br>
单元测试必须执行隔离代码，但是持久层需要和外部实体数据库交互。</br>
一个测试应该遵循三段论: 初始化场景，执行被测试方法，验证执行结果，所以一个理想的测试方法应该只有三行</br>
别重复自己</br>
junit中的每个函数有且只有一个断言</br>
整洁的测试五个原则：</br>
快速</br>
独立</br>
可重复</br>
自足验证</br>
及时</br>

mockito</br>
powermock</br>
JMock</br>


#修改代码的艺术
感知:解依赖</br>
分离：解依赖</br>
伪对象</br>
仿对象mock object</br>