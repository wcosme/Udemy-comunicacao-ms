FROM maven:3.8.4-jdk-11
WORKDIR .
RUN mvn clean install
EXPOSE 8081
CMD ["mvn", "spring-boot:run"]