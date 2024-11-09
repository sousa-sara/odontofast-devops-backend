# Stage 1: Build
FROM maven:3.8.4-openjdk-17 as builder
WORKDIR /app
COPY pom.xml .
COPY src ./src
RUN mvn clean package -DskipTests

# Stage 2: Run
FROM openjdk:17-slim
WORKDIR /app
COPY --from=builder /app/target/backend.jar /app/backend.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","backend.jar"]
