FROM dockerfile/java:oracle-java8

ADD hello.jar /opt/hello/
EXPOSE 8080
WORKDIR /opt/hello/
CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "hello.jar"]