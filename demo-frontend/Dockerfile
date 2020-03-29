FROM openjdk:12
VOLUME /tmp
ADD ./target/demo-frontend-1.0-SNAPSHOT.jar demo-frontend.jar
ENTRYPOINT ["java","-jar","/demo-frontend.jar"] 