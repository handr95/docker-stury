FROM openjdk:8-jdk-alpine

WORKDIR /app

COPY . .

RUN ./gradlew build

EXPOSE 8080

CMD ["./gradlew","bootRun"]