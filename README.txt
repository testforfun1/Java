# Java
JAVA WEB技术

第一个web项目
      一、手动编写web程序
        1.构成web目录
          MyWeb 
          目录为Web项目的根目录，一般为项目名字 
          META-INF存放项目描述信息 
          WEB-INF目录不对外公开，存放项目使用的资源 
          classes存放java的class文件 
          lib存放项目使用的.jar包 
          web.xml为项目的配置文件。
        2.配置web.xml，可以拷贝已有项目中的文件
        3.配置首页index.jsp 
      二、生成war包并放到tomcat的webapps下运行
        1.使用JDK的打包，打包之前需要先进入项目目录，我这项目为myweb 
        命令：jar cvf myweb.war *
        2.将生成的.war包拷贝到Tomcat的webapps目录中
        3.然后在Tomcat的bin目录中运行startup文件启动Tomcat，Tomcat自动在webapps目录中解压 .war包，并加载项目。
        tomcat服务器开启：默认端口为8080
        4.打开浏览器，输入localhost:8080/myweb
      一个简单的手动项目就完成了。
