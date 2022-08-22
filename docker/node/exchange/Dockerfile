#FROM anapsix/alpine-java:8
FROM openjdk:8-jdk-alpine
EXPOSE 6004
ADD /target/exchange.jar /application/exchange.jar
CMD java -jar -Xms512m -Xmx512m -Xmn200m -Xss256k /application/exchange.jar
#ENTRYPOINT ["java","-jar","-Xms512m","-Xmx512m","-Xmn200m","-Xss256k","/application/eureka.jar","--debug"]
#CMD java -jar -Xms512m -Xmx512m -Xmn200m -Xss256k /home/spring_cloud/eureka.jar --debug
