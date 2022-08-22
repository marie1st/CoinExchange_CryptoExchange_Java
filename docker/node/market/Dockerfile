#FROM anapsix/alpine-java:8
FROM openjdk:8-jdk-alpine
EXPOSE 6004
ADD /target/market.jar /application/market.jar
CMD java -jar -Xms512m -Xmx512m -Xmn200m -Xss256k /application/market.jar
#ENTRYPOINT ["java","-jar","-Xms512m","-Xmx512m","-Xmn200m","-Xss256k","/application/eureka.jar","--debug"]
#CMD java -jar -Xms512m -Xmx512m -Xmn200m -Xss256k /home/spring_cloud/eureka.jar --debug
