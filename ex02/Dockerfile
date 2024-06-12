FROM openjdk:11-jdk-slim
# 내부에서 어떤 폴더를 Default 폴더로 쓸것인지
WORKDIR /var/current/app

COPY ./deploy/aws-v3-0.0.3.jar ./application.jar

ENTRYPOINT ["java", "-jar", "application.jar"]

CMD ["--server.port=3000"]


