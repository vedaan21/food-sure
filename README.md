# Foody Express

<p align="center">
  <img style="width:25%;" src="https://www.bing.com/th/id/OGC.a62e8a8c05e1dabe118f1c15f3531b16?pid=1.7&rurl=https%3a%2f%2fd12man5gwydfvl.cloudfront.net%2fwp-content%2fuploads%2f2014%2f06%2f27233933%2fDelivery-Loop1.gif&ehk=HwYMlGZVX5hM01E7eKrYgxYLu15Iv1QyA%2bvwYEE5Q3I%3d" />
</p>


<li>An online Food Delivery Application having backend REST-API, made in Java Spring Boot, JPA-Hibernate with MySQL database.

 
 
## Used Tech Stack & Tools:
1. JAVA
2. Spring
3. Spring Boot
4. Spring data JPA
5. Hibernate
6. MySQL
7. Git
8. GitHub

[![](https://skillicons.dev/icons?i=java,spring,hibernate,mysql,git,github)]()

## Modules
1. Login Module
2. Customer Module
3. Restaurant Module
4. Order Module
5. Bill Module
6. Item Module
7. Cart Module
8. Exception Module

## Installation & Run

1. clone our Project into your local machine.
      - open any terminal
      - git clone https://github.com/sanajitjana/star-theory-7179.git
2. Open Your STS
3. Goto File -> Import -> Select Maven -> Choose Existing Maven -> Click on browse -> Choose the project location -> Select the project -> Finish
4. All done, good to go!

* Before running the API server, you should update the database config inside the [application.properties](https://github.com/sanajitjana/star-theory-7179/blob/master/FoodyExpress/src/main/resources/application.properties) file. 
* Update the port number, username and password as per your local database config.

```
    #db specific properties
    server.port=8088
    
    spring.datasource.url=jdbc:mysql://localhost:3306/foody_express_db;
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username="Your SQL username"
    spring.datasource.password="Your SQL Password"
    
    #ORM s/w specific properties
    spring.jpa.hibernate.ddl-auto=update
    spring.jpa.show-sql=true
    
    #validation exception activate
    spring.mvc.throw-exception-if-no-handler-found=true
    spring.web.resources.add-mappings=false
    
    #enable swagger
    spring.mvc.pathmatch.matching-strategy = ANT_PATH_MATCHER

```

## ER Diagram
![Online-Food-Order-App](https://user-images.githubusercontent.com/76105799/203701190-7211e27e-4afa-4110-af11-375a538fd17d.png)


