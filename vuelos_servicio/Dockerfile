# Fase de construcción
FROM maven:3.8.4-openjdk-17-slim AS build
WORKDIR /app
COPY pom.xml .
COPY src ./src
RUN mvn clean package -DskipTests=true

# Fase final
FROM openjdk:17-jdk-slim
WORKDIR /app
COPY --from=build /app/target/vuelos-servicio-0.0.1-SNAPSHOT.jar /app/microservicio-vuelo.jar
EXPOSE 8001
CMD ["java", "-jar", "/app/microservicio-vuelo.jar"]
