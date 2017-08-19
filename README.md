# Spring MVC Quick Start Kit

if you worked with `Spring MVC` framework, you probably awair of its basic configurations including `Dispatcher` and `web` xml files.

this repository based on maven and already had the basic configuration, all you need is cloneing and using it.

I downloaded this project from [Mkyong site](http://www.mkyong.com/spring-mvc/spring-mvc-hello-world-example/) and changed and added other things to it 

# How to use it

it's so simple.

1. just clone it and import/open it into your IDE (like `IntelliJ` or `NetBeans`) and then simply run it (your IDE will automatically compile and deploye it on your web service) 

2. you can also compile it using maven with following command:

   ```
   mvn clean install
   ```

   then copy the `.war` file (which will be created in `target` folder) and deploy it on your web server like `tomcat` 

# Verfiy

for checking is it working or not, just after doing previous step, go to `{your-localhost-ip}:{port}/Spring-mvc` and if it's working you should see a page with this message:

**Spring MVC Quick Start Kit (SMQSK)**

**Welcome<br>if you see this page, it means I'm working**
