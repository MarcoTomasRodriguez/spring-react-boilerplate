FROM gradle:jdk11
WORKDIR /app
ENV SERVER_PORT=80
COPY build.gradle.kts settings.gradle.kts ./
COPY src/ ./src
ENTRYPOINT gradle bootRun