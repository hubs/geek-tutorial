JavaScript核心原理解析 / 重构你对JavaScript语言的认知
======================================

周爱民 **《JavaScript语言精髓与编程实践》作者，南潮科技（Ruff）首席架构师**
-----------------------------------------------

![JavaScript核心原理解析](https://www.geekgay.com/storage/geek/geek_57d24da819624787d85a8fd891b5907b.jpg)  
  
👉👉[**订阅返现**](https://time.geekbang.org/column/intro/100039701?code=OKfsLyUbyNHnYwKKu6tlKTnUgxFpxIclf5iQU52XvWU%3D "JavaScript核心原理解析")  
  
课程目录
----

  
  
- 开篇词 | 如何解决语言问题？
- 01 | delete 0：JavaScript中到底有什么是可以销毁的
- 02 | var x = y = 100：声明语句与语法改变了JavaScript语言核心性质
- 03 | a.x = a = {n:2}：一道被无数人无数次地解释过的经典面试题
- 04 | export default function() {}：你无法导出一个匿名函数表达式
- 05 | for (let x of \[1,2,3\]) ...：for循环并不比使用函数递归节省开销
- 加餐 | 捡豆吃豆的学问（上）：这门课讲的是什么？
- 加餐 | 捡豆吃豆的学问（下）：这门课该怎么学？
- 06 | x: break x; 搞懂如何在循环外使用break，方知语句执行真解
- 07 | `${1}`：详解JavaScript中特殊的可执行结构
- 08 | x =&gt; x：函数式语言的核心抽象：函数与表达式的同一性
- 09 | (...x)：不是表达式、语句、函数，但它却能执行
- 10 | x = yield x：迭代过程的“函数式化”
- 11 | throw 1;：它在“最简单语法榜”上排名第三
- 加餐 | 让JavaScript运行起来
- 12 | 1 in 1..constructor：这行代码的结果，既可能是true，也可能是false
- 13 | new X：从构造器到类，为你揭密对象构造的全程
- 14 | super.xxx()：虽然直到ES10还是个半吊子实现，却也值得一讲
- 15 | return Object.create(new.target.prototype)：做框架设计的基本功：写一个根类
- 16 | \[a, b\] = {a, b}：让你从一行代码看到对象的本质
- 17 | Object.setPrototypeOf(x, null)：连Brendan Eich都认错，但null值还活着
- 18 | a + b：动态类型是灾难之源还是最好的特性？（上）
- 19 | a + b：动态类型是灾难之源还是最好的特性？（下）
- 20 | (0, eval)("x = 100") ：一行让严格模式形同虚设的破坏性设计（上）
- 21 | (0, eval)("x = 100") ：一行让严格模式形同虚设的破坏性设计（下）
- 22 | new Function('x = 100')();：函数的类化是对动态与静态系统的再次统一
- 结束语 | 愿你能做一个真正“懂”的程序员
- 结课测试 | 这些JavaScript知识，你真的掌握了吗？