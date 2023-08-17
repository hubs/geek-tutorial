小马哥讲Spring AOP编程思想 / 深入掌握Spring AOP的核心用法
========================================

小马哥 **《Spring Boot编程思想》作者、Spring Cloud Alibaba项目架构师**
-----------------------------------------------------

![小马哥讲Spring AOP编程思想](https://www.geekgay.com/storage/geek/geek_e3805eec0f8d522de0c3f674385316be.jpg)  
  
👉👉[**订阅返现**](https://time.geekbang.org/column/intro/100066301?code=D0d%2F5TUcriC-CyBJVfOJTAN3fmMVl74lBnKHbAHvNmQ%3D "小马哥讲Spring AOP编程思想")  
  
课程目录
----

  
  
- 06 | AOP概念：Aspect、Join Point和Advice等术语应该如何理解？
- 07 | Java AOP设计模式：代理、判断和拦截器模式
- 08 | Java AOP代理模式（Proxy）：Java静态代理和动态代理的区别是什么？
- 09 | Java AOP判断模式（Predicate）：如何筛选Join Point？
- 10 | Java AOP拦截器模式（Interceptor）：拦截执行分别代表什么？
- 11 | Spring AOP 功能概述：核心特性、编程模型和使用限制
- 12 | Spring AOP编程模型：注解驱动、XML配置驱动和底层API
- 13 | Spring AOP设计目标：Spring AOP与 AOP框架之间的关系是竞争还是互补？
- 14 | Spring AOP Advice类型：Spring AOP丰富了哪些AOP Advice呢？
- 15 | Spring AOP代理实现：为什么Spring Framework选择三种不同AOP实现？
- 16 | JDK动态代理：为什么Proxy.newProxyInstance会生成新的字节码？
- 17 | CGLIB动态代理：为什么Java动态代理无法满足AOP的需要？
- 18 | AspectJ代理代理：为什么Spring推荐AspectJ注解？
- 19 | AspectJ基础：Aspect、Join Points、Pointcuts和Advice语法和特性
- 20 | AspectJ注解驱动：注解能完全替代AspectJ语言吗？
- 21 | 面试题精选
- 22 | Spring核心基础：《小马哥讲Spring核心编程思想》还记得多少？
- 23 | @AspectJ注解驱动
- 24 | 编程方式创建 @AspectJ代理
- 25 | XML配置驱动 - 创建AOP代理
- 26 | 标准代理工厂API - ProxyFactory
- 27 | @AspectJ Pointcut指令与表达式：为什么Spring只能有限支持？
- 28 | XML配置Pointcut
- 29 | API实现Pointcut
- 30 | @AspectJ拦截动作：@Around与@Pointcut有区别吗？
- 31 | XML配置Around Advice
- 32 | API实现Around Advice
- 33 | @AspectJ前置动作：@Before与@Around谁优先级执行？
- 34 | XML配置Before Advice
- 35 | API实现Before Advice
- 36 | @AspectJ后置动作 - 三种After Advice之间的关系？
- 37 | XML配置三种After Advice
- 38 | API实现三种After Advice
- 39 | 自动动态代理
- 40 | 替换TargetSource
- 41 | 面试题精选
- 42 | Spring AOP API整体设计
- 43 | 接入点接口 - Joinpoint
- 44 | Joinpoint条件接口 - Pointcut
- 45 | Pointcut操作 - ComposablePointcut
- 46 | Pointcut便利实现
- 47 | Pointcut AspectJ实现 - AspectJExpressionPointcut
- 48 | Joinpoint执行动作接口 - Advice
- 49 | Joinpoint Before Advice标准实现
- 50 | Joinpoint Before Advice AspectJ实现
- 51 | Joinpoint After Advice标准实现
- 52 | Joinpoint After Advice AspectJ实现
- 53 | Advice容器接口 - Advisor
- 54 | Pointcut与Advice连接器 - PointcutAdvisor
- 55 | Introduction与Advice连接器 - IntroductionAdvisor
- 56 | Advisor的Interceptor适配器 - AdvisorAdapter
- 57 | AdvisorAdapter实现
- 58 | AOP代理接口 - AopProxy
- 59 | AopProxy工厂接口与实现
- 60 | JDK AopProxy实现 - JdkDynamicAopProxy
- 61 | CGLIB AopProxy实现 - CglibAopProxy
- 62 | AopProxyFactory配置管理器 - AdvisedSupport
- 63 | Advisor链工厂接口与实现 - AdvisorChainFactory
- 64 | 目标对象来源接口与实现 - TargetSource
- 65 | 代理对象创建基础类 - ProxyCreatorSupport
- 66 | AdvisedSupport事件监听器 - AdvisedSupportListener
- 67 | ProxyCreatorSupport标准实现 - ProxyFactory
- 68 | ProxyCreatorSupport IoC容器实现 - ProxyFactoryBean
- 69 | ProxyCreatorSupport AspectJ实现 - AspectJProxyFactory
- 70 | IoC容器自动代理抽象 - AbstractAutoProxyCreator
- 71 | IoC容器自动代理标准实现
- 72 | IoC容器自动代理 AspectJ 实现 - AspectJAwareAdvisorAutoProxyCreator
- 73 | AOP Infrastructure Bean接口 - AopInfrastructureBean
- 74 | AOP上下文辅助类 - AopContext
- 75 | 代理工厂工具类 - AopProxyUtils
- 76 | AOP工具类 - AopUtils
- 77 | AspectJ Enable模块驱动实现 - @EnableAspectJAutoProxy
- 78 | AspectJ XML配置驱动实现 - <aspectj-autoproxy></aspectj-autoproxy>
- 79 | AOP配置Schema-based 实现 - <config></config>
- 80 | Aspect Schema-based实现 - <aspect></aspect>
- 81 | Pointcut Schema-based实现 - <pointcut></pointcut>
- 82 | Around Advice Schema-based实现 - <around></around>
- 83 | Before Advice Schema-based实现 - <before></before>
- 84 | After Advice Schema-based实现 - <after></after>
- 85 | After Returning Advice Schema-based实现 - <after-returning></after-returning>
- 86 | After Throwing Advice Schema-based实现 - <after-throwing></after-throwing>
- 87 | Adviser Schema-based实现 - <advisor></advisor>
- 88 | Introduction Schema-based实现 - <declare-parents></declare-parents>
- 89 | 作用域代理Schema-based实现 - <scoped-proxy></scoped-proxy>
- 90 | 面试题精选
- 91 | 抽象工厂模式（Abstract factory）实现
- 92 | 构建器模式（Builder）实现
- 93 | 工厂方法模式（Factory method）实现
- 94 | 原型模式（Prototype）实现
- 95 | 单例模式（Singleton）实现
- 96 | 适配器模式（Adapter）实现
- 97 | 组合模式（Composite）实现
- 98 | 装饰器模式（Decorator）实现
- 99 | 享元模式（Flyweight）实现
- 100 | 代理模式（Proxy）实现
- 101 | 模板方法模式（Template Method）实现
- 102 | 责任链模式（Chain of Responsibility）实现
- 103 | 观察者模式（Observer）实现
- 104 | 策略模式（Strategy）实现
- 105 | 命令模式（Command）实现
- 106 | 状态模式（State）实现
- 107 | 面试题精选
- 108 | Spring AOP在 Spring 事件（Events）
- 109 | Spring AOP在Spring 事务（Transactions）理论基础
- 110 | Spring AOP在Spring 事务（Transactions）源码分析
- 111 | Spring AOP在Spring 缓存（Caching）
- 112 | Spring AOP在Spring本地调度（Scheduling）
- 113 | 面试题精选
- 114 | 结束语