# UACF-Challenge

Framework: Spring - Spring Boot (https://spring.io/)
Programming Language: Java 1.8
Build: Gradle 4.6
IDE: IntelliJ IDEA 2017.2.5
Check Endpoint: POSTMAN (https://www.getpostman.com/)
Storage: File System

Below are the steps to compile/run the attached code:
1.	Download the code "chatexample.zip" from below link: https://github.com/alkakumari1991/UACF-Challenge or
https://github.com/alkakumari1991/UACF-Challenge/blob/master/chatexample.zip

2.	Unzip the file at the location needed. 
Ex- /Users/al1w7p0/Desktop/INT/codeSpringboot
3.	Download IDE: https://www.jetbrains.com/idea/download/#section=mac
4.	Download Gradle: https://gradle.org/install/ . Follow the link to download it.
5.	Download Java 1.8- http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
6.	IMPORT PROJECT:
"	Using IDE, click on import the project.
 
"	Import project from location the file was unzipped. 
In my case (Ex- /Users/al1w7p0/Desktop/INT/codeSpringboot)

"	Click Next and select GRADLE.
 
"	Specify the Gradle JVM: 1.8 (Java Version)

7.	After import of project, go to preferences as below:
 
Select "Annotation Processors" and check "Enable annotation Processing"
 

8.	Compile Code:
"	Open Terminal and go to location where the project is placed. 
For Ex, my case below step I followed:
cd Desktop/INT/codeSpringboot/chatexample/

"Build the code:
gradle clean build

 
9.	Run Code:
"	Below is statement to run the project:
java -jar build/libs/chatexample-0.0.1-SNAPSHOT.jar


10.	Download POSTMAN- Postman is a powerful HTTP client for testing web services.
https://www.getpostman.com/

11.	Below is the Port Number and basic endpoint to see output:
http://localhost:8082/chat

We can see above configuration in file :src/main/resources/application.yml
 
POST /chat
http://localhost:8082/chat/chat/

 
GET /chat/id
http://localhost:8082/chat/chat/14

 
GET /chats/username
http://localhost:8082/chat/chats/yuvans

	 

