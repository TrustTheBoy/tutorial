#### tutorial Maven project

Nearly 69 million people have been displaced from their home due to war, persecution or violence. That’s one of every 111 people on the planet.

> 使用
```shell
 mvn spring-boot:run
```

> api for tv

`http://localhost:8080/tvseries`

##### IntelliJ IDEA Spring boot devtools 实现热部署

[click see](https://www.cnblogs.com/zxguan/p/7941711.html)

##### 日志级别
- DEBUG
- INFO
- WARN
- ERROR
    
##### 使用`curl`来测试API

`curl http://127.0.0.1:8080/tvseries` 

> callback([{"id":1,"name":"WestWorld","originRelease":"2011-09-02"},...])

`curl -H "Content-Type:application/json" -X POST --data '{"name":"西部世界","seasonCount":1,"originRelease":"2016-10-02"}' http://127.0.0.1:8080/tvseries`

> callback({"id":9999,"name":"西部世界","seasonCount":1,"originRelease":"2016-10-02"})

