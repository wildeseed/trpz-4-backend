# Використовуємо Java 17
FROM openjdk:17-jdk-slim

# Робоча папка
WORKDIR /app

# Копіюємо готовий jar файл
COPY target/radio-service-0.0.1-SNAPSHOT.jar app.jar

# Відкриваємо порт
EXPOSE 8080

# Запуск
ENTRYPOINT ["java", "-jar", "app.jar"]