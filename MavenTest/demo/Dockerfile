FROM maven:latest
LABEL authors="jaahas"

WORKDIR /app
COPY pom.xml /app
COPY . /app
RUN mvn package
CMD ["java", "-jar", "target/demo-1.0-SNAPSHOT.jar"]
