# Run a Spring Cloud Config Server

```
docker run -it -p 8888:8888 \
  -e SPRING_CLOUD_CONFIG_SERVER_GIT_URI=https://github.com/chaoyangnz/spring-cloud-config-git-repo \
  hyness/spring-cloud-config-server
```
