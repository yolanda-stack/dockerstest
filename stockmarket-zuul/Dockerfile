FROM hub.c.163.com/wuxukun/maven-aliyun:3-jdk-8      //下载maven与java的镜像
 # 指定当前操作目录
WORKDIR /stockmarketzuul                                          
#指定对外端口号
 EXPOSE 8040          
#启动java程序
#--spring.profiles.active=dev 多环境下指定环境 。 -c为清除以前启动的数据
ENTRYPOINT ["java","-jar","stockmarketzuul.jar","--spring.profiles.active=dev","-c"]