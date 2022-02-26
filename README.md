# University-Bazaar-System

Our zip file consists of the following things:
    • CSE3310DefaultProject(Android Studio Datas)
    • UBSProject(Eclipse IDE Data)
    • CSE 3310 Team 6 SRA Spring 2021.docx
    • CSE 3310 Test Plan - Increment 3 - Spring 2021.docx
    • Read-me.docx
    • User Manual.docx

The application is a android application with its majority of programming done with the help of Android Studios. Hence, almost all of the file is of Android Studio. But at the same time the application consisted of a middleware software formed with the help of Spring Boot Library. Hence, there are also files written in Java with the help of Spring Boot Library that contributes as the middleware of the application. The codes for this were written with the help of Eclipse IDE for Enterprise Java and Web Developers – 2021. The IDE was the one responsible for boot starting the middleware which then the frontend would connect with the help of REST API. Therefore, starting both frontend and middleware at the same time is necessary for the proper operation of the application. The middleware also utitlizes the help of Oracle Database as its record keeper. While it is part of the application we were not able to store much data other than the login credentials that the user registers each time. This is what allows users to register users and login to the application using those registered credentials.

Note: We could not include the Oracle database as it is like fixated to one computer and transferring required connecting it to the source computer and then transferring it. Instead we included a screenshot of what our Oracle database looks like. To connect your newly formed database either go to application.properties file within the Eclipse IDE folder that we sent once you upload that into Eclipse IDE., and put in the credentials of your database table. Or create a new table and have our default settings that is pasted below:
	server.port = 8082

#Oracle Setting
spring.datasource.url=jdbc:oracle:thin:@localhost:1521/orcl
spring.datasource.username=hr
spring.datasource.password=oracle
spring.datasource.driver-class-oracle.jdbc.driver.OracleDriver

We highly recommend having database values as the one we provided the screenshot to have better and effective performance of our application and it is actually essential to even get access to the application and view the different functionalities that are made with it. Therefore, setting up the database is also required for the operation of the application. 
