1.import this project in spring tool suit open xamp server start apahe and mysql. 
2.create database in xamp localhost myadmin with the name demo.
3.now open the given project and go to net.example.springboot in that package open RegistrationLoginApplication class now right click and go to run as click on spring app after that your project is running.
4. go to chrome and enter   http://localhost:8080/login this url you will see the output

http://localhost:8080/registration

For h2 database use this in application.properties in given project  and create schemas in src/main/resources.
spring.datasource.url = jdbc:h2:mem:demo  

thank you