FROM hub.mooc.com/kubernetes/openjdk:11.0.14.1-oraclelinux8

COPY target/springboot-web-demo-1.0-SNAPSHOT.jar /springboot-web.jar

ENTRYPOINT ["java", "-jar", "/springboot-web.jar"]
