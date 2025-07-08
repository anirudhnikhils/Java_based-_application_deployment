# 1️⃣ Base image (OpenJDK 11 on Alpine Linux)
FROM adoptopenjdk/openjdk11:alpine-jre

# 2️⃣ Set working directory inside the container
WORKDIR /app

# 3️⃣ Copy the built JAR file into the container
# By default, assume your jar is: target/myapp.jar
COPY target/spring-boot-web.jar app.jar

# 4️⃣ Command to run the JAR
ENTRYPOINT ["java", "-jar", "app.jar"]
