# Start for Studying Spring first

<Installing and Basical Setup>

1. Install the jdk(version 11) and java IDE(I installed IntelliJ)
2. Enter the https://start.spring.io
3. I checked Project - Gradle Project, Language - Java, Spring Boot -2.6.2 (As of the time of download - 2022.1.5 wed)
4. There are Two Dependencies i checked, which are (1. Spring Web, 2. Thymeleaf - templates engine for what like html (It depends on you or companies' demands.)) and push 'generate'
<img width="1163" alt="스크린샷 2022-01-05 오후 6 00 50" src="https://user-images.githubusercontent.com/86109402/148190052-1ef341f6-a380-4b89-96a5-cc13502e8a4c.png">
5. Open this project on Java IDE(IntelliJ) and take look at the folders.

** There are 'main' folder and 'test' folder in 'src' folders.

These days, It is standardized like this. The 'main' folder has 'Java' file and 'resources' file, and 'Java' file has actual packages and source files. The 'resources' file contains html, xml, properties, and setting files separately from the actual Java code file. In other words, it can be seen as the rest except for 'Java' file.
And the sources related to the test code are in the test file, which are very important to the trend these days.

6. 'build.gradle' is also important. But,I'm still in the learning steps, I'll only figure out the important points. 
    -> Simply, it sets the version and bring the library.
<img width="1399" alt="스크린샷 2022-01-05 오후 4 30 59" src="https://user-images.githubusercontent.com/86109402/148191875-e08ebbe2-9f43-47db-9294-32a89f570b9c.png">

7. Enter to the 'main - java - projectname' and Run it. Then there is the result of it.
<img width="1397" alt="스크린샷 2022-01-05 오후 5 01 11" src="https://user-images.githubusercontent.com/86109402/148193819-b90590fb-7cee-4be5-b4e1-bc6148498630.png">
** However, If you have difficulties with it, refer to the following.

  1. Check if java and javac are 11 versions in a terminal or cmd window.
  2. Enter to 'Preferences - Build, Execution, Deployment - Build Tools - Gradle' and check the Gradle JVM version, and 
     also modify 'Build and run using' and 'Run tests using' together to 'IntelliJ IDEA'. Because it is faster to run the
     projects than just using 'Gradle(Default)'
     <img width="979" alt="스크린샷 2022-01-05 오후 5 03 09" src="https://user-images.githubusercontent.com/86109402/148194869-f12c798a-a589-44d0-9aea-ade30bcb0fa3.png">

8. If all succeeded, in the search box, type localhost:8080
<img width="1324" alt="스크린샷 2022-01-05 오후 5 00 25" src="https://user-images.githubusercontent.com/86109402/148195475-5859fade-32a8-453f-81af-0c569016bcf8.png">

9. When exit it and type localhost:8080 in the search box again, it changes to like this.
<img width="1322" alt="스크린샷 2022-01-05 오후 5 03 52" src="https://user-images.githubusercontent.com/86109402/148196158-4a899490-6889-42bc-a08f-76ba8d5f28d7.png">

<Summary about Libaraies>
    
    [Spring boot Libraries]
    1. spring-boot-starter-tomcat    : tomcat server (Web server)
    2. spring-webmvc                 : Spring Web MVC
    3. spring-boot-starter-thymeleaf : Thymeleaf Templates Engine(View)
    4. spring-boot-starter           : Spring boot + Spring core + Logging
      *spring-boot
        - spring-core
      *spring-boot-starter-logging
        - logback, slf4j

    [Test Libraries]
    1. spring-boot-starter-test
        - junit : Test Framework
        - mockito : mok Library
        - assertj : Library to help test codes to write easier
        - spring-test : Support for Spring integration test.

<View Settings>
     
    
    
Ok! It's all done for starting Spring! Thank you !!



