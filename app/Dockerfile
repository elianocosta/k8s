FROM openjdk:8-jdk
WORKDIR /app
COPY ./HelloWorld.java ./
RUN javac HelloWorld.java
ENTRYPOINT [ "java", "HelloWorld"]
EXPOSE 8080

