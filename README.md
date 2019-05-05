# 《Mybatis3源码深度解析》 随书源码  

<b><details><summary>📚 第一章 搭建Mybatis源码环境</summary></b>
> 主要介绍如何搭建Mybatis源码调试环境，包括Mybatis框架源码获取途径，如何导入集成开发工具，如何运行Mybatis源码中自带的测试用例。

</details>

<b><details><summary>📚 第二章 JDBC规范详解</summary></b>
> Mybatis框架是对JDBC轻量级的封装，熟练掌握JDBC规范有助于理解Mybatis框架实现原理，本章详细介绍JDBC规范相关细节，已经全面掌握JDBC规范的读者可以跳过该章节。

</details>

<b><details><summary>📚 第三章 Mybatis常用工具类</summary></b>
> 介绍Mybatis框架中常用的工具类，避免读者对这些工具类的使用不熟悉，而导致对框架主流程理解的干扰，这些工具类包括MetaObject、ObjectFactory、ProxyFactory等。

</details>

<b><details><summary>📚 第四章 Mybatis核心组件介绍</summary></b>
> 介绍Mybatis的核心组件，包括Configuration、SqlSession、Executor、MappedStatement等，本章详细介绍了这些组件的作用及Mybatis执行SQL语句的核心流程。

</details>

<b><details><summary>📚 第五章 SqlSession创建过程</summary></b>
> 主要介绍SqlSession组件的创建过程，包括Mybatis框架对XPath方式解析XML封装的工具类，Mybatis主配置文件解析生成Configuration对象的过程。

</details>

<b><details><summary>📚 第六章 SqlSession执行Mapper过程</summary></b>
> 本章介绍Mapper接口注册过程，SQL配置转换为MappedStatement对象并注册到Configuration对象的过程。除此之外，本章还介绍了通过SqlSession执行Mapper的过程。

</details>

<b><details><summary>📚 第七章 Mybatis缓存</summary></b>
> 本章首先介绍了Mybatis一级缓存和二级缓存的使用细节，接着介绍了一级缓存和二级缓存的实现原理，最后介绍了Mybatis如何整合Redis作为二级缓存。

</details>

<b><details><summary>📚 第八章 Mybatis日志实现</summary></b>
> 基于Java语言的日志框架比较多，比较常用的有Logback、Log4j等，本章介绍了Java的日志框架发展史，并介绍了这些日志框架之间的关系。最后，本章介绍了Mybatis自动查找日志框架的实现原理。

</details>

<b><details><summary>📚 第九章 动态SQL实现原理</summary></b>
> 本章主要介绍Mybatis动态SQL的使用，动态SQL配置转换为SqlSource对象的过程，以及动态SQL的解析原理，最后从源码的角度分析动态SQL配置中#{}和${}参数占位符的区别。

</details>

<b><details><summary>📚 第十章 Mybatis插件实现原理</summary></b>
> 本章介绍了Mybatis插件的实现原理，并以实际的案例介绍了如何自定义Mybatis插件。本章中实现了两个Mybatis插件，分别为分页查询插件和慢SQL统计插件。

</details>

<b><details><summary>📚 第十一章 Mybatis级联映射与懒加载</summary></b>
> 本章介绍了Mybatis中的一对一、一对多级联映射和懒加载机制的使用细节，并介绍了级联映射和懒加载的实现原理。

</details>

<b><details><summary>📚 第十二章 Mybatis与Spring整合案例</summary></b>
> 本章中以一个用户注册RESTful接口案例，介绍了Mybatis框架与Spring框架整合的最佳实践。

</details>

<b><details><summary>📚 第十三章 Mybatis与Spring整合案例</summary></b>
> 本章介绍了Spring框架中的一些核心概念，并介绍了Spring IoC容器的使用过程。接着介绍了Mybatis和Spring整合后，动态代理产生的Mapper对象是如何与Spring Ioc容器进行关联的，最后介绍了Mybatis整合Spring事务管理的实现原理。

</details>