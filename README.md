framework_impl
---

Framework principle exploration and basic implement.
  
#### 目前为止有的原理实现有:
* 模仿 MyBatis,利用 Spring 提供的拓展点还原 MyBatis 接口代理对象生产流程
* 利用java提供的 AbstractQueuedSynchronizer 和 Lock 接口自定义一个简单的锁  
* 使用BIO实现了基本的 RPC 远程服务调用
