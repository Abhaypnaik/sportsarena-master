FROM openjdk:11-jre-slim
WORKDIR  usr/src
ENV MONGO_URI=mongodb://3.138.158.96:27017/userservice_db
ADD ./target/user-service-0.0.1-SNAPSHOT.jar /usr/src/user-service-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","user-service-0.0.1-SNAPSHOT.jar"]