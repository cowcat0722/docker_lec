FROM openjdk:11-jdk-slim
# 내부에서 어떤 폴더를 Default 폴더로 쓸것인지
WORKDIR /var/current/app

COPY ./entrypoint.sh ./entrypoint.sh

ENTRYPOINT ["/bin/bash", "entrypoint.sh"]

