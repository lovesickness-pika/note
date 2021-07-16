### spring IOC容器

Spring ioc 容器是一个IOC Service Provider，提供了两种容器类型：

BeanFactory，ApplicationContext

##### BeanFactory

- BeanFactory是基础类型的IOC容器，提供了完整的IOC服务支持，此容器默认采用延迟初始化的策略，即在容器内的某个对象第一次被访问时，才进行初始化和依赖注入操作

##### ApplicationContext

- ApplicationContext在BeanFactory的基础上构建，继承了BeanFactory的全部功能，且提供了更多的额外功能：
  - 国际化

### AOP

### 设计模式

### 循环依赖

### 事务

### 生命周期

### 传播特性
