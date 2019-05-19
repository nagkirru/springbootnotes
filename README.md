# springbootnotes
springboot notes






   BOM -- bill of materials
   spring core 4.2.3 - logback 1.1.3 
   
   by using spring boot all version matching setup already
   we dont need to spend time finding which library matches well ors o
   
   starter-arent will bring in all maven dependency
   
   it will pull plugin , java min version and so on
   
   take a look of BOM closely
   

there is no versio specified, because starter-parent defines depenedecy and versions
   

  ============
  https://start.spring.io/
  
  
  https://github.com/spring-projects/spring-boot/tree/master/spring-boot-samples
  
  
==============

how Spring boot work with out TOMCAT ?

we simply ran java main class.. what happens ?

1)App is started from java main class - PSVM main methid

2)SPrng boot initilizes Springcontext and compriseds spring app and auto config's initilizers confgi/annotations 
that direct how to initialize and start up the spring

3) Embedded server container  which will elimate web.xml 
we will have option to change port


PSVM -- starts java and app
@SpringBootApplication  -- 
@COnfiguration   --  spring cong   on start up ---  (old Web.xml)
@EnableAutoCOnfiguraion  -- springboot specific annot - auto confi'g the frameworks and wire them ..  started-web will being in this,
@COmponentScan --  looks for controllers  -- scans for Spring components  ..   best to keep MAIN class at top level


SpringApplication.run();  Starts Spring, creates Spring context, applies annotations and sets up container











