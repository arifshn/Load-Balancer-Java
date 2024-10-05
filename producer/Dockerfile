# Base image olarak Maven ve JDK kullan
FROM maven:3.9.2 AS build

# Çalışma dizinini ayarla
WORKDIR /app

# pom.xml ve src dizinini kopyala
COPY pom.xml .
COPY src ./src

# Maven ile projeyi derle
RUN mvn clean package

# Son imaj
FROM openjdk:17-jdk-slim
COPY --from=build /app/target/kafka-producer-1.0-SNAPSHOT.jar /app/kafka-producer-1.0-SNAPSHOT.jar

# Uygulamayı çalıştır
CMD ["java", "-jar", "/app/kafka-producer.jar"]

