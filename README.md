# seckill
	a 'seckill' web site which is developed by spring, spring mvc and mybatis

# Java 实现高并发秒杀
    参考文档： https://blog.csdn.net/luomingkui1109/article/details/77432192

# 环境要求
	Redis
	MySql8.0.12数据库
	Tomcat web服务中间件
	Jenkins自动化构建

# 数据库
	配置在resources下的jdbc.properties中
# 主要Controller:
	/seckill/src/main/java/com/force4us/web/SeckillController.java


# 启动项目，访问地址
	http://127.0.0.1:8888/seckill/test --测试helloworld
	http://127.0.0.1:8888/seckill/list  -- 秒杀商品列表
	http://127.0.0.1:8888/seckill/1000/detail --秒杀详情页


# Druid日志监控：web.xml配置用戶名密碼：admin/123456
	http://127.0.0.1:8888/druid/login.html    