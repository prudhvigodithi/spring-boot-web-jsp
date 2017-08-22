A Spring Boot web application example, using embedded Tomcat + JSP template, and package as an executable WAR file.

Technologies used :

Spring Boot 1.4.2.RELEASE
Spring 4.3.4.RELEASE
Tomcat Embed 8.5.6
Maven 3
Java 8

###################################
Maven package the project as an executable WAR file. A 18M++ WAR file will be generated in the target folder.
mvn clean package
###################################
Run It Locally, access http://localhost:8080

java -jar target/spring-boot-web-jsp-1.0.war
