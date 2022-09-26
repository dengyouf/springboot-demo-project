# springboot-demo-project
springboot  demo  project for devops on k8s


- docker run -it  -v /tmp/springboot-demo-project:/springboot-demo-project dengyouf/maven:3-openjdk-18-aliyun bash
- cd /springboot-demo-project && mvn clean install
- java -jar springboot-demo-0.0.1-SNAPSHOT.jar
- curl http://IP:8080/k8s

