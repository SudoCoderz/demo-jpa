# docker-jpa-sample
Simple Demo using Spring Boot + MySql + Docker compose to run and link containers

To get it started, follow the below instructions
1. clone the repository
2. run 'mvn clean install -DskipTests'
3. confirm that you have the target folder generated containing demo-jpa.jar
4. make sure you have docker installed
5. run 'docker-compose up' # this command will spin all the containers, establish the necessary links
6. open the browser and hit http://localhost:8085/dummydata. you should see the dummy record. After that you can hit the other rest end points using Postman.
