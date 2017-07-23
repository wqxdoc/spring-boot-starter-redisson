Spring Boot Starter Redisson
============================
[![](https://jitpack.io/v/linux-china/spring-boot-starter-redisson.svg)](https://jitpack.io/#linux-china/spring-boot-starter-redisson)

在Spring Boot下整合Redisson,方便客户端使用.

### 如何使用

Please refer https://jitpack.io/#linux-china/spring-boot-starter-redisson/3.3.2

* 在spring-boot-starter-redisson是依赖spring-boot-starter-data-redis的配置,所以你只需要加入spring boot redis的相关配置即可,如下:
```properties
spring.redis.host=localhost
```

* 接下来在你的代码中直接应用RedissonClient，然后就可以啦。
```
@Autowired
private RedissonClient redissonClient;
```
### spring-boot-start-hibernate5提供的服务

* org.redisson.RedissonClient: Redisson Client

### 参考文档

* Redisson Site: http://redisson.org/
* Redisson github: https://github.com/mrniko/redisson/wiki/Usage-examples
* Chinese document: https://github.com/redisson/redisson/wiki/%E7%9B%AE%E5%BD%95