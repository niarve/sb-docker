./gradlew build buildDocker
docker run -d -p 8080:8080 -t niarve/gs-spring-boot-docker
