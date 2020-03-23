# gomicro_note

go-micro学习笔记

第一章:热身和http api篇

- 第1讲:开张课、安装框架、创建第一个web api 
- 第2讲:引入外部框架gin生成web API
- 第3讲:服务注册：快速把服务注册到Consul中
- 第4讲:[准备工作课]模拟运行API(主站API、商品API)
- 第5讲:服务发现(1):获取consul服务列表、selector随机选择
- 第6讲:穿插知识点：使用内置命令参数启动、注册多个服务
- 第7讲:服务发现(2):开启多个服务、用轮询方式获取服务
- 第8讲:服务调用:基本方式调用 Api（http api）
- 第9讲:服务调用: 使用插件、调用http api的正规姿势(初步)
- 第10讲:调用http api的姿势:带参数调用(有思考题)
- 第11讲:调用http api:引入protobuf、生成参数和响应模型
- 第12讲:处理参数模型中的json tag不一致问题

第二章:rpc和微服务

- 第13讲:使用rpc构建一个简易商品服务、注册到consul
- 第14讲:在gin中调用上节课构建的rpc服务(获取商品列表)
- 第15讲:在gin中调用rpc服务(参数名处理、代码基本封装)
- 第16讲:Go-micro的装饰器wrapper的初步使用(中间件)
- 第17讲:熔断器使用(1):hystrix初步、捕获超时报错
- 第18讲:熔断器使用(2):服务降级的使用
- 第19讲:熔断器使用(3):初步整合hystrix到go-micro中
- 第20讲:上节课课后作业：增加商品详细API(rpc)
- 第21讲:熔断器使用(4):通用降级方法的编写姿势
- 第22讲:熔断器使用(5):熔断器的参数设置

[Go-micro学习笔记（1）http调用](https://huangzhongde.cn/post/Golang/go-micro_note1/)

[Go-micro学习笔记（2）gRPC使用](https://huangzhongde.cn/post/Golang/go-micro_note2/)
