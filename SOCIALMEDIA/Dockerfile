# Sử dụng base image Java 17
FROM openjdk:17-slim

# Copy file jar của ứng dụng vào container
COPY target/SOCIALMEDIA-0.0.1-SNAPSHOT.war app.war

# Mở port 8080
EXPOSE 8080

# Chạy ứng dụng
ENTRYPOINT ["java","-jar","/app.war"]
