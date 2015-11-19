# Jenkins Docker container with Docker installed

Used http://www.jayway.com/2015/03/14/docker-in-docker-with-jenkins-and-supervisord/ to help build.


To run

```bash
docker run --privileged --dns 8.8.8.8 -d --name jenkins -v /var/jenkins_home -p 8080:8080 -u root dylanpinn/jenkins
```
