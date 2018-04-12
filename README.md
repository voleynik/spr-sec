If you are using Gradle, you can run the application using ./gradlew bootRun. 
Or you can build the JAR file using ./gradlew build. 
Then you can run the JAR file:

gradlew clean build
java -jar build/libs/spr-sec.jar


	testCompile('org.springframework.boot:spring-boot-starter-test')
	testCompile('org.springframework.security:spring-security-test')
