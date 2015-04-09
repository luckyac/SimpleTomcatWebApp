SimpleTomcatWebApp
==================

This is a simple hello word web application. It contains index.jsp which produces html that says. Hello Platform!!

It can be run in any Servlet Container like Tomcat,Jetty

#Prerequisite 
* JDK 1.7
* Maven

#Build
The project is build using maven.

* mvn clean install
#Run
The webapplication can be run in tomcat using below command

* mvn tomcat:run

	Access web page as http://localhost:8080/SimpleTomcatWebApp/

#Explanation
	Maven downloads the tomcat and deploys the SimpleTomcatWebApp application init.