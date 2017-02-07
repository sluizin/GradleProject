#GradleProject
*建立一个基于Gradle的Springmvc+mybates+mysql+freeMarker的项目<br/>
*其中:<br/>
*数据库连接池:commons-dbcp<br/>
*{'mybatis:3.3.0'+'mybatis-spring:1.2.3'}(因为使用了org.mybatis.spring.mapper.MapperScannerConfigurer)[@MapperScan注解]<br/>
*
*考虑打包时的环境变量时，请使用[gradle build -Denv=test]命令进行打包[dev/test/online]默认为dev<br/>
*目录下的profile-XXXX.gradle暂时不使用<br/>
*1.bat为在cmd下的批处理<br/>
*<br/>
*http://localhost/GradleProject/controller/show/0<br/>