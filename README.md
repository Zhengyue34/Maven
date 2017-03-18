# Maven
http://blog.csdn.net/dr_lf/article/details/7292441

Maven常用指令：
命令 
    mvn pom.xml文件配置详解 
    http://maven.apache.org/ref/2.0.8/maven-model/maven.html 

    mvn -version/-v 显示版本信息 
    mvn archetype:generate   创建mvn项目 
    mvn archetype:create -DgroupId=com.oreilly -DartifactId=my-app   创建mvn项目 

    mvn package    生成target目录，编译、测试代码，生成测试报告，生成jar/war文件 
    mvn jetty:run    运行项目于jetty上, 
    mvn compile      编译 
    mvn test      编译并测试 
    mvn clean      清空生成的文件 
    mvn site      生成项目相关信息的网站 
    mvn -Dwtpversion=1.0 eclipse:eclipse   生成Wtp插件的Web项目 
    mvn -Dwtpversion=1.0 eclipse:clean   清除Eclipse项目的配置信息(Web项目) 
    mvn eclipse:eclipse     将项目转化为Eclipse项目 
   mvn -U package使用-U参数： 该参数能强制让Maven检查所有SNAPSHOT依赖更新，确保集成基于最新的状态，如果没有该参数，Maven默认以天为单    位检查更新，而持续集成的频率应该比这高很多
