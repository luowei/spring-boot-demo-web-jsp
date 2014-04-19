# Hello spring-boot-sample-web-jsp

### 打包 
1.打成可放置到tomcat容器中war包：mvn package

2.打成可独立运行的jar：
 把spring-boot-starter-tomcat与org.apache.tomcat.embed依赖的provied属性去掉;
 `<packaging>war</packaging>` 改成 `<packaging>jar</packaging>`;
 mvn package ;
 运行：java -jar xxxxx.jar
 